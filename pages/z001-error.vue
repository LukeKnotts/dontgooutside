<template>
  <div>
    <div class="container">
      <h1 class="errorheader">
        Error 4<NuxtLink class="secret" to="/z000-error"
          ><span class="invisible">(</span>0<span class="invisible"
            >)</span
          ></NuxtLink
        >4
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
  name: 'Z001Error',
}
</script>
