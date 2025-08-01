<template>
    <div>
        <el-container>
            <!-- 侧边栏 -->
            <el-aside class="aside">
                <el-menu router class="menu" text-color="#bfcbd9" background-color="#304156"
                    :default-active="$route.path">
                    <el-submenu index="/">
                        <template slot="title">
                            <i class="el-icon-s-home"></i>
                            <span slot="title">首页</span>
                        </template>
                        <el-menu-item index="/">
                            <template slot="title">
                                <i class="el-icon-odometer"></i>
                                <span slot="title">仪表盘</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item index="2">
                            <template slot="title">
                                <i class="el-icon-odometer"></i>
                                <span slot="title">学习教程</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item index="3">
                            <i class="el-icon-video-play"></i>
                            <span>学习视频</span>
                        </el-menu-item>
                    </el-submenu>

                    <el-submenu index="2">
                        <template slot="title">
                            <i class="el-icon-goods"></i>
                            <span>商品</span>
                        </template>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-shangpinliebiao-liebiaox"></i>
                                <span>商品列表</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-plus-square"></i>
                                <span>添加商品</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-caidan"></i>
                                <span>商品分类</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-hanbaocaidan"></i>
                                <template>商品类型</template>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-pinpaiguanli"></i>
                                <span>品牌管理</span>
                            </template>
                        </el-menu-item>
                    </el-submenu>

                    <el-submenu index="3">
                        <template slot="title">
                            <i class="el-icon-notebook-2"></i>
                            <span>订单</span>
                        </template>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-shangpinliebiao-liebiaox"></i>
                                <span>订单列表</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon-setting"></i>
                                <span>订单设置</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-tuihuo"></i>
                                <span>退货申请处理</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-guanggao"></i>
                                <span>退货原因设置</span>
                            </template>
                        </el-menu-item>
                    </el-submenu>

                    <el-submenu index="4">
                        <template slot="title">
                            <i class="el-icon el-icon-yingxiao"></i>
                            <span>订单</span>
                        </template>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-shangpinliebiao-liebiaox"></i>
                                <span>订单列表</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon-setting"></i>
                                <span>订单设置</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-tuihuo"></i>
                                <span>退货申请处理</span>
                            </template>
                        </el-menu-item>
                        <el-menu-item>
                            <template slot="title">
                                <i class="el-icon el-icon-guanggao"></i>
                                <span>退货原因设置</span>
                            </template>
                        </el-menu-item>
                    </el-submenu>

                </el-menu>
            </el-aside>
            <!-- 头部+主体内容 -->
            <el-container>
                <!-- 头部内容 -->
                <el-header>头部部分</el-header>
                <!-- 主体内容 -->
                <el-main>主体部分</el-main>
            </el-container>
        </el-container>
    </div>
</template>
