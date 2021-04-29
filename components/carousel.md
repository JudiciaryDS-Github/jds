---
description: >-
  Carousels are for displaying a related set of content items in a row. Items
  can be paged using the next/previous buttons or by a swipe gesture.
---

# Carousel

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#carousel-wrapper)

### For Banners

![](../.gitbook/assets/image%20%2838%29.png)

```text
<div id="section-carousel" class="carousel slide" data-ride="carousel" data-interval="5000"> 
      <!-- Carousel Indicators -->
      <ol class="carousel-indicators">
        <li title="Show Slide 1" data-target="#section-carousel" data-slide-to="0" class="active"></li>
        <li title="Show Slide 2" data-target="#section-carousel" data-slide-to="1"></li>
        <li title="Show Slide 3" data-target="#section-carousel" data-slide-to="2"></li>
        <!--   <li title="Show Slide 4" data-target="#section-carousel" data-slide-to="3"></li>-->
      </ol>
      <div class="carousel-inner"> 
        <!-- Slide #1 -->
        <div class="carousel-item active">
          <div style="display: table-cell; height: 550px; width: 100vw; vertical-align: middle; background-color: #e2dfdb;">
            <h1>Judiciary Design System</h1>
            <p>SCJDS unites style, content and components with a single set of design principles. Whether you’re a developer or designer, you’ll get all the information and guidance you need.</p>
          </div>
        </div>
        <!-- Slide #2 -->
        <div class="carousel-item">
          <div style="display: table-cell; height: 550px; width: 100vw; vertical-align: middle; background-color: #e2dfdb;">
            <h1>Title of the slide</h1>
            <p>Short description</p>
          </div>
        </div>
        <!-- Slide #3 -->
        <div class="carousel-item">
          <div style="display: table-cell; height: 550px; width: 100vw; vertical-align: middle; background-color: #e2dfdb;">
            <h1>Title of the slide</h1>
            <p>Short description</p>
          </div>
        </div>
        
      </div>
      <button class="btn btn-link carousel-control-prev" data-target="#section-carousel" data-slide="prev" title="Show Previous Slide"> <span class="carousel-control-prev-icon" aria-hidden="true"></span> <span class="sr-only">Previous</span> </button>
      <button class="btn btn-link carousel-control-next" data-target="#section-carousel" data-slide="next" title="Show Next Slide"> <span class="carousel-control-next-icon" aria-hidden="true"></span> <span class="sr-only">Next</span> </button>
    </div>
```

### For Cards

![](../.gitbook/assets/image%20%2826%29.png)

