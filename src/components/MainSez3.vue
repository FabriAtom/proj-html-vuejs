<template>
   <div class="container-3">
        <div>
            <h1 class="title-sez3">recent causes</h1>
        </div>
        <div>
            <hr class="top">
        </div>
        <div>
            <p class="paragraph-sez3">We run projects in over 30 countries in 5 contintents</p>
        </div>
        <div class="flex">
            <div class="card-sez3">
                <img class="img-1 im" src="../img/avada-charity-fair-trade-featured-200x150.jpg" alt="#">
            </div>

            <div class="card-sez3">
                <img class="im" src="../img/avada-charity-shelter-featured-400x300.jpg" alt="#">
            </div>

            <div class="card-sez3">
                <img class="im" src="../img/avada-charity-farming-featured-600x450.jpg" alt="#">
            </div>

            <div class="card-sez3">
                <img class="im" src="../img/avada-charity-vaccines-featured-400x300.jpg" alt="#">
            </div>
        </div>   
   </div> 
</template>

<script>
export default {
    name: 'MainSez3',
}
</script>

<style>
     .container-3{
        max-width: 100%;
        height: 700px;
        background:white;
    }

    .title-sez3{
        color: black;
        text-align: center;
        padding-top: 100px;
        font-size: 36px;
        font-weight: 500px;
        line-height: 36px;
        letter-spacing: 1px;
        font-family:'Montserrat', sans-serif;
    }

    .paragraph-sez3{
        font-family: 'Raleway', sans-serif;
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        line-height: 38px;
        text-align: center;
        color: grey;
    }

    .card-sez3{
        margin-top: 110px;
    }

    .im{
        width: 350px;
        margin-left: 35px;
        cursor: pointer;
    }

    .im:hover{
        background-color: rgba(242, 192, 103, 0.7);
        transition: 500ms;
        opacity: 0.4; 
    } 

    .img-1{
        margin-left: 195px;
    }

    .slid{
        width: 100%;
        height: 150px;
        background-color: rgb(230, 106, 105);
        margin-top: 65px;
        display: flex;
        cursor: pointer;
    }

    .slid:hover{
        background-color: rgb(64, 130, 146);
        transition:400ms;
    }
</style>
