---
description: >-
  A card is a flexible and extensible content container. It includes options for
  headers and footers, a wide variety of content, contextual background colors,
  and powerful display options.
---

# Card

### [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#cards-wrapper)

Cards are a useful UI component for grouping several related pieces of information together for providing a linked entry point to further details on that content. Cards work especially well in contexts where they provide summaries of many different kinds of content, rather than when simply used as a modern-looking replacement for a list of content.

### Examples

![](../.gitbook/assets/image%20%28102%29.png)

![](../.gitbook/assets/image%20%2856%29.png)

```text
<div class="row">
          <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
            <div class="card has-icon">
              <div class="card-header text-left"><span class="jds-tag has-success ">Tag/Badge</span></div>
              <div class="card-body">
                <div class="card-icon"><span><i class="fal fa-briefcase"></i></span></div>
                <h4 class="card-title">Card with icon</h4>
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
                <h4 class="card-title">Card with image</h4>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
              <div class="card-footer">
                <button type="button" class="btn btn-primary">Action</button>
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
```

### Cards with image

![](../.gitbook/assets/image%20%2866%29.png)

```text
<div class="row">
          <div class="col-xl-3 col-lg-6 col-md-12 mb-3">
            <div class="card has-image">
              <div class="card-header"><img class="card-img-top  img-fluid" src="images/img1.jpg" alt="Card image"></div>
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
            <div class="card has-image">
              <div class="card-header"><img class="card-img-top  img-fluid" src="images/img2.jpg" alt="Card image"></div>
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
            <div class="card has-image">
              <div class="card-header"><img class="card-img-top img-fluid" src="images/img3.jpg" alt="Card image"></div>
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
            <div class="card has-image">
              <div class="card-header"><img class="card-img-top img-fluid" src="images/img4.jpg" alt="Card image"></div>
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
```

### Horizontal Card

![](../.gitbook/assets/image%20%28123%29.png)

```text
<div class="card">
          <div class="card-horizontal">
            <div class="img-circle-wrapper"> <i class="fal fa-briefcase"></i> </div>
            <div class="card-body"> <span class="jds-tag has-warning">Pending</span>
              <h4 class="card-title">Card title</h4>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <button type="button" class="btn btn-primary">Action</button>
            </div>
          </div>
</div>
```

