<template>
  <div>
    <div class="bg">
      <nav-bar class="nav"></nav-bar>
      <p id="text">Our Best Rooms</p>
      <div id="container">
        <div class="holder">
          <p id="text2">Golden Deluxe Suite</p>
          <div class="grid__one">
            <img src="@/assets/bed.png" alt="bed" id="big__image" />
            <div class="grid__two">
              <img src="@/assets/tv.png" alt="tv" id="tv__image" />
              <img src="@/assets/pillows.png" alt="pillows" />
            </div>
          </div>
          <div class="text__holder">
            <div>
              <p id="text3">₦120,000/night</p>
              <p id="text4">Amenities: Free Wifi, Central Air Conditioning, Mini bar...</p>
            </div>
            <button class="btn__purple">Book Now</button>
          </div>
        </div>
        <div class="holder">
          <p id="text2">Queens Suite</p>
          <div class="grid__one">
            <img src="@/assets/room.png" alt="room" id="big__image" />
            <div class="grid__two">
              <img src="@/assets/mac.png" alt="mac" id="tv__image" />
              <img src="@/assets/passage.png" alt="passage" />
            </div>
          </div>
          <div class="text__holder">
            <div>
              <p id="text3">₦80,000/night</p>
              <p id="text4">Amenities: Free Wifi, Central Air Conditioning, Mini bar...</p>
            </div>
            <button class="btn__purple">Book Now</button>
          </div>
        </div>
        <div class="holder">
          <p id="text2">King Suite</p>
          <div class="grid__one">
            <img src="@/assets/window.png" alt="window" id="big__image" />
            <div class="grid__two">
              <img src="@/assets/light.png" alt="light" id="tv__image" />
              <img src="@/assets/bathroom.png" alt="bathroom" />
            </div>
          </div>
          <div class="text__holder">
            <div>
              <p id="text3">₦180,000/night</p>
              <p id="text4">Amenities: Free Wifi, Central Air Conditioning, Mini bar...</p>
            </div>
            <button class="btn__purple">Book Now</button>
          </div>
        </div>
      </div>
    </div>

    <FooterBar />
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import FooterBar from '@/components/FooterBar.vue';

export default {
  name: 'Room',
  components: {
    NavBar,
    FooterBar,
  },
};
</script>

<style scoped>
.bg {
  background-color: #e5e5e5;
}
.holder {
  padding-bottom: 64px;
}
#text {
  font-family: Mulish;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 45px;
  color: #333333;
  margin-bottom: 96px;
  margin-top: 81px;
  margin-left: 120px;
}
#container {
  margin-left: 120px;
  margin-right: 120px;
}
#text2 {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 30px;
  color: #9b51e0;
  margin-bottom: 32px;
}
.grid__one {
  display: grid;
  grid-template-columns: 6fr 6fr;
  margin-bottom: 32px;
}
#big__image {
  margin-right: 32px;
}
#tv__image {
  margin-bottom: 32px;
}
#text3 {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 30px;
  color: #333333;
  margin-bottom: 5px;
}
#text4 {
  font-family: Mulish;
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 23px;
  color: #333333;
}
.text__holder {
  display: flex;
  justify-content: space-between;
}
.grid__two {
  display: grid;
}
.btn__purple {
  background: #9b51e0;
  border: 1px solid #9b51e0;
  box-sizing: border-box;
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 36px;
  color: #ffffff;
  outline: none;
  padding: 8px 40px;
  cursor: pointer;
  transition-duration: 0.4s;
}
.btn__purple:hover {
  background-color: #f6f2f7;
  color: black;
}
</style>
