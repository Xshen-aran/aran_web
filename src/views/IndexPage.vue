<template>
    <a-layout>
        <a-layout-sider>Sider</a-layout-sider>
        <a-layout>
            <a-layout-header>Header</a-layout-header>
            <a-layout-content>Content</a-layout-content>
            <a-layout-footer>Footer</a-layout-footer>
        </a-layout>
    </a-layout>
</template>

<script setup lang="ts">

import { ref } from 'vue';
const collapsed = ref<boolean>(false);
const selectedKeys = ref<string[]>(['1']);
</script>

<style scoped>
#components-layout-demo-basic .ant-layout-sider {
    color: #fff;
    line-height: 120px;
    background: #3ba0e9;
}

[data-theme='dark'] #components-layout-demo-basic .ant-layout-sider {
    background: #3499ec;
}

#components-layout-demo-basic .code-box-demo {
    text-align: center;
}

#components-layout-demo-basic .ant-layout-header,
#components-layout-demo-basic .ant-layout-footer {
    color: #fff;
    background: #7dbcea;
}
</style>