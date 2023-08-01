<template>
    <div>Page for job {{ currentJobId }}</div>
</template>

<script>
export default {
    name: "JobView",
    computed: {
        currentJobId() {
            return this.$forceUpdate.id;
        },
    },
};
</script>