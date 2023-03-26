<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah enjoy hanging out together. Sometimes you hang out at your
        house, and sometimes theirs. You two like to play board games like river
        together.
      </p>
      <p>
        One day, while at Rah's house they begin to pick up some sound on the
        radio parts they have been tinkering with. Rah enjoys tinkering with
        things, and had been messing with some radio parts they've found. But
        now, the radio is beginning to buzz.
      </p>
      <p>
        <span class="rah">"Hey! I'm picking up something!"</span> Rah exclaims.
      </p>
      <p class="choices">
        <NuxtLink to="a020-ignore-radio">Ignore it</NuxtLink>
        <NuxtLink to="a032-radio-listening">Listen</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A012NeighborsHangWithRah',
}
</script>
