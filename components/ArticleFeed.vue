<template>
    <div class="flex gap-16">
        <div class="w-1/5">
            <NuxtImg class="w-full" src="/article-example.png" />
        </div>
        <div class="w-4/5 flex flex-col gap-4 justify-between">
            <div class="flex flex-col gap-4">
                <h1 class="font-bold text-3xl">Hope dies last</h1>
                <div class="font-light">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas dui id ornare arcu odio ut sem. Cras ornare arcu dui vivamus arcu felis bibendum ut. Porttitor leo a diam.
                </div>
            </div>
            <div class="flex gap-4 justify-between items-center">
                <div class="flex gap-4 items-center text-sm">
                    <div class="flex gap-2">
                        <b>Text</b>
                        <div>Jakob Gronber</div>
                    </div>
                    <div class="flex gap-2">
                        <b>Date</b>
                        <div>16 March 2022</div>
                    </div>
                    <div class="flex gap-2">
                        <b>Duration</b>
                        <div>1 Min</div>
                    </div>
                </div>
                <Label>
                    ART
                </Label>
            </div>  
        </div>
    </div>
</template>

<script setup lang="ts">
import Label from './Label.vue';


</script>

<style scoped>

</style>