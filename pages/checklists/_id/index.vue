<template>
    <div>
       test {{ id }}
    </div>
</template>

<script>
export default {
    validate({ params }) {
        return /^\d+$/.test(params.id);
    },
    data: function () {
        return {
            id: this.$route.params.id
        };
    }
};
</script>
