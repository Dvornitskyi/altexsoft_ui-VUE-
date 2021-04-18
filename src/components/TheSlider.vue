<template>
<div class="slider">
    <div class="slider__section">
        <div class="slider__section-text">
            <div class="owl-carousel">
                <div><img class="slider__img" src="../assets/920-350/920-x-350-goalie-front-and-back.jpg" alt="920-350"></div>
                <div><img class="slider__img" src="../assets/920-350/920-x-350-Banner-3-x-images.jpg" alt="920-350"></div>
                <div><img class="slider__img" src="../assets/920-350/920-x-350-Banner-Class-of-2012-Screen-printing.jpg" alt="920-350"></div>
                <div><img class="slider__img" src="../assets/920-350/920-x-350-Banner-Cloverdale-Colts-2.jpg" alt="920-350"></div>
                <div><img class="slider__img" src="../assets/920-350/920-x-350-Banner-FVD-DIVE-MEET.jpg" alt="920-350"></div>
                <div><img class="slider__img" src="../assets/920-350/920-x-350-Banner-NATURAL-LAWN-CARE.jpg" alt="920-350"></div>
            </div>
            <div class="slider__zidex-tittle">
                <p class="slider__zidex-tittle-text">
                    This Is A Very Long Slider Title
                </p>
            </div>
            <div class="slider__zidex-subtittle">
                <p class="slider__zidex-subtittle-text">
                    Vestibulumaccumsan egestibulum eu justo convallis augue estas aenean elit intesque sed. Facilispede estibulum nulla orna nisl velit.
                </p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'TheSlider'
}
</script>

<style lang="scss">
.slider {
  max-width: 1200px;
  width: 100%;
  height: 427px;
  background: #313131;
  display: flex;
  justify-content: center;
  margin: 0 auto 0 auto;
  &__section {
    max-width: 1200px;
    width: 96.666%;
    background: #ffffff;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  &__section-text {
    width: 920px;
    height: 427px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
  }
  &__zidex-tittle {
    width: 351px;
    height: 41px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    z-index: 10;
    top: 209px;
    right: 62px;
    color: #ffffff;
    background-color: #a7c353;
    font-size: 22px;
  }
  &__zidex-tittle-text {
    width: 304px;
    height: 22px;
  }
  &__zidex-subtittle {
    width: 351px;
    height: 69px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    z-index: 10;
    top: 260px;
    right: 62px;
    color: #999999;
    background-color: #ffffff;
    font-size: 13px;
  }
  &__zidex-subtittle-text {
    width: 323px;
    height: 42px;
  }
}
.nav-bg {
  background-color: #a7c353;
  border-radius: 50%;
  padding: 0px;
  height: 53px;
  width: 53px;
}
.owl-prev {
  position: absolute;
  top: 142px;
  left: 10px;
}
.owl-next {
  position: absolute;
  top: 142px;
  right: 10px;
}
.owl-dots {
  margin-top: 20px;
  padding-bottom: 40px;
  display: flex;
  justify-content: center;
  border-bottom: 2px solid #e2e2e2;
}
.owl-dot {
  height: 15px;
  width: 15px;
  border: 3px solid #a7c353 !important;
  border-radius: 50%;
  background: #a7c353 !important;
  margin-right: 3px;
}
.owl-dot.active {
  background: none !important;
}
.owl-dot:hover {
  border: 3px solid purple !important;
  transition: 1s;
}
.nav-bg:hover {
  background-color: purple;
  transition: 1s;
}

@media (max-width: 1000px) {
  .slider {
    display: none;
  }
}
</style>