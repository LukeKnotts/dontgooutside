<template>
  <div class="home">
    <TopNav />
    <div class="container">
      <p class="question-end">The End.</p>
      <p>Your journey ended before it could begin.</p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Again</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A002EarlyEnd',
}
</script>
