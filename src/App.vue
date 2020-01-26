<template>
  <div id="app">
    <CreateBuilding desc="U ovoj komponenti kreirate nove zgrade" name="CreateBuilding"/>
  </div>
</template>

<script>
import CreateBuilding from './components/CreateBuilding.vue'

export default {
  name: 'app',
  components: {
    CreateBuilding,
  }
}
</script>

<style>

</style>
