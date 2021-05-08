<template>
  <header class="head-container">
            <div class="start"><img src="@/static/youtube-logo.png" alt=""></div>
            <div class="center">
                <input type="text" value="搜尋">
                <button><a href=""><img src="@/static/search.png" alt=""></a></button>

            </div>
            <div class="end">JO</div>

  </header>
</template>
<script>
export default {
    name:"APPheader"
}
</script>

<style lang="scss">
.head-container {
        height: 56px ;
        display: flex;
        position: fixed;
        top: 0;
        width: 100%;
        background-color: rgb(255, 255, 255);
        align-items: center;
        flex-direction: row;
        justify-content:space-between;
        box-shadow:3px 3px 12px black;

        .start{
            margin: 5px;
            padding: 1.5px;
            height: 50px;
            width: 10%;
            img{
                max-height: 100%;  
                max-width: 100%; 
            }
        }
        .center{
            display: flex;
            
            width: 80%;
            input{
                
                width: 80%;
                line-height: 180%;
                font-size: 1em;
                outline :none;
            }
        }
        .end{
            text-align: center  ;
            margin: 5px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgb(250, 167, 14);
            color: blanchedalmond;
        }
    }
</style>
