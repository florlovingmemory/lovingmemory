<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <h1 class="newtitle">In Loving Memory</h1>
      <img height="292" src="~/assets/frontimage.jpg" alt="In loving memory" />
      <div class="subtitle"><div class="newname">{{ $config.name }}</div><div class="subtitle">{{ $config.dates }}</div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
