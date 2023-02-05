<template>
  <main>
    <div id="content">
      <h1>Emily & Eilean</h1>
      <h2>19 October 2024</h2>
    </div>
    <div id="background"></div>
  </main>
</template>

<script setup lang="ts">

</script>

<style scoped>
main {
  height: 100vh;
  width: 100vw;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#background {
  position: fixed;
  bottom: 0;
  top: 0;
  right: 0;
  left: 0;

  background-image: url("@/assets/cloisters_castle.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;

  opacity: .75;
  z-index: -1;
}

#content {
  text-align: center;
}

h1 {
  font-size: 96px;
}

h2 {
  font-size: 40px;
}

@media (max-width: 575px) {
  h1 {
    font-size: 48px;
  }

  h2 {
    font-size: 24px;
  }
}
</style>