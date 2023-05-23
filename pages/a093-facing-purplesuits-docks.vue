<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You take a step, but finally it is too much. Bang! The fireworks
        continue to go off, and your consciousness is fading fast. One of the
        odd workers approaches you and throws a punch your way. You attempt to
        move out of the way but they are too fast. The fist to your face knocks
        you out, and fall to the ground unconscious.
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
  name: 'A093FacingPurplesuitsDocks',
}
</script>
