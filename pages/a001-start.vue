<template>
  <div class="title">
    <TopNav />
    <div class="container">
      <h2>Don't Go Outside</h2>
      <h6 class="muscue">
        Created by Mattison Brown, Aris Fryer, John Knotts, and Luke Knotts
      </h6>
      <h6 class="muscue">*cue the title music*</h6>
      <h6 class="muscue">*have fun!*</h6>
      <p class="choices">
        <NuxtLink to="/a003-start-in-chegckle">Start</NuxtLink>
        <NuxtLink to="/a002-early-end">Don't start</NuxtLink>
      </p>

      <audio controls autoplay loop="true" hidden="true">
        <source src="/music/gameplay/title.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A002EarlyEnd',
}
</script>
