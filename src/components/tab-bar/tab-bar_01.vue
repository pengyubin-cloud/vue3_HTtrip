<template>
    <div class="tab-bar">
        <div class="tab-bar-item">
            <img src="@/assets/img/tabbar/tab_home.png" alt="">
            <span class="text">首页</span>
        </div>
        <div class="tab-bar-item">
            <img src="@/assets/img/tabbar/tab_home.png" alt="">
            <span class="text">藏页</span>   
        </div>
        <div class="tab-bar-item">
            <img src="@/assets/img/tabbar/tab_home.png" alt="">
            <span class="text">订单</span>
        </div>
        <div class="tab-bar-item">
            <img src="@/assets/img/tabbar/tab_home.png" alt="">
            <span class="text">消息</span>
        </div>
    </div>
</template>

<script setup>
    
</script>

<style lang="less" scoped>
.tab-bar {
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    height: 50px;
    display: flex;

    .tab-bar-item {
        flex: 1;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        
        img {
            width: 36px;
        }
    }

}


</style>
