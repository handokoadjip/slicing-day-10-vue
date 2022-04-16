<template>
  <section>
    <div class="container-fluid">
      <div class="row">
        <div class="col-6 col-lg-3 p-0" v-for="(list, index) in lists" :key="index" :id="list.title">
          <div class="position-relative">
            <figure class="m-0">
              <img class="image image-fluid w-100 h-image-300px" :src="list.image" :alt="`img-${index}`">
            </figure>
            <div class="image-hover position-absolute top-50 start-50 translate-middle w-100 h-100 o-0">
              <div
                class="position-relative z-999 d-flex flex-column justify-content-center align-items-center h-100 text-uppercase text-center">
                <h2 class="fs-4 fw-medium m-0">{{ list.title }}</h2>
                <p class="fs-6">{{ list.subtitle }}</p>
                <router-link class="btn btn-border px-5" :to="list.to">more</router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GalleryComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/img-1.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-2.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-3.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-4.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-5.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-6.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-7.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-8.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-9.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-10.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-11.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
        {
          image: require("@/assets/source/image/img-12.jpg"),
          title: "BROWN BEAST",
          subtitle: "CARS PHOTO",
          to: "#",
        },
      ]
    }
  }
}
</script>