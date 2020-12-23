<template>
  <div class="home">
    <section class="hero is-dark is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="column">
            <div
              class="animate__animated animate__zoomIn is-size-3 has-text-weight-bold"
            >
              Hello, My Name is Dio Okta Rovelino
            </div>
          </div>
          <div class="column">
            <div class="is-size-6 has-text-weight-light">
              Click On Button Below
            </div>
          </div>
          <div class="column mt-4">
            <b-button
              type="is-info"
              tag="router-link"
              to="/about"
              class="mr-2"
              outlined
              >About Me</b-button
            >
            <b-button
              type="is-info"
              tag="router-link"
              to="/skill"
              class="mr-2"
              outlined
              >Skill</b-button
            >
            <b-button type="is-info" tag="router-link" to="/portfolio" outlined
              >Portfolio</b-button
            >
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>
