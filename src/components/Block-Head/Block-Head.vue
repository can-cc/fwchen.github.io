<template>
  <div class="card-container">
    <img class="me-photo" alt="" src="../../assets/me.jpeg"/>
    <img class="chen" src="../../assets/chen.png"/>
    <div class="black-block"></div>
    <div class="card">
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
  .me-photo {
    width: 300px;
  }

  .black-block {
    background-color: black;
    width: 500px;
    height: 500px;
  }
</style>
