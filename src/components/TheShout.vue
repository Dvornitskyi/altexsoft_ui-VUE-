<template>
<div class="shout">
    <div class="shout__section">
        <div class="shout__section-text">
            <p class="shout__text">“ Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non diam 
                erat. In fringilla massa ut nisi ullamcorper pellentesque „</p>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'TheShout'
}
</script>

<style lang="scss">
.shout {
  max-width: 1200px;
  width: 100%;
  height: 135px;
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
    height: 135px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  &__text {
    width: 650px;
    // width: 708px;
    height: 53px;
    color: #666666;
    font-size: 22px;
    text-align: center;
  }
}
@media (max-width: 500px) {
  .shout {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 500px;
    // width: 320px;
    height: 200px;
    background: #313131;
    display: flex;
    justify-content: center;
    margin: 0 auto 0 auto;
    &__section {
      width: 300px;
      background: #ffffff;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    &__section-text {
      width: 300px;
      height: 200px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    &__text {
      width: 280px;
      // width: 708px;
      height: 153px;
      // color: #666666;
      // font-size: 22px;
      // text-align: center;
    }
  }
}
</style>