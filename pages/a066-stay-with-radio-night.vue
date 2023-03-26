<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You and Rah agree to stay indoors. Who knows what is going on out there,
        but figuring out this radio thing is your main priority right now. You
        sit in Rah's room as they continually fiddle with the machine.
      </p>
      <p>
        BANG! The sound of a firework cracks over town. What is going on? Very
        rarely are there ever fireworks in Chegckle.
      </p>
      <p><span class="rah">"What is going on?"</span> Rah jumps.</p>
      <p>
        Has there ever been a weirder night in Chegckle? Hopefully it's just a
        bunch of inmature kids, who got ahold of some fireworks. Then Rah lets
        out a yawn, and so do you. A wave of exhaustion comes over you, and you
        suddenly feel very drowsy.
      </p>
      <p class="choices">
        <NuxtLink to="a088-ignore-fireworks-rah">Stay indoors</NuxtLink>
        <NuxtLink to="a097-investigate-bang-rah"
          >See what's going on outside</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A066StayWithRadioNight',
}
</script>
