<template>
    <div class="hole">
        <div class="content">
            <div class="left"> 
                <a href="" class="spana">小米商城</a><span class="spanb">|</span>
                <a href="" class="spana">MIUI</a><span class="spanb">|</span>
                <a href="" class="spana">loT</a><span class="spanb">|</span>
                <a href="" class="spana">云服务</a><span class="spanb">|</span>
                <a href="" class="spana">金融</a><span class="spanb">|</span>
                <a href="" class="spana">有品</a><span class="spanb">|</span>
                <a href="" class="spana">小爱开放平台</a><span class="spanb">|</span>
                <a href="" class="spana">企业团购</a><span class="spanb">|</span>
                <a href="" class="spana">资质证明</a><span class="spanb">|</span>
                <a href="" class="spana">协议规则</a><span class="spanb">|</span>
                <a href="" class="spana">下载app</a><span class="spanb">|</span>
                <a href="" class="spana">SelectRegion</a>
            </div>
            <div class="right">
                <div class="login">
                    <a href="" class="spana">登录</a><span class="spanb">|</span>
                    <a href="" class="spana">注册</a><span class="spanb">|</span>
                    <a href="" class="spanarig">消息通知</a>
                </div>
                <div class="car">
                    <a href="" class="spana">购物车 (0)</a>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {

        }
    }
}
</script>
<style lang="less" scoped>
.hole {
    width: 100%;
    min-width: 1226
    px;
    height: 40px;
    background-color: rgb(121, 117, 117);
    .content {
        width: 1226px;
        //width: 65%;
        // border: 1px solid red;
        height: 40px;
        margin: 0 auto;
        .left {
            // display: block;
            text-align: center;
            height: 40px;
            line-height: 40px;
            float: left;
            .spana {
                margin-right: 6px;
                text-decoration: none;
                color: aliceblue;
                font-size: 12px;
            }
            .spanb {
                font-size: 12px;
                margin-right: 5px;
                color: whitesmoke;
            }
        }
        .right {
            float: right;
            .login {
                float: left;
                .spana {
                    height: 40px;
                    line-height: 40px;
                    text-decoration: none;
                    color: white;
                    font-size: 12px;
                    margin-right: 6px;
                }
                .spanb {
                    font-size: 12px;
                    color: white;
                    margin-right: 5px;
                }
                .spanarig {
                   height: 40px;
                    line-height: 40px;
                    text-decoration: none;
                    color: white;
                    font-size: 12px;
                    margin-right: 27px; 
                }
            }
            .car {
                cursor: pointer;
                display: block;
                float: left;
                background-color: rgb(167, 151, 131);
                width:100px;
                height: 40px;
                text-align: center;
                .spana {
                    line-height: 40px;
                    text-decoration: none;
                    font-size: 12px;
                    color: aliceblue;
                }
            }
        }
    }
}
</style>
