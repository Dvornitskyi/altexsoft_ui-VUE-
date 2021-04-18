<template>
  <div class="hello">
    <div class="header">
    <div class="header__section">
        <div class="header__section-text">
            <a href="#" class="header__logo"><img class="header__logo-img" src="../assets/logo280-75.png" alt="Logo"></a>
            <ul class="header__menu">
                <li class="header__menu-around header__menu-home"><a href="#" class="header__menu-link header__menu-link-home">HOME</a></li>
                <li class="header__menu-around"><a href="#" class="header__menu-link">STYLE DEMO</a></li>
                <li class="header__menu-around"><a href="#" class="header__menu-link">FULL WIDTH</a></li>
                <li class="header__menu-around"><a href="#" class="header__menu-link">DROPDOWN</a></li>
                <li class="header__menu-around"><a href="#" class="header__menu-link">PORTFOLIO</a></li>
                <li class="header__menu-around"><a href="#" class="header__menu-link">GALLERY</a></li>
            </ul>
        </div>
    </div>
</div>
  
  </div>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>

<style scoped lang="scss">
.header {
  max-width: 1200px;
  width: 100%;
  height: 102px;
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
    border-top: 6px solid #a7c353;
  }
  &__section-text {
    max-width: 1200px;
    width: 96.666%;
    height: 97px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #a7c353;
  }
  &__logo {
    max-width: 1200px;
    width: 28.5%;
    display: flex;
    align-items: center;
  }
  &__logo-img {
    width: 156px;
    height: 40px;
  }
  &__logo-img:hover {
    -webkit-transform: rotate(-10deg);
    -moz-transform: rotate(-10deg);
    -o-transform: rotate(-10deg);
    -ms-transform: rotate(-10deg);
    transform: rotate(-10deg);
    transition: 1s;
  }
  &__menu {
    max-width: 1200px;
    width: 63.5%;
    display: flex;
    justify-content: space-between;
  }
  &__menu-around {
    height: 97px;
    display: flex;
    align-items: center;
  }
  &__menu-link {
    white-space: nowrap;
    padding: 0 20px;
    font-size: 13px;
    font-weight: 100;
    color: #979797;
    // display: flex;
    // flex-wrap: nowrap;
  }
  &__menu-around:hover {
    background: #0f1bc5;
    cursor: pointer;
  }
  &__menu-around:hover .header__menu-link {
    color: #ffffff;
  }
  &__menu-home {
    height: 97px;
    width: 80px;
    display: flex;
    align-items: center;
    background-color: #a7c353;
  }
  &__menu-link-home {
    white-space: nowrap;
    padding: 0 20px;
    font-size: 13px;
    font-weight: 100;
    color: #ffffff;
  }
  &__menu-home:hover {
    background: #0f1bc5;
    cursor: pointer;
  }
}
@media (max-width: 1000px) {
  .header {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 1000px;
    width: 100%;
    height: 102px;
    background: #313131;
    display: flex;
    justify-content: center;
    margin: 0 auto 0 auto;
    &__section {
      width: 80%;
      background: #ffffff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-top: 6px solid #a7c353;
    }
    &__section-text {
      width: 80%;
      height: 99px;
      display: flex;
      flex-direction: column;

      align-items: center;
      border-bottom: 2px solid #a7c353;
    }
    &__logo {
      display: none;
    }
    &__menu {
      width: 80%;
      height: 99px;
      display: flex;
      flex-wrap: wrap;
    }
    &__menu-around {
      width: 50%;
      height: 33px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
}

@media (max-width: 500px) {
  .header {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 500px;
    width: 100%;
    height: 102px;
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
      border-top: 6px solid #a7c353;
    }
    &__section-text {
      width: 300px;
      height: 99px;
      display: flex;
      flex-direction: column;

      align-items: center;
      border-bottom: 2px solid #a7c353;
    }
    &__logo {
      display: none;
    }
    &__menu {
      width: 300px;
      height: 99px;
      display: flex;
      flex-wrap: wrap;
    }
    &__menu-around {
      width: 100px;
      height: 33px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
}
</style>
