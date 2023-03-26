<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>You creep a little closer to hear what they're saying.</p>
      <p>
        <span class="boat-worker1">"This is going to be big,"</span> one of them
        says.
      </p>
      <p>
        <span class="boat-worker2">
          "Whatever, let's just get along with it. The same thing happens to
          every town. You know the entertainment is just a distraction,"</span
        >
        the other worker says.
      </p>
      <p>
        <span class="boat-worker1">
          "Do you think they're going to do those fireworks again? Those were
          incredible. You'd better not just stay below deck tonight. Soon
          enough, when we move on with our lives, you'd'a wished you enjoyed
          these things while we had 'em."</span
        >
      </p>
      <p>
        You wonder what they could be talking about. Whatever they're doing
        sounds highly suspicious. And what they're doing sounds fairly
        intersting, but what intersting thing would somebody want to do in
        Chegckle?
      </p>
      <p class="choices">
        <NuxtLink to="a036-go-home-boats-alone"
          >Leave the docks and go home</NuxtLink
        >
        <NuxtLink to="a052-boat-eavesdrop-alone-contd">Keep watching</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A029BoatEavesdropAlone',
}
</script>
