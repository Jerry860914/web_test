<template>
  <header class="head-container">
            <div class="start"><img src="@/static/youtube-logo.png" alt=""></div>
            <div class="center">
                <input type="text" value="搜尋">
                <button><a href=""><img src="@/static/search.png" alt=""></a></button>

            </div>
            <div class="end">234234</div>

  </header>
</template>
<script>
export default {
    name:"APPheader"
}
</script>

<style lang="scss">
.head-container {
        height: 70px ;
        display: flex;
        position: fixed;
        top: 0;
        width: 100%;
        background-color: rgb(168, 173, 245);
        align-items: center;
        flex-direction: row;
        justify-content:space-between;

        .start{
            padding: 1px;
            height: 50px;
            width: 10%;
            img{
                max-height: 100%;  
                max-width: 100%; 
            }
        }
        .center{
            display: flex;
            justify-content: space-between;
            width: 40%;
            input{
                border-radius: 30px;
                width: 40%;
                line-height: 180%;
                font-size: 1em;
                outline :none;
            }
        }
        .end{
            width: 20%;
        }
    }
</style>
