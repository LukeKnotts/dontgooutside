<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You enjoy going to the river docks alone to watch the boats. Sitting
        under a tree, you watch as the different kinds of ships and steamers
        load or unload in Chegckle. Most of the people seem to sleep inside
        their boats. You find these otherwordly ships fascinating.
      </p>
      <p>
        One day a strange looking steamer docks at the river. It is longer that
        most ships and is built from sleek shiny metal. It has lots of flashy
        lights and looks extremely fancy. It seems to be steam powered but the
        ship seems powerful and strong. From the size, you guess that it has a
        small below deck room too, aside from its top cabin. You wonder where
        this boat could be from.
      </p>
      <p class="choices">
        <NuxtLink to="a021-come-home-night">Ignore it</NuxtLink>
        <NuxtLink to="a022-watching-boat-unload">Check it out</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A015WatchBoatsAlone',
}
</script>
