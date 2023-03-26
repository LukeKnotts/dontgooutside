<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You don't like the factories. They're big and dirty. You wish that
        Chegckle was, maybe a fishing town. Even though, it's very well possible
        that if mining was as big as it was back in the day, you would like
        Chegckle even less than you do now.
      </p>
      <p>
        Since you don't enjoy spending your time around the factories, where do
        you hang out?
      </p>
      <p class="choices">
        <NuxtLink to="/a006-forest-hang-with-rah"
          >The forest outside Chegckle</NuxtLink
        >
        <NuxtLink to="/a007-home-hang-with-rah">My house</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A004DislikesFactories',
}
</script>
