<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You decide that it is best not to eavesdrop on the workers. That's
        disrespectful to their privacy! You and Rah decide to leave the docks
        and stop watching this boat. You're pretty tired, so you decide to head
        home for the evening.
      </p>
      <p>
        You get back to your house and decide to call it a night. You get into
        bed and try to get some sleep.
      </p>
      <p>
        Then, all of a sudden, a flash of blue light jolts you awake. A
        flikering light is coming from out of your window. You take a look out
        your window and see blue light coming from the docks, and a crowd
        gathering there.
      </p>
      <p class="choices">
        <NuxtLink to="a026-late-night-entertainment">Check it out</NuxtLink>
        <NuxtLink to="a033-ignore-blue-lights">Ignore it</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A028DontEavesdropBoat',
}
</script>
