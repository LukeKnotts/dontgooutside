<template>
  <div class="phase2brown">
    <TopNav />
    <div class="container">
      <p>
        You just arn't feeling up for an adventure right now. Maybe later you'll
        check it out. Eventually you get back to your house near the river docks
        in Chegckle.
      </p>
      <p>
        On your doorstep is a neatly sealed letter, with beautifully written ink
        spelling out your name on it. It has a large red seal with the
        recognizable crest of the University of Lekna on it. The return address
        is also from Lekna. Lekna is a large town known for its prestigous
        university, and for being on Roads Bay.
      </p>
      <p>
        The inside of the letter is extremely intriguing. You've been excepted
        into the famous University of Lekna, and given a scholarship. The
        University of Lekna is a very good school and hard to get into. The fact
        that they would give a scholarship to a random person in Chegckle is
        hard to believe. The scholarship is also paying for a dorm room for the
        school year, and the letter comes with a train ticket to Lekna.
      </p>
      <p class="choices">
        <NuxtLink to="a025-reject-letter">Ignore the invite</NuxtLink>
        <NuxtLink to="b004-go-to-lekna">Go to Lekna</NuxtLink>
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'A018YouveGotMail',
}
</script>
