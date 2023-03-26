<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You practically dive down the stairs. You don't want to be caught
        snooping around.
      </p>
      <p>
        Inside the lower room is the engine, and some sleeping cots. But on the
        walls, making the room feel small, are shelves with bagged bodies. You
        are scared. You begin frantically searching the room for a good place to
        hide.
      </p>
      <p>
        Someone in a sharp purple suit walks down the stairs of the boat and
        faces you. You hear a soft chuckle, and you see the purple-suited worker
        smile.
      </p>
      <p class="choices">
        <NuxtLink to="a103-boat-fight">Negotiate</NuxtLink>
        <NuxtLink to="a103-boat-fight">Fight!</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A095BelowDeck',
}
</script>
