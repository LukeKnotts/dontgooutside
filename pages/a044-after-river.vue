<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        Rah and you continue for a little while. You two finish up a few games.
        Then Rah says that they have got to work on some things, so you decide
        to head home.
      </p>
      <p>
        That night, while you're trying to get some rest, you see some blue
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
  name: 'A044AfterRiver',
}
</script>
