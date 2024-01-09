<template>
  <div class="main">
    <div class="container">
      <div class="welcome">
        <div class="welcome__new"></div>
        <h2 class="welcome__title">Rely on us</h2>
        <p class="welcome__description">
          Our Customer Due Diligence platform helps you avoid fines or losing
          clients due to AML while protecting you from cybercrime.
        </p>
        <a href="" class="welcome__link">Learn More</a>
      </div>

      <div class="partners">
        <ul class="partners__list">
          <li class="partners__item">
            <img
              src="../assets/images/COLNAGHI.png"
              alt=""
              class="partners__item-img"
            />
          </li>
          <li class="partners__item">
            <img
              src="../assets/images/luximburg+co.png"
              alt=""
              class="partners__item-img"
            />
          </li>
          <li class="partners__item">
            <img
              src="../assets/images/Tomaso.png"
              alt=""
              class="partners__item-img"
            />
          </li>
          <li class="partners__item">
            <img
              src="../assets/images/crestia Roberts.png"
              alt=""
              class="partners__item-img"
            />
          </li>
        </ul>
        <a href="" class="partners__link">What is arcarta?</a>
      </div>

      <img
        src="../assets/images/Gallery.png"
        alt="gallery-img"
        class="gallery-img"
      />

      <div class="forwhom">
        <ul class="forwhom__list">
          <li class="forwhom__item">
            <img
              src="../assets/images/dealers.png"
              alt=""
              class="forwhom__item-img"
            />
            <h5 class="forwhom__item-title">For Art Dealers</h5>
            <p class="forwhom__item-desc">
              Galleries and independent art dealers
            </p>
            <a href="" class="forwhom__item-link">Learn More</a>
          </li>
          <li class="forwhom__item">
            <img
              src="../assets/images/advisors.png"
              alt=""
              class="forwhom__item-img"
            />
            <h5 class="forwhom__item-title">For Advisors</h5>
            <p class="forwhom__item-desc">Advisors, agents and consultants</p>
            <a href="" class="forwhom__item-link">Learn More</a>
          </li>
          <li class="forwhom__item">
            <img
              src="../assets/images/auctioneers.png"
              alt=""
              class="forwhom__item-img"
            />
            <h5 class="forwhom__item-title">For Auctioneers</h5>
            <p class="forwhom__item-desc">Online and offline auctioneers</p>
            <a href="" class="forwhom__item-link">Learn More</a>
          </li>
          <li class="forwhom__item">
            <img
              src="../assets/images/buyers.png"
              alt=""
              class="forwhom__item-img"
            />
            <h5 class="forwhom__item-title">For Buyers & Collectors</h5>
            <p class="forwhom__item-desc">
              Receiving Invoices, making card payments and sending your ID and
              address documents
            </p>
            <a href="" class="forwhom__item-link">Learn More</a>
          </li>
        </ul>
      </div>

      <Quiz />
      <div class="newsletter">
        <img
          src="../assets/icons/newsletter-img.png"
          alt="gallery"
          class="newsletter__img"
        />
        <div class="newsletter__info">
          <h3 class="newsletter__info-title">Art world insight.</h3>
          <p class="newsletter__info-description">
            Receive our newsletter direct to your inbox to follow updates to
            legislation and the EU art-market's response.
          </p>
          <form action="" class="newsletter__form">
            <input
              type="text"
              class="newsletter__form-inp"
              placeholder="Your email"
            />
            <button class="newsletter__form-btn"></button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import Quiz from "./Quiz.vue";
</script>
<style lang="sass" scoped>
.main
  flex-grow: 1
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.00) 0%, #FFF 100%), #FFF8EE

.welcome
  width: 524px
  margin: 0 auto
  text-align: center
  margin-bottom: 52px
  &__title
    font-size: 110px
    font-weight: 700
    line-height: 119px
    margin-bottom: 28px

  &__description
    font-size: 21px
    font-weight: 500
    line-height: 33px
    margin-bottom: 20px

  &__link
    font-weight: 700
    color: #fff
    font-size: 16px
    line-height: 28px
    padding: 14px 31px
    border-radius: 50px
    background: rgba(196, 115, 68, 1)
    display: inline-block
    width: 158px

.partners
  display: flex
  flex-direction: column
  gap: 30px
  justify-content: center
  align-items: center
  margin-bottom: 100px

  &__list
    display: flex
    gap: 40px

  &__item-img
    max-width: 255px
    width: 100%

  &__link
    color: #C47344
    font-size: 16px
    font-weight: 700
    line-height: 20px
    position: relative
    padding-right: 27px
    &::after
      content: ''
      position: absolute
      width: 20px
      height: 20px
      background-image: url('../assets/icons/brownArrowRight.png')
      display: inline-block
      right: 0

.gallery-img
  max-width: 1440px
  width: 100%
  margin-bottom: 133px

.forwhom
  margin-bottom: 177px
  &__list
    display: grid
    grid-template-columns: repeat(2, minmax(auto, 100%))
    gap: 30px
    justify-content: center

  &__item
    padding: 51px 40px 34px
    text-align: center
    border-radius: 10px
    border: 1px solid #DDD
    background: #FFFAF2
    box-shadow: 1px 1px 20px 0px rgba(0, 0, 0, 0.08)
    max-width: 497px
    width: 100%

    &:nth-child(2n)
      justify-self: self-start

    &:nth-child(2n+1)
      justify-self: self-end

    &-img
      margin-bottom: 26px

    &-title
      font-size: 42px
      font-weight: 700
      line-height: 52px
      margin-bottom: 16px

    &-desc
      font-size: 16px
      font-weight: 500
      line-height: 28px
      margin-bottom: 23px

    &-link
      font-size: 15px
      font-weight: 700
      line-height: 20px
      padding: 12px 37px 16px
      border: 2px solid #E1DED9
      display: inline-block
      border-radius: 50px

.newsletter
  display: flex
  align-items: center
  gap: 51px
  padding: 44px 60px
  background-color: #FAF7F3
  border-radius: 10px
  max-width: 1200px
  width: 100%
  margin: 0 auto
  margin-bottom: 146px

  &__info
    width: 544px

    &-title
      font-size: 40px
      font-weight: 700
      line-height: 54px
      margin-bottom: 24px

    &-description
      font-size: 20px
      font-weight: 500
      line-height: 32px
      margin-bottom: 31px

  &__form
    width: 360px
    position: relative

    &-inp
      width: 100%
      padding: 12px 50px 11px 31px
      font-size: 20px
      font-weight: 500
      line-height: 32px
      border-radius: 10px
      &::placeholder
        color: red

    &-btn
      background-image: url('../assets/icons/arrowWithBlackBack.svg')
      width: 29px
      height: 29px
      position: absolute
      top: 14px
      right: 9px
</style>
