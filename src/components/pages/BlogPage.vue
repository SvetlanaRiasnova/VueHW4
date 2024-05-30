<template>
  <div>
    <header class="header container">
      <div class="header__logo">
        <svg
          width="34.000000"
          height="35.000000"
          viewBox="0 0 34 35"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
        >
          <desc>Created with Pixso.</desc>
          <defs />
          <path
            id="Logo"
            d="M0 34L13.45 34L13.45 24.49C13.45 22.48 15.08 20.85 17.1 20.85C19.11 20.85 20.74 22.48 20.74 24.49L20.74 34L33.99 34L33.99 0C15.22 0 0 15.22 0 34Z"
            fill="#CDA274"
            fill-opacity="1.000000"
            fill-rule="nonzero"
          />
        </svg>
        <span class="header__logo_text">Interno</span>
      </div>
      <nav class="header__menu">
        <a href="#" class="header__nav_item">Home</a>
        <a href="#" class="header__nav_item">Project</a>
        <a href="#" class="header__nav_item">Blog</a>
      </nav>
    </header>
    <section class="banner">
      <div class="banner__info">
        <h1 class="banner__info_header">Articles & News</h1>
        <div class="banner__info_breadcrump">Home / Blog</div>
      </div>
    </section>
    <section class="latest__article container">
      <h2 class="latest__article_title">Latest Post</h2>
      <div class="latest__article_wrapper">
        <div class="latest__article_image">
          <img
            class="latest__article_image"
            src="..//../assets/img/last_article.png"
            alt="article picture"
          />
        </div>
        <div class="latest__article_content">
          <h3 class="latest__article_content-header">
            Low Cost Latest Invented Interior Designing Ideas
          </h3>
          <p class="latest__article_content-text">
            Lorem ipsum dolor sit amet, adipiscing Aliquam eu sem vitae turpis
            dignissim maximus.posuere in.Contrary to popular belief.
          </p>
          <p class="latest__article_content-text">
            Lorem Ipsum is not simply random text. It has roots in a piece of
            classica.
          </p>
          <div class="latest__article_bottom-wrap">
            <div class="latest__article_date">22 December,2022</div>
            <button class="latest__article_btn">
              <svg
                width="70.000000"
                height="70.000000"
                viewBox="0 0 70 70"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <desc>Created with Pixso.</desc>
                <defs />
                <circle
                  id="Ellipse"
                  cx="34.000122"
                  cy="35.000000"
                  r="35.000000"
                  fill="#F4F0EC"
                  fill-opacity="1.000000"
                />
                <path
                  id="Vector"
                  d="M31 44L39 35L31 26"
                  stroke="#292F36"
                  stroke-opacity="1.000000"
                  stroke-width="2.000000"
                  stroke-linejoin="round"
                  stroke-linecap="round"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </section>
    <section class="blog container">
      <h2 class="blog__header blogs__title">Articles & News</h2>
      <ArticleComponent :quantity="6"></ArticleComponent>

      <div class="count__page">
        <div class="count__page_wrap">
          <a href="#" class="count__page_number">
            <p class="count__page-number_value">01</p>
          </a>
          <a href="#" class="count__page_number">
            <p class="count__page-number_value">02</p>
          </a>
          <a href="#" class="count__page_number">
            <p class="count__page-number_value">03</p>
          </a>
          <a href="#">
            <svg
              class="count__page_svg"
              width="54.000000"
              height="54.000000"
              viewBox="0 0 70 70"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
            >
              <circle
                id="Ellipse"
                cx="34.000122"
                cy="35.000000"
                r="35.000000"
                fill="#F4F0EC"
                fill-opacity="1.000000"
              />
              <path
                id="Vector"
                d="M31 44L39 35L31 26"
                stroke="#292F36"
                stroke-opacity="1.000000"
                stroke-width="2.000000"
                stroke-linejoin="round"
                stroke-linecap="round"
              />
            </svg>
          </a>
        </div>
      </div>
    </section>
    <footer class="footer container">
      <div class="footer__logo_block">
        <div class="footer__logo">
          <svg
            width="34.000000"
            height="35.000000"
            viewBox="0 0 34 35"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
          >
            <desc>Created with Pixso.</desc>
            <defs />
            <path
              id="Logo"
              d="M0 34L13.45 34L13.45 24.49C13.45 22.48 15.08 20.85 17.1 20.85C19.11 20.85 20.74 22.48 20.74 24.49L20.74 34L33.99 34L33.99 0C15.22 0 0 15.22 0 34Z"
              fill="#CDA274"
              fill-opacity="1.000000"
              fill-rule="nonzero"
            />
          </svg>
          <span class="footer__logo_text">Interno</span>
        </div>
        <p class="footer__text">
          It is a long established fact that a reader will be distracted
          lookings.
        </p>
        <div class="footer__logo_icon">
          <svg
            width="19"
            height="16"
            viewBox="0 0 19 16"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M16.6367 4.59375C17.3398 4.06641 17.9727 3.43359 18.4648 2.69531C17.832 2.97656 17.0938 3.1875 16.3555 3.25781C17.1289 2.80078 17.6914 2.09766 17.9727 1.21875C17.2695 1.64062 16.4609 1.95703 15.6523 2.13281C14.9492 1.39453 14 0.972656 12.9453 0.972656C10.9062 0.972656 9.25391 2.625 9.25391 4.66406C9.25391 4.94531 9.28906 5.22656 9.35938 5.50781C6.30078 5.33203 3.55859 3.85547 1.73047 1.64062C1.41406 2.16797 1.23828 2.80078 1.23828 3.50391C1.23828 4.76953 1.87109 5.89453 2.89062 6.5625C2.29297 6.52734 1.69531 6.38672 1.20312 6.10547V6.14062C1.20312 7.93359 2.46875 9.41016 4.15625 9.76172C3.875 9.83203 3.52344 9.90234 3.20703 9.90234C2.96094 9.90234 2.75 9.86719 2.50391 9.83203C2.96094 11.3086 4.33203 12.3633 5.94922 12.3984C4.68359 13.3828 3.10156 13.9805 1.37891 13.9805C1.0625 13.9805 0.78125 13.9453 0.5 13.9102C2.11719 14.9648 4.05078 15.5625 6.16016 15.5625C12.9453 15.5625 16.6367 9.97266 16.6367 5.08594C16.6367 4.91016 16.6367 4.76953 16.6367 4.59375Z"
              fill="#292F36"
            />
          </svg>
          <svg
            width="17"
            height="16"
            viewBox="0 0 17 16"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M4.14062 16V5.48828H0.871094V16H4.14062ZM2.48828 4.08203C3.54297 4.08203 4.38672 3.20312 4.38672 2.14844C4.38672 1.12891 3.54297 0.285156 2.48828 0.285156C1.46875 0.285156 0.625 1.12891 0.625 2.14844C0.625 3.20312 1.46875 4.08203 2.48828 4.08203ZM16.3398 16H16.375V10.2344C16.375 7.42188 15.7422 5.24219 12.4375 5.24219C10.8555 5.24219 9.80078 6.12109 9.34375 6.92969H9.30859V5.48828H6.17969V16H9.44922V10.7969C9.44922 9.42578 9.69531 8.125 11.3828 8.125C13.0703 8.125 13.1055 9.67188 13.1055 10.9023V16H16.3398Z"
              fill="#292F36"
            />
          </svg>
        </div>
      </div>
      <div class="footer__menu">
        <p class="footer__menu_title">Pages</p>
        <a class="footer__menu_link" href="index.html">Home</a>
        <a class="footer__menu_link" href="#">Project</a>
        <a class="footer__menu_link" href="#">Blog</a>
      </div>
      <div class="footer__contact">
        <p class="footer__contact_title">Contact</p>
        <p class="footer__contact_text">
          55 East Birchwood Ave. Brooklyn, New York 11201
        </p>
        <p class="footer__contact_text-email">contact@interno.com</p>
        <p class="footer__contact_text">(123) 456 - 7890</p>
      </div>
    </footer>
  </div>
