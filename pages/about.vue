<template>
  <div class="about">
    <TopNav />
    <div class="container">
      <h1>About Page</h1>
      <p>
        [Untitled CYOA Game] is an interactive novel inspired by the choose your
        own adventure books, created by Luke Knotts (Desing, Writting, Coding),
        some other people, and Nathan Branch (<NuxtLink
          class="secret"
          to="z000-error"
          >0</NuxtLink
        >).
      </p>
      <p class="choices">
        <NuxtLink to="/">Check out the Game!</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>
