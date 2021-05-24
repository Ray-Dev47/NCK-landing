<template>
 <appheader></appheader>
 <app-body></app-body>

</template>

<script>
import Header from './components/Header.vue'
import Body from './components/body.vue'


export default {
	name: 'App',
	components: {
		appheader: Header,
		appBody: Body
	},
};
</script>

<style>
#app {
	font-family: 'lato' sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	width: 1390px;
	margin: auto;
	background-color: #fff;

}
</style>