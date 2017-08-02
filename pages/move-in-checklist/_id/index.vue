<template>
    <div>
        Rendering post {{ title }} test
    </div>
</template>

<script>
import axios from 'axios';
export default {
    layout: 'CheckList',
    validate({ params }) {
        return /^\d+$/.test(params.id);
    },
    async asyncData({ params }) {
        let { data } = await axios.get(`http://localhost:3004/posts/${params.id}`);
        return { title: data.title };
    }

};
</script>

<style lang="scss">
    
</style>
