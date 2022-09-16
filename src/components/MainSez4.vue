<template>
    <div class="sez-4">
        <div class="slid">
            <h2 class="titl-slid">View all our causes</h2>
        </div>
        <div class="container-3">
            <div>
                <h1 class="title-sez3">Latest articles</h1>
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
                <div class="card-1-2-3">
                    <div class="card">
                        <img src="../img" alt="#">

                    </div>

                    
                </div>

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

    .sez-4{
        width:100%;
        height: 1150px;
        background-color: white;
    }


    .cont{
        display: flex;


    }

    .card-1{
        margin-left: 300px;
        margin-top: 80px;
        border: 1px solid gray;

    }

    .title-yell{
        color: rgb(242, 192, 103);
        margin-top: 25px;

    }

    .paragraph-sez4{
        margin-top: 25px;
        color: gray;
    }

    .card-1-2-3{
        display: flex;

    }



</style>