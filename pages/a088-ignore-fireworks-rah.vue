<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        Rah and you stay inside. You two don't want to get involved in anythign
        crazy, and besides, someone needs to watch the radio. BANG! Another
        firework explodes, and you and Rah's energy falls another notch. You hit
        eachother to keep yourselves awake. Bang! You two yawn. Bang. Bang.
        Bang... ba... ng... Eventually, you and Rah can't fight it, and the both
        of you fall asleep.
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
  name: 'A088IgnoreFireworksRah',
}
</script>
