<template>
    <header class="header">
        <div class="header__container">
            <h2 class="header__title">Cheat-Sheet</h2>
            <div class="header__list">
                <NavList></NavList>
                <ButtonUi>Sign In</ButtonUi>
            </div>            
        </div>        
    </header>
</template>
<script setup>
import NavList from './NavList.vue';
</script>
<style lang="css" scoped>
    .header {
        position: absolute;
        z-index: 300;
        width: 100%;
        display: flex;
        justify-content: center;
    }
    .header__container {
        width: 100%;
        max-width: 1440px;
        padding: 0 20px;
        border-bottom: 1px solid gray;
        max-height: 200px;
        display: flex;
        justify-content: space-between;
        flex-direction: row;
        background-color: #252527;
    }
    .header__title {
        color: white;
        font-size: 30px;
    }
    .header__list {
        display: flex;
        
    }
</style>
