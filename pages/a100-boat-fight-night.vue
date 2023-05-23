<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You curl your fingers into fists. Rah sees you, gulps, and does the
        same. You're going to fight this worker, and get to the bottom of this
        stupid thing. The worker opens the door, with a crazy looking mask on.
        The mask looks like a welder's mask, but more extravagant.
      </p>
      <p>
        Rah runs up to the man and throws a fist for their chest. Almost
        effortlessly, the purplesuit sidesteps them and shuvs them off of the
        boat. Rah screams as they fall into the water. You run at the
        purplesuit, but they're prepared. They counter and headbut you, metal
        mask to exposed face. You fall to the ground with a blunt thud. The last
        thing you see before going unconscious is the foot of the worker looming
        over you.
      </p>
      <p>
        You roll around. Something is stopping your normal movement. You can't
        see and you think your in a bag.
      </p>
      <p class="choices">
        <NuxtLink to="b003-kidnapped">Continue</NuxtLink>
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
  name: 'A100BoatFightNight',
}
</script>
