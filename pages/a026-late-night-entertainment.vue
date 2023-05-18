<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        A crowd of people are flocking toward the docks and a dazzling blue
        light is being emitted from a funky and luxurious looking boat. You join
        the crowd and stop in front of the boat. A man in a fancy purple suit
        welcomes the crowd gathering in a circle around him and the boat.
        There's more people than you thought here.
      </p>
      <p>
        <span class="entertainer"
          >"Hello everyone! We have an extra special performance for you all
          tonight. Please, move along to the market plaza, and we'll show you
          the show of your lives!"</span
        >
        As the man says this, they twirl with their arms out.
      </p>
      <p>
        Some other people dressed in similar purple outfits are carrying boxes
        onto the boat. The man and a few people behind him turn and set off in
        the direction of the market. The crowd curiously begins behind him.
      </p>
      <p class="choices">
        <NuxtLink to="a033-ignore-blue-lights">Go back to your house</NuxtLink>
        <NuxtLink to="a048-stay-in-streets"
          >Stay in the street by the docks</NuxtLink
        >
        <NuxtLink to="a049-firework-show-market"
          >Follow them to the market</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A026LateNightEntertainment',
}
</script>
