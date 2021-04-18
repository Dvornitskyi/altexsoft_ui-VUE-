<template>
<div class="content">
    <div class="content__section">
        <div class="content__section-text">
            <div class="content__first-column">
                <h3 class="content__first-title center-title">A Little About Us</h3>
                <div class="content__first-column-image-area">
                    <img class="content__first-column-image" src="../assets/content-image.jpg" alt="">
                </div>
                <p class="content__text-colum first-colum-text-first">Justoid nonummy laoreet phasellent penatoque in antesque pellus elis eget tincidunt. Nequatdui laorem justo a non tellus laoreet tincidunt ut vel velit nonummy laoreet phasellent penatoque in antesque pellus elis eget tincidunt.</p>
                <p class="content__text-colum first-colum-text-two">Idenim semper pellente velis felit ac. Justoid nonummy laoreet phasellent penatoque in antesque pellus elis eget tincidunt.</p>
                <a href="#" class="content__link-first-column">Read More About Us »</a>
            </div>
            <div class="content__second-column">
                <h3 class="content__second-title center-title">Some of Our Services</h3>
                <div class="content__second-one"> 
                    <img class="content__second-one-image" src="../assets/64-64/1.jpg" alt="">
                    <div class="content__second-one-area">
                        <h4 class="content__second-one-title">Service Title</h4>
                        <p class="content__second-one-text">Inteligula congue id elis donec sce sag ittis intes id laoreet aenean.</p>
                    </div>
                </div>
                <div class="content__second-one"> 
                    <img class="content__second-one-image" src="../assets/64-64/2.jpg" alt="">
                    <div class="content__second-one-area">
                        <h4 class="content__second-one-title">Service Title</h4>
                        <p class="content__second-one-text">Inteligula congue id elis donec sce sag ittis intes id laoreet aenean.</p>
                    </div>
                </div>
                <div class="content__second-one"> 
                    <img class="content__second-one-image" src="../assets/64-64/3.jpg" alt="">
                    <div class="content__second-one-area">
                        <h4 class="content__second-one-title">Service Title</h4>
                        <p class="content__second-one-text">Inteligula congue id elis donec sce sag ittis intes id laoreet aenean.</p>
                    </div>
                </div>
                <div class="content__second-one"> 
                    <img class="content__second-one-image" src="../assets/64-64/4.jpg" alt="">
                    <div class="content__second-one-area">
                        <h4 class="content__second-one-title">Service Title</h4>
                        <p class="content__second-one-text">Inteligula congue id elis donec sce sag ittis intes id laoreet aenean.</p>
                    </div>
                </div>
                <a class="content__second-link" href="#">View All Of Our Services »</a>
            </div>
            <div class="content__third-column">
                <div class="content__third-one">
                    <h3 class="content__third-title center-title">What Our Clients Say</h3>
                    <div class="content__third-area">
                        <img class="content__third-image" src="../assets/content-quotes.png" alt="">
                        <p class="content__third-tittle-text">Tommy Tanker - CEO</p>
                    </div>
                    <p class="content__third-text">Justoid nonummy laoreet phasellent penatoque in antesque pellus elis eget tincidunt. Nequatdui laorem justo a non tellus laoreet tincidunt ut vel velit. Idenim semper pellente velis felit ac nullam pretium morbi lacus.</p>
                    <a class="content__third-link" href="#">View This Project »</a>
                </div>  
             
                    <div class="content__third-area">
                        <img class="content__third-image" src="../assets/content-quotes.png" alt="">
                        <p class="content__third-tittle-text">Tommy Tanker - CEO</p>
                    </div>
                    <p class="content__third-text">Justoid nonummy laoreet phasellent penatoque in antesque pellus elis eget tincidunt. Nequatdui laorem justo a non tellus laoreet tincidunt ut vel velit. Idenim semper pellente velis felit ac nullam pretium morbi lacus.</p>
                    <a class="content__third-link" href="#">View This Project »</a>

            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'TheContent'
}
</script>

<style lang="scss">
.content {
  max-width: 1200px;
  width: 100%;
  height: 510px;
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
    max-width: 1200px;
    width: 96.666%;
    height: 510px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 43px;
  }
  &__first-column {
    width: 283px;
    height: 428px;
  }
  &__first-title {
    margin-bottom: 25px;
    color: #666666;
    font-size: 22px;
  }
  &__first-column-image-area {
    width: 281px;
    height: 151px;
    border: 1px solid #e2e2e2;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
  }
  &__first-column-image {
    width: 270px;
    height: 140px;
  }
  &__text-colum {
    font-size: 13px;
    color: #999999;
  }
  .first-colum-text-first {
    margin-bottom: 30px;
  }
  .first-colum-text-two {
  }
  &__link-first-column {
    margin-top: 30px;
    margin-left: 145px;
    color: #a7c353;
    font-size: 13px;
  }
  &__second-column {
    width: 282px;
    height: 428px;
  }
  &__second-title {
    color: #666666;
    font-size: 22px;
    margin-bottom: 28px;
  }
  &__second-one {
    width: 270px;
    height: 73px;
    display: flex;
    justify-content: space-between;
    margin-bottom: 15px;
  }
  &__second-one-image {
    width: 64px;
    height: 64px;
  }
  &__second-one-area {
  }
  &__second-one-title {
    width: 92px;
    height: 11px;
    font-size: 14px;
    color: #878787;
    margin-bottom: 13px;
  }
  &__second-one-text {
    width: 175px;
    height: 47px;
    font-size: 13px;
    color: #868686;
  }
  &__second-link {
    margin-top: -60px;
    margin-left: 120px;
    font-size: 13px;
    color: #a7c353;
  }
  &__third-column {
    width: 282px;
    height: 428px;
  }
  &__third-title {
    color: #666666;
    font-size: 22px;
    margin-bottom: 23px;
  }
  &__third-area {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
  }
  &__third-image {
    width: 54px;
    height: 45px;
  }
  &__third-tittle-text {
    font-size: 16px;
    color: #989898;
    margin-left: 10px;
  }
  &__third-text {
    width: 273px;
    height: 92px;
    font-size: 13px;
    color: #888888;
  }
  &__third-link {
    margin-left: 160px;
    color: #a7c353;
    font-size: 13px;
  }
}
@media (max-width: 500px) {
  .center-title {
    text-align: center;
  }
  .content {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 500px;
    height: 1600px;
    background: #313131;
    display: flex;
    justify-content: center;
    margin: 0 auto 0 auto;
    &__section {
      width: 300px;
      background: #ffffff;
      display: flex;
      // align-items: center;
      justify-content: center;
    }
    &__section-text {
      width: 300px;
      height: 1510px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
  }
}

</style>