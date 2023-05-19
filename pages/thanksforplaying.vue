<template>
  <div class="phase2brown">
    <TopNav />
    <div class="container">
      <h6 class="muscue">Thanks for Playing!</h6>
      <p>
        Thank you for taking the time to play our game. You can head over to the
        <NuxtLink to="about">About Page</NuxtLink> to go see everyone who has
        contributed to this project, a huge thanks from all of us!
      </p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Again</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ThanksForPlaying',
}
</script>
