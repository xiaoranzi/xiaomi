<template>
    <div class="hole">
        <div class="content">
            <div class="top">
                <div class="topa">
                    <div class="topText">
                        <a href="" class="spana"><span class="spanb">预约维修服务</span></a>
                    </div>
                </div>
                <div class="topa">
                    <div class="topText">
                        <a href="" class="spana"><span class="spanb">7天无理由退货</span></a>
                    </div>
                </div>
                <div class="topa">
                    <div class="topText">
                        <a href="" class="spana"><span class="spanb">15天免费换货</span></a>
                    </div>
                </div>
                <div class="topa">
                    <div class="topText">
                        <a href="" class="spana"><span class="spanb">满150元包邮</span></a>
                    </div>
                </div>
                <div class="topa">
                    <div class="topText">
                        <a href="" class="spanc"><span class="spanb">520余家售后网点</span></a>
                    </div>
                </div>
            </div>
            <div class="foot">
                <div class="footLeft">
                    <div class="foota">
                        <div class="footHelp">帮助中心</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>账户管理</p></a>
                           <a href="" class="itemaDer"><p>购物指南</p></a>
                           <a href="" class="itemaDer"><p>订单操作</p></a>
                        </div>
                    </div>
                    <div class="foota">
                        <div class="footHelp">服务支持</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>售后政策</p></a>
                           <a href="" class="itemaDer"><p>自助服务</p></a>
                           <a href="" class="itemaDer"><p>相关下载</p></a>
                        </div>
                    </div>
                    <div class="foota">
                        <div class="footHelp">线下门店</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>小米之家</p></a>
                           <a href="" class="itemaDer"><p>服务网点</p></a>
                           <a href="" class="itemaDer"><p>授权体验店</p></a>
                        </div>
                    </div>
                    <div class="foota">
                        <div class="footHelp">关于小米</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>了解小米</p></a>
                           <a href="" class="itemaDer"><p>加入小米</p></a>
                           <a href="" class="itemaDer"><p>投资者关系</p></a>
                        </div>
                    </div>
                    <div class="foota">
                        <div class="footHelp">关注我们</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>新浪微博</p></a>
                           <a href="" class="itemaDer"><p>官方微信</p></a>
                           <a href="" class="itemaDer"><p>联系我们</p></a>
                        </div>
                    </div>
                    <div class="footb">
                        <div class="footHelp">特色服务</div>
                        <div class="itema">
                           <a href="" class="itemaDer"><p>F 码通道</p></a>
                           <a href="" class="itemaDer"><p>礼物码</p></a>
                           <a href="" class="itemaDer"><p>防伪查询</p></a>
                        </div>
                    </div>
                </div>
                <div class="footRight">
                    <div class="fotR">
                        <p class="tel"><b>400-100-5678</b></p>
                        <p class="week">周一至周日 8:00-18:00</p>
                        <p class="week">（仅收市话费）</p>
                        <button class="btn">联系客服</button>
                    </div>
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
    min-width: 1226px;
    height: 272px;
    background-color: #ffffff;
    .content {
        width: 1226px;
        margin: 0 auto;
        .top {
            display: flex;
            .topa {
                flex: 1;
                height: 80px;
                line-height: 80px;
                border-bottom: 1px solid #e0e0e0;
                text-align: center;
                .topText {
                    width: 243.73px;
                    margin: 0 auto;
                    .spana {
                        border-right: 1px solid #E0E0E0;
                        text-decoration: none;
                        color: #616161;
                        .spanb {
                            display: inline-block;
                            width: 243.72px;
                            height: 21px;
                            margin: 0 auto;
                        }
                    }
                    .spanc {
                        text-decoration: none;
                        color: #616161;
                        .spanb {
                            display: inline-block;
                            width: 243.72px;
                            height: 21px;
                            margin: 0 auto;
                        }
                    }
                }
                
            }
        }
        .foot {
            padding: 40px 0;
            height: 192px;
            .footLeft {
                float: left;
                display: flex;
                width: 979px;
                .foota {
                    flex: 1;
                    height: 112px;
                    .footHelp {
                        display: block;
                        margin-bottom: 17px;
                    }
                    .itema {
                        font-size: 12px;
                        .itemaDer {
                            display: block;
                            text-decoration: none;
                            margin-top: 10px;
                            color: #757575;
                        }
                    }
                }
                .footb {
                    border-right: 1px solid #e0e0e0;
                    flex: 1;
                    height: 112px;
                    .footHelp {
                        display: block;
                        margin-bottom: 17px;
                    }
                    .itema {
                        font-size: 12px;
                        .itemaDer {
                            display: block;
                            text-decoration: none;
                            margin-top: 10px;
                            color: #757575;
                        }
                    }
                }
            }
            .footRight {
                .fotR {
                    text-align: center;
                    .tel {
                        display: block;
                        // font-weight: bolder;
                        color:#FF6700;
                        font-size: 19px;

                    }
                    .week {
                        color: #616161;
                        font-size: 12px;
                    }
                    .btn {
                        margin-left: 66px;
                        margin-top: 16px;
                        float: left;
                        width: 120px;
                        height: 30px;
                        background-color: rgb(250, 250, 250);
                        border: 1px solid #FF6700;
                        color: #FF6700;
                    }
                    .btn:hover {
                        margin-left: 66px;
                        margin-top: 16px;
                        float: left;
                        width: 120px;
                        height: 30px;
                        background-color: #FF6700;
                        border: 1px solid #FF6700;
                        color: white;
                    }
                }

            }
        }
    }
}
</style>
