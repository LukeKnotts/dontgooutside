<template>
  <div class="phase2blue">
    <TopNav />
    <div class="container">
      <unfinished-buisness />
      <h2>Phase 2 Coming Soon!</h2>
      <p>Maybe. If we feel like it. Probably not.</p>
      <p>
        <NuxtLink class="secret" to="thanksforplaying">Thank you</NuxtLink> for
        getting this far, even if we just immediately threw a cliff hanger at
        you!
      </p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Again</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Phase2SoonMaybe',
}
</script>
