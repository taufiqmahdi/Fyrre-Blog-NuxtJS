<template>
    <div class="flex gap-8">
        <div class="font-semibold text-2xl">{{ index }}</div>
        <div class="flex flex-col gap-2">
            <div class="font-semibold text-2xl">Street Art Festival</div>
            <div class="flex gap-4 items-center text-sm">
                <div class="flex gap-2">
                    <b>Author</b>
                    <div>Jakob Gronber</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
interface Props {
    index?: string
}

const props = withDefaults(defineProps<Props>(), {
    index: '01'
})
</script>

<style scoped></style>