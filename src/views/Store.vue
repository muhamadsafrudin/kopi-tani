<script setup>
    
import Header from "../components/Header.vue";
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";


</script>
<template>      
    <Header />
    <Navbar />
 <section class="page-section cta">
            <div class="container">
                <div class="row">
                    <div class="col-xl-9 mx-auto">
                        <div class="cta-inner bg-faded text-center rounded">
                            <h2 class="section-heading mb-5">
                                <span class="section-heading-upper">Anda Datang</span>
                                <span class="section-heading-lower">Kami Buka</span>
                            </h2>
                            <ul class="list-unstyled list-hours mb-5 text-left mx-auto">
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Minggu
                                    <span class="ms-auto">Tutup</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Senin
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Selasa
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Rabu
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Kamis
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Jumat
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                                <li class="list-unstyled-item list-hours-item d-flex">
                                    Sabtu
                                    <span class="ms-auto">8:00 AM to 5:00 PM</span>
                                </li>
                            </ul>
                            <p class="address mb-5">
                                <em>
                                    <strong>Ds.Klumpit Dk.Bungul Rt06 Rw02</strong>
                                    <br />
                                    Tlogowungu, Pati
                                </em>
                            </p>
                            <p class="mb-0">
                                <small><em>Sosial Media</em></small>
                                <br />
                                <a class="text-dark mx-2" target="_blank" href="https://www.facebook.com/kopi.t.pati"><i class="fab fa-facebook-square color-facebook" ></i> Kopi Tani Pati</a>
                                <a class="text-dark mx-2" target="_blank" href="https://www.instagram.com/kopi.t.pati/"><i class="fab fa-instagram color-instagram" ></i> Kopi Tani Pati</a>
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="page-section about-heading">
            <div class="container">
                <div class="img-fluid rounded about-heading-img mb-3 mb-lg-0 bg-primary">
                    <!-- <img style="width: 100%;" class="" src="assets/image/img6.jpg" alt="..." /> -->
                </div>
                <div class="about-heading-content mt-3">
                    <div class="row">
                        <div class="col-xl-9 col-lg-10 mx-auto">
                                <iframe
                                class="rounded"
                                width="100%"
                                height="400"
                                style="border:0"
                                loading="lazy"
                                allowfullscreen
                                referrerpolicy="no-referrer-when-downgrade"
                                src="https://www.google.com/maps/embed/v1/place?key=AIzaSyD9q2fPImmXZLbg_97WyoZRowU3MKEgicY
                                    &q=kopi+tani+pati">
                                </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <Footer />
</template> 
<style>
    a {
        text-decoration: none;
    }
    .color-facebook {
        color: #3f729b;
    }
    .color-instagram {
        color: #bf00ff;
    }
</style>
