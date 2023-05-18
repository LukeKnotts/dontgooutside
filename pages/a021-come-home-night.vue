<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You decide to leave and do something else. You come home for the day.
      </p>
      <p>
        That night, after you've come home, you hear a commotion outside. You
        look out your window to see something strange. A crowd of people seems
        to be gathering at the docks, and the an entrancing light shines from
        it.
      </p>
      <p class="choices">
        <NuxtLink to="a026-late-night-entertainment">Check it out</NuxtLink>
        <NuxtLink to="a033-ignore-blue-lights">Ignore it</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A021ComeHomeNight',
}
</script>
