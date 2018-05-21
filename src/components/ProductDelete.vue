/* eslint-disable */
<template>
  <div class="delete-product">
       <h2>Delete product {{ product.name }}</h2>
    <form v-on:submit="deleteProduct">
      <p>The action cannot be undone.</p>
      <button type="submit" class="btn btn-danger">Delete</button>
      <router-link class="btn btn-default" v-bind:to="'/'">Cancel</router-link>
    </form>
  </div>
</template>

<script>
export default {
  name: 'ProductDelete',
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
