<script setup lang="ts">
import avatar from "@/assets/users/avatar.jpg"
</script>

<template>
    <div class="new-contact">
        <img class="new-contact-img" :src="avatar" alt="">
        <h1 class="new-contact-name">James Banana</h1>
        <button class="new-contact-button">+</button>
    </div>
</template>