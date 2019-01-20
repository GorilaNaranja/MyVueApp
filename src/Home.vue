<template>
  <div>
    <server-status-component v-for="server in 5"> </server-status-component>
  </div>
</template>

<script>
  import ServerStatus from './ServerStatus.vue'
  export default {
    components:{
      'server-status-component' : ServerStatus
    }
  };
</script>

<style></style>
