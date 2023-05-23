<template>
  <div class="home">
    <TopNav />
    <div class="container">
      <p class="question-end">The End.</p>
      <p>Your journey ended before it could begin.</p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Again</NuxtLink>
      </p>

      <audio controls autoplay loop="true" hidden="true">
        <source src="/music/gameplay/mainmenuwierdDGOS.mp3" type="audio/mpeg" />
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
