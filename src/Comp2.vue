<script setup lang="ts">
defineProps({
	disabled: {
		type: Boolean,
		default: false
	}
})
</script>

<template>
	{{ disabled }} <!-- Отображается: true  -->
	<button :disabled="disabled">Кнопка</button> <!-- Заблокирована  -->
</template>
