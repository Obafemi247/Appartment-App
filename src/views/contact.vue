<template>
 <div class="contact">
    <contactHeader/>
    <contactForm/>
    
  </div>

</template>

<script>
// @ is an alias to /src
import contactHeader from '@/components/contactUs.vue';
import contactForm from '@/components/contactform.vue';



export default {
  name: 'contact',
  components: {
    contactHeader, contactForm
  }
  
}
</script>
<style scoped>

</style>