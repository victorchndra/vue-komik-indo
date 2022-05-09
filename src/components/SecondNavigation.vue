<template>
  <nav>
    <router-link to="/">Komik Terbaru</router-link>
    <router-link to="/list">Daftar Komik</router-link>
    <router-link to="/china">Manhwa (Komik China)</router-link>
    <router-link to="/korea">Manhwa (Komik Korea)</router-link>
    <router-link to="/boruto">Boruto</router-link>
    <router-link to="/onepiece">One Piece</router-link>
    <router-link to="/blackclover">Black Clover</router-link>
  </nav>
</template>

<script>
export default {
  name: 'SecondNavigation',
}
</script>

<style scoped>
nav {
  padding: 15px 280px;
  background-color: #1e1e1e;
  display: flex;
  align-items: center;
  justify-content: space-evenly;

  font-size: 12px;
  font-family: Roboto, sans-serif;
}

nav a {
  text-decoration: none;
  color: #CCCCCC;
}

nav a.router-link-exact-active {
  color: white;
}
</style>