</template>

<script>
import ArticleComponent from "../ArticleComponent.vue";
export default {
  name: "BlogPage",
  components: {
    ArticleComponent,
  },
  data() {
    return {};
  },
  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped>
$familyTitle: "DM Serif Display", serif;
$familyText: "Jost", sans-serif;
$headerColor: #292f36;
$textColor: #4d5053;

@mixin flexCenter {
  display: flex;
  justify-content: center;
  align-items: center;
}

@mixin logoImage {
  display: flex;
  align-items: center;
  gap: 10px;
}

@mixin logoText {
  font-family: $familyTitle;
  font-size: 40px;
  font-weight: 400;
  color: $headerColor;
}

@mixin h2Style {
  font-family: $familyTitle;
  color: $headerColor;
  font-size: 50px;
  font-weight: 400;
  line-height: 62.5px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: $familyText;
  color: $textColor;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.banner {
  background-image: url("..//../assets/img/Banner.png");
  min-height: 356px;
  @include flexCenter;
  align-items: flex-end;

  &__info {
    text-align: center;
    background-color: #fff;
    padding: 41px;
    border-radius: 37px 37px 0px 0px;

    &_header {
      @include h2Style;
      text-align: left;
    }

    &_breadcrump {
      font-size: 22px;
      font-weight: 400;
      line-height: 33px;
    }
  }
}

.latest__article {
  padding-top: 150px;

  &_wrapper {
    border: 1px solid #e7e7e7;
    display: flex;
    gap: 62px;
    padding: 22px;
    border-radius: 62px;
    align-items: center;
  }

  &_title {
    margin-bottom: 30px;
    @include h2Style;
  }

  &_image {
    max-width: 569px;
    border-radius: 50px;
  }

  &_content {
    min-height: 478px;
    padding-top: 51px;

    &-header {
      font-family: $familyTitle;
      color: $headerColor;
      font-size: 25px;
    }

    &-text {
      padding-top: 22px;
      margin-bottom: 41px;
      font-size: 22px;
      font-style: normal;
      font-weight: 400;
      line-height: 150%;
    }
  }

  &_bottom-wrap {
    padding-top: 30px;
    width: 489px;
    @include flexCenter;
    flex-wrap: nowrap;
    justify-content: space-between;
  }

  &_btn {
    width: 52px;
    background-color: inherit;
    border: none;

    &svg circle {
      width: 52px;
      cursor: pointer;
    }
  }
}
//blog
.blog {
  margin-top: 96px;

  &__header {
    font-family: $familyTitle;
    color: $headerColor;
    font-size: 50px;
    font-weight: 400;
    line-height: 125%;
    text-align: center;
  }

  &__description {
    width: 810px;
    margin: 0 auto;
    font-size: 22px;
    font-weight: 400;
    line-height: 150%;
    text-align: center;
  }

  &__articles {
    padding-top: 52px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 27px;

    &_back {
      padding: 21px;
      width: 382px;
      @include flexCenter;
      flex-direction: column;
      box-sizing: border-box;
      border: 1px solid rgb(231, 231, 231);
      border-radius: 62px;
      box-shadow: 0px 10px 30px 0px rgba(255, 255, 255, 0.25);

      &:hover {
        background: #f4f0ec;
      }
    }
  }

  &__articles_header {
    position: absolute;
    @include flexCenter;
    margin: 0;
    width: 129px;
    height: 41px;
    transform: translate(10%, -160%);
    font-size: 16px;
    font-weight: 400;
    line-height: 150%;
    text-transform: capitalize;
    background-color: #ffffff;
    border-radius: 8px 8px 8px 0px;
  }

  &__title {
    margin: 0;
    padding-top: 21px;
    padding-right: 60px;
    width: 80%;
    font-family: $familyTitle;
    color: $headerColor;
    font-size: 25px;
    font-weight: 400;
    line-height: 125%;
    text-align: left;
  }

  &__articles_bottom {
    padding-top: 30px;
    width: 340px;
    @include flexCenter;
    flex-wrap: nowrap;
    justify-content: space-between;
  }

  &__articles_btn {
    background-color: inherit;
    border: none;

    & svg circle:hover {
      fill: #ffffff;
    }
  }
}
.blogs__title {
  text-align: left;
}

.blog_page {
  flex-wrap: wrap;
}

.count__page {
  margin-top: 51px;
  padding-bottom: 200px;
  display: flex;
  justify-content: center;

  &_wrap {
    display: flex;
    gap: 20px;
  }

  &_number {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: nowrap;
    border: 1px #cda274 solid;
    width: 52px;
    height: 52px;
    border-radius: 52px;
    text-decoration: none;

    &_value {
      font-size: 16px;
      font-style: normal;
      font-weight: 500;
      line-height: 24px;
      text-transform: capitalize;
    }

    &:hover {
      background: #f4f0ec;
      border: none;
      width: 54px;
      height: 54px;
    }
  }

  & circle#Elips:hover {
    fill: #f4f0ec;

    & circle {
      stroke: none;
    }
  }
}

.footer__blog {
  padding-top: 0;
}
</style>
