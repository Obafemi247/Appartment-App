<template>
    <nav class="navigation">
       <div class="navigationMenu">
      <span class="link__wrapper">
        <router-link class="link" to="/">Home</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/houses">Properties</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/offices">Admin</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/Services">Services</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/Contact">Contact</router-link>
      </span>
      <span class="link__wrapper">  
      <router-link class="link" to="/About">About</router-link>
      </span>
    </div>
    <div>
      <button class="navbarButton">
        Post a property
      </button>
    </div> 
    </nav>    
</template>
<script>
export default {
    name: 'Navigation'
}
</script>

<style scoped>
.navigation{
    position: absolute;
width: 1350px;
height: 84px;
left: 0px;
top: 2px;

background: #354A5F;
}

.navigationMenu{
   align-content: center;
   justify-content: center;
   flex: 1;
   margin-top:30px;
   display: flex;
 }
 .link {
   color: #fcfcfc;
   padding: 0.5 3em;
   text-decoration: none;
  
 }
 .link__wrapper {
   padding: 0.5em 1em;
 }
 

.navbarButton{
position: absolute;
width: 130px;
height: 41px;
left: 1200px;
top: 23px;
color:#FFFFFF;
background: #66DBB7;
border-radius: 5px;
}
</style>


