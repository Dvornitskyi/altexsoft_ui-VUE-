<template>
  <div class="footer">
    <div class="footer__section">
      <div class="footer__first-collum">
        <h3 class="footer__title">Company Details</h3>
        <hr class="footer__hr" />
        <ul class="footer__first-first-list">
          <li class="footer__first-text">Company Name</li>
          <li class="footer__first-text">Street & Name Number</li>
          <li class="footer__first-text">Town</li>
          <li class="footer__first-text">Postcode/Zip</li>
        </ul>
        <ul class="footer__first-second-list">
          <li class="footer__first-text">Tel: xxxxx xxxxxxxxxx</li>
          <li class="footer__first-text">Fax: xxxxx xxxxxxxxxx</li>
          <li class="footer__first-text">
            Email:<a href="#" class="footer__first-link"
              >>contact@mydomain.com</a
            >
          </li>
        </ul>
        <ul class="footer__first-third-list">
          <li class="footer__first-text subtitle">Office Hours</li>
          <li class="footer__first-text">Monday - Friday: 08:00 - 17:30</li>
          <li class="footer__first-text">Saturday: 08:00 - 13:00</li>
        </ul>
      </div>
      <div class="footer__second-collum">
        <h3 class="footer__title">Stay Social</h3>
        <hr class="footer__hr second-hr" />
        <div class="footer__second-area">
          <a class="footer__second-icon" href="#"
            ><i class="fab fa-linkedin-in"></i
          ></a>
          <a class="footer__second-link" href="#">Get linked up in LinkedIn</a>
        </div>
        <hr class="footer__hr" />
        <div class="footer__second-area">
          <a class="footer__second-icon" href="#"
            ><i class="fab fa-twitter"></i
          ></a>
          <a class="footer__second-link" href="#">Keep up with our Tweets</a>
        </div>
        <hr class="footer__hr" />
        <div class="footer__second-area">
          <a class="footer__second-icon" href="#"
            ><i class="fab fa-pinterest"></i
          ></a>
          <a class="footer__second-link" href="#">Photos on Pinterest</a>
        </div>
        <hr class="footer__hr" />
        <div class="footer__second-area">
          <a class="footer__second-icon" href="#"><i class="fas fa-rss"></i></a>
          <a class="footer__second-link" href="#">Photos on Pinterest</a>
        </div>
        <hr class="footer__hr" />
      </div>
      <div class="footer__third-collum">
        <h3 class="footer__title">From The Blog</h3>
        <hr class="footer__hr" />
        <div class="footer__third-area">
          <h5 class="footer__third-subtitle">Blog Post Title</h5>
          <p class="footer__third-text">Posted by Admin on 00.00.0000</p>
          <p class="footer__third-subtext">
            Vestibulumaccumsan egestibulum eu justo convallis augue estas aenean
            elit intesque sed facilispede estibulum.
          </p>
          <a class="footer__third-link" href="">Read More »</a>
        </div>
        <div class="footer__third-area">
          <h5 class="footer__third-subtitle">Blog Post Title</h5>
          <p class="footer__third-text">Posted by Admin on 00.00.0000</p>
          <p class="footer__third-subtext">
            Vestibulumaccumsan egestibulum eu justo convallis augue estas aenean
            elit intesque sed facilispede estibulum.
          </p>
          <a class="footer__third-link" href="">Read More »</a>
        </div>
      </div>
      <div class="footer__fourth-collum">
        <h3 class="footer__title">Contact Us</h3>
        <hr class="footer__hr" />
        <form action="#" class="footer__fourth-area">
          <input class="footer__fourth-name" type="text" placeholder="Name" />
          <input
            class="footer__fourth-email"
            type="email"
            placeholder="Email"
          />
          <textarea
            class="footer__fourth-message"
            name="text"
            placeholder="Message"
          ></textarea>
          <input class="footer__fourth-submit" type="submit" value="SUBMIT" />
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheFooter",
};
</script>

<style lang="scss">
.footer {
  max-width: 1200px;
  width: 100%;
  height: 380px;
  background: #313131;
  display: flex;
  justify-content: center;
  margin: 0 auto 0 auto;
  &__section {
    max-width: 1200px;
    width: 96.666%;
    height: 380px;
    display: flex;
    justify-content: space-between;
    padding-top: 40px;
  }
  &__first-collum {
    width: 226px;
    height: 264px;
  }
  .footer__title {
    color: #ffffff;
    font-size: 16px;
    margin-bottom: 15px;
  }
  &__hr {
    background-color: #3a3a3a;
    color: #3a3a3a;
    border: none;
    opacity: 11;
    height: 2px;
    border: 0px solid #3a3a3a;
    // margin-bottom: 20px;
  }
  &__first-first-list {
    margin-bottom: 20px;
    margin-top: 20px;
  }
  &__first-text {
    color: #999999;
    font-size: 12px;
    margin-bottom: 5px;
  }
  &__first-link {
    color: #a7c353;
    font-size: 12px;
  }
  &__first-second-list {
    margin-bottom: 20px;
  }
  &__second-collum {
    width: 226px;
    height: 251px;
  }
  &__second-area {
    margin-top: 12px;
  }
  &__second-icon {
    border: 8px solid #383838;
    border-radius: 50%;
    background-color: #383838;
    color: #ffffff;
    margin-bottom: 6px;
  }
  &__second-link {
    color: #a7c353;
    font-size: 12px;
    margin-left: 11px;
  }
  &__third-collum {
    width: 226px;
    height: 307px;
  }

  &__third-subtitle {
    color: #999999;
    font-size: 13px;
    margin-top: 20px;
    margin-bottom: 6px;
  }
  &__third-text {
    color: #999999;
    font-size: 11px;
    margin-bottom: 7px;
  }
  &__third-subtext {
    color: #999999;
    font-size: 12px;
    margin-bottom: 15px;
  }
  &__third-link {
    color: #a7c353;
    font-size: 12px;
    margin-left: 155px;
  }
  &__fourth-collum {
    width: 226px;
    height: 284px;
  }
  &__fourth-name {
    margin-top: 20px;
    background-color: #383838;
    width: 226px;
    height: 32px;
    border: none;
    border-radius: 5px;
    margin-bottom: 10px;
    padding-left: 10px;
  }
  &__fourth-email {
    background-color: #383838;
    width: 226px;
    height: 32px;
    border: none;
    border-radius: 5px;
    margin-bottom: 10px;
    padding-left: 10px;
  }
  &__fourth-message {
    background-color: #383838;
    width: 226px;
    height: 111px;
    border: none;
    border-radius: 5px;
    margin-bottom: 10px;
    padding-left: 10px;
    padding-top: 10px;
    resize: none;
  }
  &__fourth-submit {
    background-color: #a7c353;
    width: 81px;
    height: 36px;
    border: none;
    border-radius: 5px;
    font-size: 13px;
    font-weight: 600;
    cursor: pointer;
  }
}
@media (max-width: 500px) {
  .footer {
    overflow: hidden;
    overflow-x: hidden;
    max-width: 500px;
    // width: 320px;
    height: 1350px;
    background: #313131;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 0 auto;
    &__section {
      width: 300px;
      height: 1350px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      // padding-top: 40px;
    }
    &__first-collum {
      margin-bottom: 50px;
    }
    &__second-collum {
      margin-bottom: 50px;
    }
    &__third-collum {
      margin-bottom: 50px;
    }
    &__fourth-collum {
      margin-bottom: 50px;
    }
    &__title {
      text-align: center;
    }
    &__fourth-submit {
      width: 226px;
    }
  }
}
</style>
