<template>
    <div v-show="visible">
        loading效果组件{{loadText}}
    </div>
</template>

<script>
export default {
    components: {},
    props: {},
    data() {
        return {
            loadText: '默认文案',
            visible: false
        }
    },
    created() {},
    mounted() {},
    computed: {},
    watch: {
    },
    methods:{}
}
</script>

<style scoped>
</style>