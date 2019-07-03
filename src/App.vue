<template>
  <div>
    <parallax :speed-factor="0.2">
      <img src="https://images.pexels.com/photos/132037/pexels-photo-132037.jpeg">
    </parallax>
    <parallax :speed-factor="0.2">
      <img src="https://images.pexels.com/photos/132037/pexels-photo-132037.jpeg">
    </parallax>
  </div>
</template>

<script>
import Parallax from "vue-parallaxy";

export default {
  name: 'app',
  components: {
    Parallax
  }
}
</script>

<style>

</style>
