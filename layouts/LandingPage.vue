<template>
    <div>
    
        <section class="hero is-bold is-small">
            <div class="hero-header">
                <home-nav-bar>
                    <h1 slot="page-title"> Home </h1>
                </home-nav-bar>
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
    
                    <hr class="no-top-margin">
    
                </div>
            </div>
        </section>
    
        <nuxt/>
    </div>
</template>

<script>
import HomeNavBar from '../components/layouts/HomeNavBar';
import HomeNavCenter from '../components/layouts/HomeNavCenter';

export default {
    components: {
        HomeNavBar, HomeNavCenter
    }
};
</script>

<style>
.title {
    font-family: 'Lato';
    font-weight: 300;
    font-size: 4rem;
}

.subtitle {
    font-size: 2.5rem;
    font-weight: 300;
}
.hero-body{
     padding-bottom: .5rem; 
     padding-top: 2rem;
}

.no-top-margin{
    margin-top: 0;
}
</style>
