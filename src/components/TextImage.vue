<template>
  <div class="bg">
    <div class="text__image">
      <div class="holder">
        <div class="margin__righty">
          <img src="../assets/history.png" alt="history" />
        </div>
        <div class="text__holder">
          <p class="title">DELIGHT HOTELS</p>
          <p class="sub__title">Our History</p>
          <p class="text">
            Travelers throughout the world have always sought hospitable places to rest and eat.
            Although modern hotels feature conveniences such as televisions, en-suite showers and
            minibars, they fulfill the same purpose as ancient inns and boarding houses. The history
            of hotel and restaurant management goes back many years but has always involved the
            essential concept of hospitality. It all started in 1919, when Oluwaleke Adebayo bought
            his first hotel. Since then, we’ve led the industry with...
          </p>
          <button class="btn__purple">
            Read more
          </button>
        </div>
      </div>
      <div class="holder">
        <div class="text__holder margin__righty">
          <p class="title">COMFORTABILITY</p>
          <p class="sub__title">Accommodation</p>
          <p class="text">
            Each guest room and suite features mordern craftsmanship, creating an elegant and
            romantic aura through hand-painted headboards, handcrafted furnishings and original
            artwork. Our hotel offers decadent amenities, providing each guest room with high speed
            Wi-Fi, bottled water, luscious bath amenities, nightly turndown service, plush bathrobes
            and more at no extra charge.
          </p>
          <button class="btn__purple">
            Check Room Rates
          </button>
        </div>
        <div class="">
          <img src="../assets/accomodation.png" alt="accomodation" />
        </div>
      </div>
      <div class="holder">
        <div class="margin__righty">
          <img src="../assets/mouth.png" alt="history" />
        </div>
        <div class="text__holder">
          <p class="title">DELICIOUS MEALS</p>
          <p class="sub__title">Mouth Watery Meals</p>
          <p class="text">
            Savor our satisfactory and mouth-watery food prepared with love and care by our
            professional chefs. We offer Italian, Mexican, Chinese cuisines and also our Nigerian
            traditional meals that do makes you feel completely at home. We promise you home away
            from home experience in our hotel.
          </p>
          <button class="btn__purple">
            Book Now
          </button>
        </div>
      </div>
      <div class="holder">
        <div class="text__holder margin__righty">
          <p class="title">ACCESSIBILITY</p>
          <p class="sub__title">Facilities And Services</p>
          <p class="text">
            We have one of the best facilities in Lagos State for your comfortability and enjoyment.
            Facilities ranging from a well equipped gym, a steam room, spa, unisex hair and nair
            salon amongst others. These facilities also have professionals waiting to attend to you.
          </p>
          <button class="btn__purple">
            Book Now
          </button>
        </div>
        <div class="">
          <img src="../assets/accomodation.png" alt="accomodation" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TextImage',
};
</script>

<style scoped>
.bg {
  background: #f4f4f2;
}
.text__image {
  padding-top: 128px;
  width: 100%;
  padding-bottom: 128px;
}
.title {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  color: #000000;
  margin-bottom: 16px;
}
.sub__title {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 45px;
  color: #333333;
  margin-bottom: 32px;
}
.text {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  color: #333333;
  margin-bottom: 32px;
  width: 494px;
  height: 248px;
  align-content: center;
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
  padding: 8px 64px;
  cursor: pointer;
  transition-duration: 0.4s;
}
.btn__purple:hover {
  background-color: #f6f2f7;
  color: black;
}
.holder {
  display: grid;
  grid-template-columns: 6fr 6fr;
  margin: 0 120px 120px 152px;
}
.margin__righty {
  margin-right: 92px;
}
</style>
