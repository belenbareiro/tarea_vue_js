<template>
  <div id="app">
    <el-menu class="menu"
    >
      <el-menu-item index="1">
        <router-link :to="{ path: '/' }" class="custom-menu-item">Home</router-link>
      </el-menu-item>
    </el-menu>

    <router-view />
  </div>
</template>

<script>


</script>

<style>
* {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}

.menu {
  display: flex;
  text-align: center;
  justify-content: center;

}


.menu a.router-link-exact-active {
  color: #42b983;
}
</style>
