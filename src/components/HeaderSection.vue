

<script setup>
import Nav from "./Nav.vue";
import Logo from "../assets/img/Logo.png"
</script>

<template>
    <header class="flex justify-between items-center mt-[20px]">
        <div class="">
          <a href="/">
            <img :src="Logo" alt="logo">
          </a>
        </div>
        <Nav/>
        <div class="">
            <a href="/" class="py-[17px] px-[57px] border-black border-solid border text-[24px] font-normal bg-slate-100 rounded-lg hover:bg-[#263238] hover:text-white">Let's Talk</a>
        </div>
    </header>
</template>

<style scoped>


</style>
