<template>
  <div>
    <app-header v-bind:propsdata="str"></app-header>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';

export default { 
  components: {
    'app-header': AppHeader,
  },
  data: function() {
    return {
      str: 'Header',
    }
  }

}
</script>

<style>

</style>