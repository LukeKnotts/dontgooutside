<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You try not to worry about it. You decide that it might not be best to
        be out there, it's probably just a street party or something. You're
        staying indoors tonight.
      </p>
      <p>
        Suddenly you hear a knocking on your door. You don't really feel like
        answering it at this time of night.
      </p>
      <p class="choices">
        <NuxtLink to="a046-answer-the-door">Answer the door</NuxtLink>
        <NuxtLink to="a047-ignore-knocking">Ignore it</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A033IgnoreBlueLights',
}
</script>
