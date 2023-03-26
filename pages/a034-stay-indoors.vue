<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You decide to wait at home. This isn't a big deal, and if something were
        to happen, you won't add to it by being here indoors. This probably
        isn't a big deal or anything worth worrying over. You get in bed for the
        night without another interesting thing happening.
      </p>
      <p>
        Then, just as your about to drift off to sleep, a flash of blue light
        appears from outside your window. Blue light continues to flicker from
        the window. Reluctantly, you get up to see what's going on.
      </p>
      <p>
        Out the window you can see that the light is coming from the docks, and
        there's a crowd gathered there. What could everyone be doing at this
        time of night?
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
  name: 'A034StayIndoors',
}
</script>
