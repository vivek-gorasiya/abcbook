<template>
  <navbar />
  <Header />
  <second />
  <feature />
  <publish />
  <news />
  <end />
</template>


<script>
import navbar from "./components/navbar.vue";
import Header from "./components/header.vue";
import second from "./pages/slider.vue";
import feature from "./pages/feature.vue";
import publish from "./pages/publish.vue";
import news from "./pages/newssettler.vue";
import end from "./components/footer.vue";
export default {
  components: {
    navbar,
    Header,
    second,
    feature,
    publish,
    news,
    end
  },
}
</script>

<style>
  @media (min-width: 1400px) {
    .container {
        max-width: 1350px;
    }
}
</style>



