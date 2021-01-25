<template>
  <ul class="list">
      <li class="list-item"
      v-for="user in users" :key="user.id">{{user.name}}</li>

  </ul>
</template>

<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
    setup(){

        return{
          users:[]  
        }
    }
})
</script>

<style>

</style>