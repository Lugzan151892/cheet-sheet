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
        height: 100%;
    }
    .nav__link {
        display: flex;
        flex-direction: column;
        justify-content: center;
        height: 100%;
        color: #9E9EA0;
        text-decoration: none;
        margin-right: 30px;
    }
    .nav__link:hover {
        border-bottom: 1px solid #E1FC28;
        color: #FEFDFF;
    }
</style>
