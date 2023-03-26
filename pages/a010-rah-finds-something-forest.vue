<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah enjoy exploring the woods together. The forest outside of
        Chegckle is a completely different world. The forest floor doesn't see a
        lot of sun due to the trees, so on hot days the forest is a nice place
        to escape to.
      </p>
      <p>One day Rah knocks on your door bursting with excitement.</p>
      <p>
        <span class="rah">"I found the coolest thing in the woods!"</span> they
        say with excitement.
      </p>
      <p class="choices">
        <NuxtLink to="b001-cyoa-chest-rah">Check it out</NuxtLink>
        <NuxtLink to="a018-youve-got-mail">Tell Rah You're Busy</NuxtLink>
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'A010RahFindsSomethingForest',
}
</script>
