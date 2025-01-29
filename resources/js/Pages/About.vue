<script setup lang="ts">
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="About" />
    <div class="bg-gray-50 text-black/50 dark:bg-black dark:text-white/50">
        <img
            id="background"
            class="absolute -left-20 top-0 max-w-[877px]"
            src="https://laravel.com/assets/img/welcome/background.svg"
        />
        <div
            class="relative flex min-h-screen flex-col items-center justify-center selection:bg-[#FF2D20] selection:text-white"
        >
        <div class="relative w-full max-w-2xl px-6 lg:max-w-7xl">
            <h2 class="text-2xl font-semibold text-white">
                About Page
            </h2>
        </div>
        </div>
      
    </div>
</template>