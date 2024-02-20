<template>
    <p>iphone {{ name}}</p>
</template>
<script setup>
import { useRoute } from 'vue-router';



 const route = useRoute()

 const name = computed(() => {
    return route.params.name.replaceAll('-',' ');
 })

 





</script>