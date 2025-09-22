<script setup lang="ts">

import avatar from "@/assets/users/avatar.jpg"
import NewContact from "@/views/NewContact.vue";
</script>

<template>
  
    <aside class="infomation-sidebar">
      <div class="perfil box-content">
        <img class="user-image" :src="avatar" alt="">
        <h1 class="user-name">Default User</h1>
        <h2 class="user-information">Information about user</h2>
        <h3 class="user-school">User's School</h3>
      </div>
      <div class="new-network-box box-content">
        <NewContact></NewContact>
        <NewContact></NewContact>
        <NewContact></NewContact>
        <NewContact></NewContact>
      </div>
    </aside>
  
</template>