<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#aboutUs">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#story">Perjalanan Hidup</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Welcome to My Portofolio Website</div>
          <div class="intro-heading text-uppercase">Aji Bayu Permadi</div>
        </div>
      </div>
    </header>

    <!-- About -->
    <section id="aboutUs">
      <div class="container">
        <h2 class="section-heading text-uppercase">ABOUT US</h2><br>
        <p>Perkenalkan nama saya Aji Bayu Permadi, saya lahir di jawa tengah pada tanggal 03-oktober-2002 di jawa tengah, dan sekarang saya berkuliah di salah satu universitas di RIAU yakni Universitas Islam Negeri Sultan Syarif Kasim Riau, </p>
      </div>
    </section>

    <!-- Perjalanan diri -->
    <section id="story">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Perjalanan Diri ku</h2>
            <h3 class="section-subheading text-muted">Aji Bayu Permadi-UIN SUSKA RIAU</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2008-2014</h4>
                    <h4 class="subheading">SD Swasta Siak Raya</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Lulus dari sd swasta siak raya dan tidak mendapatkan peringkat</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2014-2017</h4>
                    <h4 class="subheading">Masuk MTS N SIAK</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Lulus dengan peringkat 2 di MTS N Siak</p>
                  </div>
                </div>
              </li>
              <li>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2017-2020</h4>
                    <h4>MAN 1 SIAK</h4>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2020</h4>
                    <h4 class="subheading">KULIAH DI UIN SUSKA RIAU</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">2020 kuliah dan masuk di uin suska riau pada jurusan Teknik Informatika Fakultas Sains dan Teknologi dan sekarang sudah berada di semeter 4</p>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Contact Us</h2>
            <h3 class="section-subheading text-muted">Hubungi Saya dengan masukkan data anda di bawah</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <form id="contactForm" name="sentMessage" novalidate="novalidate">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <input class="form-control" id="name" type="text" placeholder="Your Name *" required="required" data-validation-required-message="Please enter your name.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="email" type="email" placeholder="Your Email *" required="required" data-validation-required-message="Please enter your email address.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="phone" type="tel" placeholder="Your Phone *" required="required" data-validation-required-message="Please enter your phone number.">
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <textarea class="form-control" id="message" placeholder="Your Message *" required="required" data-validation-required-message="Please enter a message."></textarea>
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="clearfix"></div>
                <div class="col-lg-12 text-center">
                  <div id="success"></div>
                  <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase" type="submit">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy; Your Website 2018</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a href="#">Privacy Policy</a>
              </li>
              <li class="list-inline-item">
                <a href="#">Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
