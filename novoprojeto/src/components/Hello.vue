<template>
  <section>
    <h1>{{ titulo }}</h1>
    <Gato
     nome='Pepeu'
     data='12/12/2012'
     descricao='Um dos filhotes que ficou conosco quando sua mãe o teve ele e o seu irmão já falecido por veneno Tete'
     imagem='https://i.pinimg.com/736x/22/a2/19/22a21941d8e5fce3c6e9e3a8a258cef4--galaxy-cat-hipster-cat.jpg'> </Gato>
   
  </section>
</template>

<script>
  import Gato from './Gato'

  export default {
    name: 'hello',
    data () {
      return {
        titulo: 'Portifólio',
      }
    },
        components: {Gato}
  }
</script>

<style>

</style>
