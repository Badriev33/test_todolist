<script setup>
import { useRouter } from 'vue-router';

const router = useRouter()

</script>
<template>
    <div class="flex flex-col justify-center items-center w-full h-full">
        <h1>Тестовый проект "To do List"</h1>
        <button class="mt-1 px-2 py-1 h-10 rounded-lg bg-black text-white" @click="router.push('List')" type="button">
            Перейти к списку дел
        </button>
    </div>
</template>