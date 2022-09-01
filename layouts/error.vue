<template>
	<div>
		<div v-if="$nuxt.isOffline">You are offline</div>
		<h1 v-if="error.statusCode === 404">Page not found custom error page</h1>
		<h1 v-else>An error occurred</h1>
		<NuxtLink to="/">Home page</NuxtLink>
	</div>
</template>

<script>
export default {
	props: ['error'],
	layout: 'error' // you can set a custom layout for the error page
}
</script>
