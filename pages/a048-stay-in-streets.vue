<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        Blue light from the boat is cast on the crowds of moving people. You
        decide to stay at the edge of the docks. People pass by you following
        the strange purple boat man.
      </p>
      <p>
        It seems like most of the people left to the market, but a few stayed
        back at the docks like you. People are lingering around, drifting over
        to the market. The boat continues to sit idle in the water, bobbing up
        and down.
      </p>
      <p>
        A blue bolt blasts off from the boat, whistles through the air, and then
        explodes in the air with a huge BANG! A magnificant blue design spiders
        across the sky, and sparkly blue debree falls over the town beautifully.
      </p>
      <p>
        Then it hits you. A wave of exhaustion comes over you, and you can't
        help letting out a long dramatic yawn. You suddenly feel really tired.
        Your body feels heavy and you have little interest in being awake right
        now.
      </p>
      <p class="choices">
        <NuxtLink to="a070-ignore-fireworks-sleepy">Let yourself rest</NuxtLink>
        <NuxtLink to="a101-stumbling-docks-night">Go to that boat</NuxtLink>
        <NuxtLink to="a092-outside-too-late"
          >Figure out what's going on</NuxtLink
        >
        <NuxtLink to="b006-run">Run</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A048StayInStreets',
}
</script>
