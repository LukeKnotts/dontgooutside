<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You continue to watch, trying to enjoy the show. Bang! Bang! With each
        firework you get even more tired, barely able to hold your
        consciousness. The fireworks make pretty patterns in the sky, but
        eventually you can't stay awake any longer. Soon enough, you blink off
        to sleep. Enjoying this light show will be last thing you choose to do.
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
  name: 'A071WatchingFireworks',
}
</script>
