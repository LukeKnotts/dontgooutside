<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You avoid the stone structure. It's probably the ruins of an old
        facotory, and messing with broken rocks doesn't really peak your
        interest. You decide to leave the woods.
      </p>
      <p>
        That night, as you're trying to get some rest, you see something out
        your window. You look out to see strange blue lights flickering from the
        docks, and a crowd gathering there.
      </p>
      <p class="choices">
        <NuxtLink to="a026-late-night-entertainment">Check it out</NuxtLink>
        <NuxtLink to="a033-ignore-blue-lights">Ignore it</NuxtLink>
      </p>

      <audio controls autoplay loop="true" hidden="true">
        <source src="/music/gameplay/windowlights.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A019AvoidStoneChest',
}
</script>
