<template>
    <h1 class="notOk" v-if="age < 18">Eres menor de edad</h1>
    <h1 class="ok" v-else >Eres mayor de edad</h1>
</template>

<script lang="ts" setup>
    let age = 10;
</script>

<style scoped>
.ok {
    color: green;
}
.notOk {
    color: red;
}
</style>