<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>You and Rah decide that's it's best not to take the food.</p>
      <p>
        <span class="rah">"I don't like the vibe he gives me,"</span> Rah says.
      </p>
      <p>
        As you two are walking away from the market Rah asks if you want to come
        over to their house and play board games. Usually you two like to run
        around in town, but maybe you'll have fun.
      </p>
      <p class="choices">
        <NuxtLink to="a039-suggest-woods"
          >Offer to go to the forest instead</NuxtLink
        >
        <NuxtLink to="a038-leave-market-rah">Head over to their house</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A031RejectFood',
}
</script>
