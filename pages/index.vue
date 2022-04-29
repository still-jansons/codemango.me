<template>
    <div class="logo-wrapper">
        <img src="~/static/codemango.svg" alt="CODE MANGO">
    </div>
</template>

<script>
export default {
    name: 'IndexPage'
}
</script>

<style scoped>
    .logo-wrapper {
        height: 100vh;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .logo-wrapper img {
        max-width: 90%;
    }
</style>
