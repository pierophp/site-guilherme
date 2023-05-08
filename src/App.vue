<template>
  <div class="menu">
    <div class="item">Início</div>
    <div class="item">Ensinos Bíblicos</div>
    <div class="item">Biblioteca</div>
    <div class="item">Notícias</div>
    <div class="item">Quem Somos</div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
body {
  margin: 0;
}
.menu {
  display: flex;
  gap: 10px;
  background: #292929;
  color: #fff;
  cursor: pointer;
}

.item {
  padding: 10px 5px;
}

.item:hover {
  background: blue;
}
</style>
