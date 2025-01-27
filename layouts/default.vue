<script setup>
</script>
<template>
  <div>
    <ul>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
      </li>
      <li>
        <nuxt-link to="about">About</nuxt-link>
      </li>
      <li>
        <nuxt-link to="products">Products</nuxt-link>
      </li>
    </ul>
    <div>
      <slot />
    </div>
  </div>
</template>