<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        What is this message? Who is 715? What is 'careful with those,' supposed
        to mean?
      </p>
      <p>
        Your curiosity has been churned and you're eager to learn more. You tell
        Rah to keep the radio on. Rah agrees with you, just as curious.
      </p>
      <p>
        But this sounds almost like it could be dangerous. Do you know enough?
        Is it necessary to talk to someone about this? Could it just be some
        random people goofing around? Part of this seems all too serious, and
        you wonder if getting someone else involved is a good idea.
      </p>
      <p class="choices">
        <NuxtLink to="a036-go-home-boats-alone"
          >Go home and be cautious.</NuxtLink
        >
        <NuxtLink to="a045-staying-at-rahs"
          >Sleep at Rah's to keep listening</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A041KeepRadioOn',
}
</script>
