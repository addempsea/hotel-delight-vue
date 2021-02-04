<template>
  <div id="overlay">
    <div class="home">
      <nav-bar class="nav"></nav-bar>
      <div class="group__text">
        <div>
          <p id="home__text__one">Welcome To Delight Hotels</p>
        </div>
        <div>
          <p id="home__text__two">
            Our Hotel and Resorts remain stylish, modern, and elegant. <br />
            We offer hospitable services and we help to make travelling easy with our serene
            environment, tasty meals, unique <br />
            activities, nature and hospitality.
          </p>
        </div>
        <div class="btn__holder">
          <button id="btn">
            Book Now
          </button>
        </div>
      </div>
    </div>
    <TextImage />
    <ReviewTab />
    <ContactUs />
    <FooterBar />
  </div>
</template>

<script>
import TextImage from '@/components/TextImage.vue';
import NavBar from '@/components/NavBar.vue';
import ReviewTab from '@/components/ReviewTab.vue';
import ContactUs from '@/components/ContactUs.vue';
import FooterBar from '@/components/FooterBar.vue';

export default {
  name: 'Home',
  components: {
    NavBar,
    TextImage,
    ReviewTab,
    ContactUs,
    FooterBar,
  },
};
</script>

<style scoped>
.btn__holder {
  width: 100%;
  display: flex;
  justify-content: center;
  margin-top: 98px;
}
.group__text {
  margin-top: 343px;
}
.home {
  background: linear-gradient(
      0deg,
      rgba(17, 17, 0, 0.6),
      rgba(17, 17, 0, 0.6),
      rgba(17, 17, 0, 0.6)
    ),
    url('../assets/bg.png');
  height: 988px;
  background-size: cover;
}
#home__text__one {
  font-family: Mulish;
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 60px;
  color: #ffffff;
  text-align: center;
  margin-bottom: 32px;
}

#home__text__two {
  font-family: Mulish;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #ffffff;
  height: 140px;
  width: 723px;
  margin: 0 auto;
}
#btn {
  font-family: Mulish;
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 23px;
  color: #ffffff;
  text-align: center;
  text-decoration: none;
  background: none;
  outline: none;
  padding: 8px 26px;
  border: 1px solid white;
  cursor: pointer;
  transition-duration: 0.4s;
  box-sizing: border-box;
}
#btn:hover {
  background-color: #9b51e0;
  border: 1px solid #9b51e0;
}
</style>
