<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You pull Rah towards you waking them. You tell them that you two need to
        figure out what's going on. Rah nods. You and Rah try to look around the
        streets. Bang! Bang! Fireworks continue to go off, and you and Rah's
        energy continues to drop. The next thing you know, Rah is asleep on the
        ground. You bend down to try to wake them up, but you too fall asleep.
        You'll eventually wake up, but you'll never be the same.
      </p>
      <p class="choices">
        <NuxtLink to="a081-bad-fireworks">Continue</NuxtLink>
      </p>

      <audio controls autoplay loop="true" hidden="true">
        <source src="/music/gameplay/purplelullaby.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A106InvestigateSleepyRah',
}
</script>
