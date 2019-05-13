<template>
  <div class="home">
    <header>
      <Navbar/>

      <div class="bg-dark bg-img pt-5 pb-2">
        <div class="container-fluid main">
          <div class="row">
            <div class="col-sm-12">
              <carousel :items="1" :loop="true" :autoplay="true">
                <div class="row no-gutters position-relative">
                  <div class="col-md-6 position-static mb-5">
                    <h2 class="banner-title fontsize-32">X-t2</h2>
                    <p class="fontsize-24 mb-0 text-uppercase font-weight-bold">The ultimate mirrorless digital camera delivering creative perfection</p>
                    <p class="fontsize-16 mb-4">With advanced autofocus functions and 4K high definition video</p>
                    <a class="link-decoration text-reset font-weight-bold" href="#">Explorer <span class="text-danger ml-4 caret-md">&#x279E;</span></a>
                  </div>
                  <div class="col-md-6 mb-md-0 p-md-4">
                    <img src="../assets/images/product_10.png" class="w-75 m-auto" alt="product banner">
                  </div>
                </div>
              </carousel>

              <ul id='carousel-dots' class='nav nav-fill nav-bordered'>
                <li class='nav-item nav-link text-left active'>01. X - T2</li>
                <li class='nav-item nav-link text-left'>02. Review X Pro2 By Jhon Doe</li>
                <li class='nav-item nav-link text-left'>03. GFX Stories with Markus & Koala</li>
                <li class='nav-item nav-link text-left'>04. Travelling with the X100F</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </header>

    <main class="main">
      <div class="pageheading pageheading-devider py-5 text-center">
        <h1 class="pageheading-title">Explore Our X Collections</h1>
        <p class="pageheading-desc text-light">High-end digital cameras aimed at professional and <br /> keep enthusiast photographers.</p>
      </div>

      <section class="bg-dark-light py-5 bg-shadow-1">
        <div class="container-fluid">
          <div class="row">
            <div class="col-sm-12 col-md-5 offset-md-1 col-xl-4 offset-xl-1">
              <div class="subheading subheading-lg">
                <div class="subheading-title">GFX Series <a class="navbar-nav-dark ml-4 link-light fontsize-12" href="#">Explore <span class="text-danger caret-md">&#x279E;</span></a></div>
                <p class="subheading-desc">The world's highest level of photographic image quality is produced
                  by the integration of a large 43.8ｘ32.9mm CMOS sensor (FUJIFILM G Format) and image design technology
                  cultivated by Fujifilm's 80+ year history.</p>
              </div>
            </div>
            <div class="col-sm-12 col-md-5 col-xl-4 offset-xl-2">
              <div class="row mt-4">
                <div class="col-5">
                  <div class="img-frame img-frame-xs mx-auto">
                    <img src="../assets/images/product_1.png" alt="FUJIFILM GFX 50S" class="img-fluid">
                  </div>
                </div>
                <div class="col-7">
                  <span class="fontsize-12">GFX Mirrorless Digital Camera</span>
                  <div class="fontsize-18 font-weight-bold mb-2">FUJIFILM GFX 50S</div>
                  <p class="mb-0">Ultra high image quality medium format mirrorless camera</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-gray-dark py-5 bg-shadow-2">
        <div class="container-fluid">
          <div class="row">
            <div class="col-sm-12 col-md-10 offset-md-1">
              <div class="subheading subheading-lg">
                <h2 class="subheading-title">X Series <a class="navbar-nav-dark ml-4 link-light fontsize-12" href="#">Explore <span class="text-danger caret-md">&#x279E;</span></a></h2>
                <p class="subheading-desc">"FUJIFILM X" combines traditional styling with cutting edge innovative
                  technology. The line-up will
                  further expand in line with Fujifilm's aim that the X series should "make you fall in love with
                  photography all over again".</p>
              </div>

              <b-tabs nav-class="nav tab-bordered" :no-nav-style="true">
                <b-tab title="X Mirrorless Digital Camera" active>
                  <carousel :items="4" :margin="25">
                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_2.png" alt="FUJIFILM X-Pro2" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FUJIFILM X-Pro2</h3>
                      <p class="subheading-desc">Offers the world’s only Hybrid Multi Viewfinder and features a brand new 24MP X-Trans III sensor</p>
                    </div>

                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_3.png" alt="FUJIFILM X-T2" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FUJIFILM X-T2</h3>
                      <p class="subheading-desc">Delivers creative perfection with advanced autofocus functions and 4K HD video.</p>
                    </div>

                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_4.png" alt="FUJIFILM X-T1" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FUJIFILM X-T1</h3>
                      <p class="subheading-desc">Features evolved SLR-style handling, mechanical dials and weather-resistance</p>
                    </div>

                    <a href="#" class="blank-item">
                      <div class="blank-text">
                        Find More <br/> Cameras
                        <div class="text-danger caret-md">&#x279E;</div>
                      </div>
                    </a>
                  </carousel>
                </b-tab>
                <b-tab title="X Premium Compact Camera">
                  <carousel :items="4" :margin="25">
                    <a href="#" class="blank-item">
                      <div class="blank-text">
                        Find More <br/> Cameras
                        <div class="text-danger caret-md">&#x279E;</div>
                      </div>
                    </a>
                  </carousel>
                </b-tab>
              </b-tabs>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-gray-light py-5 bg-shadow-3">
        <div class="container-fluid">
          <div class="row">
            <div class="col-sm-12 col-md-10 offset-md-1">
              <div class="subheading subheading-lg">
                <h3 class="subheading-title">FinePix <a class="navbar-nav-dark ml-4 link-light fontsize-12" href="#">Explore <span class="text-danger caret-md">&#x279E;</span></a></h3>
                <p class="subheading-desc">From cutting-edge long-zoom models to fashion-conscious point-and-shoot compacts, there's a Fujifilm FinePix digital camera to satisfy every kind of photographer.</p>
              </div>

              <b-tabs nav-class="nav tab-bordered" :no-nav-style="true">
                <b-tab title="S Series : High Zoom">
                  <carousel :items="4" :margin="25">
                    <a href="#" class="blank-item">
                      <div class="blank-text">
                        Find More <br/> Cameras
                        <div class="text-danger caret-md">&#x279E;</div>
                      </div>
                    </a>
                  </carousel>
                </b-tab>
                <b-tab title="XP Series : Tough" active>
                  <carousel :items="4" :margin="25">
                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_5.png" alt="FinePix XP120" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FinePix XP120</h3>
                      <p class="subheading-desc">With four protective features - against water, dust, shock, and freezing temperatures</p>
                    </div>

                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_6.png" alt="FinePix XP90" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FinePix XP90</h3>
                      <p class="subheading-desc">With four protective features - against water, dust, shock, and freezing temperatures</p>
                    </div>

                    <div class="subheading subheading-sm">
                      <div class="img-frame img-frame-xs mx-auto">
                        <img src="../assets/images/product_7.png" alt="FinePix XP8" class="img-fluid">
                      </div>
                      <h3 class="subheading-title">FinePix XP8</h3>
                      <p class="subheading-desc">With four protective features - against water, dust, shock, and freezing temperatures</p>
                    </div>

                    <a href="#" class="blank-item">
                      <div class="blank-text">
                        Find More <br/> Cameras
                        <div class="text-danger caret-md">&#x279E;</div>
                      </div>
                    </a>
                  </carousel>
                </b-tab>
              </b-tabs>
            </div>
          </div>
        </div>
      </section>

      <section class="py-5" style="background-color: transparent;">
        <div class="container-fluid">
          <div class="row">
            <div class="col-sm-6 col-md-5 offset-md-1 col-xl-4 offset-xl-1">
              <div class="subheading subheading-lg mb-5">
                <img src="../assets/images/product_8.png" alt="Accessories" class="img-fluid">
                <h2 class="subheading-title text-dark">Find your match accessories</h2>
                <p class="subheading-desc text-gray-light">To support your exploration</p>
                <a class="link-decoration text-dark font-weight-bold" href="#">See All Accessories <span class="text-danger ml-4 caret-md">&#x279E;</span></a>
              </div>
            </div>
            <div class="col-sm-6 col-md-5 col-xl-4 offset-xl-2">
              <div class="subheading subheading-lg">
                <img src="../assets/images/product_9.png" alt="Leses" class="img-fluid">
                <h2 class="subheading-title text-dark">What kind of photos would you like to shoot?</h2>
                <p class="subheading-desc text-gray-light">Find the right combination between camera and lense</p>
                <a class="link-decoration text-dark font-weight-bold" href="#">Explorer Lenses  <span class="text-danger ml-4 caret-md">&#x279E;</span></a>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <div class=" bg-white pb-5">
      <div class="container-fluid main">
        <div class="row">
          <div class="col-sm-12">
            <div class="pageheading py-5 text-center m-auto">
              <h1 class="pageheading-title text-dark">Bring your inspiration</h1>
              <p class="pageheading-desc text-gray-light">Explore inspiring photos, connect with other enthusiasts <br/> and learn more about photography.</p>
              <a class="link-decoration text-dark font-weight-bold" href="#">Get More Inspiration <span class="text-danger ml-4 caret-md">&#x279E;</span></a>
            </div>

            <div class="row no-gutters mx-2n text-dark">
              <div class="col-sm-12 col-md-6 px-1">
                <div class="overlayimg overlayimg-lg">
                  <img src="https://placeimg.com/640/480/any" alt="Inspiration by mac" class="img-fluid">
                  <div class="overlayimg-label">Review</div>
                  <div class="overlayimg-wrapper">
                    <div class="subheading subheading-md">
                      <h2 class="subheading-title mb-1">EF-X500 Testing on location #2</h2>
                      <p class="subheading-desc fontsize-12 text-light">Max De Martino visits Val Fontanabuona to capture portraits of artisans with the EF-X500.</p>
                      <div class="fontsize-12 text-light">2017.07.31  by Max De Martino</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-sm-12 col-md-6">
                <div class="row no-gutters">
                  <div class="col-sm-6 px-1">
                    <div class="overlayimg">
                      <img src="https://placeimg.com/640/480/any" alt="Inspiration by hendi" class="img-fluid">
                      <div class="overlayimg-label">Tips</div>
                      <div class="overlayimg-wrapper">
                        <div class="subheading subheading-sm">
                          <h2 class="subheading-title mb-1">X100F and the X100 Camera System</h2>
                          <div class="fontsize-12 text-light">2017.07.31  by Max De Martino</div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-sm-6 px-1">
                    <div class="overlayimg">
                      <img src="https://placeimg.com/640/480/any" alt="Inspiration by laura" class="img-fluid">
                      <div class="overlayimg-label">In Actions</div>
                      <div class="overlayimg-wrapper">
                        <div class="subheading subheading-sm">
                          <h2 class="subheading-title mb-1">GFX stories with Heinz Zak -Top of Austria-</h2>
                          <div class="fontsize-12 text-light">2017.07.31  by Max De Martino</div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-sm-6 px-1">
                    <div class="overlayimg">
                      <img src="https://placeimg.com/640/480/any" alt="Inspiration by jhon" class="img-fluid">
                      <div class="overlayimg-label">Interview</div>
                      <div class="overlayimg-wrapper">
                        <div class="subheading subheading-sm">
                          <h2 class="subheading-title mb-1">An Interview with Piet Van den Eynde</h2>
                          <div class="fontsize-12 text-light">2017.07.31  by Max De Martino</div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-sm-6 px-1">
                    <div class="overlayimg">
                      <img src="https://placeimg.com/640/480/any" alt="Inspiration by abe" class="img-fluid">
                      <div class="overlayimg-label">Tips</div>
                      <div class="overlayimg-wrapper">
                        <div class="subheading subheading-sm">
                          <h2 class="subheading-title mb-1">Battery life management</h2>
                          <div class="fontsize-12 text-light">2017.07.31  by Max De Martino</div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <Footer class=" bg-dark py-5 px-sm-3 py-md-5">
      <div class="container-fluid main">
        <div class="row">
          <div class="col-12 col-sm-4 col-md-2">
            <div class="img-frame img-frame-xs">
              <img src="../assets/images/logo_2.png" alt="Fujifilm" class="img-fluid mb-2">
              <div class="fontsize-11 text-light">&copy; FUJIFILM Corporate</div>
            </div>
          </div>
          <div class="col-6 col-sm-4 mb-3">
            <div class="subheading subheading-bordered subheading-sm">
              <h1 class="subheading-title">Products</h1>
            </div>
            <div class="row">
              <div class="col-12 col-sm-12 col-md-6">
                <ul class="list-unstyled mb-0">
                  <li>Cameras</li>
                  <li>Lenses</li>
                  <li>Accessories</li>
                </ul>
              </div>
              <div class="col-12 col-sm-12 col-md-6">
                <ul class="list-unstyled">
                  <li>Inspiration</li>
                  <li>Service & Support</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-6 col-sm-4 col-md-2 mb-3">
            <div class="subheading subheading-bordered subheading-sm">
              <h1 class="subheading-title">Activity</h1>
            </div>
            <ul class="list-unstyled">
              <li>Promotion</li>
              <li>News & Events</li>
              <li>Community</li>
            </ul>
          </div>
          <div class="col-6 col-2 col-sm-4 offset-sm-4 col-md-2 offset-md-0 mb-3">
            <div class="subheading subheading-bordered subheading-sm">
              <h1 class="subheading-title">Need Help</h1>
            </div>
            <ul class="list-unstyled">
              <li>Contact Us</li>
              <li>Store Location</li>
              <li>Service Center</li>
            </ul>
          </div>
          <div class="col-6 col-sm-4 col-md-2 mb-3">
            <div class="subheading subheading-bordered subheading-sm">
              <h1 class="subheading-title">Follow Us</h1>
            </div>
            <div class="row">
              <div class="mt-2 mb-3 col-12 col-sm-12">
                <a href="#" class="fa-stack text-reset">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-facebook fa-stack-1x text-dark"></i>
                </a>
                <a href="#" class="fa-stack text-reset">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-twitter fa-stack-1x text-dark"></i>
                </a>
                <a href="#" class="fa-stack text-reset">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-instagram fa-stack-1x text-dark"></i>
                </a>
                <a href="#" class="fa-stack text-reset">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-youtube-play fa-stack-1x text-dark"></i>
                </a>
              </div>
              <div class="col-12 col-sm-12 mt-2 mb-3">
                <div class="dropdown">
                  <button type="button" class="btn btn-outline-light btn-sm rounded-pill px-3 dropdown-toggle"
                    data-toggle="dropdown">En | <i class="fa fa-chevron-down fa-fw caret-sm"></i></button>
                  <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">English</a>
                    <a class="dropdown-item" href="#">Indonesian</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </Footer>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import carousel from 'vue-owl-carousel'
import { BTabs, BTab } from 'bootstrap-vue/es/components'

export default {
  components: {
    Navbar,
    carousel,
    BTabs,
    BTab
  }
}
</script>
