<template>
    <div class="hole">
        <div class="content">
            <div class="logo">
                <img class="imglogo" src="../assets/xiaomi.png">
            </div>
            <div class="nav">
                <!-- <el-menu mode="horizontal">
                    <el-submenu index="1">
                        <template slot="title">我的工作台</template>
                        <el-menu-item index="1-1">选项一</el-menu-item>
                        <el-menu-item index="1-2">选项一</el-menu-item>
                        <el-menu-item index="1-3">选项一</el-menu-item>
                    </el-submenu>
                </el-menu> -->
                <div class="goodsItem">
                    <a href="" class="spana">全部商品分类</a>
                </div>
                <div class="liItem">
                    <a href="" class="spana">小米手机</a>
                    <a href="" class="spana">Redmi红米</a>
                    <a href="" class="spana">电视</a>
                    <a href="" class="spana">笔记本</a>
                    <a href="" class="spana">家电</a>
                    <a href="" class="spana">路由器</a>
                    <a href="" class="spana">智能硬件</a>
                    <a href="" class="spana">服务</a>
                    <a href="" class="spana">社区</a>
                </div>
                
                <!-- <el-tabs v-model="activeName" type="card" @tab-click = 'handleClick'>
                    <el-tab-pane label="小米手机" name="first">小米手机</el-tab-pane>
                    <el-tab-pane label="Redmi红米" name="second">小米手机</el-tab-pane>
                    <el-tab-pane label="电视" name="three">小米手机</el-tab-pane>
                    <el-tab-pane label="笔记本" name="four">小米手机</el-tab-pane>
                    <el-tab-pane label="家电" name="five">小米手机</el-tab-pane>
                    <el-tab-pane label="路由器" name="six">小米手机</el-tab-pane>
                    <el-tab-pane label="智能硬件" name="seven">小米手机</el-tab-pane>
                </el-tabs> -->
            </div>
            <div class="search">
                <div class="divInp">   
                    <el-input class="inputSearch" style="width:200px"></el-input>
                </div>
                <div class="divSear">
                    <el-button class="el-icon-search"></el-button>
                </div>
                
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            activeName: 'first'
        }
    },
    methods: {
        handleClick(){

        }
    }
}
</script>
<style lang="less" scoped>
.hole {
    width: 100%;
    min-width: 1226px;
    height: 100px;
    .content {
        width: 1226px;
        margin: 0 auto;
        height: 100px;
        .logo {
            float: left;
            line-height: 100px;
            .imglogo {
                margin-top: 20px;
                width: 55px;
                height: 55px;
            }
        }
        .nav {
            float: left;
            // height: 300px;
            // background-color: rgb(182, 189, 186);
            .goodsItem {
                cursor: pointer;
                float: left;
                height: 50px;
                line-height: 100px;
                text-align: center;
                margin-left: 30px;
                margin-right: 10px;
                padding-left: 40px;
                .spana {
                    text-decoration: none;
                    color: black;
                }
            }
            .liItem {
                cursor: pointer;
                height: 50px;
                width: 780px;
                line-height: 100px;
                .spana {
                    margin: 0 10px;
                    text-decoration: none;
                    color: black;
                }
            }
            
        }
        .search {
            width: 252px;
            float: right;
            // height: 100px;
            line-height: 100px;
            .divInp {
                float: left;
            }
            .divSear {
                float: left;
            }
            .divSear:hover {
                // color: rgb(255, 123, 0);
                float: left;
            }
            /* .inputSearch {
                float: left;
            } */
            /* .el-icon-search {
                 float: left;
            } */
        }
        
    }
    /deep/.el-input__inner {
        height: 50px;
        border-radius: 0;
        border-right: hidden;
    }
    /deep/.el-button {
        height: 50px;
        width: 52px;
        border-radius: 0;
    }
    /deep/.el-button:hover {
        height: 50px;
        width: 52px;
        border-radius: 0;
        color: white;
        background-color: rgb(247, 144, 9);
    }
}
</style>
