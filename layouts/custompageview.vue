<template>
	<div>
		<div v-if="$nuxt.isOffline">You are offline</div>
		<h1>this is a custom page template</h1>
		<Nuxt />
	</div>
</template>