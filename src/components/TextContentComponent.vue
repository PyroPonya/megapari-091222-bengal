<template>
  <div class="text_container">
    <div class="title"></div>
    <div v-if="false" class="heading">
      <div v-for="(el, id) in fatText" :key="id" :class="el" class="num"></div>
    </div>
    <div class="desc">প্রথম জমাতে 100% বোনাস পান</div>
    <a href="https://m6748923.xyz/ru/registration?tag=d_1914807m_30577c_&pb=4548d857729740efae8407358e226802&click_id=%7bclick_id%7d&partner_id=%7bpartner_id%7d&r=registration">
      <div class="btn">
        <div class="btn_text">একটি বোনাস পান</div>
      </div>
    </a>
    <a v-if="false" href="https://m6748923.xyz/ru/registration?tag=d_1914807m_30577c_&pb=4548d857729740efae8407358e226802&click_id=%7bclick_id%7d&partner_id=%7bpartner_id%7d&r=registration">
      <div class="btn_desc">কিভাবে রিসিভ করবেন 125000 BDT</div>
    </a>
  </div>
</template>

<script>
export default {
  setup() {
    const fatText = [
      'num_1',
      'num_2',
      'num_5',
      'num_0 num_0_1',
      'num_0 num_0_2',
      'num_0 num_0_3',
      'num_b',
      'num_d',
      'num_t',
    ];
    return {
      fatText,
    };
  },
};
</script>

<style scoped>
.text_container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.title {
  height: 72px;
  width: 612px;
  background-image: url('../assets/megapari_logo.svg');
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  margin-bottom: 110px;
}

.heading {
  display: flex;
  flex-direction: row;
  margin-bottom: 60px;
}

.num {
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  height: 100px;
  width: 100px;
}

.num_1 {
  background-image: url('../assets/num_1.png');
  animation: glow_1 1s infinite alternate;
  animation-delay: 0.1s, 0s;
}
.num_2 {
  background-image: url('../assets/num_2.png');
  animation: glow_2 1s infinite alternate;
  animation-delay: 0.2s, 0s;
}
.num_5 {
  background-image: url('../assets/num_5.png');
  animation: glow_5 1s infinite alternate;
  animation-delay: 0.3s, 0s;
}
.num_0_1 {
  background-image: url('../assets/num_0.png');
  animation: glow_0 1s infinite alternate;
  animation-delay: 0.4s, 0s;
}
.num_0_2 {
  background-image: url('../assets/num_0.png');
  animation: glow_0 1s infinite alternate;
  animation-delay: 0.5s, 0s;
}
.num_0_3 {
  background-image: url('../assets/num_0.png');
  animation: glow_0 1s infinite alternate;
  animation-delay: 0.6s, 0s;
}
.num_b {
  background-image: url('../assets/num_b.png');
  animation: glow_b 1s infinite alternate;
  animation-delay: 0.7s, 0s;
}
.num_d {
  background-image: url('../assets/num_d.png');
  animation: glow_d 1s infinite alternate;
  animation-delay: 0.8s, 0s;
}
.num_t {
  background-image: url('../assets/num_t.png');
  animation: glow_t 1s infinite alternate;
  animation-delay: 0.9s, 0s;
}

@keyframes glow_1 {
  0% {
    background-image: url('../assets/num_1.png');
  }
  100% {
    background-image: url('../assets/num_1_glow.png');
  }
}
@keyframes glow_2 {
  0% {
    background-image: url('../assets/num_2.png');
  }
  100% {
    background-image: url('../assets/num_2_glow.png');
  }
}
@keyframes glow_5 {
  0% {
    background-image: url('../assets/num_5.png');
  }
  100% {
    background-image: url('../assets/num_5_glow.png');
  }
}
@keyframes glow_0 {
  0% {
    background-image: url('../assets/num_0.png');
  }
  100% {
    background-image: url('../assets/num_0_glow.png');
  }
}
@keyframes glow_b {
  0% {
    background-image: url('../assets/num_b.png');
  }
  100% {
    background-image: url('../assets/num_b_glow.png');
  }
}
@keyframes glow_d {
  0% {
    background-image: url('../assets/num_d.png');
  }
  100% {
    background-image: url('../assets/num_d_glow.png');
  }
}
@keyframes glow_t {
  0% {
    background-image: url('../assets/num_t.png');
  }
  100% {
    background-image: url('../assets/num_t_glow.png');
  }
}

.desc {
  max-width: 450px;
  font-weight: 800;
  font-size: 74px;
  line-height: 90px;
  text-align: center;
  color: #ffffff;
  margin-bottom: 32px;
}

.btn {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #0fdc92;
  border-radius: 19px;
  font-weight: 700;
  font-size: 40px;
  line-height: 48px;
  color: #ffffff;
  height: 86px;
  width: 373px;
  animation: breath 0.9s infinite alternate;
  animation-delay: 0.3s, 0s;
  -webkit-transform: skew(-20deg);
  -moz-transform: skew(-20deg);
  transform: scale(1) skew(-20deg);
  margin-bottom: 32px;
}

@keyframes breath {
  0% {
    transform: scale(1) skew(-20deg);
  }
  100% {
    transform: scale(1.05) skew(-20deg);
  }
}
.btn_text {
  -webkit-transform: skew(20deg);
  -moz-transform: skew(20deg);
  transform: skew(20deg);
}
.btn:hover {
  background: linear-gradient(180deg, #15ff49 0%, #1c8e00 100%);
}
.btn:active {
  background: linear-gradient(180deg, #15ff49 0%, #1c8e00 100%);
}

.btn_desc {
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #ffffff;
  height: 30px;
}

.btn_desc:hover {
  background: linear-gradient(180deg, #ffffff 0%, #48baef 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.btn_desc:active {
  background: linear-gradient(180deg, #ffffff 0%, #48baef 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

@media (max-width: 450px) {
  .text_container {
    display: grid;
    grid-template-columns: 1fr;
    justify-items: center;
  }
  .title {
    background-image: url('../assets/megapari_logo_mobile.svg');
    height: 36px;
    width: 306px;
    margin-bottom: 90px;
  }
  .desc {
    grid-row-start: 2;
    grid-row-end: 3;
  }
  .heading {
    display: grid;
    grid-row-start: 3;
    grid-row-end: 4;
    grid-template-columns: repeat(6, 1fr);
  }
  .num {
    height: 60px;
    width: 50px;
  }
  .num_b {
    grid-column-start: 3;
    grid-column-end: 4;
  }
  .num_d {
    grid-column-start: 4;
    grid-column-end: 5;
  }
  .num_t {
    grid-column-start: 5;
    grid-column-end: 6;
  }
  .desc {
    font-size: 48px;
    line-height: 58px;
    max-width: 300px;
  }
  .btn {
    width: 290px;
    height: 67px;
    margin-bottom: 30px;
  }
  .btn_text {
    font-size: 31.0992px;
    line-height: 38px;
  }
  .btn_desc {
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
  }
}
</style>
