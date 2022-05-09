<template>
  <nav class="container">
    <div class="navbar-left">
      <img
        src="https://i2.wp.com/i2.wp.com/kentut.xyz/uploads/2020/12/komikindo.png?w=140?w=140"
        alt=""
      />
      <div class="navbar">
        <router-link to="/">Beranda</router-link>
        <router-link to="/about">Komik Berwarna</router-link>
        <router-link to="/hot">Komik Hot</router-link>
      </div>
    </div>
    <div class="navbar-right">
      <router-link to="/account"><i class="fas fa-user"></i></router-link> | 
      <router-link to="/account"><i class="fas fa-search"></i></router-link>
    </div>
    </nav>
</template>

<script>

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Navigation',

}
</script>

<style scoped>

nav {
  padding: 15px 0px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  font-family: 'Roboto', sans-serif;
  font-size: 15px;
}

nav .container {
  width: 70%;
}

nav img {
  margin-right: 16px;
}

nav .navbar a {
  text-decoration: none;
  color: white;
  padding: 8px 12px;
  margin: 0px 5px;
}

nav .navbar a:hover {
  background-color: #0693e3;
  border-radius: 8px;
}

nav .navbar a.router-link-exact-active {
  color: white;
}

nav .navbar-left {
  display: flex;
  align-items: center;
}

nav .navbar-right a {
  color: #CCC;
  font-size: 1rem;
  padding: 8px 12px;
}

</style>