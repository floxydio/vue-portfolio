<template>
  <div class="about">
    <Navbar />
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div
            class="columns is-variable is-1-mobile is-0-tablet is-3-desktop is-8-widescreen is-2-fullhd"
          >
            <div class="column mt-3">
              <img src="@/assets/index.jpeg" alt="" />
            </div>
            <div class="column mt-5 animate__animated animate__zoomIn">
              <div class="has-text-left mb-5 ">
                <h1 class="has-text-info is-size-2">Dio Rovelino</h1>
                <p class="has-text-weight-light mt-2 mb-5">
                  Junior Front End Developer
                </p>
                <p class="has-text-weight-bold mt-5 mb-5">
                  Hai, Perkenalkan Nama saya Dio Okta Rovelino <br />
                  Saya berumur 20 Tahun, Saya adalah Mahasiswa di Universitas
                  Bina Sarana Informatika (Semester 3) Saya hobi mempelajari
                  ilmu baru terutama Web Developer Memang pengalaman pekerjaan
                  saya pada Web Developer ini masih belum ada tapi kegigihan
                  saya dalam mempelajari hal baru adalah tantangan buat saya.
                </p>

                <a
                  href="https://www.github.com/floxydio"
                  target="_blank"
                  class="has-text-dark"
                  ><i class="fab fa-github is-size-3"></i
                ></a>
                <a
                  href="https://www.linkedin.com/in/dio-okta-rovelino-76a204189"
                  target="_blank"
                  class="has-text-dark"
                  ><i class="fab fa-linkedin is-size-3 ml-3"></i
                ></a>
              </div>
            </div>
          </div>
          <b-button
            tag="router-link"
            to="/skill"
            type="is-info"
            class="is-pulled-right"
            outlined
            >Skill -></b-button
          >
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: "About",
  components: {
    Navbar,
  },
};
</script>

<style>
img {
  height: 450px;
}
</style>
