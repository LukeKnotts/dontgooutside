<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p><span class="chef">"I'm sorry to hear that,"</span> says the chef.</p>
      <p>There is an awkward pause before they speak again.</p>
      <p>
        <span class="chef"
          >"Well, feel free to come back and try the soup."</span
        >
      </p>
      <p>
        The man seems offended, but simply smiles. You and Rah leave the stand,
        and give yourselves a decent amount of distance from that strange purple
        suited man.
      </p>
      <p>
        <span class="rah">
          "Should we go back to watch the boats? Or maybe we should just go
          home."</span
        >Rah asks.
        <span class="rah"
          >"It might be best to just try to avoid these people."</span
        >
      </p>
      <p class="choices">
        <NuxtLink to="a050-go-home-boats-rah"
          >Avoid these people and go home</NuxtLink
        >
        <NuxtLink to="a061-boat-unattended-rah"
          >Go back and watch the boats</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A086DenySoupAgainRah',
}
</script>
