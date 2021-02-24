<template>
  <div class="home">
    <br />
    <br />
    <div class="main bg-image">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="text-white display-4">DevMusic</h1>
        </div>
      </div>
    </div>
    <br />
    <!-- Section: Social media -->
    <section class="mb-4">
      <!-- Facebook -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-facebook-f"></i
      ></a>

      <!-- Twitter -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-twitter"></i
      ></a>

      <!-- Google -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-google"></i
      ></a>

      <!-- Instagram -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-instagram"></i
      ></a>

      <!-- Linkedin -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-linkedin"></i
      ></a>
      <!-- Github -->
      <a
        class="btn btn-link section btn-floating btn-lg text-dark m-1"
        href="#!"
        role="button"
        data-mdb-ripple-color="dark"
        ><i class="fab text-info fa-github"></i
      ></a>
    </section>
    <!-- Section: Social media -->
    <br />
    <br />
    <br />
    <h1>Become A Subscriber</h1>
    <br />
    <br />
    <div class="container form">
      <form>
        <!-- Name input -->
        <div class="form-outline mb-4">
          <input type="text" id="form5Example1" class="form-control" />
          <label class="form-label" for="form5Example1">Name</label>
        </div>

        <!-- Email input -->
        <div class="form-outline mb-4">
          <input type="email" id="form5Example2" class="form-control" />
          <label class="form-label" for="form5Example2">Email address</label>
        </div>

        <!-- Checkbox -->
        <div class="form-check d-flex justify-content-center mb-4">
          <input
            class="form-check-input me-2"
            type="checkbox"
            value=""
            id="form5Example3"
            checked
          />
          <label class="form-check-label" for="form5Example3">
            I have read and agree to the terms
          </label>
        </div>

        <!-- Submit button -->
        <button type="submit" class="btn max btn-primary btn-block mb-4">
          Subscribe
        </button>
      </form>
    </div>
    <br />
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1518609878373-06d740f60d8b?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt=""
            class="img-fluid"
          />
        </div>
        <div class="col-md-6">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Omnis eaque
          accusamus placeat amet minus dolores eveniet dolorum assumenda ex
          possimus quibusdam ullam porro laudantium repellat aliquid temporibus
          est, sequi rerum? Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Odit culpa perspiciatis explicabo, aperiam distinctio
          exercitationem eaque esse, quaerat blanditiis sit, optio dolorum neque
          odio possimus commodi officia impedit? Impedit, repellendus.
        </div>
      </div>
      <br />
      <HelloWorld />
      <br />
      <div class="row">
        <div class="col-md-6">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Omnis eaque
          accusamus placeat amet minus dolores eveniet dolorum assumenda ex
          possimus quibusdam ullam porro laudantium repellat aliquid temporibus
          est, sequi rerum? Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Odit culpa perspiciatis explicabo, aperiam distinctio
          exercitationem eaque esse, quaerat blanditiis sit, optio dolorum neque
          odio possimus commodi officia impedit? Impedit, repellendus.
        </div>
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt=""
            class="img-fluid"
          />
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
  </div>
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

<style lang="scss" scoped>
.main {
  background: url(https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  padding-top: 30%;
  padding-bottom: 30%;
}

.form {
  width: 360px;

  input {
    background-color: lightgrey !important;
    opacity: 0.3 !important;
  }
}
.section {
  font-size: 2em !important;
}

.card {
  padding: 15px !important;
}

.max {
  width: 130px !important;
  margin-left: auto;
  margin-right: auto;
  border-radius: 30px !important;
}
.icon {
  font-size: 2.3em;
  color: grey;
  opacity: 0.4;
  padding-bottom: 7px;
}
</style>
