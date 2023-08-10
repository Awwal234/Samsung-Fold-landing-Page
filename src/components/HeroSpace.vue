<script setup lang="ts">
import DesignOne from '@/components/Design/DesignOne.vue'
</script>

<template>
    <div class="mt-[100px] ">
        <div class="bg_hero mb-[120px] pt-[194px] pl-[100px] w-full h-[914px]">
            <div class="samsungsharp texthero text-[44px] font-[700]">
                Galaxy Z Fold3 5G
            </div>
        </div>
        <DesignOne />
    </div>
</template>

<style scoped>
.bg_hero {
    background: url('/image/herosam.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
    background-position: contain;
}

.texthero {
    animation: 2s alternate-reverse infinite slide;
}

@keyframes slide {
    20% {
        position: relative;
        top: 6px;
    }

    50% {
        position: relative;
        top: 9px;
        opacity: 0.7;
    }

    80% {
        position: relative;
        top: 10px;
        opacity: 0.4;
    }

    100% {
        position: relative;
        top: 12px;
        opacity: 0;
    }
}
</style>