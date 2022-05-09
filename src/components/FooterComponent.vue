<template>
  <footer>
    <div class="footer-bar">
      <router-link to="/">Beranda</router-link>
      <router-link to="/adult">Komik Dewasa</router-link>
      <router-link to="/dmca">DMCA</router-link>
    </div>
    <div class="copyright">
      <p>&copy; 2022 by KomikIndo. All Rights Reserved.</p>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
footer {
  margin-top: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.footer-bar {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0px 13px;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  width: 98%;
  padding: 10px 0px;
}

.footer-bar a {
  text-decoration: none;
  color: #CCC;
  font-weight: bold;
  font-size: 14px;
  padding: 10px;
}

.copyright {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 15px 0px;
  padding: 0px 13px;
  width: 98%;
  padding: 10px 0px;
}

.copyright p {
  font-size: 13px;
  color: #ccc;
}
</style>