<script setup lang="ts">
import avatar from '@/assets/users/avatar.jpg'
import LeftSidebarHomeview from '@/views/LeftSidebarHomeview.vue'
import RightSidebarHomeview from '@/views/RightSidebarHomeview.vue'
import FeedItem from '@/views/FeedItem.vue'
</script>

<template>
  <main class="main-home">
    <section>
      <LeftSidebarHomeview></LeftSidebarHomeview>
    </section>

    <section class="box-content main-box">
      <FeedItem></FeedItem>
    </section>

    <section>
      <RightSidebarHomeview></RightSidebarHomeview>
    </section>
  </main>
</template>
