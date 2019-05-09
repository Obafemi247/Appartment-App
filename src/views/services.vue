<template>
 <div class="services">
    <servicePage/>
    <bottomPage/>
    
  </div>

</template>

<script>
// @ is an alias to /src
import servicePage from '@/components/serviceHeader.vue';
import bottomPage from '@/components/seviceBottom.vue';




export default {
  name: 'services',
  components: {
    servicePage, bottomPage
  }
  
}
</script>
<style scoped>

</style>