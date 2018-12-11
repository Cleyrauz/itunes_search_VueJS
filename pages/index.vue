<template>
  <div>
      <h1>Search iTunes</h1>
      <br/>

      <form>
          <input placeholder="Enter artist name" v-model="search" autofocus  />
      </form>
  </div>
</template>

<script>

export default {
  components: {
  },
    data() {
      return {
        search: ''
      }
    }
  }
</script>

<style>
* {
  text-align: center;
}
h1 {
  padding: 20px;
}
</style>
