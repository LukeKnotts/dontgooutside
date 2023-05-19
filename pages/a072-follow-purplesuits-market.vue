<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        As soon as the purple suited people attempted to dissolve into the
        crowd, you kept your eyes on them. You don't trust them or their fancy
        fireworks. You need to follow these people. So you do. You push your way
        through the crowd, fighting the erge to fall asleep.
      </p>
      <p>
        You see the purple-dressed stranger you have been following take a turn
        down an alley. Their turn was in the direction of the docks, where their
        boat is.
      </p>
      <p class="choices">
        <NuxtLink to="a074-following-purplesuit-alley"
          >Follow them into the alley</NuxtLink
        >
        <NuxtLink to="a082-go-to-their-boat">Go to the docks</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A072FollowPurplesuitsMarket',
}
</script>
