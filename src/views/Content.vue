<template>
  <div class="content text-center">
    <br />
    <br />
    <br />
    <h1 class="display-4">Our Projects</h1>
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>Barbershop</h2>
            </div>
            <div class="card-body">
              <a href="https://barber-cuts.netlify.app/" target="_blank">
                <img
                  src="https://images.unsplash.com/photo-1598887142487-3c854d51eabb?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in September 2019
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>Kees Cleaning</h2>
            </div>
            <div class="card-body">
              <a
                href="https://kees-cleaning-service.netlify.app/"
                target="_blank"
              >
                <img
                  src="https://images.unsplash.com/photo-1584813470613-5b1c1cad3d69?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in July 2020
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>Tax Service</h2>
            </div>
            <div class="card-body">
              <a
                href="https://crystals-tax-service.netlify.app/"
                target="_blank"
              >
                <img
                  src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in February 2021
            </div>
          </div>
        </div>
      </div>
      <br />
      <div class="row">
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>E-Vites</h2>
            </div>
            <div class="card-body">
              <a href="https://evites.netlify.app/" target="_blank">
                <img
                  src="https://images.unsplash.com/photo-1551963474-cc9e699de3b4?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in November 2020
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>Decorating</h2>
            </div>
            <div class="card-body">
              <a href="https://www.touchbyme.net" target="_blank">
                <img
                  src="https://images.unsplash.com/photo-1530103862676-de8c9debad1d?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in December 2020
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center bg-image hover-zoom">
            <div class="card-header">
              <h2>Insurance</h2>
            </div>
            <div class="card-body">
              <a href="https://www.brookslifeagency.net/" target="_blank">
                <img
                  src="https://images.unsplash.com/photo-1517554558809-9b4971b38f39?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
                  alt="project"
                  width="100%"
                />
              </a>
            </div>
            <div class="card-footer text-muted">
              Completed in May 2019
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <Gallery />
    <br />
    <div class="text-center">
      <!-- Start Square Appointments Embed code -->
      <a
        target="_top"
        style=" background-color: #1E93CC; color: white; height: 40px; text-transform: uppercase; font-family: 'Square Market', 'helvetica neue', helvetica, arial, sans-serif; letter-spacing: 1px; line-height: 38px; padding: 0 28px; border-radius: 3px; font-weight: 500; font-size: 14px; cursor: pointer; display: inline-block; "
        href="https://square.site/book/L49S1YRWQN1ZG/clear-web-designs"
        rel="nofollow"
        >Book an Appointment</a
      >
      <!-- End Square Appointments Embed code -->
    </div>
  </div>
  <br />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Gallery from "@/components/Gallery.vue"; // @ is an alias to /src

@Options({
  components: {
    Gallery
  }
})
export default class Home extends Vue {}
</script>

<style>
.home {
  color: teal;
}
main {
  background: url(https://images.unsplash.com/photo-1496171367470-9ed9a91ea931?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 30%;
  padding-bottom: 30%;
  width: 100%;
}

.icon {
  font-size: 2.7em !important;
  color: grey;
  opacity: 0.7;
}
.img-content {
  letter-spacing: 32px !important;
}
</style>
