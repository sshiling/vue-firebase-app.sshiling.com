<template>
  <div id="app" class="app">
    <header>
      <h1 class="app-title">Vue Firebase App</h1>
      <p>Realtime Walkie-Talkie Voice Chat</p>
    </header>

    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
header {
  text-align: center;
}
button, input {
  margin-bottom: 10px;
}
</style>

<style scoped>
.app {
  margin: 20px auto 0 auto;
  padding-bottom: 20px;
  max-width: 600px;
  border: 1px solid #ebebeb;
  border-radius: 0.42rem;
}

.app-title {
  margin: 20px 0;
  padding: 0;
}
</style>
