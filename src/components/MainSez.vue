<template>
    <div class="sez-2">
        <div class="text">
            <h1 class="title">Every moment counts</h1>
            <div><hr class="hr"></div>
            <p class="padd-top padd">Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id <br> velit. Aliquam mattis metus a nisi pretium.</p>
            <p class="padd">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum nisi. Curabitur non mi <br> et turpis pharetra vulputate. Ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum <br> nisi.</p>
            <p class="padd">Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id  <br> velit.</p>
            <button class="butt-hov">Our mission</button>
        </div>

        <div class="hearth">
            <div  class="text-icon">
                <div class="block-icon">
                    <i class="fa-regular fa-heart">2032</i>
                    <h4>Volunteers worldwide</h4>
                </div>
                <div class="block-icon">
                    <i class="fa-solid fa-earth-americas">132</i>
                    <h4>Active projects</h4>
                </div>
                <div class="block-icon">
                    <i class="fa-solid fa-dollar-sign">3.8M</i>
                    <h4>Donated</h4>
                </div>


            </div>
            
        </div>

    </div>
  
</template>

<script>
export default {
    name: 'MainSez',

}
</script>

<style>
    .hr{
        margin-top:20px;
        margin-bottom:25px;
        width: 190px;
        border: 2px solid rgb(242, 192, 103);

    } 
    .sez-2{
      display: flex;
    }

    .text{
       width: 67%;
       height: 650px;
       background-color: white;
       padding-left: 80px;
       padding-top: 80px;
       padding-right: 80px;
    }

    .hearth{
        width: 33%;
        height: 650px;
        background-image: url(../img/home-content-bg-1.jpg);  
    }

    .title{
        text-transform: uppercase;
        font-size: 36px;
        text-align: left;
        font-weight: 500;
        font-style: normal;
    }

    .padd{
        margin-bottom: 40px;
        font-family: raleway;
        font-size: 18px; 
        font-weight: 400px;
    } 

    .padd-top{
        padding-top: 30px;
    }

    .butt-hov{
        background-color: rgb(242, 192, 103);
        color: white;
        font-family: Montserrat;
        font-weight: 500;
        font-style: normal;
        font-size: 14px;
        padding: 13px 29px; 
        border: 0;
        cursor: pointer;
    }

    .text-icon{
        text-align: center;
        line-height: normal;
        color: white;
        padding-top: 100px;
        font-family: Raleway;
    }

    .block-icon{
        
    }

</style>
