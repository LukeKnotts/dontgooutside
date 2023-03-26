<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You like to spend time watching the boats come along the river. You're
        fascinated by their functionality, and how they load and unload. You
        wonder where they come from and where they go.
      </p>
      <p>
        Your neighbor Rah seems to have similar interests as you. Do you hang
        out with them?
      </p>
      <p class="choices">
        <NuxtLink to="a014-hang-with-rah-boats">Yes</NuxtLink>
        <NuxtLink to="a015-watch-boats-alone">No</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A008WatchBoatsUnload',
}
</script>
