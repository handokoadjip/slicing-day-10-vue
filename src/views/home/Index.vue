<template>
  <GalleryComponent />
  <NewsComponent />
  <SectionFooterComponent />
</template>

<script>
import GalleryComponent from "@/components/GalleryComponent.vue";
import NewsComponent from "@/components/NewsComponent.vue";
import SectionFooterComponent from "@/components/SectionFooterComponent.vue";

export default {
  name: "HomePage",
  components: {
    GalleryComponent,
    NewsComponent,
    SectionFooterComponent,
  },
  mounted() {
    document.title = "Creative Market | Mountain Everest"
  }
}
</script>
