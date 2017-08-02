<template>
    <div>
    
        <section class="hero is-bold is-small">
            <div class="hero-header">
                <home-nav-bar></home-nav-bar>
            </div>
            <!-- Hero content: will be in the middle -->
            <div class="hero-body">
                <div class="container has-text-centered">
                    <h1 class="title">
                        Welcome To Roomie Split
                    </h1>
                    <h2 class="subtitle">
                        Apps to simplify living with others.
                    </h2>
    
                    <hr>
    
                    <home-nav-center></home-nav-center>
    
                    <hr>
    
                </div>
            </div>
        </section>
    
        <el-row :gutter="20">
            <el-col :sm="{span: 8, offset: 4}" :xs="24">
                <div class="card">
                    <header class="card-header">
                        <p class="card-header-title">
                            Component
                        </p>
                        <a class="card-header-icon">
                            <span class="icon">
                                <i class="fa fa-angle-down"></i>
                            </span>
                        </a>
                    </header>
                    <div class="card-content">
                        <div class="content">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                            <a>@bulmaio</a>.
                            <a>#css</a>
                            <a>#responsive</a>
                            <br>
                            <small>11:09 PM - 1 Jan 2016</small>
                        </div>
                    </div>
                    <footer class="card-footer">
                        <a class="card-footer-item">Save</a>
                        <a class="card-footer-item">Edit</a>
                        <a class="card-footer-item">Delete</a>
                    </footer>
                </div>
            </el-col>
            <el-col :span="8" :xs="24">
                <div class="card">
                    <header class="card-header">
                        <p class="card-header-title">
                            Component
                        </p>
                        <a class="card-header-icon">
                            <span class="icon">
                                <i class="fa fa-angle-down"></i>
                            </span>
                        </a>
                    </header>
                    <div class="card-content">
                        <div class="content">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                            <a>@bulmaio</a>.
                            <a>#css</a>
                            <a>#responsive</a>
                            <br>
                            <small>11:09 PM - 1 Jan 2016</small>
                        </div>
                    </div>
                    <footer class="card-footer">
                        <a class="card-footer-item">Save</a>
                        <a class="card-footer-item">Edit</a>
                        <a class="card-footer-item">Delete</a>
                    </footer>
                </div>
            </el-col>
        </el-row>
    </div>
</template>

<script>
import HomeNavBar from '../components/layouts/HomeNavBar';
import HomeNavCenter from '../components/layouts/HomeNavCenter';

export default {
    components: {
        HomeNavBar, HomeNavCenter
    },
    data: function () {
        return {
            test: 'derp'
        };
    }
};
</script>

<style lang="scss">
.title {
    font-family: 'Lato';
    font-weight: 300;
    font-size: 4rem;
}

.subtitle {
    font-size: 2.5rem;
    font-weight: 300;
}

.level-item {
    font-size: 1.4rem;
}
</style>
