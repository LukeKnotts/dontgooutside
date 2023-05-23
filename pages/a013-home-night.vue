<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You would rather read and work on things on your own. You don't hate
        Rah, you just arn't particularly intersted in hanging out.
      </p>
      <p>
        One night, while you're trying to get some rest, you see some blue
        flikering lights coming from out of your window. You look out your
        window to see the light coming from the docks, and a crowd gathering
        there.
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
  name: 'A013HomeNight',
}
</script>
