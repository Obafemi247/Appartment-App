<template>
    <div class="servicePage">
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

        <h5> OUR SERVICES</h5>
        <span class="imga"><img ></span>
        <span id="noteHouse">Connecting house owners and tenants</span>
        
        <span id="noteHouse2">We willc onnect you faster that other <br> connections </span>
        <button id="viewP">view our properties</button>
    </div>
</template>

<style>
.servicePage{
 position: absolute;
width: 1350px;
height: 700px;
left: 0px;
top: 0px;
background: url("../assets/cont.png");
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

h5{
position: absolute;
width: 261px;
height: 24px;
left: 539px;
top: 110px;
font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 28px;
color: #000000;
}
#noteHouse{
position: absolute;
width: 316px;
height: 34px;
left: 540px;
top: 255px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 21px;

color: #FFFFFF;

}

.imga{
position: absolute;
width: 100px;
height: 100px;
top: 300px;
left: 645px;
bottom:0px;
right:0px;
background: url("../assets/home.png");
}
#noteHouse2{
position: absolute;
width: 256px;
height: 28px;
left: 567px;
top: 489px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;
text-align: center;

color: #FFFFFF;
}

#viewP{
position: absolute;
width: 130px;
height: 41px;
left: 634px;
top: 581px;
background: #66DBB7;
border-radius: 4px;
}
</style>
