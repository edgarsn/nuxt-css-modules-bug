<template>
  <div :class="$style['show-thumbnails']">
      <show-thumbnail/>
  </div>
</template>

<script>
import ShowThumbnail from "~/components/ShowThumbnail/ShowThumbnail";

export default {
  name: "ShowThumbnails",
  components: {
    ShowThumbnail,
  },
}
</script>

<style lang="scss" src="./show_thumbnails.module.scss" module></style>
