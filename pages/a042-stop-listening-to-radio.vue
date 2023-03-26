<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You inform Rah that you two have just intercepted a stranger's radio
        call, and should just ignore it. You turn off the radio. Rah frowns.
      </p>
      <p>
        <span class="rah">"We can play river or something else,"</span> Rah
        says, sounding disappointed.
      </p>
      <p class="choices">
        <NuxtLink to="a021-come-home-night">Leave Rah's house</NuxtLink>
        <NuxtLink to="a043-river-with-rah">Play river with Rah</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A042StopListeningToRadio',
}
</script>
