<template>
  <div class="bg">
    <div class="review__holder">
      <div class="text__holder">
        <span class="text">What Our Customers Say</span>
      </div>
      <div class="images">
        <img src="@/assets/dp1.png" alt="1" />
        <img src="@/assets/dp2.png" alt="2" />
        <img src="@/assets/dp3.png" alt="3" />
        <img src="@/assets/dp4.png" alt="4" />
        <img src="@/assets/dp5.png" alt="5" />
      </div>
      <div class="comment__holder">
        <span class="comment"
          >My experience in Delight hotels was amazing. From the <br />
          environment to the meals, it made my vacation more enjoyable.</span
        >
      </div>
      <div class="name__holder">
        <span class="name">Romoke Odunuga</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'review',
  data() {
    return {};
  },
};
</script>

<style scoped>
.bg {
  background: #ffffff;
}
.review__holder {
  padding: 128px 0;
}
.images {
  display: flex;
  align-items: center;
  width: 100%;
  justify-content: center;
  margin-bottom: 32px;
}

.images > img {
  margin-right: 104px;
}
.text__holder {
  width: 100%;
  text-align: center;
  padding-bottom: 42px;
}
.text {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 45px;
  color: #000000;
}
.comment {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  text-align: center;
  color: #333333;
}
.name {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 23px;
  text-align: center;
  color: #9b51e0;
}
.comment__holder {
  text-align: center;
  margin-bottom: 32px;
}
.name__holder {
  text-align: center;
}
</style>
