<template>
    <nav class="nav">
        <a class="nav__link" v-for="link in navLinks" :key="link" href="#">{{ link }}</a>
    </nav>
</template>
<script setup>
import {navLinks} from '../constants/data.js'

</script>
<style lang="css" scoped>
    .nav {
        display: flex;
        /* height: 200px; */
    }
    .nav__link {
        display: flex;
        flex-direction: column;
        height: 100%;
        border-bottom: 1px solid #E1FC28;
    }
</style>
