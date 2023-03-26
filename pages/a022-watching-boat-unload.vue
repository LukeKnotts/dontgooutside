<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        Your curiousness leads you to investigate the boat. You watch two men,
        who are unloading varous crates and odd looking machinary off of the
        boat. You wonder what they're doing. For some reason, this seems
        different than other boat unloading operations that happen so often at
        the river docks.
      </p>
      <p>
        The workers seem to be chatting. The people unlaoding the boat are just
        out of earshot, but if you got a little closer, you would be able to
        hear them.
      </p>
      <p class="choices">
        <NuxtLink to="a028-dont-eavesdrop-boat">Turn back</NuxtLink>
        <NuxtLink to="a029-boat-eavesdrop-alone">Eavesdrop on them</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A022WatchingBoatUnload',
}
</script>
