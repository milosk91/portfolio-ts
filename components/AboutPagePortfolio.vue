<template>
  <div>
    <NavBarPortfolio />
    <div class="container">
      <div class="left">
        <div class="square">
          <span></span>
          <span></span>
          <span></span>
          <div class="content">
            <h2>Hi there!</h2>
            <p>
              I'm currently working as a Front-End Developer and UI/UX Designer,
              and would like to become a Full-Stack Developer in the future.
            </p>
          </div>
        </div>
      </div>

      <div class="right">
        <div class="square">
          <span></span>
          <span></span>
          <span></span>
          <div class="content">
            <p>
              With my passion for technology I become a self-learned Front-End
              Developer and UI/UX Designer. Now with a more then a year of
              experience working in the company, and more then a two years since
              I started learning about this profession.
            </p>
          </div>
        </div>
      </div>
    </div>
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
export default class AboutPagePortfolio extends Vue {
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
.container {
  display: flex;
  justify-content: center;
}

.square {
  position: relative;
  width: 550px;
  height: 550px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.square span:nth-child(1) {
  position: absolute;
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
  color: rosybrown;
  text-align: center;
  transition: 0.5s;
  font-size: 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: 'Roboto', sans-serif;
}
.right {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  margin-top: 6rem;
}

.left {
  width: 100%;
  margin-top: 6rem;
  display: flex;
  justify-content: center;
}
h2 {
  font-size: 3.5rem;
  font-weight: 400;
  max-width: 330px;
  margin-bottom: 1rem;
}
p {
  font-size: 1.5rem;
  margin-top: 0.5rem;
  font-weight: 300;
  max-width: 370px;
  line-height: 2.5rem;
}
</style>
