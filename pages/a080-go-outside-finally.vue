<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You finally go outside. A bunch of kids wouldn't be launching fireworks,
        would they? As you step out the door, drowsiness falls over you. It is
        hard to describe, but it feels as if everything around you is dying
        out...
      </p>
      <p>
        BANG! Another firework shakes you awake. You frantically look back and
        forth at the swirling blue lights around you. Blue dust seems to be
        falling over the town, and your energy takes a nose dive.
      </p>
      <p class="choices">
        <NuxtLink to="a092-outside-too-late"
          >Get as far from here as you can</NuxtLink
        >
        <NuxtLink to="a092-outside-too-late"
          >Try to figure out what's going on</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A080GoOutsideFinally',
}
</script>
