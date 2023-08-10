<script setup lang="ts">
import DesignTwo from '@/components/Design/DesignTwo.vue'
</script>

<template>
    <div>
        <div class="flex w-[60%] mb-[82px] space-x-[91px] mx-auto justify-center">
            <div class="w-[40%] samsungsharp leading-[50.4px] text-[42px] font-[700]">
                Get ready to unfold your world
            </div>
            <div class="samsungone w-[60%] text-[18px] font-[400] leading-[27.72px]">
                This is everything you'd want in a premium, durable, 5G smartphone.1
                Then we made it unfold — revealing a massive screen so you can watch,
                work and play like never before.
            </div>
        </div>
        <div class="flex mb-[377px] mx-auto w-[50%] space-x-[20px]">
            <div class="w-[50%] cursor-pointer h-fit">
                <div class="w-fit h-fit picone"><img loading="lazy" src="/image/voiceone.png" class="w-fit mx-auto" /></div>
                <div class="mx-auto mt-[11px] leading-[120%] font-[700] samsungsharp text-[18px] text-center">Voices of
                    Galaxy
                </div>
            </div>
            <div class="w-[50%] cursor-pointer h-fit">
                <div class="w-fit h-fit pictwo"><img loading="lazy" src="/image/voicetwo.png" class="w-fit mx-auto" /></div>
                <div class="mx-auto mt-[11px] leading-[120%] font-[700] samsungsharp text-[18px] text-center">
                    Untold Stories
                </div>
            </div>
        </div>
        <DesignTwo />
    </div>
</template>

<style scoped>
.picone:hover {
    transform: scaleY(1.02);
    transform: scaleX(1.02);
}

.pictwo:hover {
    transform: scaleY(1.02);
    transform: scaleX(1.02);
}
</style>