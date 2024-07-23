<script setup>
    // const props = defineProps(['operador']);
    const props = defineProps({
        operador: String
    });
    // console.log(props)
    const hola = "hola Vue"
</script>
<template>
    <button
        type="button"
        class="h-10 w-10 flex items-center justify-center font-bold bg-lime-500 rounded-full hover:outline-none hover:ring-2 hover:ring-offset-2 hover:ring-lime-500 text-white text-2xl"
        @click="$emit('fn',hola)"
      >{{operador}}</button>
</template>