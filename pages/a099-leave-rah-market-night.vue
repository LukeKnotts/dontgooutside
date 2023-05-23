<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You know it is important to see what is going on. You trust Rah to take
        care of themselves, but you need to keep an eye on what these purple
        firework people are doing. You look up at their 'show.' What are they
        trying to do here?
      </p>
      <p>
        Bang! Bang! Each firework makes you more tired than the last, but you
        continue to watch, trying to figure out what is going on. Bang. Bang...
        Ba... ng... You try not to fall asleep, but eventually, you blink off to
        sleep. Soon you'll wake up, you just won't be the same.
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
  name: 'A099LeaveRahMarketNight',
}
</script>
