<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        What are these people up to? You decide the best thing to do is to
        investigate the stand. The person at the counter seems to be a cook. You
        want to see what they're selling so you ask the man at the stand.
      </p>
      <p>You ask the him what's for sale, to which they smile.</p>
      <p>
        <span class="cheff">
          "Oh, no need for money. Since you're new, let me bring you the cheff's
          special,"</span
        >
        they man chirps cheerily.
      </p>
      <!--
        Don't worry, the cheff's special is gluten free.
        -->
      <p>
        Quickly, the man steps behind the purple curtain. You hear some
        sizziling and the clanging of pots and pans from behind the curtain. Not
        long later, he emerges again. In the cheff's hands is moderately sized
        thin metal bowl. He sets it on the counter in front of you, and waits
        there smiling. The soup smells amazing.
      </p>
      <p class="choices">
        <NuxtLink to="a056-try-soup-alone">Try the soup</NuxtLink>
        <NuxtLink to="a078-deny-soup-alone">Reject the soup</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A055InvestigateStandBoats',
}
</script>
