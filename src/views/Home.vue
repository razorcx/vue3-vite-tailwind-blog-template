<script setup>
import Header from "../components/Header.vue"
import LatestArticles from "../components/LatestArticles.vue"
import Podcasts from "../components/Podcasts.vue"
import Cta from "../components/Cta.vue"
import MostPopular from '../components/MostPopular.vue'
import Footer from "../components/Footer.vue"
import Nav from "../components/Nav.vue"
</script>

<template>
    <div>
        <Nav />

        <Header />

        <LatestArticles />

        <Podcasts />

        <Cta />

        <MostPopular />

        <Footer />
    </div>
</template>