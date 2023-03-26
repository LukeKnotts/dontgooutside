<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You yawn and pull open the door. Whoever it is, it better be important.
        On your doorstep is a strange looking person in a purple tuxedo,
        carrying a large tray of cookies. Their snazy suit is spotless, and the
        cookies look good. But then again, now isn't really a desireable time
        for door-to-door salespeople.
      </p>
      <p>
        <span class="cookie-purplesuit">
          "Care to try a cookie? They're fresh, and onehundred percent
          free!"</span
        >
        says the cheerful purple-dressed salesperson.
      </p>
      <p>They give a large hearty smile, but in an unsettling way.</p>
      <p class="choices">
        <NuxtLink to="a058-take-a-cookie">Try a cookie</NuxtLink>
        <NuxtLink to="a059-reject-cookie">Do not try a cookie</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A046AnswerTheDoor',
}
</script>
