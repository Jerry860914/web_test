<template>
  <footer class="foot-container">
          <div class="foot_item"><img src="../static/chip.png" alt=""></div>
          <div class="foot_item"><img src="../static/download.png" alt=""></div>
          <div class="foot_item"><img src="../static/statistics.png" alt=""></div>
          <div class="foot_item"><img src="../static/worlwide2.png" alt=""></div>

  </footer>
</template>
<script>
export default {
    name:"APPheader",
}
</script>

<style lang="scss">
.foot-container {
        z-index:5;
        height: 56px ;
        display: flex;
        position: fixed;
        bottom: 0;
        width: 100%;
        background-color: rgb(94, 226, 208);
        align-items: center;
        flex-direction: row;
        justify-content:space-between;
        .foot_item {
          background-color: aliceblue;
          text-align: center;
          width :25%;
          height: 100%;
          img {  
            max-height: 100%;  
            
            width: auto;
            height: auto;
          }
        }


    }

</style>
