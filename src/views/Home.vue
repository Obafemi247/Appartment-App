<template>
 <div class="home">
    <page-header />
    <appCard/>
    <clientTestie/>
    <appNote/>
    <pageFooter/>
  </div>

</template>

<script>
// @ is an alias to /src
import PageHeader from '@/components/header.vue';
import appCard from '@/components/appCard.vue';
import clientTestie from '@/components/testimonial.vue';
import appNote from '@/components/postproperty.vue';
import pageFooter from '@/components/footer.vue';


export default {
  name: 'home',
  components: {
    PageHeader, appCard, clientTestie, appNote, pageFooter
  }
  
}
</script>
<style scoped>

</style>

