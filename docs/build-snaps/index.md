---
layout: base
title: Build snaps
---
<style>
.p-logo-link {
  border: 1px solid transparent;
  border-radius: 2px;
  display: block;
  margin-top: 0;

  &:hover {
    border-color: #cdcdcd;
    text-decoration: none;
  }
}

.p-logo-links {
  align-items: flex-start;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;

  .p-logo-link {
    // by default (on mobile) use col-3 width (4 items in a row)
    width: 21.875%; // mobile-col-1

    // on larger screens use col-2 width (6 items in a row)
    @media screen and (min-width: 620px) {
      width: 15.04854%; // col-2
    }
  }

  // don't limit max-height of logo in card header
  .p-card__header img {
    display: block;
    max-height: none;
    width: 100%;
  }
}
</style>

<div class="p-strip is-deep is-bordered">
      <div class="row">
        <div class="col-12">
          <h2>Snapcraft integrates with your language</h2>
          <p class="p-heading--five">See how Snapcraft works with your language to make packaging and installing your software easy.</p>
        </div>
      </div>
      <div class="row">
        <div class="col-12 p-logo-links">
          <a class="p-logo-link p-card" href="/build-snaps/python">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/c3d9d13f-python-logo.png" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">Python</p>
          </a>
          <a class="p-logo-link p-card" href="/build-snaps/node">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/9735ad74-node-logo.png" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">Node.js</p>
          </a>
          <a class="p-logo-link p-card" href="/build-snaps/go">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/c85a212e-go-logo.png" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">Go</p>
          </a>
          <a class="p-logo-link p-card" href="/build-snaps/moos">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/04ff3e39-MOOSV-10-256.jpg" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">MOOS</p>
          </a>
          <a class="p-logo-link p-card" href="/build-snaps/ros">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/dc84f68e-c8749268-logo-ros.png" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">ROS</p>
          </a>
          <a class="p-logo-link p-card" href="/build-snaps/pre-built">
            <header class="p-card__header">
              <img src="https://assets.ubuntu.com/v1/f14812c7-adwaita-package.png" style="height: 105px; max-height: 105px;" alt="">
            </header>
            <p class="u-no-margin">Pre-built apps</p>
          </a>
        </div>
      </div>
    </div>
<div class="p-strip is-deep">
      <div class="row">
        <div class="col-6">
          <h2>Using something else?</h2>
        </div>
        <div class="col-6">
          <ul class="p-list u-no-margin">
            <li class="p-list__item"><a href="/build-snaps/">Learn to create a snap</a> with a widely applicable example</li>
            <li class="p-list__item"><a href="/reference/">Read the reference</a> for a comprehsive view of what's possible</li>
          </ul>
        </div>
      </div>
    </div>
