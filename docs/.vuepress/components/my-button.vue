<template>
    <button @click="handleClick">我是一个按钮</button>
</template>

<script>
export default {
    methods: {
        handleClick() {
            console.log('点击成功！');
        }
    }
}
</script>