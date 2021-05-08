<template>
  <div class ="content">  
    <APPheader/>
    <APPfooter/>
    <Nuxt />
  </div>
</template>
<script>
import APPheader from "../components/APPheader"
import APPfooter from "../components/APPfooter"
export default {
  components: {
    APPheader,
    APPfooter
  }
}
</script>

<style lang= "scss">
$font-stack:'Share Tech Mono', monospace;

body {
    background-color:white;
    font-family: $font-stack;
    line-height: 1.6;
    height: 100%;
}

*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}



</style>
