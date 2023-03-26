<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You arn't sure you trust this man. You deny the soup, just to be same.
        The man frowns
      </p>
      <p><span class="cheff">"Are you sure?"</span> They ask.</p>
      <p>They seem hurt by your refusal.</p>
      <p class="choices">
        <NuxtLink to="a056-try-soup-alone">Try the soup</NuxtLink>
        <NuxtLink to="a087-deny-soup-again-alone"
          >Reject the soup again</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A078DenySoupAlone',
}
</script>
