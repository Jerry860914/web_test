<template>
    <div class="nav">
        <div class="nav_item head"> <p>ALL</p></div>
        <div class="nav_item">Music</div>
        <div class="nav_item">One</div>
        <div class="nav_item">Anime</div>
        <div class="nav_item">Love </div>
        <div class="nav_item">Live</div>
        
        

            

    </div>
</template>
<script>
export default {
    name : "nav_bar"
}
</script>
<style lang="scss">
.nav {
    height: 30px;
    display: flex;
    width: 100%;
    background-color: rgb(255, 255, 255);
    align-items: center;
    justify-content: space-around;
    margin-top: 10px;

    .nav_item {
        text-align: center;
        height: 100%;
        width:100px;
        border-radius: 25px;
        background-color:rgb(218, 218, 218);
        
    }
    .head {
        background-color:rgb(168, 168, 168);
    }
    
}




</style>