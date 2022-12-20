<template>
  <img alt="Vue logo" src="./assets/profile.png" class="profile_pic">
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.profile_pic {
  border-radius: 50%; /* This will make the image a circle */
  height: 240px; /* You can adjust the size of the image by changing the height and width values */
  width: 240px;
}

</style>
