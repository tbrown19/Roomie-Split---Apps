<template>
    <nav-bar>
        <li id="site-header">
            Roomie Split
        </li>
        <el-menu-item index="/">
            <a>Home</a>
        </el-menu-item>
    
        <el-menu-item index="/explanation">
            Rent Splitter
        </el-menu-item>
    
        <el-menu-item index="/about">
            Move In Checklist
        </el-menu-item>
    </nav-bar>
</template>

<script>
import NavBar from './NavBar.vue';
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

<style>

</style>
