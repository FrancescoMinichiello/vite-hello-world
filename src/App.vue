<script>
//importo il file in cima e gli assegno un nome(buona norma chiamarlo come il file)
import appTitle from './components/appTitle.vue';
import appHero from './components/appHero.vue';

export default{
  //lo inserisco nella lista dei componenti
  components:{
    appTitle,
    appHero
  },
    data(){
        return{
        }
    }
}
</script>

<template>
    <div>
      <appTitle/>
    </div>
    <div>
      <appHero/>
    </div>
</template>

<style scoped>

</style>
