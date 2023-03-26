<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You feel kind of uncomfortable. You decide that you're going to head
        home for the day. You don't feel like pushing your luck.
      </p>
      <p>
        You make your way home. If there was some sort of sketchy thing going
        on, you think you would rather be inside your house for it.
      </p>
      <p class="choices">
        <NuxtLink to="a034-stay-indoors">Stay indoors</NuxtLink>
        <NuxtLink to="a060-call-police">Go home and call the police</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A036GoHomeBoatsAlone',
}
</script>
