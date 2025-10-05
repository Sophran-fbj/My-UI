<template>
  <h1 class="row-title">普通引入</h1>
  <div class="row">
    <My-Icon icon="user-secret" />
    <My-Icon icon="bars" />
    <My-Icon icon="shield-halved" />
    <My-Icon icon="file" />
    <My-Icon icon="filter" />
    <My-Icon icon="gear" />
    <My-Icon icon="barcode" />
    <My-Icon icon="folder" />
    <My-Icon icon="folder-open" />
  </div>
  <h1 class="row-title">设置不同的大小</h1>
  <div class="row">
    <My-Icon icon="user-secret" size="2xs" />
    <My-Icon icon="bars" size="xs" />
    <My-Icon icon="shield-halved" size="sm" />
    <My-Icon icon="file" size="lg" />
    <My-Icon icon="filter" size="xl" />
    <My-Icon icon="gear" size="2xl" />
    <My-Icon icon="barcode" size="2x" />
    <My-Icon icon="folder" size="3x" />
    <My-Icon icon="folder-open" size="4x" />
  </div>
  <h1 class="row-title">旋转与翻转</h1>
  <div class="row">
    <My-Icon icon="user-secret" rotation="90" size="xl" />
    <My-Icon icon="bars" rotation="270" size="xl" />
    <My-Icon icon="shield-halved" rotation="180" size="xl" />
    <My-Icon icon="file" flip="horizontal" size="xl" />
    <My-Icon icon="filter" flip="vertical" size="xl" />
    <My-Icon icon="folder-open" flip="both" size="xl" />
  </div>
  <h1 class="row-title">动画效果</h1>
  <div class="row">
    <My-Icon icon="user-secret" size="xl" beat />
    <My-Icon icon="bars" size="xl" beat-fade />
    <My-Icon icon="shield-halved" size="xl" bounce />
    <My-Icon icon="file" size="xl" fade />
    <My-Icon icon="filter" size="xl" flip />
    <My-Icon icon="gear" size="xl" shake />
    <My-Icon icon="barcode" size="xl" spin />
    <My-Icon icon="folder" size="xl" spin spin-reverse />
    <My-Icon icon="folder-open" size="xl" spin-pulse />
  </div>
  <h1 class="row-title">添加自定义属性</h1>
  <div class="row">
    <My-Icon icon="user-secret" size="xl" type="primary" />
    <My-Icon icon="bars" size="xl" type="success" />
    <My-Icon icon="shield-halved" size="xl" type="info" />
    <My-Icon icon="file" size="xl" type="warning" />
    <My-Icon icon="filter" size="xl" type="danger" />
    <My-Icon icon="gear" size="xl" color="#e47412" />
    <My-Icon icon="barcode" size="xl" color="#7ec102" />
    <My-Icon icon="folder" size="xl" color="skyblue" />
    <My-Icon icon="folder-open" size="xl" color="rgba(122, 122, 122, .5)" />
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>

