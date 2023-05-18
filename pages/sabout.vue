<template>
  <div class="about">
    <TopNav />
    <div class="container">
      <h1>About <em>Don't Go Outside</em></h1>
      <p>
        <em>Don't Go Outside</em> is an interactive novel inspired by the
        <em>Choose Your Own Adventure</em> books. Below are the creators of
        <em>Don't Go Outside</em>. -- Luke Knotts (Desing, Writting, Coding),
        some other people, and Nathan Branch (<NuxtLink
          class="secret"
          to="z000-error"
          >0</NuxtLink
        >).
      </p>
      <img src="~/static/Images/Test Images/IMG_0817.jpeg" />
      <p class="choices">
        <NuxtLink to="/">Check out the Game!</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SAboutPage',
}
</script>

<style>
img {
  width: 350px;
  height: 250px;
}
</style>
