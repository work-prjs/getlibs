
<template>
	<div id="app">
		<h1>{{msg}}</h1>
	</div>
</template>

<script>

import Vue from 'vue';

export default class App extends Vue {
	msg = 'Hello World!';
}

</script>

<style>

h1 {color: red}

</style>