<script setup lang="ts">
import avatar from "@/assets/users/avatar.jpg"

</script>

<template>

    <section class="feedItem">
        <div class="feedItem-header">
            <img class="feedItem-header-img" :src="avatar"></img> 
            <div class="feedItem-header-desc">

                <h1 class="feedItem-header-desc-name">James Banana</h1>
                <h2 class="feedItem-header-desc-description">Designer | Writer </h2>

            </div>
        </div>
        
        <div class="feedItem-body">
            <p class="feedItem-body-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, voluptatem ratione recusandae, quae nam nostrum iste voluptatum excepturi eveniet quia error quas maiores? Ad, numquam aliquam perferendis illum sit iure.</p>
            <img class="feedItem-body-img" :src="avatar" alt="">
        </div>
        
    </section>

</template>