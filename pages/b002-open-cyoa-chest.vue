<template>
  <div class="phase2">
    <TopNav class="topnav-phase2" />
    <div class="container">
      <p>
        You lift up the lid of the chest. You are able to remove the heavy stone
        lid of the chest. Inside is a small wood box with similar carvings on
        it. You lift the small box out of the chest and carefully open it.
        Inside is a moederately large piece of paper, rolled up and tied with a
        red ribbon.
      </p>
      <p>
        You untie the ribbon and unroll the paper. The paper feels old and has a
        sweet scent to it. You hold out the paper to see what is on it. On the
        paper is a strangely drewn map, leading to an 'X' somewhere up in the
        mountains. And, it doesn't look too far away.
      </p>
      <p class="choices">
        <NuxtLink to="phase-2-soon-maybe">Go to the 'X'</NuxtLink>
        <NuxtLink to="a019-avoid-stone-chest">Head back home</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'B002OpenCyoaChest',
}
</script>
