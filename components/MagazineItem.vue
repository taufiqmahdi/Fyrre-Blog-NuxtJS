<template>
    <div class="flex flex-col gap-4 border border-black p-8">
        <div class="flex gap-4 justify-between items-center">
            <div class="font-light">16 March 2022</div>
            <Label>
                Art
            </Label>
        </div>
        <div>
            <NuxtImg class="w-full" src="/article-example.png" />
        </div>
        <div class="flex flex-col gap-4">
            <NuxtLink to="/magazine/test">
                <h1 class="font-bold text-3xl hover:underline">Hope dies last</h1>
            </NuxtLink>
            <div class="font-light text-lg">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                dolore magna aliqua. Egestas dui id ornare arcu odio ut sem. Cras ornare arcu dui vivamus arcu felis
                bibendum ut. Porttitor leo a diam.
            </div>
        </div>
        <div>
            <div class="flex gap-4 items-center text-sm">
                <div class="flex gap-2">
                    <b>Text</b>
                    <div>Jakob Gronber</div>
                </div>
                <div class="flex gap-2">
                    <b>Duration</b>
                    <div>1 Min</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>