<template>
  <div class="header">
    <img alt="Vue logo" src="./assets/profile.png" class="profile_pic">
    <h1 class="headline">Magnus Haxen</h1>
    <h2 class="headline">Curriculum Vitae</h2>
  </div>
  <CV msg="Welcome to Your Vue.js App"/>
</template>

<script>
import CV from './components/CV.vue'

export default {
  name: 'App',
  components: {
    CV
  }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #22313f;
  padding-top: 60px;
  background-image: url('./assets/bg_blurr.png');
  background-attachment: fixed;
  background-size: cover;
  font-size: 20px;
}

.profile_pic {
  border-radius: 50%; /* This will make the image a circle */
  height: 240px; /* You can adjust the size of the image by changing the height and width values */
  width: 240px;
  transition: 0.5s;
}

.profile_pic:hover {
  height: 290px; /* You can adjust the size of the image by changing the height and width values */
  width: 290px;
}

.headline {
  color: #fef1e4;
}

.header {
  padding-top: 64px;
  padding-bottom: 64px;
  font-size: 32px;
}

</style>
