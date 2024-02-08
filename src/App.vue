<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import { reactive, ref } from 'vue'

const counter = reactive({ count: 0 })
const message = ref('Hello World!')
</script>

<!-- <template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style> -->

<!-- <template>
  <h1>{{ message }}</h1>
  <p>Count is: {{ counter.count }}</p>
</template> -->

<style>
        body {
            padding-top: 56px; /* Add height of navbar */
        }

        .hero-section {
            background: url('../src/assets/vue_background.jpg') center/cover no-repeat;
            color: #fff;
            text-align: center;
            padding: 100px 0;
        }

        .feature-section {
            background-color: #f8f9fa;
            padding: 80px 0;
        }
    </style>

<template>
  <div class="m-5">
    <!-- <NuxtPage /> -->
    <div class="btn btn-warning">Warning</div>
    <div class="btn btn-primary">Primary</div>
    <div class="btn btn-secondary">Secondary</div>
    <div class="btn btn-info">Info</div>
    <div class="btn btn-dark">Dark</div>
    <div class="btn btn-light">Light</div>
    <div class="btn btn-success">Success</div>
    <div class="btn btn-danger">Danger</div>
    <div class="btn btn-warning">Warning</div>
  </div>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
        <a class="navbar-brand" href="#">Your Logo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero-section">
    <div class="container">
        <h1 class="display-4">Welcome to Our Website</h1>
        <p class="lead">Discover amazing things with Bootstrap 5</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn More</a>
    </div>
</section>

<!-- Feature Section -->
<section class="feature-section">
    <div class="container">
        <div class="row">
            <div class="col-lg-4">
                <h2>Feature 1</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque tristique velit eu massa pulvinar.</p>
            </div>
            <div class="col-lg-4">
                <h2>Feature 2</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque tristique velit eu massa pulvinar.</p>
            </div>
            <div class="col-lg-4">
                <h2>Feature 3</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque tristique velit eu massa pulvinar.</p>
            </div>
        </div>
    </div>
</section>

<!-- Contact Form -->
<section class="contact-section">
    <div class="container">
        <h2>Contact Us</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>

  <!-- card -->
        <div class="card-section">
          <div class="card" style="width: 18rem;">
            <img src="../src/assets/computer01.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="../src/assets/computer02.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="../src/assets/computer03.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="../src/assets/computer04.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
  </section>
  <footer class="footer">
    <div class="copyright">
      <p>&copy; copyright 2024</p>
    </div>
  </footer>
</template>
