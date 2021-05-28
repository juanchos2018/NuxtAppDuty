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

  head: function() {
			return this.$seo({
				name: 'Yojuce',
				title: 'Ventas Yojuce',
				templateTitle: 'Ventas Yojuce',
				description: 'Venta de Artículos'
			})
		}

}


</script>

<style>
</style>
