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
	text: {{ text }}
	<hr />
	disabled: {{ disabled }}
	<hr />
	<button :disabled="disabled">Кнопка</button>
</template>
