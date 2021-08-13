# Bootstrap Product Cards

Responsive Product Cards built with the latest Bootstrap 5. Lots of examples of different designs for eCommerce components.

## Basic example

```html
<section style="background-color: #eee;">
  <div class="container py-5">
    <div class="row justify-content-center">
      <div class="col-md-8 col-lg-6 col-xl-4">
        <div class="card text-black">
          <i class="fab fa-apple fa-lg pt-3 pb-1 px-3"></i>
          <img
            src="https://mdbootstrap.com/img/Photos/Horizontal/E-commerce/Products/3.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="text-center">
              <h5 class="card-title">Believing is seeing</h5>
              <p class="text-muted mb-4">Apple pro display XDR</p>
            </div>
            <div>
              <div class="d-flex justify-content-between">
                <span>Pro Display XDR</span><span>$5,999</span>
              </div>
              <div class="d-flex justify-content-between">
                <span>Pro stand</span><span>$999</span>
              </div>
              <div class="d-flex justify-content-between">
                <span>Vesa Mount Adapter</span><span>$199</span>
              </div>
            </div>
            <div class="d-flex justify-content-between total font-weight-bold mt-4">
              <span>Total</span><span>$7,197.00</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```
## Product comparison template

```html
<section style="background-color: #eee;">
  <div class="container py-5">
    <div class="row">
      <div class="col-md-12 col-lg-4 mb-4 mb-lg-0">
        <div class="card text-black">
          <img
            src="https://mdbootstrap.com/img/Photos/new-templates/bootstrap-product-cards/img1.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="text-center mt-1">
              <h4 class="card-title">iPhone X</h4>
              <h6 class="text-primary mb-1 pb-3">Starting at $399</h6>
            </div>

            <div class="text-center">
              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Quick Look</h5>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">5.8″</span>
                <span>Super Retina HD display1</span>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">
                  <i class="fas fa-camera-retro"></i>
                </span>
                <ul class="list-unstyled mb-0">
                  <li aria-hidden="true">—</li>
                  <li>Wide</li>
                  <li>Telephoto</li>
                  <li aria-hidden="true">—</li>
                </ul>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">2x</span>
                <span>Optical zoom range</span>
              </div>

              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Capacity</h5>
              </div>

              <div class="d-flex flex-column mb-4 lead">
                <span class="mb-2">64GB</span>
                <span class="mb-2">256GB</span>
                <span style="color: transparent;">0</span>
              </div>
            </div>

            <div class="d-flex flex-row">
              <button
                type="button"
                class="btn btn-primary flex-fill me-1"
                data-mdb-ripple-color="dark"
              >
                Learn more
              </button>
              <button type="button" class="btn btn-danger flex-fill ms-1">Buy now</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4 mb-md-0">
        <div class="card text-black">
          <img
            src="https://mdbootstrap.com/img/Photos/new-templates/bootstrap-product-cards/img2.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="text-center mt-1">
              <h4 class="card-title">iPhone 11</h4>
              <h6 class="text-primary mb-1 pb-3">Starting at $499</h6>
            </div>

            <div class="text-center">
              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Quick Look</h5>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">6.1″</span>
                <span>Liquid Retina HD display1</span>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">
                  <i class="fas fa-camera-retro"></i>
                </span>
                <ul class="list-unstyled mb-0">
                  <li aria-hidden="true">Ultra Wide</li>
                  <li>Wide</li>
                  <li aria-hidden="true">—</li>
                  <li aria-hidden="true">—</li>
                </ul>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">2x</span>
                <span>Optical zoom range</span>
              </div>

              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Capacity</h5>
              </div>

              <div class="d-flex flex-column mb-4 lead">
                <span class="mb-2">64GB</span>
                <span class="mb-2">128GB</span>
                <span>256GB</span>
              </div>
            </div>

            <div class="d-flex flex-row">
              <button
                type="button"
                class="btn btn-primary flex-fill me-1"
                data-mdb-ripple-color="dark"
              >
                Learn more
              </button>
              <button type="button" class="btn btn-danger flex-fill ms-1">Buy now</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4 mb-md-0">
        <div class="card text-black">
          <img
            src="https://mdbootstrap.com/img/Photos/new-templates/bootstrap-product-cards/img3.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="text-center mt-1">
              <h4 class="card-title">iPhone 11 Pro</h4>
              <h6 class="text-primary mb-1 pb-3">Starting at $599</h6>
            </div>

            <div class="text-center">
              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Quick Look</h5>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">5.8″</span>
                <span>Super Retina HD display1</span>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">
                  <i class="fas fa-camera-retro"></i>
                </span>
                <ul class="list-unstyled mb-0">
                  <li aria-hidden="true">Ultra Wide</li>
                  <li>Wide</li>
                  <li>Telephoto</li>
                  <li aria-hidden="true">—</li>
                </ul>
              </div>

              <div class="d-flex flex-column mb-4">
                <span class="h1 mb-0">4x</span>
                <span>Optical zoom range</span>
              </div>

              <div class="p-3 mx-n3 mb-4" style="background-color: #eff1f2;">
                <h5 class="mb-0">Capacity</h5>
              </div>

              <div class="d-flex flex-column mb-4 lead">
                <span class="mb-2">64GB</span>
                <span class="mb-2">256GB</span>
                <span>512GB</span>
              </div>
            </div>

            <div class="d-flex flex-row">
              <button
                type="button"
                class="btn btn-primary flex-fill me-1"
                data-mdb-ripple-color="dark"
              >
                Learn more
              </button>
              <button type="button" class="btn btn-danger flex-fill ms-1">Buy now</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

#### Much more examples and a detailed description can be found at [📄 Product Cards documentation page](https://mdbootstrap.com/docs/standard/extended/product-cards/)


