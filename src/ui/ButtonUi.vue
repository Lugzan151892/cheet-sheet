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
        background-color: #E1FC28;
        padding: 20px;
        border-radius: 5px;
        cursor: pointer;
    }
</style>
