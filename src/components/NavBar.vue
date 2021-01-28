<template>
  <span>
    <div class="nav__container" v-if="routeName === 'Home'">
      <div>
        <router-link :to="{ name: 'Home' }" class="logo" id="logo1">Delight Hotels</router-link>
      </div>
      <div>
        <ul class="nav__links_holder">
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links">Rooms</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links">Facilities</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links">Offers</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links">Gallery</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links">Contact</router-link>
          </li>
          <li class="nav__links__btn">
            <button class="btn">Book now</button>
          </li>
        </ul>
      </div>
    </div>
    <div class="nav__container" v-else>
      <div>
        <router-link :to="{ name: 'Home' }" class="logo" id="logo2">Delight Hotels</router-link>
      </div>
      <div>
        <ul class="nav__links_holder">
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links__black">Rooms</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links__black"
              >Facilities</router-link
            >
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links__black">Offers</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links__black">Gallery</router-link>
          </li>
          <li class="nav__links_holder_li">
            <router-link :to="{ name: 'rooms' }" class="nav__links__black">Contact</router-link>
          </li>
          <li class="nav__links__btn">
            <button class="btn">Book now</button>
          </li>
        </ul>
      </div>
    </div>
  </span>
</template>

<script>
export default {
  name: 'NavBar',
  data() {
    return {
      routeName: null,
    };
  },
  mounted() {
    this.routeName = this.$route.name;
  },
};
</script>

<style scoped>
.nav__container {
  display: flex;
  justify-content: space-between;
  padding: 36px 120px 0px 120px;
}
.nav__links_holder {
  display: flex;
  align-items: center;
}
.nav__links_holder_li {
  margin-right: 32px;
  text-decoration: none;
  list-style: none;
}
.logo {
  text-decoration: none;
  font-family: Allura;
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 45px;
}
#logo1 {
  color: #ffffff;
}
#logo2 {
  color: #000000;
}
.nav__links {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: #ffffff;
  text-decoration: none;
  list-style: none;
}
.nav__links__black {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: rgba(51, 51, 51, 0.8);
  text-decoration: none;
  list-style: none;
}
.nav__links:hover {
  border-bottom: 4px solid #9b51e0;
}
.nav__links__btn {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: #ffffff;
  text-decoration: none;
  list-style: none;
  transition-duration: 0.4s;
}
.nav__links__btn:hover {
  background-color: #ffffff;
}
.btn {
  padding: 8px 40px;
  background: #9b51e0;
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: #ffffff;
  align-items: center;
  outline: none;
  border: none;
  cursor: pointer;
  transition-duration: 0.4s;
}
.btn:hover {
  background-color: #f6f2f7;
  color: black;
}
.nav__links_holder > a.router-link-exact-active {
  color: #000000;
}
</style>
