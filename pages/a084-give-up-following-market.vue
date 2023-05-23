<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        There is no way you can follow them in your current state. Your eyes
        feel like they are lifting dumbells to stay open, and your muscles are
        telling you to stop moving. You stumble back to the market plaza, your
        vision blurring as bright blue lights boom overhead. In the market
        everyone is either wobbling around as if in a trance, or on the ground
        asleep. You realize that these fireworks must be putting everyone to
        sleep. And for the last time, you trip and fall.
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
  name: 'A084GiveUpFollowingMarket',
}
</script>
