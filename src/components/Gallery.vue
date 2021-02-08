<template>
  <div class="container text-center">
    <br />
    <!-- Carousel wrapper -->
    <div
      id="carouselBasicExample"
      class="carousel slide carousel-fade"
      data-mdb-ride="carousel"
    >
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="0"
          class="active"
        ></li>
        <li data-mdb-target="#carouselBasicExample" data-mdb-slide-to="1"></li>
        <li data-mdb-target="#carouselBasicExample" data-mdb-slide-to="2"></li>
      </ol>

      <!-- Inner -->
      <div class="carousel-inner">
        <!-- Single item -->
        <div class="carousel-item active">
          <img
            src="https://mdbootstrap.com/img/Photos/Slides/img%20(15).jpg"
            class="d-block w-100 img"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Making Sense Of the World</h5>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://mdbootstrap.com/img/Photos/Slides/img%20(22).jpg"
            class="d-block w-100 img"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Discover the unknown</h5>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://mdbootstrap.com/img/Photos/Slides/img%20(23).jpg"
            class="d-block w-100 img"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Explore Curiosity</h5>
          </div>
        </div>
      </div>
      <!-- Inner -->

      <!-- Controls -->
      <a
        class="carousel-control-prev"
        href="#carouselBasicExample"
        role="button"
        data-mdb-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselBasicExample"
        role="button"
        data-mdb-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </a>
    </div>
    <!-- Carousel wrapper -->
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class Gallery extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.img {
  max-width: 750px;
  margin-left: auto;
  margin-right: auto;
}
</style>
