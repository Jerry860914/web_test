<template>
    
    <div class="page">
        <nav_bar/>
        <div class="item" v-for ="(items, itemid) in arr" :key ="itemid">
            <div class="item_img"><img :src="items.url" alt=""> <div class="time">{{items.time}}</div></div>
            <div class="title">
                <div class="item_icon">  </div>
                <p>{{items.title}}</p>
            </div>
            
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
            arr:[{time:"5:02:11" ,title:"[中文] MSI 季中邀請賽 小組賽 Day 4 | MSI 2021", url:require('../static/test_data/0.png')},
                 {time:"5:02:11" ,title:"RNG vs UOL UOL下路二換四大肆慶祝  2021 MSI季中邀請賽精華 Highlights", url:require('../static/test_data/9.png')},
                 {time:"5:02:11" ,title:"20210426 1500 陳嘉偉 股市總司令", url:require('../static/test_data/2.jpg')},
                 {time:"5:02:11" ,title:"KOF XIV 頂上對決 ET vs 廣州小孩 FT10(下) 千算萬算不如...那一腳來的快!!", url:require('../static/test_data/3.jpg')},
                 {time:"5:02:11" ,title:"KOF XIV 頂上對決 ET vs 廣州小孩 FT10(下) 千算萬算不如...那一腳來的快!!", url:require('../static/test_data/4.jpg')},
                 {time:"5:02:11" ,title:"【モンハンライズ】アプデに挑むお姉さんたち", url:require('../static/test_data/5.jpg')},
                 {time:"5:02:11" ,title:"[中文] MSI 季中邀請賽 小組賽 Day 4 | MSI 2021", url:require('../static/test_data/10.jpg')},
                 {time:"5:02:11" ,title:"good mood lofi. 1 HOUR // ⟦ upbeat lofi ⟧ // hip hop radio [study relax vibe]", url:require('../static/test_data/11.jpg')},
                 {time:"5:02:11" ,title:"Friends Forever | Upbeat Lofi Hip Hop Mix", url:require('../static/test_data/6.jpg')},
                 {time:"5:02:11" ,title:"《一日系列第一百五十六集》這次邰哥與達達開啟一段與馬的友誼關係～哈！紫微我來了！", url:require('../static/test_data/7.jpg')},
                 {time:"5:02:11" ,title:"RNG vs UOL UOL下路二換四大肆慶祝  2021 MSI季中邀請賽精華 Highlights", url:require('../static/test_data/8.jpg')},
                 {time:"5:02:11" ,title:"日曜モーニング: Morning Coffee Jazz - Relaxing Jazz Piano Music", url:require('../static/test_data/9.jpg')},
                 {time:"5:02:11" ,title:"C9 vs INF Ackerman猶豫的銳兒阿卡曼之恥 Perkz歐洲法王炮娘凱瑞！", url:require('../static/test_data/7.jpg')},
                 {time:"5:02:11" ,title:"おやすみジブリ・夏夜のピアノメドレー【睡眠用BGM、動画中広告なし】", url:require('../static/test_data/0.png')},
                 {time:"5:02:11" ,title:"【モンハンライズ】アプデに挑むお姉さんたち", url:require('../static/test_data/2.jpg')},
                 {time:"5:02:11" ,title:"おやすみジブリ・夏夜のピアノメドレー【睡眠用BGM、動画中広告なし】", url:require('../static/test_data/7.jpg')},
                 {time:"5:02:11" ,title:"《一日系列第一百五十六集》這次邰哥與達達開啟一段與馬的友誼關係～哈！紫微我來了！", url:require('../static/test_data/10.jpg')},
                 {time:"5:02:11" ,title:"RNG vs UOL UOL下路二換四大肆慶祝  2021 MSI季中邀請賽精華 Highlights", url:require('../static/test_data/5.jpg')},
                 {time:"5:02:11" ,title:"日曜モーニング: Morning Coffee Jazz - Relaxing Jazz Piano Music", url:require('../static/test_data/3.jpg')},
                 {time:"5:02:11" ,title:"KOF XIV 頂上對決 ET vs 廣州小孩 FT10(下) 千算萬算不如...那一腳來的快!!", url:require('../static/test_data/12.jpg')},
                 
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
    
    background-color: rgb(255, 255, 255);
    margin: 10px;
    height: 300px;
    width: 400px;
    .item_img{
        position: relative;
        height: 80%;
        width: 100%;
        img{
            
            height: 100%;
            width: 100%;
        }
        .time{
            
            position: absolute;
            color: white;
            bottom: 0;
            right: 0;
        }
    }
    .title{
        height: 20%;
        text-align: center;
        display: flex;
        align-items: center;
        .item_icon {
            width: 20%;
            height: 100%;
            border-radius: 50%;
            background-color: yellow;
        }
        p {
            
            width: 80%;
        }
    }

}
</style>