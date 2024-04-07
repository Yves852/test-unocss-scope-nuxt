<template>
  <div>
    <nav class="flex flex-row gap-5">
      <NuxtLink to="/">Index</NuxtLink>
      <NuxtLink to="/page">Second page</NuxtLink>
    </nav>
    <NuxtPage />
  </div>
</template>

<style>
body {
  background-color: black;
  color: white;
}
</style>