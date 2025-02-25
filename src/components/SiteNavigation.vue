<template>
     <header class="sticky top-0 bg-weather-primary shadow-lg">
        <nav class="container flex flex-col sm:flex-row items-center gap-4 text-white py-6">
            <RouterLink :to="{name:'home'}">
                <div class="flex items-center gap-3 flex-1">
                    <i class="fa fa-sun text-2xl" aria-hidden="true"></i>
                    <p class="text-2xl">My weather</p>
                </div>
            </RouterLink>

            <div class="flex gap-3 flex-1 justify-end">
                <i class="fa-solid fa-circle-info text-2xl hover:text-weather-secondary duration-150 cursor-pointer" aria-hidden="true"></i>
                <i class="fa fa-plus text-2xl hover:text-weather-secondary duration-150 cursor-pointer" aria-hidden="true"></i>


            </div>
        </nav>
     </header>
</template>

<script setup>
import { RouterLink  } from 'vue-router';
</script>

 