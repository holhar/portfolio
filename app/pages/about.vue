<template>
    <div>
        This page is about me.
    </div>
    <div>
        <button @click="enableCustomLayout">Update layout</button>
    </div>
</template>

<script setup lang="ts">
useHead({
    title: 'About'
})

function enableCustomLayout() {
    setPageLayout('another')
}
//definePageMeta({
//    layout: 'custom'
//})
</script>