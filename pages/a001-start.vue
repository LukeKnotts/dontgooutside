<template>
  <div class="home">
    <TopNav />
    <div class="container">
      <p>CYOA Game</p>
      <p class="choices">
        <NuxtLink to="/a003-start-in-chegckle">Start</NuxtLink>
        <NuxtLink to="/a002-early-end">Don't start</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A002EarlyEnd',
}
</script>
