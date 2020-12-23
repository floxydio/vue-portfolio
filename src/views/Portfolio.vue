<template>
  <div class="portfolio">
    <Navbar />
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div
            class="columns is-variable is-1-mobile is-0-tablet is-3-desktop is-8-widescreen is-2-fullhd animate__animated animate__backInUp"
          >
            <div class="column mt-3">
              <div class="card">
                <div class="media-content">
                  <p class="title is-4 mb-5">Landing Page</p>
                </div>
                <i class="fab fa-html5 is-size-4 mr-2"></i>
                <i class="fab fa-css3 is-size-4"></i>
                <div class="content mt-5">
                  <p>HTML + CSS</p>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://github.com/floxydio/landingpage"
                    ><i class="fab fa-github"></i> Github Code</b-button
                  >
                </div>
              </div>
            </div>
            <div class="column mt-3">
              <div class="card">
                <div class="media-content">
                  <p class="title is-4 mb-5">Vue Store</p>
                </div>
                <img src="@/assets/logo.png" alt="" class="image " />
                <div class="content mt-5">
                  <p>Vue + Buefy</p>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://github.com/floxydio/vuestore"
                    ><i class="fab fa-github"></i> Github Code</b-button
                  >
                  <div class="mr-1 mt-4"></div>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://vue-storeio.herokuapp.com/#/"
                    >Demo</b-button
                  >
                </div>
              </div>
            </div>
            <div class="column">
              <div class="card">
                <div class="media-content">
                  <p class="title is-4 mb-5">CI3 Display Store</p>
                </div>
                <i class="fas fa-fire is-danger fa-lg"></i>
                <div class="content mt-5">
                  <p>Codeigniter 3 + Bootstrap 4</p>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://github.com/floxydio/ci3-display-store"
                    ><i class="fab fa-github"></i> Github Code</b-button
                  >
                </div>
              </div>
            </div>
            <div class="column">
              <div class="card">
                <div class="media-content">
                  <p class="title is-4 mb-5">Real Time Chat Vue</p>
                </div>
                <img src="@/assets/logo.png" alt="" class="image " />
                <div class="content mt-5">
                  <p>Vue JS + Socketio</p>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://github.com/floxydio/realtime-chat-socketio"
                    ><i class="fab fa-github"></i> Github Code</b-button
                  >
                  <div class="mr-1 mt-4"></div>
                  <b-button
                    type="is-info"
                    tag="a"
                    href="https://real-time-chatio.herokuapp.com/"
                    >Demo</b-button
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: "Portfolio",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
img {
  width: 24px;
  height: 24px;
  margin-left: auto;
  margin-right: auto;
}
</style>
