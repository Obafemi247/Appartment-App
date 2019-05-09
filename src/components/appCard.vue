<template>
    <div id="appCard">
        <div>
        <h2><strong>Latest Properties</strong></h2>
        <p class="note">view the latest property on the market. You are sure to see something good.</p>
        </div>
        <span class="image"></span><span class="image2"></span><span class="image3"></span>
    <div id="display">
        <p class="note2">View all houses</p>
    </div>



    <div id="mail">
        <p class="note3"> Signup to get the latest offers in your inbox</p>
       <span class="box"> <input type="email" placeholder="Email" id="input"> <button id="button">signup</button></span>
    </div>
    </div>
</template>

<style scoped>
#card{
    position: absolute;
width: 1350px;
height: 69px;
left: -1px;
top: 676px;
background: #F2F6FF;

}
h2{
font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 28px;
color: #000000;
top:400px;
}


.image{
    position: absolute;
width: 288px;
height: 346px;
left: 234px;
top: 834px;
background: url("../assets/Group.png");
}
.image2{
position: absolute;
width: 288px;
height: 346px;
left: 586px;
top: 834px;
background: url("../assets/Group.png");
}
.image3{
position: absolute;
width: 288px;
height: 346px;
left: 938px;
top: 834px;
background: url("../assets/Group.png");
}
.note{
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;
color: #000000;
}
.note2{
position: absolute;
width: 102px;
height: 20px;
left: 661px;
top: 1257px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;

color: #000000;
}
#mail{
position: absolute;
width: 1350px;
height: 208px;
left: 0px;
top: 1364px;

background: #354A5F;
}
.note3{
    position: absolute;
width: 350px;
height: 28px;
left: 595px;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 21px;

color: #FFFFFF;

}
.box{
position: absolute;
width: 791px;
height: 92px;
left: 324px;
top:80px;
background: #FFFFFF;
}
#input{
    position: absolute;
width: 554px;
height: 41px;
left: 50px;
top: 24px;

background: #FFFFFF;
border: 1px solid #C4C4C4;
box-sizing: border-box;
border-radius: 5px;
}
#button{
position: absolute;
width: 130px;
height: 41px;
left: 637px;
top:24px;

background: #66DBB7;
border-radius: 4px;
}
</style>
