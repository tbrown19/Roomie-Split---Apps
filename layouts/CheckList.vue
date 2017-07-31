<template>
    <div id="app">
        <check-list-nav></check-list-nav>
        <el-row type="flex" justify="center" :gutter="20">
            <el-col :span="22" :lg="{span:18}" id="main-content">
                <nuxt/>
            </el-col>
        </el-row>
    </div>
</template>

<script>
import CheckListNav from '~/components/Layouts/CheckListNavBar.vue';
export default {
    components: {
        CheckListNav
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
