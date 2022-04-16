<template>
  <section>
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-3">
          <div class="wrapper text-black p-5 text-uppercase d-flex flex-column justify-content-between h-100">
            <h2 class="display-4 fw-bold">latest news</h2>
            <router-link class="btn btn-border-black px-5" to="#">more</router-link>
          </div>
        </div>
        <div class="col-lg-9">
          <div class="row">
            <div class="col-lg-6 p-0" v-for="(list, index) in lists" :key="index" :id="list.title">
              <div class="position-relative">
                <figure class="m-0">
                  <img class="image img-fluid w-100 h-image-300px" :src="list.image"
                    alt="image-1">
                </figure>
                <div class="image-hover position-absolute top-50 start-50 translate-middle w-100 h-100">
                  <div
                    class="position-relative z-999 d-flex flex-column justify-content-center align-items-start p-5 h-100 text-uppercase">
                    <h2 class="fs-4 fw-medium m-0">{{ list.title }}</h2>
                    <p class="fs-6">{{ list.subtitle }}</p>
                    <a class="btn btn-border px-5" :href="list.href">more</a>
                  </div>
                </div>
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
  name: "NewsComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/img-1.jpg"),
          title: "DROP IN AXLE ROLL-IN SLIDE NOSEBLUNT SLIDE STEVE SEVERIN.",
          subtitle: "POSTED ON JANUARY 2022",
          href: "#",
        },
        {
          image: require("@/assets/source/image/img-2.jpg"),
          title: "DROP IN AXLE ROLL-IN SLIDE NOSEBLUNT SLIDE STEVE SEVERIN.",
          subtitle: "POSTED ON JANUARY 2022",
          href: "#",
        },
        {
          image: require("@/assets/source/image/img-3.jpg"),
          title: "DROP IN AXLE ROLL-IN SLIDE NOSEBLUNT SLIDE STEVE SEVERIN.",
          subtitle: "POSTED ON JANUARY 2022",
          href: "#",
        },
        {
          image: require("@/assets/source/image/img-4.jpg"),
          title: "DROP IN AXLE ROLL-IN SLIDE NOSEBLUNT SLIDE STEVE SEVERIN.",
          subtitle: "POSTED ON JANUARY 2022",
          href: "#",
        },
      ]
    }
  }
}
</script>