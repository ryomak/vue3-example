<template>
    <PhotoComponent />
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
import PhotoComponent from '../components/PhotoComponent.vue'

export default defineComponent({
  components:{
    PhotoComponent
  },
  setup() {
  }
})
</script>

<style scoped>
img {
  width: 200px;
}
h1 {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
 
