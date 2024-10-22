<script setup></script>
<template>
  <div class="nav-bar">
    <div class="nav">
      <div class="logo">Paper Trade</div>
      <ul>
        <li>Home</li>
        <li>Stands</li>
        <li>Market</li>
      </ul>
    </div>
    <div class="nav" style="gap: 10px">
      <div class="nav-button">Log in</div>
      <div class="nav-button solid">Sign up</div>
    </div>
  </div>
</template>
<style scoped>
.nav-bar {
  display: flex;
  align-content: center;
  justify-content: space-between;
  background-color: black;
  padding: 0px 16px;
}
.nav {
  display: flex;
  align-items: center;
}
.logo {
  margin: auto;
  color: white;
  font-size: 24px;
}
ul {
  display: flex;
  list-style-type: none;
  justify-content: space-between;
  gap: 30px;
  color: white;
}
.nav-button {
  color: lightblue;
  border: 1px solid;
  border-radius: 30px;
  padding: 5px 16px;
}
.solid {
  background-color: lightblue;
  border: 1px solid lightblue;
  color: black;
}
</style>
