<template>
  <div id="app">
    <Header />
    <Main />
  </div>
</template>

<script>
import Header from './components/Header';
import Main from './components/Main';

export default {
  name: 'App',
  components: {
    Header,
    Main,
  }
}
</script>

<style>
@import "./assets/styles/normalize.css";
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=PT+Sans:wght@400;700&display=swap");

#app {
  font-family: "PT Sans", Helvetica, Arial, sans-serif;
  background: rgb(240, 246, 252);
  height: 100vh;
  padding: 10px 38px 0;
}
</style>
