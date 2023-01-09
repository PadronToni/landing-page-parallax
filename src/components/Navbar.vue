<script setup lang="ts">
import { RouterLink } from 'vue-router'
import Logo from './Logo.vue';
</script>

<template>
	<nav class="flex items-center justify-center gap-4 absolute w-full top-0 z-50"
		aria-label="Primary Navigation">
		<RouterLink to="/" aria-label="Go home" class="p-1 m-4 rounded-full">
			<Logo class="fill-white "></Logo>
		</RouterLink>
	</nav>
</template>
