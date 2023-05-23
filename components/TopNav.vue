<template>
  <nav>
    <div>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
      <div class="alignright">
        <NuxtLink to="/gamehelp">Help</NuxtLink>
      </div>
    </div>
  </nav>
</template>

<style>
nav {
  font-family: 'Roboto Slab', serif;
  font-size: 24px;
  background: rgb(236, 30, 255);
  padding: 0.5% 0;
}

@media (max-width: 700px) {
  nav {
    font-size: 18px;
    padding: 0.2% 0;
  }
}

.alignright {
  float: right;
  padding: 0 3% 0.5% 0 0;
}

.home nav {
  background: rgb(149, 154, 160);
}

.about nav {
  background: rgb(160, 155, 149);
}

.title nav {
  background: rgb(149, 154, 160);
}

.phase1 nav {
  background: rgb(173, 163, 161);
}

.phase1night nav {
  background: rgb(170, 161, 159);
}

.phase2forest nav {
  background: rgb(166, 183, 184);
}

.phase2blue nav {
  background: rgb(166, 183, 184);
}

.phase2brown nav {
  background: rgb(184, 179, 166);
}
.phase3 nav {
  background: rgb(177, 215, 206);
}

a {
  margin: 0% 2% 0% 2%;
}
</style>
