<template>
 <appheader></appheader>
 <app-body></app-body>
<app-footer></app-footer>
</template>

<script>
import Header from './components/Header'
import Body from './components/Body'
import Footer from './components/Footer';


export default {
	name: 'App',
	components: {
		appheader: Header,
		appBody: Body,
		appFooter: Footer,

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