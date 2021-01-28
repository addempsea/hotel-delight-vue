<template>
  <div class="bg">
    <div class="text_holder">
      <p class="title">Send A Message</p>
      <p class="content"
        >Do you want to make enquiries or book one of our amazing services? <br />
        Our inbox is always open, kindly reach out to us and you will be <br />
        attended to as soon as we get it. Thank you.</p
      >
      <button class="btn__purple">
        Contact Us
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'contact-us',
};
</script>

<style scoped>
.bg {
  background: #f4f4f2;
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
.text_holder {
  text-align: center;
  padding: 72px 0;
}
.title {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 45px;
  text-align: center;
  color: #333333;
  margin-bottom: 52px;
}
.content {
  font-family: Mulish;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 36px;
  text-align: center;
  color: #333333;
  margin-bottom: 52px;
}
</style>
