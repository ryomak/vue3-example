<template>
<div>
    {{p1.name}}
    <figure>
    <img :src="p1.id">
    </figure>
</div>
</template>

<script lang="ts">
import { ref, reactive,defineComponent } from 'vue'
import { Photo } from '../domains/photo'

export default defineComponent({
  setup() {
    const p1 :Photo = {
        id: 1,
        randId: "3",
        like:3,
        name:"photo1"
    }

    return {
        p1
    }
  }
})
</script>