```text
<div class="row">
          <div class="col-6">
            <h3 class="text-left">Carousel with cards</h3>
          </div>
          <div class="col-6 text-right"> <a class="btn btn-outline-primary mb-3 mr-1" href="#carouselExampleIndicators2" role="button" data-slide="prev"> <span class="fas fa-chevron-left"></span> </a> <a class="btn btn-outline-primary mb-3 " href="#carouselExampleIndicators2" role="button" data-slide="next"> <span class="fas fa-chevron-right"></span> </a> </div>
          <div class="col-12">
            <div id="carouselExampleIndicators2" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item">
                  <div class="row">
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-icon">
                        <div class="card-header text-left"><span class="jds-tag has-success ">Tag/Badge</span></div>
                        <div class="card-body">
                          <div class="card-icon"><span><i class="fal fa-briefcase"></i></span></div>
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-icon">
                        <div class="card-header text-left"><span class="jds-tag has-example-light ">Tag/Badge</span></div>
                        <div class="card-body">
                          <div class="card-icon"><span><i class="fal fa-briefcase"></i></span></div>
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary mr-1">Action</button>
                          <button type="button" class="btn btn-outline-primary">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-icon">
                        <div class="card-header text-left"><span class="jds-tag has-warning ">Tag/Badge</span></div>
                        <div class="card-body">
                          <div class="card-icon"><span><i class="fal fa-briefcase"></i></span></div>
                          <h4 class="card-title">Clickable Card (Stretched Link)</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary stretched-link">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-icon">
                        <div class="card-header text-left"><span class="jds-tag has-warning ">Tag/Badge</span></div>
                        <div class="card-body">
                          <div class="card-icon"><span><i class="fal fa-briefcase"></i></span></div>
                          <h4 class="card-title">Clickable Card (Stretched Link)</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary stretched-link">Action</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="carousel-item active carousel-item-left">
                  <div class="row">
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-image"> <img class="card-img-top" src="images/img1.jpg" alt="Card image">
                        <div class="card-body">
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-image"> <img class="card-img-top" src="images/img2.jpg" alt="Card image">
                        <div class="card-body">
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-image"> <img class="card-img-top img-fluid" src="images/img3.jpg" alt="Card image">
                        <div class="card-body">
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary">Action</button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-image"> <img class="card-img-top img-fluid" src="images/img3.jpg" alt="Card image">
                        <div class="card-body">
                          <h4 class="card-title">Card title</h4>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer">
                          <button type="button" class="btn btn-primary">Action</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="carousel-item carousel-item-next carousel-item-left">
                  <div class="row">
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-options">
                        <div class="dropdown cards-dropdown"><a href="#" class="dots dropdown-toggle" data-toggle="dropdown" aria-expanded="false"><i class="far fa-ellipsis-v"></i><span class="sr-only">Dropdown</span></a>
                          <div class="dropdown-menu" style=""> <a class="dropdown-item" href="#">Item 1</a> <a class="dropdown-item" href="#">Item 2</a> <a class="dropdown-item" href="#">Item 3</a> </div>
                        </div>
                        <div class="card-body">
                          <h6>Date</h6>
                          <h5 class="card-title">Card with Menu</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer"> <span class="jds-tag has-warning mr-auto">Tag/Badge</span>
                          <button type="button" class="btn btn-link mr-3"><i class="fal fa-arrow-to-bottom"></i></button>
                          <button type="button" class="btn btn-link"><i class="fal fa-calendar-alt"></i></button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-options">
                        <div class="dropdown cards-dropdown"><a href="#" class="dots dropdown-toggle" data-toggle="dropdown" aria-expanded="false"><i class="far fa-ellipsis-v"></i><span class="sr-only">Dropdown</span></a>
                          <div class="dropdown-menu" style=""> <a class="dropdown-item" href="#">Item 1</a> <a class="dropdown-item" href="#">Item 2</a> <a class="dropdown-item" href="#">Item 3</a> </div>
                        </div>
                        <div class="card-body">
                          <h6>Date</h6>
                          <h5 class="card-title">Card with Menu</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer"> <span class="jds-tag has-warning mr-auto">Tag/Badge</span>
                          <button type="button" class="btn btn-link mr-3"><i class="fal fa-arrow-to-bottom"></i></button>
                          <button type="button" class="btn btn-link"><i class="fal fa-calendar-alt"></i></button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-options">
                        <div class="dropdown cards-dropdown"><a href="#" class="dots dropdown-toggle" data-toggle="dropdown" aria-expanded="false"><i class="far fa-ellipsis-v"></i><span class="sr-only">Dropdown</span></a>
                          <div class="dropdown-menu" style=""> <a class="dropdown-item" href="#">Item 1</a> <a class="dropdown-item" href="#">Item 2</a> <a class="dropdown-item" href="#">Item 3</a> </div>
                        </div>
                        <div class="card-body">
                          <h6>Date</h6>
                          <h5 class="card-title">Card with Menu</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer"> <span class="jds-tag has-warning mr-auto">Tag/Badge</span>
                          <button type="button" class="btn btn-link mr-3"><i class="fal fa-arrow-to-bottom"></i></button>
                          <button type="button" class="btn btn-link"><i class="fal fa-calendar-alt"></i></button>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
                      <div class="card has-options">
                        <div class="dropdown cards-dropdown"><a href="#" class="dots dropdown-toggle" data-toggle="dropdown" aria-expanded="false"><i class="far fa-ellipsis-v"></i><span class="sr-only">Dropdown</span></a>
                          <div class="dropdown-menu" style=""> <a class="dropdown-item" href="#">Item 1</a> <a class="dropdown-item" href="#">Item 2</a> <a class="dropdown-item" href="#">Item 3</a> </div>
                        </div>
                        <div class="card-body">
                          <h6>Date</h6>
                          <h5 class="card-title">Card with Menu</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                        <div class="card-footer"> <span class="jds-tag has-warning mr-auto">Tag/Badge</span>
                          <button type="button" class="btn btn-link mr-3"><i class="fal fa-arrow-to-bottom"></i></button>
                          <button type="button" class="btn btn-link"><i class="fal fa-calendar-alt"></i></button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
```

