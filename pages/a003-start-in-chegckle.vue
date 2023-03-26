<template>
  <div class="phase1">
    <TopNav />
    <div class="container">
      <p>
        You live in the small town of Chegckle, neatly nested in the forest on
        the river. It rests at the foot of the looming Crater Mountains that
        stretch toward the town. Chegckle is a small and pleasant town. It is
        rare for people to come to Chegckle outside of the exports and imports
        along the river. Chegckle does have frequent relations with importers
        and exporters along the river, it's just that nobody really bothers to
        stop in Chegckle. Maybe visitors will stay for a place to fall asleep,
        -if they can't do that on their boat. Chegckle also has a small train
        station with a single track intersecting the town, but trains don't
        often go through Chegckle, and even less often do they stop in Chegckle.
        Rarely does anyone leave or move to Chegckle. The town has an intersting
        history, but not one intersting enough to attract much attention.
      </p>
      <p>
        Chegckle is mainly a factory town. There was mining in the past, but
        that has stopped now since the demand for ore from Chegckle is pretty
        much nonexistant. Now the factories take up a significant amount of
        space in the town. Their complex machinary can be heard, spinning and
        mixing things, if you are close to one of the buildings.
      </p>
      <p>Do you like the factories?</p>
      <p class="choices">
        <NuxtLink to="/a004-dislikes-factories"
          >No, I don't like the factories</NuxtLink
        >
        <NuxtLink to="/a005-likes-factories"
          >Yes, I like the factories</NuxtLink
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'A003StartInChegckle',
}
</script>
