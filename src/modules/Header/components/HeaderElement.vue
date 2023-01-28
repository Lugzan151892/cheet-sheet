<template>
    <header class="header">
        <div class="header__container">
            <h2 class="header__title">Cheat - <span class="header__title_span">Sheet</span></h2>
            <div class="header__list">
                <NavList></NavList>
                <ButtonUi>Sign Up</ButtonUi>
            </div>            
        </div>        
    </header>
</template>
<script setup>
import NavList from './NavList.vue';
</script>
<style lang="css" scoped>
    .header {        
        width: 100%;
        display: flex;
        justify-content: center;
    }
    .header__container {
        width: 100%;
        height: 10vh;
        max-width: 1440px;
        padding: 0 20px;
        border-bottom: 1px solid gray;
        max-height: 200px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-direction: row;
        background-color: #252527;
    }
    .header__title {
        color: #FEFDFF;
        font-size: 30px;
    }
    .header__title_span {
        color: #E1FC28;
    }
    .header__list {
        height: 100%;
        display: flex;
        align-items: center;
    }
</style>
