<template>
  <div>
    <b-jumbotron class="flex bg-white flex-wraps mt-5">

      <Navbar />

      <b-container fluid>
        <Hero />
      </b-container>
    </b-jumbotron>


    <section class="my-20">

    </section>

    <section class="my-20">

    </section>
</div>
</template>


<script>
import Navbar from "~/components/Navbar.vue";
import Hero from "~/components/Hero.vue";
export default {
  components: {
    Navbar,
    Hero
  }
}
</script>
