<template>
  <div class="quiz">
    <div class="quiz__card">
      <div class="quiz__card-num">01</div>
      <img
        src="../assets/icons/laptop.png"
        alt="laptop"
        class="quiz__card-img"
      />
      <h3 class="quiz__card-title">Compliance Quiz</h3>
      <a href="" class="quiz__card-link">Begin</a>
    </div>
    <div class="quiz__info">
      <div class="quiz__info-new">New</div>
      <h3 class="quiz__info-title">Does Anti-money Laundering affect you?</h3>
      <p class="quiz__info-text">
        A short, interactive quiz to check if your art business is affected by
        5AMLD regulation.
      </p>
      <a href="" class="quiz__info-link">Take the Quiz</a>
    </div>
  </div>
</template>
<script setup></script>
<style lang="sass">
.quiz
  display: flex
  justify-content: center
  align-items: center
  gap: 85px
  padding-top: 21px
  margin-bottom: 135px

  &__card
    padding: 20px 25px
    width:220px
    border-radius: 10px
    height: 260px
    background-color: #32686F
    box-shadow: 1px 1px 12px 0px rgba(0, 0, 0, 0.55)
    position: relative
    z-index: 1


    &::after
      position: absolute
      content: ''
      left: -8px
      top: 8px
      width:100%
      border-radius: 10px
      height: 100%
      background-color: #32686F
      box-shadow: 1px 1px 12px 0px rgba(0, 0, 0, 0.55)
      z-index: -1

    &-num
      color: rgba(255, 255, 255, 1)
      margin-bottom: 23px

    &-img
      margin-bottom: 12px

    &-title
      font-size: 28px
      font-weight: 700
      line-height: 32px
      color: #FFF
      margin-bottom: 33px

    &-link
      border-top: 1px solid rgba(255, 255, 255, 0.18)
      padding-top: 9px
      color:  rgba(255, 255, 255, 1) !important
      font-weight: 500
      display: block
      width: 100%
      position: relative
      &::after
        content: ''
        position: absolute
        width: 20px
        height: 20px
        right: 0
        background-image: url('../assets/icons/arrowRight.svg')

  &__info
    width:465px

    &-new
      padding: 0 14px
      background: #F9A28F
      border-radius: 20px
      margin-bottom: 18px
      width: 54px
      height: 25px
      color: #fff
      font-size: 12px
      font-weight: 700
      line-height: 25px

    &-title
      font-size: 53px
      font-weight: 700
      margin-bottom: 25px

    &-text
      font-size: 21px
      font-weight: 500
      line-height: 33px
      margin-bottom: 23px

    &-link
      padding:11px 27px 16px
      border:2px solid #E1DED9
      border-radius: 50px
      font-size: 15px
      font-weight: 700
      display: inline-block
</style>
