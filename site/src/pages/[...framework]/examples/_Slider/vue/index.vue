<script setup lang="ts">
import Comp from './Component.vue'
</script>

<template>
	<Comp :min="0" :defaultValue="[50]" :max="100" :step="1" />
</template>
