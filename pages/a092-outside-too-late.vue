<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You stumble around trying to get your bearings. People are lingering all
        around the streets drifting around randomly. Or maybe you're just too
        tired to figure out what is going on. You see people curled up on the
        ground and your vision continues to blur. You yawn, and rub your eyes.
        As soon as you let your eyes close, you fall into a deep sleep.
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
  name: 'A092OutsideTooLate',
}
</script>
