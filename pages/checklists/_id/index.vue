<template>
    <div>
        test {{ title }}
    </div>
</template>

<script>
import axios from 'axios';
export default {
    layout: 'nav',
    validate({ params }) {
        return /^\d+$/.test(params.id);
    },
    async asyncData({ params }) {
        let { data } = await axios.get(`http://localhost:3004/posts/${params.id}`);
        return { title: data.title };
    }

};
</script>
