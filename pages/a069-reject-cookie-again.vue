<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        Their insistency only makes you more reluctant to take a cookie. You
        tell them no, and then close the door. You stand behind your frontdoor,
        thankful for locks.
      </p>
      <p>
        BANG! Suddenly the sound of a fireworks jolts the last bit of sleepiness
        out of you. Now you're really agitated.
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
  name: 'A069RejectCookieAgain',
}
</script>
