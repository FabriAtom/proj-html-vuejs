<template>
<div class="container-5">
    <div>
        <h1 class="title-sez5">CHANGE A LIFE TODAY</h1>
    </div>
    <div>
        <hr class="top">
    </div>
    <div>
        <p class="paragraph-sez5">As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn’t <br> take much to change a life, Get in touch today and start making the difference.</p>
    </div>
    <div class="title-center-5">
        <button class="button-5" type="button">Volunteer</button>
        <button class="button-5" type="button">Donate now</button>
    </div>
</div>
  
</template>

<script>
export default {
    name: 'HomeFooter'
}
</script>

<style>

.container-5{
        max-width: 100%;
        height: 570px;
        background-image: url(../img/home-footer.jpg);
        background-position: center;
    }

    .paragraph-sez5{
        font-family: 'Raleway', sans-serif;
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        line-height: 38px;
        text-align: center;
        color: white; 
    }

    .title-sez5{
        color: white;
        text-align: center;
        padding-top: 100px;
        font-size: 34px;
        font-weight: 500px;
        line-height: 36px;
        letter-spacing: 2px;
        font-family:'Montserrat', sans-serif;
    }

    .button-5{
        padding: 15px 65px;
        background-color:rgba(255,255,255,0.0);
        color: white;
        border-color: white;
        margin-right: 50px;
        cursor: pointer;
        text-align: center;
    }

    .button-5:hover{
        color: rgb(242, 192, 103);
        border-color:rgb(242, 192, 103);
    }

    .title-center-5{
        text-align: center;
        color: white;
        padding-top: 60px;
        font-size: 30px;
    }
</style>