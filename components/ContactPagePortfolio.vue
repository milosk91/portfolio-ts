<template>
  <div>
    <NavBarPortfolio />
    <div class="container">
      <div class="right">
        <div class="image">
          <img src="/ja.png" class="img" alt="" />
        </div>
      </div>

      <div class="left">
        <div class="square">
          <span></span>
          <span></span>
          <span></span>
          <div class="content">
            <h2>Contact Me</h2>
            <p>
              Thank you for visiting my design portfolio. If you’d like to see
              more or would like to get in touch, my contact information is
              provided below.
            </p>
            <div class="contact">
              <svg
                class="svg"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
              >
                <a href="mailto:milos.koruga.1@gmail.com" target="_blank">
                  <!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                  <path
                    d="M464 64C490.5 64 512 85.49 512 112C512 127.1 504.9 141.3 492.8 150.4L275.2 313.6C263.8 322.1 248.2 322.1 236.8 313.6L19.2 150.4C7.113 141.3 0 127.1 0 112C0 85.49 21.49 64 48 64H464zM217.6 339.2C240.4 356.3 271.6 356.3 294.4 339.2L512 176V384C512 419.3 483.3 448 448 448H64C28.65 448 0 419.3 0 384V176L217.6 339.2z"
                  />
                </a>
              </svg>
              <svg
                class="svg"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <a
                  href="https://www.linkedin.com/in/milos-koruga-0ba958206/"
                  target="_blank"
                >
                  <!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                  <path
                    d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
                  />
                </a>
              </svg>
              <svg
                class="svg"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
              >
                <a href="https://www.instagram.com/m.koruga/" target="_blank">
                  <!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                  <path
                    fill="404987"
                    d="M224.1 141c-63.6 0-114.9
                  51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9
                  287.7 141 224.1 141zm0 189.6c-41.1
                  0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7
                  74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8
                  26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8
                  26.8zm76.1
                  27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9
                  0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1
                  147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37
                  2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2
                  34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8
                  19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7
                  2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7
                  9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9
                  132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7
                  29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
                  />
                </a>
              </svg>
            </div>
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
export default class ContactPagePortfolio extends Vue {
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
  width: 100%;
  justify-content: space-around;
  margin-top: 8rem;
}
.content {
  max-width: 400px;
  color: rosybrown;
  text-align: center;
  display: flex;
  flex-direction: column;
  font-family: 'Roboto', sans-serif;
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
  width: 100%;
  height: 100%;
  border: 2px solid rosybrown;
  border-radius: 38% 63% 63% 37% / 41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate 6s linear infinite;
}

.square span:nth-child(2) {
  position: absolute;
  width: 100%;
  height: 100%;
  border: 2px solid #ecb;
  border-radius: 38% 63% 63% 37%/41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate2 4s linear infinite;
}

.square span:nth-child(3) {
  position: absolute;
  width: 100%;
  height: 100%;
  border: 2px solid #ecc;
  border-radius: 38% 63% 63% 37%/41% 44% 56% 59%;
  transition: 0.5s;
  animation: animate 10s linear infinite;
}

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
}

.img {
  max-width: 500px;
  max-height: 500px;
  border: 1px solid #ececec;
  border-radius: 68% 33% 53% 27% / 91% 64% 86% 39%;
}
.image {
  display: flex;
  justify-content: center;
}
.contact {
  display: flex;
  justify-content: center;
}
p {
  font-size: 1.5rem;
  margin-top: 0.25rem;
  font-weight: 300;
}
h2 {
  font-size: 2rem;
  font-weight: 400;
}
.svg {
  max-width: 2.5rem;
  fill: rosybrown;
  opacity: 1;
  margin-right: 1rem;
}
.svg:hover {
  opacity: 0.6;
  cursor: pointer;
  transform: scale(1.1);
}
path {
  fill: rosybrown;
}
</style>
