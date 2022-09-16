<template>
  <div class="foot">
     <div class="logo-foot">
            <img id="logo" src="../img/avada-charity-mobile-logo-retina.png" alt="Logo">

        </div>
        <div class="copyright">
            <p id="center">© Copyright 2012 - 2022 | Avada Theme by <a id="text" href="#">ThemeFusion</a>| All Rights Reserved | Powered by <a id="text" href="#">WordPress</a></p>
            <div class="foot-iconn">
                <a href="#"><i class="fa-brands fa-facebook foot-icon"></i></a>
                <a href="#"><i class="fa-brands fa-instagram foot-icon"></i></a>
                <a href="#"><i class="fa-brands fa-twitter foot-icon"></i></a>
                <a href="#"><i class="fa-brands fa-youtube foot-icon"></i></a>
            </div>
        </div>
  </div>
</template>

<script>
export default {
    name: 'LastFooter'
}
</script>

<style>

.logo-foot{
    height: 180px;
}

.copyright{
    height: 150px;
    background-color: rgb(249, 249, 249);
}


#text{
    text-decoration: none;
    color: rgb(242, 192, 103);
}

#center{
    text-align: center;
    padding-top: 35px;
    font-size: 14px;
    letter-spacing: normal;
    line-height: 36px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

#logo{
    text-align: center;
    background-size: contain;
    background-repeat: no-repeat;
    margin:0 ;
    margin-left: 800px;
    margin-top: 60px;
    font-size: 16px;
    height: 60px;
}

.foot-icon{
    color: rgb(242, 192, 103);
    font-size: 34px;
    width: 34px;
    background-color: white;
    border-radius: 100%;
    margin-left: 10px;
    margin-top: 20px;
}

.foot-iconn{
    margin-left: 860px;
}

</style>