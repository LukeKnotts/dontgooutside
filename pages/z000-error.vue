<template>
  <div>
    <div class="container">
      <h1 class="errorheader">
        5<NuxtLink class="secret" to="/z001-error"
          ><span class="invisible">(</span>0<span class="invisible"
            >)</span
          ></NuxtLink
        >2 Bad Gateway
      </h1>
      <hr />
      <p class="errortext">
        Content could not be loaded due to borders. Return
        <NuxtLink class="inlinelink" to="/">home</NuxtLink>.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Z000Error',
}
</script>
