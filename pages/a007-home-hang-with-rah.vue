<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You like to spend your time indoors. You busy yourself with books on all
        the topics that interest you, and enjoy playing board games. You
        especially enjoy the classic board game river.
      </p>
      <p>
        Your neighbor Rah seems to have similar interests to you. Do you hang
        out with them?
      </p>
      <p class="choices">
        <NuxtLink to="a012-neighbors-hang-with-rah">Yes</NuxtLink>
        <NuxtLink to="a013-home-night">No</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A007HomeHangWithRah',
}
</script>
