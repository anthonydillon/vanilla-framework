---
title: Color settings
table_of_contents: true
---

## Color

These guidelines are the framework upon which we have built our system for how color is used in Vanilla, we use a fairly neutral color palette along with a traffic light palette.

<div class="u-equal-height">
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #fff"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-x-light<br><span class="p-muted-heading">#fff</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #f7f7f7"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-light<br><span class="p-muted-heading">#f7f7f7</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #e5e5e5"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-mid-x-light<br><span class="p-muted-heading">#e5e5e5</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #cdcdcd"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-mid-light<br><span class="p-muted-heading">#cdcdcd</span>
    </p>
  </div>
</div>
<div class="u-equal-height">
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #666"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-mid-dark<br><span class="p-muted-heading">#666</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #111"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-dark<br><span class="p-muted-heading">#111</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #000"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-x-dark<br><span class="p-muted-heading">#000</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #333"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-brand<br><span class="p-muted-heading">#333</span>
    </p>
  </div>
</div>
<div class="u-equal-height">
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #c7162b"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-negative<br><span class="p-muted-heading">#c7162b</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #f99b11"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-caution<br><span class="p-muted-heading">#f99b11</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #0e8420"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-positive<br><span class="p-muted-heading">#0e8420</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #335280"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-information<br><span class="p-muted-heading">#335280</span>
    </p>
  </div>
</div>
<div class="u-equal-height">
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #007aa6"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-link<br><span class="p-muted-heading">#007aa6</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #333"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-accent<br><span class="p-muted-heading">#333</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #333"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-accent-background<br><span class="p-muted-heading">#333</span>
    </p>
  </div>
  <div class="col-3 p-card u-no-padding">
    <div class="p-strip is-shallow is-bordered" style="background-color: #fff"></div>
    <p class="p-card__content u-no-margin" style="padding: 1rem">
      $color-navigation-background<br><span class="p-muted-heading">#fff</span>
    </p>
  </div>
</div>

You can define a brand color (`$color-brand`) that can be used for call-to-action buttons and other highlights across the framework. The default Vanilla brand color is `$color-dark`.

<img class="p-image--bordered" src="https://assets.ubuntu.com/v1/7446a44a-basics-brand-color.png" alt="brand-color">

### Accessibility

It’s important for us to meet all web accessibility standards. Vanilla encourages meeting the minimum contrast ratios specified by WCAG 2.1 Level AA for text, icons and background colors.

<div class="row">
   <div class="col-6">
   <div class="p-notification--positive">
   <p class="p-notification__response"><span class="p-notification__status">Do:</span>Use a minimum contrast ratio of 4.5 for normal text and UI components</p>
   </div>
   <img class="p-image--bordered" src="https://assets.ubuntu.com/v1/e1183cd5-basics-text-color-do.png" alt="text-color-do">
   <img class="p-image--bordered" src="https://assets.ubuntu.com/v1/92607803-basics-button-color-do.png" alt="button-color-do">
   </div>
  <div class="col-6">
  <div class="p-notification--negative">
  <p class="p-notification__response"><span class="p-notification__status">Don't:</span>Use dark text that isn’t legible on dark backgrounds</p>
  </div>
  <img class="p-image--bordered" src="https://assets.ubuntu.com/v1/66aa056d-basics-text-color-don%27t.png" alt="text-color-don't">
  <img class="p-image--bordered" src="https://assets.ubuntu.com/v1/0929f834-basics-button-color-don%27t.png" alt="button-color-don't">
  </div>
</div>

### Design

For more information [view the color design spec](https://github.com/ubuntudesign/vanilla-design/tree/master/Color), which includes the specification in markdown format and a PNG image.
