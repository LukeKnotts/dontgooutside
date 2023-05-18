<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah decide to take a closer look at this intriguing boat. You
        two walk a bit closer and see two men who seem to be unloading the boat.
        It looks like they're talking but they seem to be just out of earshot.
        Oddly, the workers are wearing purple uniforms that look similar to
        suits.
      </p>
      <p class="choices">
        <NuxtLink to="a028-dont-eavesdrop-boat">Turn back</NuxtLink>
        <NuxtLink to="a035-boat-eavesdrop-rah">Eavesdrop on them</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A027InvestigateBoatRah',
}
</script>
