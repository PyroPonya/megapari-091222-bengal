<template>
  <div class="container_balls">
    <div class="volleyball"></div>
    <div class="baseball"></div>
    <div class="football"></div>
  </div>
</template>

<script setup></script>

<style scoped>
.container_balls {
  position: relative;
  height: 100%;
  width: 30%;
}
.volleyball {
  position: absolute;
  top: 141px;
  left: 120px;
  width: 208px;
  height: 248px;
  background-image: url('../assets/volley_ball.png');
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  animation: volley 0.9s infinite alternate;
  animation-delay: 0.3s, 0s;
}
.baseball {
  position: absolute;
  top: 470px;
  left: 420px;
  width: 102px;
  height: 140.05px;
  background-image: url('../assets/base_ball.png');
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  animation: base 0.9s infinite alternate;
  animation-delay: 0.9s, 0s;
}
.football {
  position: absolute;
  top: 560px;
  left: -30px;
  width: 453px;
  height: 496px;
  background-image: url('../assets/foot_ball.png');
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  animation: foot 0.9s infinite alternate;
  animation-delay: 0.6s, 0s;
}

@keyframes volley {
  0% {
    top: 141px;
  }
  100% {
    top: 161px;
  }
}
@keyframes base {
  0% {
    top: 470px;
  }
  100% {
    top: 490px;
  }
}
@keyframes foot {
  0% {
    top: 560px;
  }
  100% {
    top: 540px;
  }
}

@media (max-width: 450px) {
  .container_balls {
    display: none;
  }
}
</style>
