<template>
	<view>
		<button @click="toggle">toggle</button>
		<h1 v-if="awesome">Vue is awesome!</h1>
		<h1 v-else>Oh no 😢</h1>
	</view>
</template>

<script setup>
	import {
		ref
	} from 'vue'

	const awesome = ref(true)

	function toggle() {
		awesome.value = !awesome.value
	}
</script>

<style>

</style>
