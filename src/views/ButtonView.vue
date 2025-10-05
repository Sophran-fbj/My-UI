<template>
  <h1 class="row-title">普通按钮</h1>
  <div class="row">
    <My-Button>默认按钮</My-Button>
    <My-Button type="primary">主要按钮</My-Button>
    <My-Button type="success">成功按钮</My-Button>
    <My-Button type="warning">警告按钮</My-Button>
    <My-Button type="danger">危险按钮</My-Button>
    <My-Button type="info">信息按钮</My-Button>
  </div>
  <h1 class="row-title">朴素按钮</h1>
  <div class="row">
    <My-Button plain>默认按钮</My-Button>
    <My-Button type="primary" plain>主要按钮</My-Button>
    <My-Button type="success" plain>成功按钮</My-Button>
    <My-Button type="warning" plain>警告按钮</My-Button>
    <My-Button type="danger" plain>危险按钮</My-Button>
    <My-Button type="info" plain>信息按钮</My-Button>
  </div>
  <h1 class="row-title">圆角按钮</h1>
  <div class="row">
    <My-Button round>默认按钮</My-Button>
    <My-Button type="primary" round>主要按钮</My-Button>
    <My-Button type="success" round>成功按钮</My-Button>
    <My-Button type="warning" round>警告按钮</My-Button>
    <My-Button type="danger" round>危险按钮</My-Button>
    <My-Button type="info" round>信息按钮</My-Button>
  </div>
  <h1 class="row-title">禁用状态</h1>
  <div class="row">
    <My-Button disabled>默认按钮</My-Button>
    <My-Button type="primary" disabled>主要按钮</My-Button>
    <My-Button type="success" disabled>成功按钮</My-Button>
    <My-Button type="warning" disabled>警告按钮</My-Button>
    <My-Button type="danger" disabled>危险按钮</My-Button>
    <My-Button type="info" disabled>信息按钮</My-Button>
  </div>
  <h1 class="row-title">等待状态</h1>
  <div class="row">
    <My-Button loading>默认按钮</My-Button>
    <My-Button type="primary" loading>主要按钮</My-Button>
    <My-Button type="success" loading>成功按钮</My-Button>
    <My-Button type="warning" loading>警告按钮</My-Button>
    <My-Button type="danger" loading>危险按钮</My-Button>
    <My-Button type="info" loading>信息按钮</My-Button>
  </div>
  <h1 class="row-title">图标按钮</h1>
  <div class="row">
    <My-Button icon="file">默认按钮</My-Button>
    <My-Button type="primary" icon="gear">主要按钮</My-Button>
    <My-Button type="info" icon="folder" plain>信息按钮</My-Button>
    <My-Button type="success" icon="bug" plain>成功按钮</My-Button>
    <My-Button type="warning" icon="code" round>警告按钮</My-Button>
    <My-Button type="danger" icon="cube" round>危险按钮</My-Button>
  </div>
  <h1 class="row-title">不同尺寸的按钮</h1>
  <div class="row">
    <My-Button icon="file" size="small">默认按钮</My-Button>
    <My-Button type="primary" icon="gear" size="small">主要按钮</My-Button>
    <My-Button type="info" icon="folder" plain>信息按钮</My-Button>
    <My-Button type="success" icon="bug" plain>成功按钮</My-Button>
    <My-Button type="warning" icon="code" plain size="large">警告按钮</My-Button>
    <My-Button type="danger" icon="cube" plain size="large">危险按钮</My-Button>
  </div>
  <h1 class="row-title">圆形按钮</h1>
  <div class="row">
    <My-Button type="danger" circle>验</My-Button>
    <My-Button type="primary" icon="gear" circle></My-Button>
    <My-Button type="info" icon="folder" circle plain></My-Button>
    <My-Button type="success" icon="bug" circle plain></My-Button>
    <My-Button type="warning" icon="code" circle disabled></My-Button>
    <My-Button type="danger" icon="cube" circle disabled></My-Button>
  </div>
  <h1 class="row-title">按钮事件</h1>
  <div class="row">
    <My-Button type="primary" @click="clickHandler" ref="btnRef">主要按钮</My-Button>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const btnRef = ref(null)

function clickHandler() {
  window.alert('按钮被点击了')
  console.log(btnRef.value.ref)
  console.log(btnRef.value)
}

</script>

<style lang="scss" scoped></style>
