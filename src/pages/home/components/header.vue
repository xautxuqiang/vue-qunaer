<template>
    <div class="header">
        <div class="header-left">
            <div class="back-icon"><i class="iconfont icon-fanhui"></i></div>
        </div>
        <div class="header-input">
            <span><i class="iconfont icon-sousuo"></i></span>
            输入城市游玩主题
        </div>
        <div class="header-right">
            城市
            <span><i class="iconfont icon-jiantou"></i></span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
    @import '~@/assets/styles/varibles.styl'
    .header
        line-height: 43px
        display: flex
        background: $bgColor
        color: #fff
        .header-left
            width: 32px
            float: left
            .back-icon
                text-align: center
                font-size: 20px
        .header-input
            flex: 1
            background: #fff
            border-raidus: 5px
            height: 32px
            margin-top: 5px
            margin-left: 5px
            color: #ccc
            line-height: 32px
            padding-left: 10px
        .header-right
            width: 62px
            float: right
            text-align: center
            .icon-jiantou

                font-size: 10px
</style>