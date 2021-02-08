<template>
  <div class="home">
    <main class="jumbotron img-fluid bg-image text-center">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="display-4 text-white mb-0">Vue.js Developer</h1>
        </div>
      </div>
    </main>
    <br />
    <br />
    <br />
    <div class="container">
      <h1 class="text-center display-4">Features & Services</h1>
      <br />
      <div class="row">
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fab icon fa-connectdevelop"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Build Websites</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              227 Projects Built In Vue.js
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fas icon fa-globe"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Hosting</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              87 Sites Managed By Node.js
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fas icon fa-tools"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Maintenance</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              Maintaining with Node.js
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <HelloWorld />
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
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
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
