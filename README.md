<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Verlocity</title>
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
      integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
      crossorigin="anonymous"
    />
    <script
      src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
      integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
      integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
      integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
      crossorigin="anonymous"
    ></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="home.css" />
  </head>
  <body>
    <div class="header">
      <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
          <a class="navbar-brand logo" href="#">
            <h1 class="logo--title scroll">Velocity</h1>
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="header--menu navbar-nav ml-auto">
              <li class="nav-item active">
                <a class="nav-link" href="#"
                  >Home <span class="sr-only">(current)</span></a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Pricing</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="navbarDropdownMenuLink"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  Pages
                </a>
                <div
                  class="dropdown-menu"
                  aria-labelledby="navbarDropdownMenuLink"
                >
                  <a class="dropdown-item" href="#">Action</a>
                  <a class="dropdown-item" href="#">Another action</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                </div>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#"
                  >Login <span class="sr-only">(current)</span></a
                >
              </li>
              <li class="nav-item active">
                <a class="nav-link btn btn-outline-secondary" href="#"
                  >Sign up free <span class="sr-only">(current)</span></a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
    <!--End header -->
    <div class="slider">
      <div
        id="carouselExampleIndicators"
        class="carousel slide"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="carousel-caption d-xs-block d-sm-block d-md-block">
              <h5>
                Let's get your product online fast and get attention right away!
              </h5>
              <p>
                Velocity is a Bootstrap 5 template designed to help you promote
                your product effectively to your target users
              </p>
              <div class="try-btn btn btn-primary">Try Velocity for Free</div>
              <a href="" class="youtube-video">
                <i class="fa-brands fa-youtube"></i> Watch The video
              </a>
            </div>

            <img
              class="d-block w-100 slider-thumb"
              src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/background/bg-header-1.jpg"
              alt="First slide"
            />
          </div>
          <div class="carousel-item">
            <div class="carousel-caption d-none d-md-block">
              <h5>
                Let's get your product online fast and get attention right away!
              </h5>
              <p>
                Velocity is a Bootstrap 5 template designed to help you promote
                your product effectively to your target users
              </p>
              <div class="try-btn btn btn-primary text-capitalize">
                Try Velocity for Free
              </div>
              <a href="" class="youtube-video">
                <i class="fa-brands fa-youtube"></i> Watch The video
              </a>
            </div>
            <img
              class="d-block w-100 slider-thumb"
              src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/background/bg-header-2.jpg"
              alt="Second slide"
            />
          </div>
          <div class="carousel-item">
            <div class="carousel-caption d-none d-md-block">
              <h5>
                Let's get your product online fast and get attention right away!
              </h5>
              <p>
                Velocity is a Bootstrap 5 template designed to help you promote
                your product effectively to your target users
              </p>
              <div class="try-btn btn btn-primary">Try Velocity for Free</div>
              <a href="" class="youtube-video">
                <i class="fa-brands fa-youtube"></i> Watch The video
              </a>
            </div>
            <img
              class="d-block w-100 slider-thumb"
              src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/background/bg-header-3.jpg"
              alt="Third slide"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- End slider -->
    <div class="content">
      <div class="why">
        <div class="container">
          <h1 class="why--title text-center">How Can Velocity Help You?</h1>
          <p class="why--description text-center">
            We take care of the UX and front-end design so you can save time
            building your site
          </p>
        </div>
        <div class="why--content">
          <div class="container">
            <div class="evidence">
              <div class="row">
                <div class="col-lg-4">
                  <h1
                    class="evidence--title text-sm-center text-lg-left text-xs-center"
                  >
                    Save you time and effort
                  </h1>
                  <div class="evidence--description">
                    <p class="">
                      Explain one of your product benefits here. Let users know
                      how they can benefit using your product. It’s also a good
                      idea to back it up with a testimonial or tweet from your
                      users.
                    </p>
                    <p class="">
                      The original PSD of the graphic is included in the
                      package. You can easily customise the PSD to meet your
                      needs.
                    </p>
                  </div>

                  <div class="evidence--quote mb-sm-5 mb-xs-5">
                    <div class="quote--profile">
                      <img
                        src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-s-1.png"
                        alt=""
                        class="profile--thumb img-fluid"
                      />
                    </div>
                    <div class="quote--content">
                      <p class="quote--content--inform">
                        <a href="" class="quote--link">@velocity</a> Love it!
                        Thank you for making my life easier and saving me time!
                        I’ll definitely recommend it to my friends. :)
                      </p>
                      <p class="quote--source">@LisaW, New York</p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-7 offset-lg-1">
                  <img
                    class="evidence--thumb ml-auto img-fluid"
                    src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/figures/figure-1.png"
                    alt=""
                  />
                  <p class="thumb--caption text-center">
                    (Screenshot: Coral - App & website startup kit)
                  </p>
                </div>
              </div>
            </div>
            <div class="evidence">
              <div class="row">
                <div class="col-lg-4">
                  <h1
                    class="evidence--title text-sm-center text-lg-left text-xs-center"
                  >
                    Works across all devices
                  </h1>
                  <div class="evidence--description">
                    <p class="">
                      Explain one of your product benefits here. Let users know
                      how they can benefit using your product. It’s also a good
                      idea to back it up with a testimonial or tweet from your
                      users.
                    </p>
                    <p class="">
                      The original PSD of the graphic is included in the
                      package. You can easily customise the PSD to meet your
                      needs.
                    </p>
                  </div>

                  <div class="evidence--quote mb-sm-5 mb-xs-5">
                    <!-- <div class="row"> -->
                    <div class="quote--profile">
                      <img
                        src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-s-2.png"
                        alt=""
                        class="profile--thumb img-fluid"
                      />
                    </div>
                    <div class="quote--content">
                      <p class="quote--content--inform">
                        I find the mobile app very useful when I'm on the go.
                        Sed ut perspiciatis unde omnis iste natus error sit
                        voluptatem
                      </p>
                      <p class="quote--source">@JackT, San Francisco</p>
                    </div>
                    <!-- </div> -->
                  </div>
                </div>
                <div class="col-lg-8">
                  <div class="evidence--thumb position-relative">
                    <img
                      class="evidence--thumb ml-auto img-fluid"
                      src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/figures/figure-2.png"
                      alt=""
                    />
                    <a href="" class="youtube-icon youtube-video"
                      ><i class="fa-regular fa-circle-play"></i
                    ></a>
                  </div>

                  <p class="thumb--caption text-center">
                    (Screenshot: Coral - App & website startup kit)
                  </p>
                </div>
              </div>
            </div>
            <div class="evidence">
              <div class="row">
                <div class="col-lg-4">
                  <h1
                    class="evidence--title text-sm-center text-lg-left text-xs-center"
                  >
                    Works across all devices
                  </h1>
                  <div class="evidence--description">
                    <p class="">
                      Explain one of your product benefits here. Let users know
                      how they can benefit using your product. It’s also a good
                      idea to back it up with a testimonial or tweet from your
                      users.
                    </p>
                    <p class="">
                      The original PSD of the graphic is included in the
                      package. You can easily customise the PSD to meet your
                      needs.
                    </p>
                  </div>

                  <div class="evidence--quote mb-sm-5 mb-xs-5">
                    <!-- <div class="row"> -->
                    <div class="quote--profile">
                      <img
                        src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-s-3.png"
                        alt=""
                        class="profile--thumb img-fluid"
                      />
                    </div>
                    <div class="quote--content">
                      <p class="quote--content--inform">
                        I find the mobile app very useful when I'm on the go.
                        Sed ut perspiciatis unde omnis iste natus error sit
                        voluptatem
                      </p>
                      <p class="quote--source">@JackT, San Francisco</p>
                    </div>
                    <!-- </div> -->
                  </div>
                </div>
                <div class="col-lg-8">
                  <img
                    class="evidence--thumb ml-auto img-fluid"
                    src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/figures/figure-3.png"
                    alt=""
                  />
                  <p class="thumb--caption text-center">
                    (Screenshot: Coral - App & website startup kit)
                  </p>
                </div>
              </div>
            </div>
            <div class="evidence">
              <div class="row">
                <div class="col-lg-4">
                  <h1
                    class="evidence--title text-sm-center text-lg-left text-xs-center"
                  >
                    Works across all devices
                  </h1>
                  <div class="evidence--description">
                    <p class="">
                      Explain one of your product benefits here. Let users know
                      how they can benefit using your product. It’s also a good
                      idea to back it up with a testimonial or tweet from your
                      users.
                    </p>
                    <p class="">
                      The original PSD of the graphic is included in the
                      package. You can easily customise the PSD to meet your
                      needs.
                    </p>
                  </div>

                  <div class="evidence--quote mb-sm-5 mb-xs-5">
                    <!-- <div class="row"> -->
                    <div class="quote--profile">
                      <img
                        src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-s-4.png"
                        alt=""
                        class="profile--thumb img-fluid"
                      />
                    </div>
                    <div class="quote--content">
                      <p class="quote--content--inform">
                        I find the mobile app very useful when I'm on the go.
                        Sed ut perspiciatis unde omnis iste natus error sit
                        voluptatem
                      </p>
                      <p class="quote--source">@JackT, San Francisco</p>
                    </div>
                    <!-- </div> -->
                  </div>
                </div>
                <div class="col-lg-8">
                  <img
                    class="evidence--thumb ml-auto img-fluid"
                    src=" https://themes.3rdwavemedia.com/velocity/bs5/assets/images/figures/figure-4.png"
                    alt=""
                  />
                  <p class="thumb--caption text-center">
                    (Screenshot: Coral - App & website startup kit)
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="featured text-center">
          <h1 class="featured--title">Want to discover all the features?</h1>
          <a href="" class="featured--btn btn btn-outline-danger"
            >Take a Tour</a
          >
        </div>
      </div>
      <div class="about-us">
        <div class="container">
          <h1 class="about-us--title text-center">
            What are people saying about Velocity?
          </h1>
          <div class="about-us--content">
            <div
              id="carouselExampleIndicators"
              class="carousel slide"
              data-ride="carousel"
            >
              <ol class="carousel-indicators caros">
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="0"
                  class="active"
                ></li>
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="1"
                ></li>
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="2"
                ></li>
              </ol>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <div class="person-profile">
                    <img
                      src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-m-1.png"
                      alt=""
                      class="thumb-profile"
                    />
                  </div>
                  <div class="comment-inform">
                    <p class="comment">
                      At vero eos et accusamus et iusto odio dignissimos ducimus
                      qui blanditiis praesentium voluptatum deleniti atque
                      corrupti quos dolores et quas molestias excepturi sint.
                    </p>
                    <p class="name-person">Diana Luna</p>
                    <p class="position-person">Entrepreneur, Maecenas</p>
                  </div>
                </div>
                <div class="carousel-item">
                  <div class="person-profile">
                    <img
                      src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-m-2.png"
                      alt=""
                      class="thumb-profile"
                    />
                  </div>
                  <div class="comment-inform">
                    <p class="comment">
                      At vero eos et accusamus et iusto odio dignissimos ducimus
                      qui blanditiis praesentium voluptatum deleniti atque
                      corrupti quos dolores et quas molestias excepturi sint.
                    </p>
                    <p class="name-person">Diana Luna</p>
                    <p class="position-person">Entrepreneur, Maecenas</p>
                  </div>
                </div>
                <div class="carousel-item">
                  <div class="person-profile">
                    <img
                      src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/people/profile-m-3.png"
                      alt=""
                      class="thumb-profile"
                    />
                  </div>
                  <div class="comment-inform">
                    <p class="comment">
                      At vero eos et accusamus et iusto odio dignissimos ducimus
                      qui blanditiis praesentium voluptatum deleniti atque
                      corrupti quos dolores et quas molestias excepturi sint.
                    </p>
                    <p class="name-person">Diana Luna</p>
                    <p class="position-person">Entrepreneur, Maecenas</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section-press">
        <div class="container">
          <h1 class="section-title text-center text-capitalize">
            Press Coverage
          </h1>
          <div class="press-list row">
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="col-md-2 col-sm-4 col-xs-4">
              <a href="">
                <img
                  src="https://themes.3rdwavemedia.com/velocity/bs5/assets/images/press/press-1.png"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>
          <div class="press-lead text-center">
            <h1 class="title">Have press inquires?</h1>
            <p class="press-link">
              <a href="" class="text-link">Download our press kit</a> or
              <a href="" class="text-link">Get in touch</a>
            </p>
          </div>
        </div>
      </div>
      <div class="cta-section">
        <div class="container text-center">
          <h1 class="cta-section--title">
            Ready to promote your product online?
          </h1>
          <p class="cta-section--intro">
            More than <span class="text-color">300,000</span> users are using
            Velocity
          </p>
          <a href="" class="cta-btn btn btn-danger text-capitalize"
            >Get velocity now</a
          >
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="footer-content">
        <div class="container">
          <div class="row">
            <div class="footer-col col-lg-2 col-md-4">
              <div
                class="footer-col--inner text-sm-center text-md-left text-xs-center"
              >
                <h3 class="title">About us</h3>
                <ul class="list-unstyled">
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i>
                      Who we are</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i>
                      Pree</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i>
                      Blog</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i>
                      Jobs</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i>
                      Contact us</a
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-col col-lg-2 col-md-4">
              <div
                class="footer-col--inner text-sm-center text-md-left text-xs-center"
              >
                <h3 class="title">Product</h3>
                <ul class="list-unstyled">
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> How it works</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> API</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Download Apps</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Pricing</a
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-col col-lg-2 col-md-4">
              <div
                class="footer-col--inner text-sm-center text-md-left text-xs-center"
              >
                <h3 class="title">Support</h3>
                <ul class="list-unstyled">
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Help</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Documentation</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Terms of
                      services</a
                    >
                  </li>
                  <li>
                    <a href="" class="text-link">
                      <i class="fa-solid fa-caret-right"></i> Privacy</a
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-col col-lg-6">
              <div class="footer-col--inner">
                <ul class="social list-unstyled d-flex">
                  <li class="social--item">
                    <a class="social-link" href="">
                      <i class="fa-brands fa-twitter"></i>
                    </a>
                  </li>
                  <li class="social--item">
                    <a class="social-link" href=""
                      ><i class="fa-brands fa-facebook-f"></i
                    ></a>
                  </li>
                  <li class="social--item">
                    <a class="social-link" href=""
                      ><i class="fa-brands fa-github"></i
                    ></a>
                  </li>
                  <li class="social--item">
                    <a class="social-link" href="" class="social-link"
                      ><i class="fa-brands fa-instagram"></i
                    ></a>
                  </li>
                  <li class="social--item">
                    <a class="social-link" href=""
                      ><i class="fa-brands fa-pinterest-p"></i
                    ></a>
                  </li>
                </ul>
                <div class="form-footer">
                  <p class="intro">
                    Stay up to date with the latest news and offers from
                    Velocity
                  </p>
                  <div class="sign-up row no-gutters">
                    <div class="col-12 col-lg-auto">
                      <input
                        type="email"
                        class="form-control"
                        id="exampleInputEmail1"
                        aria-describedby="emailHelp"
                        placeholder="Enter email"
                      />
                    </div>
                    <div class="col-12 col-lg-auto">
                      <button class="btn-sign-footer btn btn-primary">
                        Subscribe Now
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="border-bottom"></div>
          <div class="has-divider row">
            <div class="col-lg-6">
              <div
                class="footer-col--inner text-xs-center text-md-center text-lg-left"
              >
                <h3 class="title">Mobile Apps</h3>
                <ul class="list-unstyled download-list">
                  <li class="dowload-item">
                    <a
                      href=""
                      class="btn-dowload-app btn btn-outline-secondary text-left"
                    >
                      <i class="fa-brands fa-apple"></i>
                      Download for iOS
                    </a>
                  </li>
                  <li class="dowload-item">
                    <a
                      href=""
                      class="btn-dowload-app btn btn-outline-secondary text-left"
                    >
                      <i class="fa-brands fa-android"></i>
                      Download for Android
                    </a>
                  </li>
                  <li class="dowload-item">
                    <a
                      href=""
                      class="btn-dowload-app btn btn-outline-secondary text-left"
                    >
                      <i class="fa-brands fa-windows"></i>
                      Windows coming soon...
                    </a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-6">
              <div
                class="footer-col--inner text-xs-center mt-xs-20 text-md-center text-lg-left"
              >
                <h3 class="title">Contact Us</h3>
                <div class="address">
                  <span class="street-address">
                    <i class="fa-solid fa-location-dot"></i> 56 College
                    Road</span
                  >
                  <br />
                  <span class="city">London</span>
                  <br />
                  <span class="postal-code">SW1Y 4LG</span>
                  <br />
                  <span class="country-name">UK</span>
                </div>
                <div class="phone">
                  <i class="fa-solid fa-phone-flip"></i> 0800 123 4567
                </div>
                <div class="email">
                  <i class="fa-solid fa-envelope"></i>
                  <a href="">mintn1k35@gmail.com</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="cpy-right text-center">
          Template Copyright @
          <a href="" class="cpyright-link"> 3rd Wave Media</a>
        </div>
      </div>
    </div>
    <script>
      $(".carousel").carousel({
        interval: 3000,
      });
      $(document).ready(function () {
        $(window).scroll(function () {
          if ($(window).scrollTop() > 10) {
            $(".header").addClass("scroll");
          } else {
            $(".header").removeClass("scroll");
          }
        });
      });
    </script>

  </body>
</html>
