<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>The cheff frowns again.</p>
      <p>
        <span class="cheff">"I'm so sorry to hear that,"</span> He says,
        sounding a little bit happy.<span class="cheff"> "You know..."</span>
        the man offers,
        <span class="cheff"
          >"You could come behind the curtain, and I could show you how we make
          all of our delicious soups,"</span
        >
        they offer.
      </p>
      <p>He smiles at you, waiting for an answer.</p>
      <p class="choices">
        <NuxtLink to="a079-behind-purple-curtain"
          >Go behind the curtain</NuxtLink
        >
        <NuxtLink to="a104-leave-stall-alone">Leave the stand</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A087DenySoupAgainAlone',
}
</script>
