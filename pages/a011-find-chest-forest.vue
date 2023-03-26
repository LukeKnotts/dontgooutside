<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You like to head out into the forest to have space to yourself. You
        enjoy exploring the woods. The forest outside of Chegckle is a
        completely different world. The forest floor doesn't see a lot of sun
        due to the trees, so on hot days the forest is a nice place to escape
        to.
      </p>
      <p>
        One day, as you're out strolling in the woods you see what seems to be
        an odd looking stone box. As you get closer you see it has intricate
        carvings of elaborate desings. You brush away the plants revealing an
        odd stone treasure chest. It is worn from the elements and seems to have
        been waiting under the brush for a while.
      </p>
      <p>
        The lid seems to be cracked slightly, and you might be able to open the
        chest.
      </p>
      <p class="choices">
        <NuxtLink to="b002-open-cyoa-chest">Open the chest</NuxtLink>
        <NuxtLink to="a019-avoid-stone-chest">Ignore it</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A11FindChestForest',
}
</script>
