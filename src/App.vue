<template>
    <header></header>

    <main>
        <h1>Frontend Mentor | QR code component</h1>
        <div class="container">
            <qr-code class="center" />
        </div>
        <div class="attribution">
            Challenge by
            <a
                href="https://www.frontendmentor.io?ref=challenge"
                target="_blank"
                >Frontend Mentor</a
            >. Coded by
            <a href="https://github.com/grantmcdade">Grant McDade</a>.
        </div>
    </main>
</template>

<script setup lang="ts">
import QrCode from '@/components/QrCode.vue';
</script>

<style scoped></style>
