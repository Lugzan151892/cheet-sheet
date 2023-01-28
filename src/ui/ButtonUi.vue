<template>
    <button class="button">
        <slot></slot>
    </button>
</template>
<script>
export default {
    name: 'ButtonUi',    
}
</script>
<script setup>

</script>
<style lang="css" scoped>
    .button {
        display: inline-block;
        background-color: #E1FC28;
        padding: 15px 30px;
        border-radius: 5px;
        cursor: pointer;
        transition: all 0.5s ease;
    }
    .button:hover {
        transform: scale(1.1);
    }
</style>
