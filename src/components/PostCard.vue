<template>
<div class="post-card">
    <h3>Titulo</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non sit aut, qui doloribus molestias atque, expedita minima quae voluptas voluptate provident beatae corrupti dignissimos cum ratione cumque nam, exercitationem quas?</p>
    <PostButton />
</div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue';
</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>