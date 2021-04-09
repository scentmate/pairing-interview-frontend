<template>
    <div class="container">
        <h1>Welcome to Dev Session</h1>
    </div>
</template>

<script>
export default {
    mounted() {
        console.log(process.env.NODE_ENV)
    },
}
</script>

<style>
body {
    padding: 50px;
    font: 14px 'Lucida Grande', Helvetica, Arial, sans-serif;
}

a {
    color: #00b7ff;
}
</style>
