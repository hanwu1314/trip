<script setup>

</script>
<template>
    <div class="favor">
        <h2>favor</h2>
        <template v-for="(item) in 100">
            <div>
                列表数据:{{ item }}
            </div>
        </template>
    </div>
</template>
<style lang='less' scoped>
.favor {
    height: 50vh;
    overflow-y: auto;
    background-color: orange;
}
</style>