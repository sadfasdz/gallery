<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <img src="../assets/icons/logo.svg" alt="logo" class="header__logo" />
        <nav class="header__nav">
          <ul class="header__nav-list">
            <li class="header__nav-item">
              <a href="" class="header__nav-link">What is arcarta?</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">Solutions</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">Resources</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">FAQs</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">Contact</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">Login</a>
            </li>
            <li class="header__nav-item">
              <a href="" class="header__nav-link">Get Started</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script setup></script>
<style lang="sass" scoped>

.header
  background-color: #FFF8EE

  &__inner
    display: flex
    justify-content: space-between
    align-items: center
    padding: 33px 0

  &__nav-list
    display: flex
    gap: 43px
    align-items: center

  &__nav-item
    a
      font-weight: 700
      line-height: 20px

  &__nav-item:last-child
    a
      padding: 13px 28px
      background-color: #C47344
      border-radius: 50px
      color: white
</style>
