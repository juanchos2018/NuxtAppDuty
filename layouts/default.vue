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

  
   head() {
      return {
        title: this.title,
        meta: [  
          {
            hid: 'ventas yojuce',
            name: 'ventas yojuce',
            content: 'ventas de articulos'
          }
        ]
      }
   } 
}


</script>

<style>
</style>
