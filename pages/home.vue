<template>
    
    <div class="page">
        <div class="item" v-for ="(items, itemid) in arr" :key ="itemid">
            {{items.title}}
            {{items.url}}
        </div>  
        
    </div>
</template>
<script>
export default {
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
    padding-top: 70px;
    padding-bottom: 70px;
    flex-wrap: wrap;
}
.item {
    background-color: salmon;
    margin: 10px;
    height: 300px;
    width: 300px;


}
</style>