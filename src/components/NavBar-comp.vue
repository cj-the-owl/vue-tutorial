<template>
    <nav class="topnav">
        <routerlink class="active" to="/">Home</routerlink>
        <routerlink to="/">Tutorials</routerlink>
        <routerlink to="/">About</routerlink>
    </nav>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    .topnav {
        background-color: #333;
        overflow: hidden;
    }

    routerlink {
        float: left;
        color: #f2f2f2f2;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        font-size: 17px;
    }
</style>