<template>
  <div class="slide" v-editable="blok">
    <img :src="blok.image" />
  </div>
</template>

<script>
export default {
  props: ["blok"]
};
</script>

<style lang="scss">
.slide img {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  display: flex;
}

.slide {
  background: url("../assets/images/grass.jpg") no-repeat;
  background-size: cover;
  background-attachment: scroll;
}
</style>
