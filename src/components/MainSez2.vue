<template>
    <div class="container-2">
        <div class="title-2">
            <h1 class="title-22">our values</h1>
        </div>
        <div>
            <hr class="top">
        </div>
        <div>
            <p class="paragraph2">Think Big. Act Bigger.</p>
        </div>
        <div class="flex">
            <div class="card">
                <i class="fa-solid fa-droplet icon"></i>
                <h3 class="title-3">Clean Water</h3>
                <p id="paragraphID">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                <button class="butt-hover">Learn More</button>
            </div>
            <div class="card">
                <i class="fa-solid fa-stethoscope icon"></i>
                <h3 class="title-3">Vaccinations</h3>
                <p id="paragraphID">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                <button class="butt-hover">Learn More</button>
            </div>
            <div class="card">
                <i class="fa-solid fa-graduation-cap icon"></i>
                <h3 class="title-3">Education</h3>
                <p id="paragraphID">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                <button class="butt-hover">Learn More</button>
            </div>
            <div class="card">
                <i class="fa-solid fa-leaf icon"></i>
                <h3 class="title-3">Farming</h3>
                <p id="paragraphID">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                <button class="butt-hover">Learn More</button>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: 
     'MainSez2'  
}
</script>

<style>
    .container-2{
        max-width: 100%;
        height: 920px;
        background-image: url(../img/home-content-bg-2.jpg);
        background-attachment:fixed;
        background-position: center;
    }

    .title-22{
        color: white;
        text-align: center;
        padding-top: 130px;
    }

    .flex{
        display: flex;
    }

    .card{
        height: 327px;
        width: 292px;
        margin-left: 135px;
        margin-top: 110px;
    }

    .title-2{
        font-size: 25px;
        font-style: normal;
        font-weight: 500;
        letter-spacing: 3px;
        font-family:'Montserrat', sans-serif;
    }

    .paragraph2{
        font-family:'Raleway', sans-serif;
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        line-height: 38px;
        text-align: center;
        color: white;  
    }

    .top{
        margin-top:40px;
        margin-bottom:40px;
        width: 191px;
        margin-left: 850px;
        border: 2px solid rgb(242, 192, 103);
    }

    .butt-hover{
        background-color: rgb(242, 192, 103);
        color: white;
        font-family:'Montserrat', sans-serif;
        font-weight: 500;
        font-style: normal;
        font-size: 14px;
        padding: 15px 65px; 
        border: 0;
        margin-left: 45px;
        margin-top: 35px;
        cursor: pointer;
    }

    .butt-hover:hover{
        background-color: rgb(38, 46, 68);
    }

    #paragraphID{
        line-height: 36px;
        letter-spacing: normal;
        font-weight: 400px;
        font-size: 16px;
        font-family: 'Raleway', sans-serif;
        color: lightgray;
        text-align: center;
    }
    
    .title-3{
        color: white;
        text-align: center;
        font-size: 23px;
        font-style: normal;
        font-weight: 500;
        letter-spacing: 1px;
        line-height: 28px;
        margin-top: 10px;
        margin-bottom: 24px;
        cursor: pointer;
    }

    .icon{
        font-size: 70px;
        font-weight: 400;
        height: 70px;
        color: rgb(242, 192, 103);
        margin-left: 110px;
        margin-bottom: 10px;
        cursor: pointer;
    }
</style>