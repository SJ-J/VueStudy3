<template>
  <!-- <div class="header">
    <ul class="header-button-left">
      <li>Cancel</li>
    </ul>
    <ul class="header-button-right">
      <li>Next</li>
    </ul>
    <img src="./assets/logo.png" class="logo" />
  </div> -->

  <ContainerBox />

  <!-- <div class="footer">
    <ul class="footer-button-plus">
      <input type="file" id="file" class="inputfile" />
      <label for="file" class="input-plus">+</label>
    </ul>
 </div> -->

</template>

<script>

import postData from './assets/data.js';
import ContainerBox from './components/Container.vue';

export default {
  name: 'App',
  data(){
    return {
      data : postData,
    }
  },
  components: {
    ContainerBox: ContainerBox,
  }
}
</script>

<style>
@import 'style.css';
</style>

