<template>
    <div class="card text-center p-3">
        <div class="card__media">
            <img :src="imageQrCode" alt="QR Code Image" />
        </div>
        <div class="card__title">
            Improve your front-end skills by building projects
        </div>

        <div class="card__content mb-3">
            Scan the QR code to visit Frontend Mentor and take your coding
            skills to the next level
        </div>
    </div>
</template>

<script setup lang="ts">
import imageQrCode from '@/assets/images/image-qr-code.png';
</script>

<style scoped></style>
