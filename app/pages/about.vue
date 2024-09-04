<template>
    <div>
        This page is about me.
    </div>
    <div>
        <button @click="enableCustomLayout">Update layout</button>
    </div>
</template>
<script setup lang="ts">

function enableCustomLayout() {
    setPageLayout('another')
}
//definePageMeta({
//    layout: 'custom'
//})
</script>