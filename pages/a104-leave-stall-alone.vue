<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You don't trust this guy, and his insistancy for you to try his soup
        doesn't help. He quickly shake your head to the chef and begin to walk
        the other way. It's probably best to just give them some space.
      </p>
      <p>Then you are lightly jerked backward as the man grabs your arm.</p>
      <p>
        <span class="chef">"I don't think you want to do that,"</span> smiles
        the chef.
      </p>
      <p class="choices">
        <NuxtLink to="a105-chef-fight">Fight</NuxtLink>
        <NuxtLink to="a105-chef-fight">Run</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A104LeaveStallALone',
}
</script>
