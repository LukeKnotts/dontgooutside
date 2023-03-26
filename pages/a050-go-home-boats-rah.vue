<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You feel kind of uncomfortable. Rah seems to be feeling similarly. You
        decide that you're going to head home for the day. You tell Rah maybe
        you two should go home, and they agree.
      </p>
      <p>
        You and Rah walk toward your homes and eventually split up. You wave to
        Rah as they go toward their house. Hopefully those weirdos at the dock
        are not involved in anything serious, and you'll have an uneventful
        night. You think you made the right choice coming home and avoiding the
        situation.
      </p>
      <p class="choices">
        <NuxtLink to="a034-stay-indoors">Stay indoors</NuxtLink>
        <NuxtLink to="a060-call-police">Go home and call the police</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A036GoHomeBoatsRah',
}
</script>
