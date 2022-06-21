<template>
  <div class="hello">
    <div class="nav-bar">
      <div class="nav-item">
        Főoldal
      </div>
      <div class="nav-item">
        Képzéseim
      </div>
      <div class="nav-item">
        Youtube
      </div>
      <div class="nav-item">
        Rólam
      </div>
    </div>
    <div class="name">
      <div class="logo">
        <img src="../assets/logos/logo256_vector.svg" alt="Brand logo">
      </div>
      <div class="logo">
        <img src="../assets/logos/logo256_vector_2.svg" alt="Brand logo">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeComponent',
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.nav-bar {
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.nav-item {
  border: 1px solid red;
  flex: 1;
  text-align: center;
}
.logo {
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: 100vh;
}
</style>
