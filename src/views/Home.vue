<template>
  <main>
    <div>

       
        <quote :data="quote"/>
      
    </div>
  </main>
</template>
<script>
import randomQuotes from 'random-quotes';
import quote from './components/quote.vue';
export default {
  components:{
    quote
  },
  created(){
    this.quote = randomQuotes();
  },
  data(){
    return{
      quote:''
    }
  }
}
</script>
