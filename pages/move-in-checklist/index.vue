<template>
    <div>
        <div id="intro-text" class="has-text-centered">
            <h1 class="title">Create a sharable move in checklist.</h1>
            <h1 class="title">Get started by entering a name for your checklist.</h1>
        </div>
        <!-- <primary-inputs :inputs="inputs" @inputsValidnessChanged="inputsValidnessChanged"></primary-inputs>
            <slide-fade>
                <el-row type="flex" justify="center" v-if="mainInputsCompleted">
                    <button id="nextStepButton" @click='proceedToNextStep' class="button is-primary is-large is-outlined">Next Step</button>
                </el-row>
            </slide-fade> -->
        <div id="example-text" class="has-text-centered">
            <h1 class="title"> Or
                <a href="https://roomiesplit.com/calculator/-KpuPGVGGs9DbehcO4xV"> checkout an example.</a>
            </h1>
        </div>
    
    </div>
</template>

<script>
export default {
    layout: 'CheckList'
};
</script>

<style lang="scss">
.title {
    font-family: 'Lato';
    font-weight: 300;
    font-size: 2rem;
}
</style>
