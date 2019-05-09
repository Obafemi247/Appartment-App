<template>
 <header class="page__header">
    <div class="header__form">
      <h1>Find the perfect home for you.</h1>
      <form action="POST">
        <div class="form__row">
          <label for="location">Location:</label>
          <input type="text" name="location" id="location" class="form__input">
        </div>
        <div class="form__row">
          <div class="form__group">
            
            <input type="text" name="location" id="location" class="form__input1"> 
          </div>
          <div class="form__group">
            <input type="text" name="location" id="location" class="form__input2"> 
          </div>
        </div>
        <button type="submit" class="form__button ">SEARCH</button>
      </form>
    </div>
  </header>
</template>
<style>
.page__header {
  height: 600px;
  background: url("../assets/Background.png");
  text-align: center;
  display: flex;
  margin: auto;
}
.header__form {
  background: #ffffff;
  border-radius: 10px;
  padding: 2em;
  margin: auto;
  height:250px;
}
.form__input{
  position: absolute;
width: 437px;
height: 40px;
left: 443px;
top: 294px;

border: 1px solid #C4C4C4;
box-sizing: border-box;
border-radius: 5px;

}
.form__input1{
  position: absolute;
width: 200px;
height: 35px;
left: 443px;
top: 351px;
border: 1px solid #C4C4C4;
box-sizing: border-box;
border-radius: 5px;
}

.form__input2{
position: absolute;
width: 200px;
height: 35px;
left: 680px;
top: 351px;
border: 1px solid #C4C4C4;
box-sizing: border-box;
border-radius: 5px;
}
.form__button{
position: absolute;
width: 130px;
height: 41px;
left: 600px;
top: 400px;

background: #66DBB7;
border-radius: 4px;
}

</style>