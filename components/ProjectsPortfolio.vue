<template>
  <div>
    <NavBarPortfolio />
    <div class="block">
      <span class="demonstration">My Projects</span>
      <el-carousel>
        <el-carousel-item v-for="item in 3" :key="item">
          test
        </el-carousel-item>
      </el-carousel>
    </div>

    <!-- <div class="left">
        <div class="square">
          <span></span>
          <span></span>
          <span></span>
          <div class="content">
            <h2>test</h2>
            <p>test</p>
          </div>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import NavBarPortfolio from '~/components/NavBarPortfolio.vue'

@Component({
  components: {
    NavBarPortfolio,
  },
})
export default class ProjectsPortfolio extends Vue {
  /* Props */
  /* State */
  /* Data */
  /* Hooks */
  /* Methods */
  /* Computed */
  /* Watchers */
}
</script>

<style scoped>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  /* background: #f6f6f6; */
}
.block {
  /* height: 600px; */
}

.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 150px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
.container {
  display: flex;
  flex-direction: row;
}

.square {
  position: relative;
  width: 500px;
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.square span:nth-child(1) {
  position: absolute;
  top: 150px;
  left: 150px;
  width: 100%;
  height: 100%;
  border: 2px solid rosybrown;
  border-radius: 38% 63% 63% 37% / 41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate 6s linear infinite;
}

/* .square:hover span:nth-child(1) {
  border: none;
  background: rosybrown;
} */

.square span:nth-child(2) {
  position: absolute;
  top: 150px;
  left: 150px;
  width: 100%;
  height: 100%;
  border: 2px solid #ecb;
  border-radius: 38% 63% 63% 37%/41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate2 4s linear infinite;
}

/* .square:hover span:nth-child(2) {
  border: none;
  background: #ecb;
} */

.square span:nth-child(3) {
  position: absolute;
  top: 150px;
  left: 150px;
  width: 100%;
  height: 100%;
  border: 2px solid #ecc;
  border-radius: 38% 63% 63% 37%/41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate 10s linear infinite;
}

/* .square:hover span:nth-child(3) {
  background: #ecc;
  border: none;
} */

@keyframes animate {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

@keyframes animate2 {
  0% {
    transform: rotate(360deg);
  }

  100% {
    transform: rotate(0deg);
  }
}

.content {
  position: relative;
  top: 150px;
  left: 150px;
  padding: 40px 60px;
  color: rosybrown;
  text-align: center;
  transition: 0.5s;
  font-size: 16px;
  border: none;
  background: transparent;
  display: flex;
  flex-direction: column;
}
.right {
  width: 50%;
  height: 100%;
}

.left {
}

.img {
  width: 500px;
  height: 500px;
  border: 1px solid #ececec;
  border-radius: 38% 63% 63% 37% / 41% 44% 56% 59%;
}
.image {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 150px;
}
</style>
