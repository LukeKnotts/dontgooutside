<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You have to get to that boat. You stumble to the boat sitting in the
        water. Then you trip. You pull yourself back up with a mighty yawn, and
        drag yourself further along. Bang! Bang! Fireworks continue to go off,
        and your vision is beginning to blur. You blink, and that is all it
        takes. You fall to sleep and hit the ground in a inpenetrable slumber.
        When you wake up, you won't be the same.
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
  name: 'A101StumblingDocksNight',
}
</script>
