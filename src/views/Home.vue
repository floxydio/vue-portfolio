<template>
  <div class="home">
    <section class="hero is-dark is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="column">
            <div class="hello is-size-3 has-text-weight-bold">
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

<style scoped>
.hello {
  overflow: hidden;
  white-space: nowrap;
  letter-spacing: 0.1em;
  animation: typing 5s steps(50, end);
}
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}
</style>
