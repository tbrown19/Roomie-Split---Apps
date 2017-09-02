<template>
    <div>
        <nav-bar>
            <h1 slot="page-title"> Move in Checklist</h1>
        </nav-bar>
        <el-row type="flex" justify="center" :gutter="20">
            <el-col :span="22" :lg="{span:18}" id="main-content">
                <nuxt/>
            </el-col>
        </el-row>
    </div>
</template>

<script>
import NavBar from '../components/layouts/NavBar';
export default {
    components: {
        NavBar
    },
    data() {
        return {
            activeIndex: this.$router.currentRoute.path
        };
    }
};

</script>

<style lang="scss" scoped>

#main-content{
    padding-top: 1%;
}
</style>
