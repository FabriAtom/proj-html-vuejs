<template>
    <div class="sez-4">
        <div class="slid">
            <h2 class="titl-slid">View all our causes</h2>
        </div>
        <div class="container-3">
            <div>
                <h1 class="title-sez3">latest articles</h1>
            </div>
            <div>
                <hr class="top">
            </div>
            <div>
                <p class="paragraph-sez3">Together we make all the difference</p>
            </div>
            <div class="cont">
                <div class="card-1">
                    <img src="../img/photo-1444213007800-cff19e1677ac-600x450.jpg" alt="#">
                    <h3 class="title-yell">Understanding community complexities</h3>
                    <p class="paragraph-sez4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Prasent ac <br> nibh vestibulum, laoreet ipsum.</p>
                </div>
                <div id="container-card">
                    <div class="card-orizz">
                        <div class="img4">
                            <img class="img-sez4" src="../img/photo-1444664597500-035db93e2323-177x142.jpg" alt="#">
                        </div>
                        <div class="text-4">
                            <h3 class="title-yell-1">The human story of uniqueness</h3>
                            <p class="paragraph-sez4">Lorem ipsum dolor sit amet, consectetur adipiscing <br> elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div> 
                    </div>
                    <div class="card-orizz">
                        <div class="img4">
                            <img class="img-sez4" src="../img/photo-1447430617419-95715602278e-177x142.jpg" alt="#">
                        </div>
                        <div class="text-4">
                            <h3 class="title-yell-1">The human story of uniqueness</h3>
                            <p class="paragraph-sez4">Lorem ipsum dolor sit amet, consectetur adipiscing <br> elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div> 
                    </div>
                    <div class="card-orizz">
                        <div class="img4">
                            <img class="img-sez4" src="../img/photo-1460230525622-630fe3294cd7-177x142.jpg" alt="#">
                        </div>
                        <div class="text-4">
                            <h3 class="title-yell-1">The human story of uniqueness</h3>
                            <p class="paragraph-sez4">Lorem ipsum dolor sit amet, consectetur adipiscing <br> elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div> 
                    </div>
                    <div class="card-orizz">
                        <div class="img4">
                            <img class="img-sez4" src="../img/photo-1460600421604-5e138c208b9c-177x142.jpg" alt="#">
                        </div>
                        <div class="text-4">
                            <h3 class="title-yell-1">The human story of uniqueness</h3>
                            <p class="paragraph-sez4">Lorem ipsum dolor sit amet, consectetur adipiscing <br> elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div> 
                    </div>
               </div>
            </div>
        </div>
        <div class="slid-2">
            <h2 class="titl-slid-2">View all our articles</h2>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MainSez3'
}
</script>

<style>
    .flex-cont{ 
        display: flex;
        height: 133px;

    }

    .sez-4{
        width:100%;
        height: 1350px;
        background-color: white;
    }

    .cont{
        display: flex;
        width: 100%;
    }

    .card-1{
        margin-left: 300px;
        margin-top: 80px;
        border: 1px solid lightgray;

    }

    .title-yell{
        color: rgb(242, 192, 103);
        margin-top: 25px;
        font-size: 20px;
        font-style: normal;
        font-weight: 500;
        letter-spacing: 1px;
        line-height: 36px;
        text-decoration-style: solid;
        margin-left: 15px;
    }

    .paragraph-sez4{
        color: gray;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 36px;
        font-family:'Raleway', sans-serif;
        margin-left: 15px;
        margin-top: 3px;
    }

    .title-yell-1{
        color: rgb(242, 192, 103);
        margin-left: 15px;
        font-size: 20px;
        letter-spacing: 1px;
        cursor: pointer;
        font-weight: 500;
        font-style: normal;
        line-height: 30px;
    }
 
    .card-orizz{
        display: flex;
        margin-bottom: 10px;
    }

    #container-card{
        margin-top: 80px;
    }

    .img4{
        margin-left: 50px;
    }

    .img-sez4{
        width: 144px;
    }

    .text-4{
        height: 143px;  
    }

    .slid{
        width: 100%;
        height: 150px;
        background-color: rgb(230, 106, 105);
        margin-top: 65px;
        display: flex;
        cursor: pointer;
    }

    .slid-2{
        width: 65%;
        background-color: rgb(230, 106, 105);
        display: flex;
        cursor: pointer;
        height: 60px;
        margin-top: 333px;
        margin-left: 297px;
    }

    .titl-slid {
        text-align: center;
        color: white;
        margin-top: 55px;
        margin-left: 835px;
        font-style: normal;
        font-weight: 500px;
        line-height: 38px;
        font-family:'Montserrat', sans-serif;
        cursor: pointer;
        letter-spacing: 2px;
        font-size: 22px;
    }

    .titl-slid-2 {
        text-align: center;
        color: white;
        font-style: normal;
        font-weight: 500px;
        line-height: 38px;
        font-family:'Montserrat', sans-serif ;
        cursor: pointer;
        letter-spacing: 2px;
        margin-left: 500px;
        margin-top: 8px;
        font-size: 18px;
    }
    .slid-2:hover{
        background-color: rgb(64, 130, 146);
        transition:400ms;
    }

</style>