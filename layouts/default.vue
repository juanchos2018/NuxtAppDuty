<template>
  <div class="app-wrapper">
    <Header/>
     <main class="app-content">      
      <nuxt/>
    
    </main>
   <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  name: 'default',
  components: {
    Header,
    Footer,
   
  },

  
 head: {
    title: 'Yojuce',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'ventasyojuce', name: 'ventasyojuce', content: 'ventasyojuce' }
    ], 
   }
}


</script>

<style>
</style>
