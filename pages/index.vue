<template>
      <div class="flex flex-col h-screen justify-between">
        
        <div>
         <Header />
        </div>

        <div class="flex-1 overflow-y-auto p-5">
          <Tutorial />
        </div>

        <div>
          <Footer />
        </div>

      </div>
</template>

<script>
import Tutorial from '../components/default/Tutorial.vue'
import Footer from '../components/page-tools/Footer.vue'
import Header from '../components/page-tools/Header.vue'
export default {
  name: "app",
  components: {
    Tutorial,
    Header,
    Footer
  }
}
</script>
