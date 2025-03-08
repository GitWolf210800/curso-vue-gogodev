<template>
    <form>
        <input type="text" v-model="inputText" />
        <input type="checkbox" v-model="agree" /> Acepto los términos y condiciones
        <select>
            <option>Spain</option>
            <option>UK</option>
            <option>France</option>
        </select>
    </form>
    <h3>{{ inputText }}</h3>
</template>

<script lang="ts">
import { Ref, ref, defineComponent } from 'vue';

export default defineComponent({
    data() {
        return {
            inputText: '',
            agree: true
        }
    }
}); 

</script>

<style scoped>
</style>