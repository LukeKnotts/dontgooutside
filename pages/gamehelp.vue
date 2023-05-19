<template>
  <div class="about">
    <TopNav />
    <div class="container">
      <h1>Help Page</h1>
      <h6 class="subtitle">Maybe we can answer your questions!</h6>
      <p>
        <em>Don't Go Outside</em> is an interactive novel, where the reader
        interacts with the game. Feel free to play this game however you want
        (as long as it is legal).
      </p>

      <p>
        You play the game by reading and observing what is onscreen, and
        clicking on the links that match what you want to do in the game. For
        example, if the screen says that there is a red door and a blue door,
        and then prompts you with the question, "which door do you want to
        enter?" you would select the link that has the answer you like the best.
        Maybe in this scenario it would be the red door. After clicking the
        link, you would be taken to a new web page where the story would
        continue.
      </p>

      <p>
        If you ever get lost while playing the game, feel free to use the
        'Home,' 'About,' or 'Help' buttons on the top of most pages to navigate
        back to the Home page, About page, or Help page.
      </p>

      <p class="choices">
        <NuxtLink to="/">Check out the Game!</NuxtLink>
      </p>

      <hr />

      <h3>Site Map</h3>
      <p class="choices">
        <NuxtLink to="/">Home Page</NuxtLink>
        <NuxtLink to="/about">About Page</NuxtLink>
        <NuxtLink to="/gamehelp">Help Page (very elusive)</NuxtLink>
        <NuxtLink to="/a001-start">Title Screen</NuxtLink>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GameHelp',
}
</script>
