<script setup>
    
import Header from "../components/Header.vue";
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";


</script>
<template>      
    <Header />
    <Navbar />
         <section class="page-section">
            <div class="container">
                <div class="product-item">
                    <div class="product-item-title d-flex">
                        <div class="bg-faded p-5 d-flex ms-auto rounded">
                            <h2 class="section-heading mb-0">
                                <span class="section-heading-upper">there are many variants of coffee</span>
                                <!-- <span class="section-heading-lower">Original Coffe</span> -->
                            </h2>
                        </div>
                    </div>
                    <img class="product-item-img mx-auto d-flex rounded img-fluid mb-3 mb-lg-0" src="assets/image/img2.jpg" alt="..." />
                    <div class="product-item-description d-flex me-auto">

                        <div class="bg-faded p-5 rounded">
                            <p class="mb-0">Ada beberapa varian kopi yang kami produksi diantaranya yaitu original coffe dan kopi lanang</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="page-section">
            <div class="container">
                <div class="product-item">
                    <div class="product-item-title d-flex">
                        <div class="bg-faded p-5 d-flex me-auto rounded">
                            <h2 class="section-heading mb-0">
                                <span class="section-heading-upper"></span>
                                <span class="section-heading-lower">original coffee</span>
                            </h2>
                        </div>
                    </div>
                    <img class="product-item-img mx-auto d-flex rounded img-fluid mb-3 mb-lg-0" src="assets/image/img4.jpg" alt="..." />
                    <div class="product-item-description d-flex ms-auto">
                        <div class="bg-faded p-5 rounded"><p class="mb-0">Original coffee adalah varian kopi yang dibuat dari 100% murni kopi pilihan tanpa campuran bahan lainnya, varian ini banyak diminati oleh kalangan pecinta kopi.</p></div>
                    </div>
                </div>
            </div>
        </section>
        <section class="page-section">
            <div class="container">
                <div class="product-item">
                    <div class="product-item-title d-flex">
                        <div class="bg-faded p-5 d-flex ms-auto rounded">
                            <h2 class="section-heading mb-0">
                                <span class="section-heading-lower">Kopi lanang</span>
                            </h2>
                        </div>
                    </div>
                    <img class="product-item-img mx-auto d-flex rounded img-fluid mb-3 mb-lg-0" src="assets/image/img5.jpg" alt="..." />
                    <div class="product-item-description d-flex me-auto">
                        <div class="bg-faded p-5 rounded">
                            <p class="mb-0">
                               Kopi Lanang merupakan biji kopi yang memiliki bentuk fisik biji tunggal, dan diperoleh dari proses penyortiran yang hanya sekitar 5-10% dari hasil panen. Kelebihan dari kopi lanang : aroma yang kuat, keasaman rendah dan aftertaste yang lama. Cocok untuk drip, french press, esspresso ataupun tubruk.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <Footer />
</template> 

