<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        The factories have always facinated you. The complex things that happen
        inside them, processing raw material or making things at superhuman
        speeds, it all interests you.
      </p>
      <p>
        You like the indsutrial areas of Chegckle, and learning about things in
        town. Where do you like to spend your time?
      </p>
      <p class="choices">
        <NuxtLink to="a007-home-hang-with-rah">My house</NuxtLink>
        <NuxtLink to="a008-watch-boats-unload"
          >The docks watching boats</NuxtLink
        >
        <NuxtLink to="a009-market-hang-with-rah">Exploring the market</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A005LikesFactories',
}
</script>
