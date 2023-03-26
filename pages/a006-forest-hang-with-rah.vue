<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You can hardly stand the factories and all the industry in town. You
        like to run out into the forest outside the town and explore in the
        twisting tangled trees.
      </p>
      <p>
        Your neighbor Rah seems to have similar interests to you. Do you hang
        out with them?
      </p>
      <p class="choices">
        <NuxtLink to="/a010-rah-finds-something-forest">Yes</NuxtLink>
        <NuxtLink to="/a011-find-chest-forest">No</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A006ForestHangWithRah',
}
</script>
