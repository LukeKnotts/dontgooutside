<template>
  <div class="home">
    <TopNav />
    <div class="container">
      <h1>Home Page</h1>
      <p>
        Welcome to [Untitled CYOA Game]! Please enjoy! Just remember, if you're
        offered a coffee, don't except it.
      </p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Game</NuxtLink>
        <NuxtLink to="/about">What is CYOA Game?</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
body {
  font-size: 20px;
  line-height: 1.4em;
  margin: 0;
  padding: 0;
}

.home {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(201, 211, 213);
}

.about {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(213, 207, 201);
}

.phase1 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(234, 209, 187);
}

.phase2 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(201, 219, 225);
}

.phase3 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(245, 130, 197);
}

.container {
  min-height: 100vh;
  padding: 0 0 50px 0;
}

.rah {
  font-family: serif;
  color: rgb(65, 153, 22);
}

.entertainer {
  font-family: serif;
  color: rgb(210, 145, 47);
}

.radio715 {
  font-family: serif;
  color: blue;
}

.physical715 {
  font-family: serif;
  color: rgb(102, 102, 223);
}

.radio51 {
  font-family: serif;
  color: red;
}

.phone-fake-cop {
  font-family: serif;
  color: brown;
}

.boat-worker1 {
  font-family: serif;
  color: purple;
}

.boat-worker2 {
  font-family: serif;
  color: rgb(229, 32, 206);
}

.cheff {
  font-family: serif;
  color: grey;
}

.cookie-purplesuit {
  font-family: serif;
  color: rgb(11, 158, 119);
}

.question-end {
  font-family: serif;
  color: red;
}

.sweet-end {
  font-family: serif;
  color: rgb(255, 0, 255);
}

.firework-end {
  font-family: serif;
  color: rgb(0, 51, 255);
}

a {
  color: rgb(51, 143, 174);
  text-decoration: underline;
  margin: 0% 20px 0% 20px;
}

a.secret {
  color: rgb(0, 0, 0);
  text-decoration: none;
  margin: 0%;
  cursor: text;
}

a:hover {
  color: rgb(34, 112, 138);
}

a.secret:hover {
  color: rgb(0, 0, 0);
  text-decoration: none;
  margin: 0% 0% 0% 0%;
  cursor: text;
}

.livium:hover {
  color: rgb(33, 183, 168);
}

p {
  text-indent: 10%;
  margin: 20px 15% 20px 15%;
}

p.choices {
  text-align: center;
  margin-top: 50px;
  text-indent: 0%;
}

p.choices a {
  display: inline-block;
  white-space: nowrap;
  margin-bottom: 20px;
}

@media (max-width: 500px) {
  p.choices a {
    display: block;
    white-space: normal;
  }
}
</style>
