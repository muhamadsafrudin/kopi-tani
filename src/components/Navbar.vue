<template>
    <nav class="navbar navbar-expand-lg navbar-dark py-lg-4" id="mainNav">
        <div class="container">
            <a class="navbar-brand text-uppercase fw-bold d-lg-none" href="index.html">KOPI TANI PATI</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mx-auto">
                    <li class="nav-item px-lg-4"><router-link active-class="active" :to="'/home'" class="nav-link text-uppercase">Home</router-link></li>
                    <li class="nav-item px-lg-4"><router-link active-class="active" :to="'/about'" class="nav-link text-uppercase">About</router-link></li>
                    <li class="nav-item px-lg-4"><router-link active-class="active" :to="'/products'" class="nav-link text-uppercase">Products</router-link></li>
                    <li class="nav-item px-lg-4"><router-link active-class="active" :to="'/store'" class="nav-link text-uppercase">Store</router-link></li>
                </ul>
            </div>
        </div>
    </nav>
</template>