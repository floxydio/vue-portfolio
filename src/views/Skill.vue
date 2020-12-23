<template>
  <div class="skill">
    <Navbar />
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div
            class="columns is-variable is-1-mobile is-0-tablet is-3-desktop is-8-widescreen is-2-fullhd"
          >
            <div class="column mt-3 animate__animated animate__bounceInLeft">
              <img src="@/assets/index.jpeg" alt="" />
            </div>
            <div class="column ">
              <div
                class="has-text-left mb-5 animate__animated animate__bounceInDown"
              >
                <h1 class="has-text-info is-size-2 has-text-centered">
                  My Skill
                </h1>
                <p class="has-text-weight-bold mt-5 mb-5"></p>
                <span class="mt-5 is-size-4">Front End</span>
                <p class="mt-4">HTML</p>
                <b-progress type="is-info" value="85"></b-progress>
                <p>CSS ( Intermediate )</p>
                <b-progress type="is-info" value="65"></b-progress>
                <p>Bootstrap ( Intermediate )</p>
                <b-progress type="is-info" value="60"></b-progress>
                <p>Tailwind ( Beginner )</p>
                <b-progress type="is-info" value="40"></b-progress>
                <p>Javascript ( Intermediate )</p>
                <b-progress type="is-info" value="60"></b-progress>
                <p>Vue JS ( Beginner )</p>
                <b-progress type="is-info" value="45"></b-progress>
                <p>React JS ( Beginner )</p>
                <b-progress type="is-info" value="20"></b-progress>

                <span class="mt-5 is-size-4">UI/UX</span>

                <p class="mt-5">Figma ( Beginner )</p>
                <b-progress type="is-info" value="40"></b-progress>

                <span class="mt-5 is-size-4">Back End</span>
                <p class="mt-4">PHP</p>
                <b-progress type="is-info" value="65"></b-progress>
                <p>CodeIgniter 3 ( Beginner )</p>
                <b-progress type="is-info" value="45"></b-progress>
              </div>
            </div>
          </div>
          <b-button
            tag="router-link"
            to="/portfolio"
            type="is-info"
            class="is-pulled-right"
            outlined
            >Portfolio -></b-button
          >
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: "Skill",
  components: {
    Navbar,
  },
};
</script>

<style></style>
