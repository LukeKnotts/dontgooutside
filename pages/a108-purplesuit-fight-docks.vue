<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You attempt to move, but your tired body isn't very responsive. In what
        feel like no time at all one of the purple workers is right in front of
        you. They throw their arm at your face too quickly for you to avoid. The
        last thing you see before you are knocked out is the creepy gas mask of
        purplesuit who punched you.
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
  name: 'A108PurplesuitFightDocks',
}
</script>
