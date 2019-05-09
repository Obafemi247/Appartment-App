<template>
    <div id="contact_form">
    <form id="form">
        <label class="inputs">NAME:</label>
        <input type="text" id="names">

        <label class="inputs1">EMAIL:</label>
        <input id="email" type="email">

        <label class="inputs2">MESSAGE:</label>
        <input id="message" type="text">

        <button id="send">SEND</button>
    </form>
    <span id="number">TEL      :  09030788363673<br>
                      EMAIL  :  INFO@betterhold.com</span>
    </div>
</template>

<style>
#contact_form{
    position: absolute;
left: 0%;
right: 0%;
top:345px;
height: 600px;

background: #F2F6FF;
}
#form{
position: absolute;
width: 630px;
height: 398px;
left: 348px;
top: 60px;

background: #FFFFFF;
border: 1px solid #888686;
box-sizing: border-box;
border-radius: 20px;
}

#message{
position: absolute;
width: 525px;
height: 100px;
left: 55px;
top:220px;

background: #FFFFFF;
border: 1px solid #888686;
box-sizing: border-box;
border-radius: 10px;
}
#send{
position: absolute;
width: 130px;
height: 41px;
left: 250px;
top: 340px;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;
text-align: center;
color: #FFFFFF;
background: #66DBB7;
border-radius: 4px;
}
#email{
position: absolute;
width: 525px;
height: 44px;
left: 55px;
top: 135px;

background: #FFFFFF;
border: 1px solid #888686;
box-sizing: border-box;
border-radius: 10px;
}
#names{
position: absolute;
width: 525px;
height: 44px;
left: 55px;
top: 40px;

background: #FFFFFF;
border: 1px solid #888686;
box-sizing: border-box;
border-radius: 10px;
}
#number{
position: absolute;
width: 216px;
height: 44px;
left: 555px;
top: 503px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;

color: #000000;
}
.inputs{
position: absolute;
width: 94px;
height: 20px;
left: 50px;
top: 10px;
font-size: 14px;
line-height: 16px;
color: #000000;
}
.inputs1{
position: absolute;
width: 94px;
height: 20px;
left: 50px;
top: 117px;
font-size: 14px;
line-height: 16px;
color: #000000;
}
.inputs2{
position: absolute;
width: 94px;
height: 20px;
left: 50px;
top: 200px;
font-size: 14px;
line-height: 16px;
color: #000000;
}
</style>
