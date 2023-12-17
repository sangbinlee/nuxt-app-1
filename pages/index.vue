<!-- <script setup lang="ts">
definePageMeta({
  layout: false,
})
</script> -->

<template>
  <div>
    <NuxtLayout name="custom"> 
    
        <header>
      <nav>
        <ul>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/carousels">carousels</NuxtLink></li>
          <li><NuxtLink to="/app">app</NuxtLink></li>
          <li><NuxtLink to="/login">login</NuxtLink></li>
          <li><NuxtLink to="/posts/1">Post 1</NuxtLink></li>
          <li><NuxtLink to="/posts/2">Post 2</NuxtLink></li>
        </ul>
      </nav>
    </header>
     
      The rest of the page
    </NuxtLayout>
  </div>
</template>
 