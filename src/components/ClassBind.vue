<template>
<p v-bind:style="{backgroundColor : '#ccc', color : c}">El mensaje se ha enviado satisfactoriamente</p>
<button @click="handleClick()">Cambiar Color</button>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
let hasError = true;
let c = ref('#fff');
const handleClick = () => c.value = '#ff0000';
</script>

<style scoped>
.danger {
    color: red;
}
</style>