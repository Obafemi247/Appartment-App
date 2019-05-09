<template>
    <div id="contactHeader">
     <nav class="Menu">
        <span class="wrapper">
            <router-link class="link1" to="/">Home</router-link>
        </span>
        <span class="wrapper"> 
            <router-link class="link1" to="/houses">Properties</router-link>
        </span>
        <span class="wrapper"> 
            <router-link class="link1" to="/offices">Admin</router-link>
        </span>
        <span class="wrapper"> 
            <router-link class="link1" to="/Services">Services</router-link>
        </span>
        <span class="wrapper">
            <router-link class="link1" to="/Contact">Contact</router-link>
        </span>
        <span class="wrapper">  
        <router-link class="link1" to="/About">About</router-link>
        </span>
     </nav>
    <div>
        <h3>CONTACT  US  TODAY!</h3>
        <span class="shortnote">We will connect you faster that other connections</span> 
    </div>
    </div>    
</template>

<style>
#contactHeader{
    position: absolute;
width: 1350px;
height: 342px;
left: 0px;
top: 0px;
background: url("../assets/contact.png");
}

.Menu{
   flex: 1;
   margin-top:50px;
 }
 .wrapper {
   color: #fcfcfc;
   text-decoration: none;
 }
 .link1 {
   padding: 0.5em 1em 4em;
   color: #fcfcfc;
   text-decoration: none;
 }
 h3{
position: absolute;
width: 339px;
height: 20px;
left:500px;
top: 159px;

font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 24px;

color: #FFFFFF;
 }
.shortnote{
 position: absolute;
width: 256px;
height: 28px;
left: 542px;
top: 222px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;
text-align: center;

color: #FFFFFF;
}
</style>
