<template>
  <div>
    list来了
    父子组件间的通信
    <li v-for="(item, index) in comments" :key="index">{{ item.content }}</li>
  </div>
</template>

<script>
export default {
  props: ['comments'],
  data () {
    return {
      // coms: this.comments
    }
  }
}
</script>

<style scoped>

</style>
