<template>
    <footer class="Footer relative bottom-0 overflow-hidden mt-10">
        <div class="row align-items-center justify-content-center">
            <div class="col-md-8 d-flex flex-column justify-content-center">
                <div class="flex flex-col text-center justify-center items-center">
                    <div class="text-primary_color dark:text-light_color">
                        <h1 class="text-4xl font-bold text-white logo_text">
                            Clinic name
                        </h1>
                        <p class="mt-15">
                            <span class="mx-auto flex-wrap">
                                <span class="mx-2">
                                    <img class="card-img-top mx-auto" src="@/assets/imgs/sms.svg" alt="Card image cap">
                                    <nuxt-link class="link_text" to="/imprint">hello@skillbirdge.com </nuxt-link>
                                </span>
                                <span class="mx-2">
                                    <img class="card-img-top mx-auto" src="@/assets/imgs/call.svg" alt="Card image cap">
                                    <nuxt-link class="link_text" to="/privacy"> +91 91813 23 2309 </nuxt-link>
                                </span>
                                <span class="mx-2">
                                    <img class="card-img-top mx-auto" src="@/assets/imgs/location.svg"
                                        alt="Card image cap">
                                    <nuxt-link class="link_text" to=""> Somewhere in the World </nuxt-link>
                                </span>
                            </span>
                        </p>
                    </div>
                </div>
                <div class="row align-items-center justify-content-center last_card">
                    <div class="card" style="width: 100% ; background-color: #13324F ; border :none">
                        <div class="card-body">
                            <div class="row align-items-center justify-content-center">
                                <div class="col-md-4 d-flex flex-row justify-content-center">
                                    <img class="Buttons_image mx-2" src="@/assets/imgs/Group 19.svg"
                                        alt="Card image cap">
                                    <img class="Buttons_image mx-2" src="@/assets/imgs/Group 18.svg"
                                        alt="Card image cap">
                                    <img class="Buttons_image mx-2" src="@/assets/imgs/Group 20.svg"
                                        alt="Card image cap">
                                </div>
                                <div class="col-md-4 d-flex flex-column justify-content-center contact_text">
                                    The ultimate destination for
                                    all of your medical needs
                                </div>
                                <div class="col-md-4 d-flex flex-column justify-content-center contact_text">
                                    Privacy Policy | Terms of Service
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.Footer {
    padding-top: 4rem;
    background-color: #13324F;
    height: 25rem;
}

.link_text {
    text-decoration: none;
    color: white;
    font-size: large;
    font-weight: 500;
}

.card-img-top {
    width: 1.8rem;
    height: 1.8rem;
}

.Buttons_image {
    width: 3rem;
    height: 3rem;
}

.card-body {
    color: white;
}

.contact_text {
    font-weight: 500;
    font-size: large;
}

.logo_text {
    margin-bottom: 3rem;
}

.last_card {
    margin-top: 1.5rem;
    border: none;
}
</style>
