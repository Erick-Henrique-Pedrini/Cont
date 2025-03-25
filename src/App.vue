<script setup>
import {ref} from 'vue'
const cont = ref(0)
function add(){
  cont.value++
}
function rev(){
  cont.value--
}
</script>
<template>
  <h1>contador</h1>
  <h2>{{ cont }}</h2>
  <button @click="add()">add</button>
  <button @click="rev()">rev</button>

</template>