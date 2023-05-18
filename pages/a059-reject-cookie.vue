<template>
  <div class="phase1night">
    <TopNav />
    <div class="container">
      <p>
        You decline their offer. Taking cookies from a stranger doesn't seem
        like the best idea. Before you can close the door, the salesperson
        continues to speak
      </p>
      <p>
        <span class="cookie-purplesuit">"C'mon! They're fresh!"</span> they say,
        smiling somehow even bigger.
      </p>
      <p class="choices">
        <NuxtLink to="a058-take-a-cookie">Take a cookie</NuxtLink>
        <NuxtLink to="a069-reject-cookie-again">Do not take a cookie</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A059RejectCookie',
}
</script>
