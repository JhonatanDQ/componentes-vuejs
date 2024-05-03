<script setup>
import { ref } from 'vue'
let counter = ref(0)

function add(){
    counter.value++
    console.log('Hola xd' , counter)
}
</script>

<template>
   <div @click="add" class="button bg-blue-200 border-black py-1 rounded-full mt-2 cursor-pointer px-2 max-w-40 mx-3 text-center select-none">
   Numero de clicks: {{ counter }}
   </div>
</template>