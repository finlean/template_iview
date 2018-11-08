<template>
    <div class="test">
        我是iView UI
        <Icon type="ios-american-football" />
        <Button type="success">iView UI</Button>
    </div>
</template>

<script>
    export default {
        name: 'test',
        data() {
            return {};
        },
        created() {
            this.$api.logout({
                password: 'qwer1234',
                userNo: '13402318457'
            });
        },
        methods: {}
    };
</script>

<style lang='less' scoped>
    .test {
        color: red;
    }
</style>
