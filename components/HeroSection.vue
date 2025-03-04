<template>
  <section class="hero-section py-5" style="background-color: #ffefe9">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <h1 class="hero-title fw-bold mb-4">
            Get Expert
          </h1>
          <h1 class="hero_title_2">
            Medical Consultation!
          </h1>
          <p class="hero-desc mb-4">
            Our doctors provide expert medical advice and consultation. Get in touch with our team to discuss.
          </p>
          <div>
            <button class="hero-primary-btn">
              <img src="../assets/imgs/Map pin.svg" alt="Bank Illustration" class="icon img-fluid" />
              Search Doctors in your location
              <img src="../assets/imgs/Group 1.svg" alt="Bank Illustration" class="icon_search img-fluid" />
            </button>
          </div>
        </div>

        <div class="col-md-6 text-center">
          <img src="../assets/imgs/image1.svg" alt="Bank Illustration" class="hero-image img-fluid" />
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts" setup>
import { ref } from "vue";
</script>

<style scoped>
.hero-section {
  background-color: #ECF6FF !important;
  height: 80vh;
}

.hero-title {
  color: #234A6B;
  font-size: 4rem;
}

.hero_title_2 {
  color: #0086FF;
  font-size: 4rem;
}

.hero-desc {
  color: #395b64;
  font-size: 20px;
}

.hero-image {
  width: 100%;
  height: 25rem;
  object-fit: contain;
}

.hero-primary-btn {
  border-radius: 8px;
  padding-inline: 2rem;
  padding-top: 0rem;
  padding-bottom: 0rem;
  background-color: white;
  color: #395b64;
  border: none;
}

.hero-secondary-btn {
  border-radius: 8px;
  border: 1px solid #395b64;
  padding: 24px 52px 24px 52px;
  background-color: transparent;
  color: white;
}

.icon {
  width: 1rem;
  height: 1rem;
  margin-right: 1rem;
}

.icon_search {
  width: 5rem !important;
  height: 4rem !important;
  margin-left: 2rem;
}
</style>
