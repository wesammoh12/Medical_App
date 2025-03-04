<template>
    <section class="hero-section py-5" style="background-color: #F9FCFF">
        <div class="row align-items-center justify-content-center">
            <div class="col-md-8 d-flex flex-column justify-content-center">
                <div class="row align-items-center justify-content-center last_row">
                    <div class="col-md-6 d-flex justify-content-start">
                        <img class="last_image" src="@/assets/imgs/image23.svg" alt="Card image cap">
                    </div>
                    <div class="col-md-6">
                        <div class="card" style="width: 100%">
                            <div class="card-body">
                                <h3 class="card-title title_card">World-Class Preventive,
                                    Prescriptive & Curative
                                    Medical Practices</h3>
                                <p class="card-text">
                                    Being in the healthcare sector, we consider it our paradigm duty to ensure Safety of
                                    our patients, effectiveness of our treatments, transparency in our practices, and
                                    absolute timely care.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="d-flex flex-column align-items-center justify-content-center">
                    <h1 class="first_row">Our Specialty</h1>
                    <p style="color : #000000;">
                        We provide the world class services with the |best medical team!
                    </p>
                </div>
                <div class="row align-items-center justify-content-center">
                    <div class="col-md-4 d-flex justify-content-center">
                        <div class="card" style="width: 15rem;">
                            <img class="card-img-top mx-auto" src="@/assets/imgs/Frame1.svg" alt="Card image cap">
                            <div class="card-body">
                                <h3 class="card-title">Dentistry</h3>
                                <p class="card-text">Get consultation Form our
                                    Dentistry team</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 d-flex justify-content-center">
                        <div class="card card_selected" style="width: 15rem;">
                            <img class="card-img-top mx-auto" src="@/assets/imgs/Frame2.svg" alt="Card image cap">
                            <div class="card-body">
                                <h3 class="card-title">General Diagnosis</h3>
                                <p class="card-text text-white">Get consultation form our
                                    General Diagnosis team</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 d-flex justify-content-center">
                        <div class="card" style="width: 15rem;">
                            <img class="card-img-top mx-auto" src="@/assets/imgs/Frame3.svg" alt="Card image cap">
                            <div class="card-body">
                                <h3 class="card-title">Neuro Surgery</h3>
                                <p class="card-text">Get consultation form our
                                    Neuro Surgery team</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>
import { ref } from "vue";
</script>

<style scoped>
.navLink {
    color: #F9FCFF;
    text-decoration: none;
    font-weight: 500;
}

.card-text {
    color: #1D1C3199;
}

.card {
    border: none;
    padding-bottom: 1rem;
    padding-top: 1rem;
}

.card_selected {
    background-color: #3D9DF1;
    color: white !important;
}

.card-title {
    margin-bottom: 25px !important;
    font-size: 16px;
}

.first_row {
    color: #234A6B;
}

.card-img-top {
    width: 5.8rem;
    height: 5.8rem;
}

.card-body {
    justify-items: center;
}

.last_row {
    margin-top: 3rem;
    margin-bottom: 5rem;
    padding-inline: 3.8rem;
}

.apps_row {
    margin-top: 1rem;
    padding-inline: 1.2rem;
}

.last_image {
    width: 100%;
    object-fit: cover;
    height: 13rem;
    border-radius: 12px;
}

.title_card {
    color: #234A6B;
    font-size: 22px;
}
</style>
