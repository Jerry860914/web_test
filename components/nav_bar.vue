<template>
    <div class="nav">
        <div class="nav_item head"> <p>ALL</p></div>
        <div class="nav_item">234</div>
        <div class="nav_item">234</div>
        <div class="nav_item">234</div>
        <div class="nav_item">234</div>
        <div class="nav_item">234</div>
        <div class="nav_item">234</div>
        

            

    </div>
</template>
<script>
export default {
    name : "nav_bar"
}
</script>
<style lang="scss">
.nav {
    display: flex;
    width: 100%;
    background-color: rgb(255, 255, 255);
    align-items: center;
    justify-content: space-around;
    margin: 10px;

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