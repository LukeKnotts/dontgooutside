<template>
  <div class="sorry">
    <p class="heading">Unfinished Area</p>
    <p class="sorrypara">
      This part of the website is unfinished. Sorry to leave you hanging. Please
      feel free to pick another route instead.
      <NuxtLink class="sorrylink" to="a001-start">Back to Beginning</NuxtLink>
    </p>
  </div>
</template>

<style>
p.sorrypara {
  text-indent: 0;
  text-align: left;
  width: 93%;
  margin: 2% auto;
}

.sorry {
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: 18px;
  background: rgb(145, 156, 178);
  padding: 0.5% 0;
  border-radius: 20px;
  width: 70%;
  margin: 3% auto;
}

.heading {
  font-family: 'Roboto Slab', serif;
  font-size: 20px;
  color: rgb(90, 19, 19);
}

a.sorrylink {
  color: rgb(30, 105, 111);
  text-decoration: underline;
  margin: 0%;
  cursor: grab;
}

a:hover.sorrylink {
  color: rgb(24, 80, 87);
}
</style>
