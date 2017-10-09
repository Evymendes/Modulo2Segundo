<template>
	<div>
		<img src="https://i.pinimg.com/736x/22/a2/19/22a21941d8e5fce3c6e9e3a8a258cef4--galaxy-cat-hipster-cat.jpg">
		<p> {{nome}}</p>
		<p> {{data}}</p> 
		<p>{{descricao}}</p>
	</div>
	
</template>

<script>
	export default {
		name: 'Gato',
		props: ['nome', 'data', 'descricao' ]		
	}	
</script>

<style>
	div img{
		width:30%;
	}
</style>