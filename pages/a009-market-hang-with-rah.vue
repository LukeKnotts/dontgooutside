<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You enjoy spending your time running around the market exploring the
        market stalls. All the different buisness and what they sell you find
        quite interesting. The market is one of your favorite places in
        Chegckle.
      </p>
      <p>
        Your neighbor Rah seems to have similar interests as you. Do you hang
        out with them?
      </p>
      <p class="choices">
        <NuxtLink to="a017-market-alone">No</NuxtLink>
        <NuxtLink to="a016-strange-stand-rah">Yes</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A009MarketHangWithRah',
}
</script>
