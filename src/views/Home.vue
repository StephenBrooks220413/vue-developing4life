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
    <div class="certs">
      <!-- Button trigger modal -->
      <button
        type="button"
        class="btn btn-primary"
        data-mdb-toggle="modal"
        data-mdb-target="#exampleModal"
      >
        <h3>Certifications</h3>
      </button>

      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModal"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">Certificates</h5>
              <button
                type="button"
                class="btn-close"
                data-mdb-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <!-- javascript -->
            <div class="modal-body">
              <a
                href="https://www.youracclaim.com/badges/07383ef1-eb67-4677-ba8b-864c527b74fe/public_url"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/220x220/images/0c84aca1-2775-45d0-a6d0-9995d0779b38/MTA-Introduction_to_Programming_Using_JavaScript.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
              <!-- html & css -->
              <a
                href="https://www.youracclaim.com/badges/e9cc788b-1595-4941-9141-0d8fb3a24bc3/public_url"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/220x220/images/9bc1696c-a565-4faf-8e06-3e24d62a00c5/MTA-Introduction-to-Programming-using-HTML-and-CSS-2019.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
              <!-- asp.Net -->
              <a
                href="https://www.youracclaim.com/org/quickstart/badge/build-web-apis-using-asp-net.1"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/680x680/images/9af01f17-3b97-405b-a607-2062baa0f47c/d36985d219044396be0c68de9f6d70ad-01.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
              <!-- bootstrap -->
              <a
                href="https://www.youracclaim.com/org/quickstart/badge/bootstrap-4-exploring-new-features.1"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/680x680/images/086a0344-813a-4b2e-872d-8cb49237037a/2a4ac60cbad44f5c96694ce6df9daa70-01.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
              <!-- vue.js -->
              <a
                href="https://www.youracclaim.com/org/quickstart/badge/getting-started-with-vue-js.1"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/680x680/images/2100e37b-6bb5-49e2-a570-5b29fda85b3e/54a371fb922f4bc1adadae0802082b4e-01.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
              <!-- angular.js -->
              <a
                href="https://www.youracclaim.com/org/quickstart/badge/angular-fundamentals.1"
                target="_blank"
              >
                <img
                  src="https://images.youracclaim.com/size/680x680/images/d7585c5e-4f9b-42f8-a101-6bac7ecc5715/3f9b889c6f03492280263d47ff068c00-01.png"
                  class="hover-zoom"
                  width="200px"
                  alt=""
                />
              </a>
            </div>
            <div class="modal-footer">
              <button
                type="button"
                class="btn btn-secondary"
                data-mdb-dismiss="modal"
              >
                Close
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="container">
      <h1 class="text-center display-4">Features & Services</h1>
      <div class="row">
        <div class="col-md-4">
          <br /><br />
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
          <br /><br />
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
          <br /><br />
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
  padding-top: 35%;
  padding-bottom: 35%;
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
.certs {
  width: 300px;
  margin-left: auto;
  margin-right: auto;
  font-size: 2.3em !important;
}
</style>
