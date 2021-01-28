<template>
  <div class="bg">
    <div class="container">
      <div class="grid__one">
        <router-link :to="{ name: 'rooms' }" class="footer__links">Rooms</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Restaurants&Bars</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Facilities</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Offers</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Gallery</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links last">Contact</router-link>
      </div>
      <div class="line"></div>
      <div class="grid__two">
        <router-link :to="{ name: 'rooms' }" class="footer__links">Accessibility</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Trust&Safety</router-link>
        <router-link :to="{ name: 'rooms' }" class="footer__links">Help Center</router-link>
        <div>
          <a href="https://twitter.com/_addempsea" class="footer__links link"
            ><img src="@/assets/twitter.png" alt="twitter"
          /></a>
          <a href="https://www.facebook.com/Addempsea" class="footer__links"
            ><img src="@/assets/fb.png" alt="facebook"
          /></a>
        </div>
        <p class="footer__links two">Delight Hotels Copyright {{ year }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'footerBar',
  data() {
    return {
      year: null,
    };
  },
  mounted() {
    this.year = new Date().getFullYear();
  },
};
</script>

<style scoped>
.bg {
  background: #ffffff;
}
.container {
  padding: 32px 117px 37px 120px;
}
.grid__one {
  display: grid;
  width: 100%;
  grid-template-columns: repeat(6, 1fr);
}
.footer__links {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: #333333;
  text-decoration: none;
}
.grid__two {
  display: grid;
  width: 100%;
  grid-template-columns: repeat(6, 1fr);
}
.two {
  grid-column: auto / span 2;
}
.link {
  padding-right: 11.5px;
}
.line {
  border: 1px solid #dee1ef;
  margin: 32px 0px;
  width: 100%;
}
</style>
