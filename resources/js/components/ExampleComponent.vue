<template>
    <div class="notification">
        <h2>{{ message }}</h2>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Hello World'
            }
        }
    }
</script>


<style>
    .notification {
        color: red;
        background-color: green;
    }
</style>
