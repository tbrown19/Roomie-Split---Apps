<template>
    <div>
        <el-row :gutter="20">
            <el-col :sm="{span: 9, offset: 3}" :xs="24">
                <div class="card">
                    <div class="card-content">
                        <h1 class="tool-card-title has-text-centered">
                            Rent Calculator
                        </h1>
                        <div class="content has-text-centered">
                            When living with roommates it can be difficult to decide how much each person should contribute towards the rent.
                            <br> <br> 
                            This tools allow you to calculate the values based on a number of customizable factors and calculations.
                        </div>
                    </div>
                    <footer class="card-footer">
                        <router-link class="card-footer-item" to="/contact">View</router-link>
                    </footer>
                </div>
            </el-col>
             <el-col :span="9" :xs="24">
                    <div class="card">
                    <div class="card-content">
                        <h1 class="tool-card-title has-text-centered">
                            Move In Checklist
                        </h1>
                        <div class="content has-text-centered">
                            When moving into a new apartmemnt or house there are a number of items that have to be brought by different people.
                            <br> <br>
                            This tools allow you to create a move in check list to keep track of who is bringing what.
                        </div>
                    </div>
                    <footer class="card-footer">
                        <router-link class="card-footer-item" to="/move-in-checklist">View</router-link>
                    </footer>
                </div>
                </el-col> 
        </el-row>
    </div>
</template>

<script>
export default {
    layout: 'LandingPage'
};
</script>

<style lang="scss" scoped>
.tool-card-title {
    font-size: 2rem;
    font-family: 'Lato', sans-serif;
    font-weight: 300;
}

.card-content {
    padding-top: 12px;
}

.card-footer-item {
    font-size: 1.4rem;
}
</style>
