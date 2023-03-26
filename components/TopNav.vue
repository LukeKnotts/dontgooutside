<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
  </nav>
</template>

<style>
nav {
  font-family: 'Roboto Slab', serif;
  font-size: 25px;
  background: rgb(236, 30, 255);
  padding: 0.5% 0;
}
.home nav {
  background: rgb(166, 175, 184);
}

.about nav {
  background: rgb(166, 175, 184);
}

.phase1 nav {
  background: rgb(173, 163, 161);
}

.phase2 nav {
  background: rgb(166, 183, 184);
}

.phase3 nav {
  background: rgb(177, 215, 206);
}

a {
  margin: 0% 2% 0% 2%;
}
</style>
