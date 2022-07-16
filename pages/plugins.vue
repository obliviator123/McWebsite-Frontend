<template>
  <div style="max-width: 1200px; margin-left: auto; margin-right: auto">
    <div class="block" style="width: auto">
      <h1><a href="https://imjustdoom.com" class="title"><b>CraftBukkit</b></a></h1>
      <p class="description">Some description for a thing</p>
    </div>
    <div class="block" style="width: auto">
      <h1><a href="https://imjustdoom.com" class="title"><b>CraftBukkit</b></a></h1>
      <p class="description">Some description for a thing</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'plugins',
}
</script>

<style scoped>
.block {
  background-color:hsla(0,100%,50%,1);
  background-image:
  radial-gradient(at 40% 20%, hsla(316,100%,74%,1) 0px, transparent 50%),
  radial-gradient(at 80% 0%, hsla(117,100%,56%,1) 0px, transparent 50%),
  radial-gradient(at 0% 50%, hsla(283,100%,93%,1) 0px, transparent 50%),
  radial-gradient(at 80% 50%, hsla(268,100%,76%,1) 0px, transparent 50%),
  radial-gradient(at 0% 100%, hsla(310,100%,77%,1) 0px, transparent 50%),
  radial-gradient(at 80% 100%, hsla(170,100%,70%,1) 0px, transparent 50%),
  radial-gradient(at 0% 0%, hsla(271,100%,76%,1) 0px, transparent 50%);
  border-radius: 6px;
  padding: 10px;
  margin: 8px 0;
}
.title {
  font-size: 20px;
  text-decoration-thickness: auto;
  color: #0ca8a8;
}
.description {
  color: white;
  text-decoration-thickness: 1px;
}
</style>
