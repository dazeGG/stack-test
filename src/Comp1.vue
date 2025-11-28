<script setup lang="ts">
import Comp2 from './Comp2.vue';
</script>

<template>
	<!-- Явно передаем :disabled="false", но он игнорируется! -->
	<Comp2 :disabled="false" :text="'asdasd'" />
</template>
