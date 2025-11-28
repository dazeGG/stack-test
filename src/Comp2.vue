<script setup lang="ts">
defineProps({
	disabled: {
		type: Boolean,
		default: false
	},
	text: {
		type: String,
		default: 'zxczxc'
	}
})
</script>

<template>
	{{ text }}
	<hr>
	{{ disabled }} <!-- Отображается: true  -->
	<button :disabled="disabled">Кнопка</button> <!-- Заблокирована  -->
</template>
