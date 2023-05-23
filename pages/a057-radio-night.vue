<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You tell Rah that you two need to keep listening to the radio. Rah seems
        stressed, but you are able to calm them down. You don't like this
        either. You watch Rah tinker with the radio until it's dark outside. As
        Rah is working, a blue light flahses into the room from outside the
        window.
      </p>
      <p>
        You and Rah get up and look out the window. You two see a crowd
        gathering around the colorful light source, coming from the docks.
      </p>
      <p class="choices">
        <NuxtLink to="a066-stay-with-radio-night"
          >Stay indoors with the radio</NuxtLink
        >
        <NuxtLink to="a067-late-night-entertainment-rah">Check it out</NuxtLink>
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
  name: 'A057RadioNight',
}
</script>
