<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah head outside sleepily. Fireworks unravel in the sky above
        you two. People are lingering about the streets all around, in a tired
        and haphazard manner. You and Rah anxiously look around, but your
        drowsiness is hindering your senses. You can see the boat in the docks
        that was emitting all the light, being loaded by several workers dressed
        in purple. Rah spins around, struggling to stand upright.
      </p>
      <p>
        <span class="rah">"What if these fireworks are toxic..."</span>Rah
        attempts to say, but before they can finish anything, they let out a
        massive yawn.
      </p>
      <p class="choices">
        <NuxtLink to="a106-investigate-sleepy-rah"
          >Investigate the commotion</NuxtLink
        >
        <NuxtLink to="a107-investigate-boat-rah-night"
          >Stop the purplesuits from leaving</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A097InvestigateBangRah',
}
</script>
