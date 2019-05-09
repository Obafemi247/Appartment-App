<template>
    <div id="bottomPage">

        <span class="frame"></span>
        <span class="frame1"></span><span class="placehold"></span>
        <span class="frame2"></span>

    </div>
</template>


<style>

#bottomPage{
position: absolute;
width: 1350px;
height: 600px;

right: 0.35%;
top: 700px;
background: #F2F6FF;

}

.frame{
position: absolute;
width: 400px;
height: 472px;
left: 33px;
top: 87px;
background: url("../assets/but2.png");
}
.frame1{
position: absolute;
width: 400px;
height: 472px;
left: 480px;
top: 87px;
background: url("../assets/but1.png");
}
.frame2{
position: absolute;
width: 400px;
height: 472px;
left: 901px;
top: 87px;
background: url("../assets/but2.png");
}
.placehold{
position: absolute;
width: 100px;
height: 100px;
left: 630px;
top: 230px;

background-image: url("../assets/placeholder.png");
}
</style>
