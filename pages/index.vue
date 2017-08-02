<template>
    <div>
    
        <section class="hero is-bold is-small">
            <div class="hero-header">
                <nav class="navbar">
                    <div class="navbar-brand">
                        <a class="navbar-item" href="http://bulma.io" id="site-header">
                            RoomieSplit
                        </a>
    
                        <div class="navbar-burger">
                            <span></span>
                            <span></span>
                            <span></span>
                        </div>
                    </div>
                </nav>
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
    
                    <nav class="level">
                        <p class="level-item has-text-centered">
                            <a class="link is-info">About</a>
                        </p>
                        <p class="level-item has-text-centered">
                            <a class="link is-info">Tools</a>
                        </p>
                        <p class="level-item has-text-centered">
                            <a class="link is-info">Contact</a>
                        </p>
                    </nav>

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
export default {
    data: function () {
        return {
            test: 'derp'
        };
    }
};
</script>

<style lang="scss">
.navbar {
    background-color: #324157;
}

#site-header {
    color: #f5f5f5;
    margin: 0;
    padding: 0 20px;
    box-sizing: border-box;
    border-bottom: 5px solid transparent;
    font-family: 'Righteous', cursive;
    font-size: 2rem;
}

.title {
    font-family: 'Lato';
    font-weight: 300;
    font-size: 4rem;
}

.subtitle {
    font-size: 2.5rem;
    font-weight: 300;
}

.level-item{
    font-size: 1.4rem;
}
</style>
