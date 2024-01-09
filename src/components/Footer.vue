<template>
  <footer class="footer">
    <div class="container">
      <div class="footer__inner">
        <div class="footer__info">
          <img
            src="../assets/icons/logo.svg"
            alt="logo"
            class="footer__info-logo"
          />
          <p class="footer__info-desc">
            Our Customer Due Diligence platform helps you avoid fines or losing
            clients due to AML while protecting you from cybercrime.
          </p>
          <div class="footer__info-provider">
            <p class="footer__info-provider-title">Approved Service Provider</p>
            <img
              src="../assets/images/provider.jpg"
              class="footer__info-provider-img"
            />
          </div>
          <div class="footer__info-partnership">
            <p class="footer__info-partnership-title">
              Approved Service Provider
            </p>
            <img
              src="../assets/icons/partnership.svg"
              class="footer__info-partnership-img"
            />
          </div>
          <div class="footer__info-register">
            Registered with the Information Commissioner's Office (ICO)
            Registration number: ZA679248
          </div>
          <div class="footer__info-copyright">© Arc-Pay Ltd 2021</div>
        </div>
        <div class="footer__links">
          <ul class="footer__links-links">
            <li class="footer__links-title">Links</li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Home</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">About us</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Why arcarta</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Success Stories</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">FAQ's</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Contact Us</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Join</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Invite</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Compliance Quiz</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">ID Document Quiz</a>
            </li>
          </ul>
          <ul class="footer__links-solutions">
            <li class="footer__links-title">Solutions</li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">For Galleries</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">For Galleries</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">For Auctioneers</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">For Secure Payments</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">For Buyers & Collectors</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Online AML Training</a>
            </li>
          </ul>
          <ul class="footer__links-resources">
            <li class="footer__links-title">Resources</li>

            <li class="footer__links-item">
              <a href="" class="footer__links-link">Articles</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Resources</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Help Centre</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">The Bigger Picture</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Login</a>
            </li>
            <li class="footer__links-item">
              <a href="" class="footer__links-link">Brand Assets</a>
            </li>
            <li class="footer__links-item footer__links-new">
              <a href="" class="footer__links-link">The Art Market Report</a>
            </li>
          </ul>
        </div>
        <div class="footer__socials">
          <img
            src="../assets/images/social-img.png"
            alt=""
            class="footer__socials-img"
          />
          <ul class="footer__socials-links">
            <li class="footer__socials-item">Privacy & Terms</li>
            <li class="footer__socials-item">
              <a href="" class="footer__socials-link">
                <img
                  src="../assets/icons/twitter.svg"
                  class="footer__socials-icon"
                />
              </a>
            </li>
            <li class="footer__socials-item">
              <a href="" class="footer__socials-link">
                <img
                  src="../assets/icons/instagram.svg"
                  class="footer__socials-icon"
                />
              </a>
            </li>
            <li class="footer__socials-item">
              <a href="" class="footer__socials-link">
                <img
                  src="../assets/icons/youtube.svg"
                  class="footer__socials-icon"
                />
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script setup></script>
<style lang="sass">
.footer
  &__inner
    display: grid
    grid-template-columns: 340px
    gap: 35px
    padding: 0 10px 80px

  &__info
    width: 340px

    &-logo
      width: 150px
      height: 30px
      margin-bottom: 19px

    &-desc
      font-size: 13px
      line-height: 20px
      margin-bottom: 30px

    &-provider
      margin-bottom: 29px
      &-title
        font-size: 13px
        font-weight: 500
        line-height: 20px
        margin-bottom: 10px

    &-partnership
      margin-bottom: 20px
      &-title
        font-size: 12px
        font-weight: 500
        line-height: 20px
        margin-bottom: 10px

    &-register
      font-size: 13px
      line-height: 20px
      color: #D3D3D3
      margin-bottom: 20px

    &-copyright
      font-size: 13px
      line-height: 20px
      color: #D3D3D3

  &__links
    display: flex
    justify-content: flex-end
    gap: 108px

    &-title
      font-size: 12px
      font-weight: 500
      line-height: 20px
      margin-bottom: 12px
      color: #333

    &-item
      margin-bottom: 7px

    &-link
      font-size: 13px
      line-height: 20px
      color: #313131

    &-new
      &::after
        content: 'New'
        font-size: 11px
        font-weight: 700
        line-height: 21px
        display: inline-block
        background: #F9A28F
        padding: 1px 14px
        border-radius: 20px
        color: #fff
        margin-left: 8px

  &__socials
    grid-column: span 2
    display: flex
    justify-content: space-between
    align-items: flex-end

    &-links
      display: flex
      align-items: flex-end

    &-item
      margin-left: 10px
      &:first-child
        margin-right: 5px
        color: #D3D3D3
        font-size: 13px
        line-height: 20px
</style>
