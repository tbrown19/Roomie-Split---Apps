<template>
    <nav class="navbar">
        <div class="navbar-brand">
            <router-link class="navbar-item" id="site-header" to="/">Roomie Split</router-link>
    
            <div class="navbar-burger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
        <div class="navbar-menu">
            <!-- navbar start, navbar end -->
            <div class="navbar-start">
                <span class="navbar-item" id="page-title-header">
                    <slot name="page-title"></slot>
                </span>
            </div>
            <div class="navbar-end">
                <!-- navbar items -->
                <router-link class="navbar-item" to="">Sign In</router-link>
                <router-link class="navbar-item" to="">Sign Up</router-link>
            </div>
        </div>
    </nav>
</template>

<style lang="scss">
.navbar {
    background-color: #324157;
}

.navbar-item {
    color: #f5f5f5;
    font-family: 'Roboto', sans-serif;
    font-size: 1.25rem;
}

#site-header {
    font-family: 'Righteous', cursive;
    font-size: 2rem;
    &:hover {
        background-color: transparent;
        color: #f5f5f5;
    }
}

#page-title-header {
    margin-left: 1rem;
    font-size: 1.75rem;
    font-family: 'Lato', cursive;
}
</style>
