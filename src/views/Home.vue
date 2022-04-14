<script setup>
    
import Header from "../components/Header.vue";
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";


</script>
<template>      
    <Header />
    <Navbar />
        <section class="page-section clearfix">
            <div class="container">
                <div class="intro">
                    <img class="intro-img img-fluid mb-3 mb-lg-0 rounded" src="/assets/image/img3.jpg" alt="..." />
                    <div class="intro-text left-0 text-center bg-faded p-5 rounded">
                        <h2 class="section-heading mb-4">
                            <!-- <span class="section-heading-upper">Kopi asli Pati</span> -->
                            <span class="section-heading-lower">Asli Kopi Pati</span>
                        </h2>
                        <p class="mb-3">Setiap cangkir kopi artisan berkualitas kami dimulai dengan bahan-bahan pilihan lokal. Setelah Anda mencobanya, kopi kami akan menjadi tambahan yang menyenangkan untuk rutinitas pagi Anda setiap hari - kami jamin!</p>
                        <div class="intro-button mx-auto"><a class="btn btn-primary btn-xl" target="_balank" href="https://shopee.co.id/KOPI-TANI-PATI-i.32044820.1919090182">Order sekarang</a></div>
                    </div>
                </div>
            </div>
        </section>

        <section class="page-section cta">
            <div class="container">
                <div class="row">
                    <div class="col-xl-9 mx-auto">
                        <div class="cta-inner bg-faded text-center rounded">
                            <h2 class="section-heading mb-4">
                                <span class="section-heading-upper">Janji kita</span>
                                <span class="section-heading-lower">Untukmu</span>
                            </h2>
                            <p class="mb-0">Ketika Anda datang ke kedai kami, kami berdedikasi untuk menyediakan Anda dengan layanan yang ramah, suasana yang ramah, dan di atas segalanya, produk unggulan yang dibuat dengan bahan-bahan berkualitas tinggi. Jika Anda tidak puas, beri tahu kami dan kami akan melakukan apa pun yang kami bisa untuk memperbaikinya!</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <Footer />
</template> 

