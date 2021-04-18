<template>
<div class="copyright">
    <div class="copyright__section">
        <p class="copyright__text">Copyright © 2013 Domain Name - All Rights Reserved</p>
        <p class="copyright__text">Template by OS Templates</p>
    </div>
</div>
</template>

<script>
export default {
  name: 'TheCopyright'
}
</script>

<style lang="scss">
.copyright {
  max-width: 1200px;
  width: 100%;
  height: 55px;
  background: #313131;
  display: flex;
  justify-content: center;
  margin: 0 auto 0 auto;
  &__section {
    max-width: 1200px;
    width: 96.666%;
    height: 55px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-top: 2px solid #3a3a3a;
  }
  &__text {
    color: #999999;
    font-size: 12px;
  }
}
@media (max-width: 500px) {
  .copyright {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 500px;
    margin-top: 50px;
    width: 100%;
    // width: 320px;
    height: 100px;
    background: #313131;
    display: flex;
    justify-content: center;
    margin: 0 auto 0 auto;
    &__section {
      width: 300px;
      height: 100px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      border-top: 2px solid #3a3a3a;
    }
    &__text {
      text-align: center;
    }
  }
}
</style>