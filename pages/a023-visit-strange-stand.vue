<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        It isn't often that new stalls open in the market. You wonder what this
        new stand has to offer, and who operates it. You approach the odd stand.
        It has lots of strange decorations and trickets. It intrigues you.
      </p>
      <p>
        You approach the stand. The stand has a tent that extends behind itself
        with a curtain that conceals what's behind. In front of the curtain is a
        old man dressed in an odd purple suit. He welcomes you two jollily.
      </p>
      <p>
        <span class="chef"
          >"Would you two like to try the amazing chef's special? It's
          fresh!"</span
        >
        the chef tells you.
      </p>
      <p>
        A delightful smell leaks from behind the stall's curtain. He smiles
        enthusiastically.
      </p>
      <p class="choices">
        <NuxtLink to="a031-reject-food">Say 'no'</NuxtLink>
        <NuxtLink to="a030-try-food">Try the food</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A023VisitStrangeStand',
}
</script>
