<template>
  <header>
    <div class="block__one">
      <div class="container">
        <div class="header__wrap">
          <img class="header__wrap-icon" src="../assets/img/icons/logo.svg" alt="">
          <div class="header__wrap-icons_social">
            <img class="header__wrap-icons_social-icon" src="../assets/img/icons/discord.svg" alt="">
            <img class="header__wrap-icons_social-icon" src="../assets/img/icons/twitter.svg" alt="">
            <img class="header__wrap-icons_social-icon" src="../assets/img/icons/medium.svg" alt="">
            <div class="header__wrap-icons_social_btn">
              Whitepaper
            </div>
          </div>

        </div>
      </div>


    </div>
  </header>
</template>

<script>
export default {
  name: "v-Header"
}
</script>

<style lang="scss" scoped>
.block__one {
  background-image: url("../assets/img/bg-one.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  height: 100vh;
}

.header__wrap {
  display: flex;
  justify-content: space-between;

  &-icons_social {
    display: flex;
    align-items: center;
    column-gap: 21px;
    margin-bottom: 82px;

    &_btn {
      background-image: url("../assets/img/icons/ btn.svg");
      background-repeat: no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      width: 194px;
      height: 56.5px;
      cursor: pointer;
      margin-left: 32px;

      font-family: 'NeueMachina  ',sans-serif;
      font-weight: 700;
      font-size: 16px;
      color: var(--main);
    }
  }
}
</style>