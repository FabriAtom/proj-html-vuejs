<template>
    <div class="container">
        <div id="fusion">
            <div class="logo">
                <img src="../img/avada-charity-logo.png" alt="#">
            </div>
            <div class="navbar">
                <ul>
                    <li><a class="home" href="#">Home</a></li>
                    <li><a class="hover" href="#">Mission</a></li>
                    <li><a class="hover-causes" href="#">Causes <i class="fa-solid fa-arrow-down"></i></a>
                         <ul>
                            <li><a class="hover-1" href="#">fair trade</a></li>
                            <li><a class="hover-1" href="#">Farming</a></li>
                            <li><a class="hover-1" href="#">Vaccines</a></li>
                            <li><a class="hover-1" href="#">Education</a></li> 
                            <li><a class="hover-1" href="#">Clean water</a></li>
                            <li><a class="hover-1" href="#">Shelter</a></li>
                        </ul>
                    </li>
                    <li><a class="hover" href="#">Journal</a></li>
                    <li><a href="#"><button class="butt-hov">Donate</button></a></li>
                </ul>
            </div>
        </div>
        <div class="title-center">
           <h1 id="title">Make a difference</h1>
           <p id="paragraph">As long as poverty, injustice & inequality persist, none of us can truly rest</p>
            <button class="button" type="button">Our mission</button>
            <button class="button-2" type="button">Donate now</button>

        </div>
    </div>

</template>

<script>
export default {
    name: 'HeaderFirst',

}
</script>

<style>
    .container{
        max-width: 100%;
        height: 960px;
        background-image:url(../img/home-page-slider.jpg);
        background-attachment: fixed;
        background-position: top;
    }

    #fusion{
        max-width:100%;
        height: 60px;
        padding: 45px 85px;
        display: flex;
    }
    
    .logo{
        width: 400px;
        height: 55px;
        background-size: contain;
        background-repeat: no-repeat;
        margin: 0;
        cursor: pointer;
    }

    .navbar{
        width: 785px;
        height: 60px;
        color: white;
        margin-left: 500px; 
    }

    .navbar li > ul{
        opacity: 0;
        list-style-type:none;
        background-color: white;
    }


    .navbar li:hover > ul{
        opacity: 1;
    }

    .navbar > ul {
        list-style-type:none;
        display: flex;
        justify-content: space-between;
        font-size: 25px;
    }

    .title-center{
        text-align: center;
        color: white;
        padding-top: 240px;
        font-size: 30px;
    }

    #title {
        margin-bottom: 20px;
        font-family:'Montserrat', sans-serif;
        font-weight: 500;
        font-size: 70px;
        font-style: normal;
        letter-spacing: 2px;
        line-height: 77px;
    }

    #paragraph{
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        font-family: 'Raleway', sans-serif;
    }

    .button{
        padding: 15px 45px;
        background-color:rgba(255,255,255,0.0);
        color: white;
        border-color: white;
        margin-right: 10px;
        margin-top:30px;
        cursor: pointer;
        font-family:'Montserrat', sans-serif;
    }

    .button:hover{
        color: rgb(242, 192, 103);
        border-color:rgb(242, 192, 103);
    }

    .button-2{
        border-color: rgb(242, 192, 103);
        background-color:rgba(242,192,103,0.0);
        padding: 15px 45px;
        color:rgb(242, 192, 103);
        margin-left: 10px;
        margin-top:30px;
        cursor: pointer;
        font-family:'Montserrat', sans-serif;
    }

    .button-2:hover{
        background-color: rgb(38, 46, 68);
        border-color: white;
        color: white;
    }

    .home{
        color: rgb(242, 192, 103);
        text-decoration: none;
    }

    .hover{
        color: white;
        text-decoration: none;
        cursor: pointer;
    }

    .hover:hover{
        color: rgb(242, 192, 103);
        text-decoration: none;
        transition: 500ms;
    }

    .hover-causes{
        color:white;
        text-decoration: none;
    }
    .hover-causes:hover{
        color: rgb(242, 192, 103);
        text-decoration: none;
        transition: 500ms;
    }

    .hover-1{
        color: black;
        text-decoration: none;
        cursor: pointer;
    }

    .hover-1:hover{
        background-color:rgb(242, 192, 103);
        color: white;
    }

    .butt-hov{
        background-color: rgb(242, 192, 103);
        color: white;
        font-family: 'Montserrat', sans-serif;
        font-weight: 500;
        font-style: normal;
        font-size: 14px;
        padding: 13px 29px; 
    }
    .butt-hov:hover{
        background-color: rgb(38, 46, 68);
    }
</style>