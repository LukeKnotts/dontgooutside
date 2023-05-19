<template>
  <div class="about">
    <TopNav />
    <div class="container">
      <h1>About <em>Don't Go Outside</em></h1>
      <h6 class="subtitle">
        Created by Mattison Brown, Aris Fryer, John Knotts, and Luke Knotts
      </h6>
      <p>
        <em>Don't Go Outside</em> is an interactive novel inspired by the
        <em>Choose Your Own Adventure</em> books. Below are some of the people
        who contributed to <em>Don't Go Outside</em>. This project took us all a
        while, and is still kinda a work in progress. Thank you for taking a
        look at the things we're up to.
      </p>

      <p class="choices">
        <NuxtLink to="/">Check out the Game!</NuxtLink>
        <NuxtLink to="/gamehelp">Help Page</NuxtLink>
      </p>

      <hr />
      <h3>Credits!</h3>
      <p>
        Luke Knotts (Desing, Writting, Coding, Music, Art) is a creative type
        who enjoys making things. They have led development on this game, being
        helped by some cool people.
      </p>
      <p>
        "I want to add something important to this world that makes a meaningful
        difference."<br /><br />
      </p>

      <p>
        Mattison Brown (Graphics, Art), drew up all of the graphics that Luke
        edited and put into the game. Their art skills are why this game has
        some sick pics!!
      </p>
      <p>"Idk I can think about it"<br /><br /></p>

      <p>
        Aris Fryer (Music), is a composer and game developer. Aris produced the
        entire soundtrack, and wrote almost all of it as well.
      </p>
      <p>"idk what i want on my description yet"<br /><br /></p>

      <p>
        John Knotts (Coding, Design), taught Luke how to code the entirety of
        this game. And when it came to the advanced stuff, John handled those
        very well.
      </p>
      <p>"Ha! Nice"<br /><br /></p>

      <p>
        Elkan Lee (Writing), contributed ideas that eventually led to one of the
        main stories in <em>Don't Go Outside</em>.
      </p>
      <p>"don't get stuck in the past!"<br /><br /></p>

      <p>
        Nathan Branch (<NuxtLink class="secret" to="z000-error">0</NuxtLink>),
        had some ideas that were incorporated into this game. The have cool
        ideas.
      </p>
      <p>"You don't need to credit me"<br /><br /></p>

      <img src="~assets/images/test-images/IMG_0817.jpeg" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style>
img {
  width: 350px;
  height: 250px;
}
</style>
