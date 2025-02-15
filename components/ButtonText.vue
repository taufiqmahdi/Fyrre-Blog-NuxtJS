<template>
    <NuxtLink :to="to" class="flex gap-2 uppercase font-bold items-center">
        <span v-if="labelPosition === 'start'">
            <svg class="w-5 h-5" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M7.828 13L13.192 18.364L11.778 19.778L4 12L11.778 4.222L13.192 5.636L7.828 11L20 11V13L7.828 13Z" fill="black" /> </svg>
        </span>
        <slot />
        <span v-if="labelPosition === 'end'">
            <svg class="w-5 h-5" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M16.172 11L10.808 5.636L12.222 4.222L20 12L12.222 19.778L10.808 18.364L16.172 13H4V11H16.172Z" fill="black"/> </svg>
        </span>
    </NuxtLink>
</template>

<script setup lang="ts">
    interface Props {
        to?: string
        labelPosition?: 'start' | 'end'
    }

    const props = withDefaults(defineProps<Props>(), {
        to: '/',
        labelPosition: 'end'
    })
</script>

<style scoped>

</style>