<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah enjoy running around the market together exploring the
        market. It's cool to see all of the different buisnesses.
      </p>
      <p>
        One day, while at the market, you and Rah see a strange new stand. It
        isn't often new stands open in the market, and this stand stands out in
        an odd way.
      </p>
      <p>
        <span class="rah"
          >"I've never seen a purple tent behind a market stand before,"</span
        >
        Rah muses.
      </p>
      <p class="choices">
        <NuxtLink to="a024-avoid-strange-stand">Avoid the stand</NuxtLink>
        <NuxtLink to="a023-visit-strange-stand">Check out the stand</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A016StrangeStandRah',
}
</script>
