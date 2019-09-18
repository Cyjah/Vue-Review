<template>
  <div id="app">
    <Add/>
    <List :comments="comments"/>
  </div>
</template>

<script>
import Add from './components/Add'
import List from './components/List'
export default {
  data () {
    return {
      comments: [
        {
          name: 'Bob',
          content: 'Bob说什么'
        },
        {
          name: 'Vince',
          content: 'Vince说什么'
        }
      ]
    }
  },
  components: {
    Add,
    List
  }
}
</script>

<style scoped>

</style>
