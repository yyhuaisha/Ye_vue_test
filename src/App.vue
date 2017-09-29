<template>
  <div>
    <p v-once></p>
    <button @click="world='people'">改变world值</button>
  </div>
</template>

<script>
import myComponent from './component/myComponent.vue'
import VueRouter from "vue-router"
import VueResource from 'vue-resource'
export default {
  data () {
    return {
      world: 'World'
    }
  }
}
</script>

<style>

</style>
