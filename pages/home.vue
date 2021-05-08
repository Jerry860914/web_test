<template>
    
    <div class="page">
        <nav_bar/>
        <div class="item" v-for ="(items, itemid) in arr" :key ="itemid">
            {{items.title}}
            {{items.url}}
        </div>  
        
    </div>
</template>
<script>
import nav_bar from "../components/nav_bar"


export default {
    components : {
        nav_bar
    },

    data() {
        return{
            arr:[{title:"100", url:"100"},
                 {title:"200", url:"100"},
                 {title:"300", url:"100"},
                 {title:"400", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
                 {title:"500", url:"100"},
            ]
        }

    }

}
</script>
<style lang="scss">
$item-per-row:5;
.page {
    display: flex;
    justify-content: center;
    flex-direction: row;
    padding-top: 56px;
    padding-bottom: 56px;
    flex-wrap: wrap;
}
.item {
    background-color: salmon;
    margin: 10px;
    height: 300px;
    width: 300px;


}
</style>