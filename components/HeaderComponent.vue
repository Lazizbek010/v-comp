<template>
  <div class="nav">
    <ul>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
        
      </li>
      <li>
        <NuxtLink to="/about">About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/contact">Contact</NuxtLink>

      </li>
    </ul>
  </div>
</template>

<script setup>
</script>

<style>
*{
    margin: 0;
    padding: 0;
}
.nav{
    background: #000;
    padding: 10px;
}
ul{
    display: flex;
    gap: 20px;
}
ul li a{
    color: red;
    font: 24 700 sans-serif;
}
</style>