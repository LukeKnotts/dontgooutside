<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You decide that it would be a good idea to leave the market for today.
        You excpet Rah's offer, and you two head to their home. You two leave
        the market without another sketchy encounter, and get home safely.
      </p>
      <p>
        Once you get to Rah's house, they get out a river set and some seemingly
        random pieces of metal and wires.
      </p>
      <p>
        <span class="rah">"I found these radio parts in a dumpster!"</span> they
        exclaim.
      </p>
      <p>
        Rah holds out the old pieces of metal in their hands so you can see them
        better.
      </p>
      <p>
        <span class="rah">
          "So, wanna mess with these radio parts, or play a game of river or
          something?"</span
        >
        they say, turning to you.
      </p>
      <p class="choices">
        <NuxtLink to="a043-river-with-rah">River</NuxtLink>
        <NuxtLink to="a032-radio-listening">Radio parts</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A038LeaveMarketRah',
}
</script>
