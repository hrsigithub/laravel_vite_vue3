<script setup>
import Counter from "./comonents/Counter.vue";
import logo from "../images/naka.jpg";
</script>

<template>
    <h1>Hello World</h1>
    <img :src="logo" />
    <img src="../images/naka.jpg" />
    <Counter />
</template>