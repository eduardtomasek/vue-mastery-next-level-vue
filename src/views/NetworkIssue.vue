<template>
	<div>
		<h1>Oh-Oh!</h1>
		<h3>It looks like you're experiencing some network issues.</h3>
		<router-link :to="{ name: 'event-list' }">Go back to the home page</router-link>
	</div>
</template>
