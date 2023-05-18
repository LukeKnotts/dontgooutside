<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You push through the crowd following Rah. Where are they going? What has
        gotten into them? You stagger after Rah listening to the boom's and
        bang's from the fireworks. You follow Rah back to the docks where all of
        the purplesuit workers are gathering.
      </p>
      <p><span class="rah">"They need to be... stopped..."</span> Rah yawns.</p>
      <p>
        Rah crumbles to the ground and immediately falls asleep. With the thud
        as Rah hits the ground the purplesuits turn to you. They are wearing
        monstrous industrial masks, and they begin to walk toward you.
      </p>
      <p class="choices">
        <NuxtLink to="a108-purplesuit-fight-docks">Fight!</NuxtLink>
        <NuxtLink to="a108-purplesuit-fight-docks">Negotiate</NuxtLink>
        <NuxtLink to="a108-purplesuit-fight-docks">Run!</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A098FollowRah',
}
</script>
