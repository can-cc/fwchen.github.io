<template>
  <div class="container">
    <img class="me-photo" alt="" src="../../assets/me.jpeg"/>
    <img class="chen" src="../../assets/chen.png"/>
    <div class="black-block"></div>
    <div class="card">
      <div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
  import { Component, Prop, Vue } from 'vue-property-decorator';

  @Component
  export default class BlockHead extends Vue {
  }
</script>

<style scoped>
  .container {
    
  }

  .me-photo {
    position: absolute;
    width: 300px;
    left: 50%;
    top: 50%;
    transform: translate(-200px, -350px);
    z-index: 10;
  }

  .chen {
    width: 200px;
    position: absolute;
    z-index: 20;
  }

  .card {
    height: 250px;
    width: 350px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    background-color: white;
    box-shadow: 0 0 3px #bebebe;
  }

  .black-block {
    background-color: black;
    width: 500px;
    height: 500px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-450px, -50%);
  }
</style>
