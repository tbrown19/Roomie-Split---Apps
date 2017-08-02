<template>
    <div id="app">
        <home-nav-bar>
            <h1 slot="page-title"> Move in Checklist</h1>
        </home-nav-bar>
        <el-row type="flex" justify="center" :gutter="20">
            <el-col :span="22" :lg="{span:18}" id="main-content">
                <nuxt/>
            </el-col>
        </el-row>
    </div>
</template>

<script>
import HomeNavBar from '../components/layouts/HomeNavBar';
export default {
    components: {
        HomeNavBar
    },
    data() {
        return {
            activeIndex: this.$router.currentRoute.path
        };
    }
};

</script>

<style lang="scss">
body {
    margin: 0 !important;
}
</style>
