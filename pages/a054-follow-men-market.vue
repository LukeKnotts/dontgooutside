<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        What are these people up to? You decide to follow them to the market.
        You follow the two workers to a strange looking market stall. The smell
        of a savory soup and something sweet seep out of the stand. Beyond the
        stand's table, a large purple curtain conceals the source of the smells.
      </p>
      <p>
        The two workers from the docks go around the stall's desk, and behind
        the curtains of the market stand. You continue to watch the stall
        attentively. Then a man dressed in an odd purple suit emerges from the
        curtain, smiling in an uncomfortably welcoming way. The purple suited
        man looks around, seemingly for customers to the stand. It appears they
        are trying to sell some sort of food.
      </p>
      <p class="choices">
        <NuxtLink to="a062-boat-unattended">Go back to the boat</NuxtLink>
        <NuxtLink to="a055-investigate-stand-boats"
          >Order some food from the stand</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A054FollowMenMarket',
}
</script>
