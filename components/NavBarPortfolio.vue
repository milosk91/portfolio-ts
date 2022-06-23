<template>
  <div class="navbar">
    <el-button class="button" plain @click="goToHome()">
      <img src="/mk-logo-rosybrown.png" class="logo" />
    </el-button>
    <el-menu mode="horizontal" @select="handleSelect">
      <el-menu-item index="1" @click="goToHome()">Home.</el-menu-item>
      <el-menu-item index="2" @click="goToAbout()">About Me.</el-menu-item>
      <el-menu-item index="3" @click="goToProjects()">Projects.</el-menu-item>
      <el-menu-item index="4" @click="goToContact()">Contact Me.</el-menu-item>
    </el-menu>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component
export default class NavBarPortfolio extends Vue {
  /* Props */
  /* State */
  /* Data */
  activeIndex: string = '1'

  /* Hooks */
  /* Methods */
  handleSelect(activeIndex: string): void {
    this.activeIndex = activeIndex
  }

  goToHome(): void {
    this.$router.push('/home')
  }

  goToAbout(): void {
    this.$router.push('/about')
  }

  goToProjects(): void {
    this.$router.push('/projects')
  }

  goToContact(): void {
    this.$router.push('/contact')
  }
  /* Computed */
  /* Watchers */
}
</script>

<style scoped>
.navbar {
  width: 100%;
  display: flex;
  justify-content: center;
  font-family: 'Roboto', sans-serif;
}

.el-menu--horizontal .el-menu-item:not(.is-disabled):focus,
.el-menu--horizontal .el-menu-item:not(.is-disabled):hover {
  background: #f6f6f6;
  text-decoration: line-through;
  text-decoration-color: red;
}
.el-menu--horizontal > .el-menu-item.is-active {
  border-bottom: 2px solid rosybrown;
  background: #f6f6f6;
  color: #303133;
}

.logo {
  position: relative;
  display: block;
  padding: 15px 0px 0px 15px;
  max-width: 120px;
  max-height: 80px;
}

.button {
  position: absolute;
  top: 0px;
  left: 0px;
  border: none;
}
</style>
