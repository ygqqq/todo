<template>
  <div id="app">
    {{$route.params.status}}
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import url(./assets/index.css);
</style>
