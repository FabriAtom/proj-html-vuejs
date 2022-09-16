<template>
    <div class="sez-2">
        <div class="text">
            <h1 class="title">Every moment counts</h1>
            <div><hr class="hr"></div>
            <p class="padd">Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id <br> velit. Aliquam mattis metus a nisi pretium.</p>
            <p class="padd">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum nisi. Curabitur non mi <br> et turpis pharetra vulputate. Ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum <br> nisi.</p>
            <p class="padd">Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id  <br> velit.</p>
            <button class="butt-hov">Our mission</button>
        </div>
        <div class="hearth">
            <div class="text-icon">
                <div class="block-icon">
                   <i class="fa-regular fa-heart icon-2">2032</i>
                   <h2 class="title-hearth">Volunteers worldwide</h2>
                </div>
                <div class="block-icon">
                    <i class="fa-solid fa-earth-americas icon-2">132</i>
                    <h2 class="title-hearth">Active projects</h2>
                </div>
                <div class="block-icon">
                    <i class="fa-solid fa-dollar-sign icon-2">3.8M</i>
                    <h2 class="title-hearth">Donated</h2>
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
        background-image: url(../img/home-content-bg-1.jpg);  
    }

    .title{
        text-transform: uppercase;
        font-size: 36px;
        text-align: left;
        font-weight: 500;
        font-style: normal;
        font-family: 'Montserrat', sans-serif;
    }

    .padd{
        margin-bottom: 30px;
        font-family: 'Raleway', sans-serif;
        font-size: 18px; 
        font-weight: 400px;
        line-height: 26px;
        color: grey;
    } 

    .butt-hov{
        background-color: rgb(242, 192, 103);
        color: white;
        font-family: 'Montserrat', sans-serif;
        font-weight: 500;
        font-style: normal;
        font-size: 14px;
        padding: 13px 42px; 
        border: 0;
        cursor: pointer;
        background-attachment: scroll;
    }

    .text-icon{
        text-align: center;
        line-height: normal;
        color: white;
        padding-top: 100px;
        font-family:'Montserrat', sans-serif;
    }

    .block-icon{
        width: 100%;
        height:200px;
    }

    .title-hearth{
        margin-top: 7px;
    }

    .icon-sez1{
        display: inline;
    }

    .icon-2{
        font-size: 34px;
        width: 34px;
        margin-top: 20px;
        margin-right: 80px;
    }
</style>
