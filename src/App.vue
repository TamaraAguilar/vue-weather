<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      api_key: "0e4b1bd15a4b803b8de1aad53d2a2dcf",
    };
  },
};
</script>

<style>
#app {
  background-image: url("./assets/cold-bg.jpg");
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Montserrat", sans-serif;
}
</style>
