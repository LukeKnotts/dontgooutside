<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        Free cookies, perhaps it isn't a horrible thing. You take one of the
        cookies and take a bite from it. It tastes a little weird and your
        stomach feels like it does a quick summersault. A blue light from across
        the town flashes against the cookie person's face, and they smile.
        Little do you know, that will be the last cookie you ever eat. Well, now
        you do, because I just told you.
      </p>
      <p class="choices">
        <NuxtLink to="a068-bad-cookie">Continue</NuxtLink>
      </p>

      <audio controls autoplay loop="true" hidden="true">
        <source src="/music/gameplay/purplelullaby.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A058TakeACookie',
}
</script>
