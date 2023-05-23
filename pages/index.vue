<template>
  <div class="home">
    <TopNav />
    <div class="container">
      <h1>Don't Go Outside</h1>
      <h6 class="subtitle">
        Created by Mattison Brown, Aris Fryer, John Knotts, and Luke Knotts
      </h6>
      <p>
        Welcome to the <em>Don't Go Outside</em> home page! I hope you enjoy the
        silly project we've been working on! Just remember, if you're offered a
        coffee, don't except it.
      </p>
      <p class="choices">
        <NuxtLink to="/a001-start">Play Game</NuxtLink>
        <NuxtLink to="/about">What is <em>Don't Go Outside</em>?</NuxtLink>
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
  background-image: linear-gradient(rgb(199, 184, 170), rgb(165, 180, 186));
}

.about {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(199, 184, 170), rgb(186, 170, 165));
}

.title {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(199, 184, 170), rgb(51, 81, 99));
}

.phase1 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(234, 209, 187), rgb(186, 186, 165));
}

.phase1night {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(199, 178, 159), rgb(124, 163, 178));
}

.phase2forest {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(234, 209, 187), rgb(142, 169, 142));
}

.phase2blue {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(234, 209, 187), rgb(144, 160, 168));
}

.phase2brown {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-image: linear-gradient(rgb(234, 209, 187), rgb(162, 128, 119));
}

.phase3 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  background-color: rgb(243, 170, 212);
}

.container {
  min-height: 100vh;
  padding: 0 0 50px 0;
}

.rah {
  font-family: 'Alkatra', cursive;
  color: rgb(0, 0, 0);
}

.entertainer {
  font-family: 'Abril Fatface', cursive;
  color: rgb(0, 0, 0);
}

.radio715 {
  font-family: 'Rubik Pixels', cursive;
  color: rgb(0, 0, 0);
}

.physical715 {
  font-family: 'Kanit', sans-serif;
  color: rgb(0, 0, 0);
}

.radio51 {
  font-family: 'Rubik 80s Fade', cursive;
  color: rgb(0, 0, 0);
}

.phone-fake-cop {
  font-family: 'Nova Square', cursive;
  color: rgb(0, 0, 0);
}

.boat-worker1 {
  font-family: 'Gamja Flower', cursive;
  color: rgb(0, 0, 0);
}

.boat-worker2 {
  font-family: 'Handlee', cursive;
  color: rgb(0, 0, 0);
}

.chef {
  font-size: 32px;
  font-family: 'Tangerine', cursive;
  color: rgb(0, 0, 0);
}

.cookie-purplesuit {
  font-family: 'Comic Neue', cursive;
  color: rgb(0, 0, 0);
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
  color: rgb(32, 106, 130);
  text-decoration: underline;
  margin: 0% 20px 0% 20px;
}

a.secret {
  color: rgb(0, 0, 0);
  text-decoration: none;
  margin: 0%;
  cursor: text;
}

a.inlinelink {
  color: rgb(44, 118, 143);
  text-decoration: underline;
  margin: 0;
}

a:hover {
  color: rgb(22, 77, 96);
}

a.secret:hover {
  color: rgb(0, 0, 0);
  text-decoration: none;
  margin: 0% 0% 0% 0%;
  cursor: text;
}

.livium:hover {
  color: rgb(28, 151, 139);
}

p {
  text-indent: 0%;
  text-align: justify;
  text-justify: inter-word;
  margin: 20px 15% 20px 15%;
}

p.choices {
  text-align: center;
  margin-top: 50px;
  text-indent: 0%;
  text-justify: left;
}

p.choices a {
  display: inline-block;
  white-space: nowrap;
  margin-bottom: 20px;
}

h1 {
  margin: 5% 15% 5px 10%;
}

h1.errorheader {
  text-align: center;
}

h2 {
  text-align: center;
  margin: 5% 0 5px 0;
}

h3 {
  margin: 5% 15% 3% 15%;
}

h6.subtitle {
  margin: 5px 15% 3px 8%;
  color: rgb(77, 77, 77);
}

h6.muscue {
  margin: 5px 0 3px 0;
  color: rgb(77, 77, 77);
  text-align: center;
}

p.errortext {
  text-align: center;
  font-family: 'Times New Roman', Times, serif;
}

p.unformatted {
  text-align: left;
}

.invisible {
  font-size: 1px;
}

@media (max-width: 700px) {
  p {
    font-size: 13px;
    line-height: 1.6em;
  }
}

@media (max-width: 500px) {
  p.choices a {
    display: block;
    white-space: normal;
  }

  @media (max-width: 500px) {
    h6.subtitle {
      font-size: 12px;
      line-height: 1.4em;
    }
  }

  @media (max-width: 500px) {
    h6.muscue {
      font-size: 12px;
      line-height: 2em;
    }
  }
}
</style>
