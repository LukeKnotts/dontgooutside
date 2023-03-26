<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah stay back in the streets, blue light being cast on the
        moving people heading to the market. Most of the people are following
        the boat man, but a few are lingering behind like you and Rah. The boat
        sits still in the water, the last crate having been set on it, and being
        left presumably unattended.
      </p>
      <p>
        A blue bolt whistles off of the boat just when you thought it was still.
        BANG! A brilliant blue spark splashes against the sky, glittering blue
        particles radianting off of the explosion.
      </p>
      <p>
        Then it hits you. A wave of exhaustion comes over you and Rah, causing
        both of you to yawn. Suddenly your eyelids are heavy, and your legs are
        sore. You don't feel like being awake right now. You hear a snore and
        turn. Rah is lying on the ground, sleeping.
      </p>
      <p class="choices">
        <NuxtLink to="a070-ignore-fireworks-sleepy">Let yourself rest</NuxtLink>
        <NuxtLink to="a101-stumbling-docks-night">Go to that boat</NuxtLink>
        <NuxtLink to="a106-investigate-sleepy-rah"
          >Figure out what's going on</NuxtLink
        >
        <NuxtLink to="b006-run">Leave Rah, you have to run!</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A110StayInStreetsRah',
}
</script>
