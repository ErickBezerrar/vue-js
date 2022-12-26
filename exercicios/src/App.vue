<template>
<div>
    <h1>{{ printnome() }}</h1>
    <p>{{ idade, preco }}</p>
</div>
</template>

<script>
export default{
    data(){
        return{
            nome: "Erick" , 
            idade: 25 , 
            preco: 500

        }
    },
    methods: {
      printnome(){
        return this.nome
      }  
    },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
