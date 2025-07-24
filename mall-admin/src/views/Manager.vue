<template>
    <div>
        <el-container>
            <!-- 侧边栏 -->
            <el-aside  class="aside">
                <el-menu router class="menu" text-color="red" :default-active="$route.path">
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
