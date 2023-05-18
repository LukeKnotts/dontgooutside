<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You don't answer the door. If you wanted to socialize you would've
        headed out to that street party or whatever it was. Whoever it is knocks
        again. After a moment, you hear footsteps leaving your doorstep.
      </p>
      <p>
        BANG! You jump as the loud sound of a firework explodes overhead. You're
        considerably agitated.
      </p>
      <p class="choices">
        <NuxtLink to="a070-ignore-fireworks-sleepy"
          >Ignore it, and try to go to sleep</NuxtLink
        >
        <NuxtLink to="a080-go-outside-finally">See what's going on</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A047IgnoreKnocking',
}
</script>
