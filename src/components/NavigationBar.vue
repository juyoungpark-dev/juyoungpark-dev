<template>
  <div id="navbar-full">
    <div class="container">
      <nav
        class="navbar navbar-ct-blue navbar-transparent navbar-fixed-top"
        role="navigation"
      >
        <div class="container">
          <!-- Brand and toggle get grouped for better mobile display -->
          <div class="navbar-header">
            <button
              type="button"
              class="navbar-toggle"
              data-toggle="collapse"
              data-target="#bs-example-navbar-collapse-1"
            >
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <a href="https://www.linkedin.com/in/juyoung-park-to">
              <div class="logo-container">
                <div class="logo">
                  <img src="assets/img/profile1.jpeg" />
                </div>
                <div class="brand">Juyoung Park</div>
              </div>
            </a>
          </div>

          <!-- Collect the nav links, forms, and other content for toggling -->
          <div
            class="collapse navbar-collapse"
            id="bs-example-navbar-collapse-1"
          >
            <ul class="nav navbar-nav navbar-right">
              <li>
                <!-- Button trigger modal -->
                <a href="#" data-toggle="modal" data-target="#myModal">
                  Projects
                </a>
              </li>

              <li>
                <a
                  href="/assets/files/JuyoungPark_fullstack_resume_dark.pdf"
                  class="btn btn-round btn-default"
                  download
                >
                  Download
                </a>
              </li>
            </ul>
          </div>
          <!-- /.navbar-collapse -->
        </div>
        <!-- /.container-fluid -->
      </nav>
    </div>
    <!--  end container-->

    <div class="blurred-container">
      <div class="motto">
        <div>Juyoung</div>
        <div class="border no-right-border">Full</div>
        <div class="border">Stack</div>
        <div>Park</div>
      </div>
      <div
        class="img-src"
        style="background-image: url('assets/img/cover_4.jpg')"
      ></div>
      <div
        class="img-src blur"
        style="background-image: url('assets/img/cover_4_blur.jpg')"
      ></div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "NavigationBar",
  setup() {},
  methods: {
    clickProjects() {},
  },
});
</script>
