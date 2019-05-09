<template>
    <div class="propertyTop">
        <div>
            <input type="text" placeholder="Search for homes, Offices" class="offices">
            <span class="home">HOME</span>
            <span class="availableHouse"></span>
            <span class="availableHouse2"></span>
        </div>


        <div>
            
            <span class="off">OFFICES</span>
            <span class="availableHouse3"></span>
            <span class="availableHouse4"></span>
        </div>
    </div>

</template>

<style>

.propertyTop{
position: absolute;
width: 1440px;
height: 68px;
left: 0px;
top: 202px;
background: #FFFFFF;
border: 1px solid #C4C4C4;
box-sizing: border-box;
}

.offices{
position: absolute;
width: 618px;
height: 60px;
left: 411px;
top: 124px;
color: #888686;
background: #FFFFFF;
border: 1px solid #888686;
box-sizing: border-box;
border-radius: 10px;
}

.home{
position: absolute;
width: 1440px;
height: 68px;
left: 0px;
top: 202px;

background: #FFFFFF;
border: 1px solid #C4C4C4;
box-sizing: border-box;
}

.availableHouse{
position: absolute;
width: 1318px;
height: 326px;
left: 60px;
top: 296px;
background:url("../assets/housesPix.png");
}
.availableHouse2{
position: absolute;
width: 1320px;
height: 326px;
left: 60px;
top: 680px;
background:url("../assets/housesPix.png");
}


.off{
position: absolute;
width: 1440px;
height: 68px;
left: 0px;
top: 1100px;
background: #FFFFFF;
border: 1px solid #C4C4C4;
box-sizing: border-box;
}
.availableHouse3{
position: absolute;
width: 1320px;
height: 326px;
left: 60px;
top: 1202px;
background:url("../assets/housesPix.png");
}

.availableHouse4{
position: absolute;
width: 1320px;
height: 326px;
left: 60px;
top: 1575px;
background:url("../assets/housesPix.png");
}
</style>

