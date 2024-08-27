        <script setup>
       import navData from "../data/navData.js"
        </script>


<template  >
    <nav>
        <ul class="flex justify-between items-center gap-[30px] ">
            <li v-for="(item, index) in navData" :key="index">
                <a :href="item.path" class="text-[20px]  font-medium text-slate-700 hover:text-black" >{{ item.name }}</a>
            </li>
        </ul>
    </nav>
  
</template>
<style >
    
</style>