# Color

<style>
  .container {
    --width: 1300px;
  }
</style>

## Color palette

### Primary colors

Our colors express our commitment to being a welcoming, vibrant, and accessible brand. The palette is simple and flexible allowing for application across business segments while maintaining unity.

<style>
  .color-palette {
    display: flex;
    flex-wrap: wrap;
    gap: 0.125rem;
  }
  .color-palette .color {
    padding: 1rem;
    width: 8rem;
    height: 8rem;
    border-radius: 4px;
    position: relative;
    background: var(--color);
    border: 1px solid white;
  }
  .color-palette.interactive .color {
    cursor: pointer;
  }
  .color-palette .color-palette-column {
    display: flex;
    flex-direction: column;
    gap: 0.125rem;
  }
  .color-palette .color-sm {
    width: 7.25rem;
    height: 8rem;
  }
  .color-palette .color-lg {
    width: 14rem;
    height: 14rem;
    display: flex;
    flex-direction: column;
  }
  .color-palette .color-lg > p {
    flex: 1 0 auto;
  }
  .color-palette .color:focus-within {
    box-shadow: 0 0 0 0.125rem var(--color);
    border-color: white;
  }
  .color-palette .color > :not(input) {
    cursor: auto;
  }
  .color-palette .color > h5:first-child {
    margin-top: 0;
  }
  .color-palette .color input[type="color"] {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
    background: none;
    cursor: pointer;
    z-index: -1;
  }
  .color-palette .color input[type="color"]::-webkit-color-swatch {
    border: none;
  }
  .color-palette .color input[type="color"]::-moz-color-swatch {
    border: none;
  }
  .color-palette .color code {
    color: inherit;
  }
</style>

<!-- IF ANY OF THESE COLORS ARE UPDATED, THEY NEED TO BE UPDATED IN ./colors.scss -->
<div class="color-palette interactive">
  <div class="color" style="--color: var(--sg-sky-blue)">
    <h5>Sourcegraph Blue</h5>
    <code>#00cbec</code>
  </div>
  <div class="color" style="--color: var(--sg-vivid-violet); color: white">
    <h5>Sourcegraph Violet</h5>
    <code>#a112ff</code>
  </div>
  <div class="color" style="--color: var(--sg-vermillion); color: white">
    <h5>Sourcegraph Vermillion</h5>
    <code>#ff5543</code>
  </div>
</div>

<script async defer src="interactive-color-palette.js"></script>

### Secondary colors

Use supporting colors for graphic elements, illustrations, callouts, website UI elements, and more.

Primary logo colors have been marked. The secondary colors, along with shades and tints, were chosen to support and compliment these three core colors.

<!-- IF ANY OF THESE COLORS ARE UPDATED, THEY NEED TO BE UPDATED IN ./colors.scss -->
<div class="color-palette interactive">
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #fff2cf">
      <code>#fff2cf</code>
      <small>Lemon 200</small>
    </div>
    <div class="color color-sm" style="--color: var(--sg-lemon)">
      <code>#ffdb45</code>
      <small>Lemon 300</small>
    </div>
    <div class="color color-sm" style="--color: #ffc247">
      <code>#ffc247</code>
      <small>Lemon 400</small>
    </div>
    <div class="color color-sm" style="--color: #ff9933; color: white">
      <code>#ff9933</code>
      <small>Lemon 500</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #ffdfdc">
      <code>#ffdfdc</code>
      <small>Vermillion 100</small>
    </div>
    <div class="color color-sm" style="--color: #ffc9c9">
      <code>#ffc9c9</code>
      <small>Vermillion 200</small>
    </div>
    <div class="color color-sm" style="--color: var(--sg-vermillion); color: white">
      <code>#ff5543</code>
      <small>Vermillion 300</small>
      <div><img src="logo/versions/Sourcegraph_Logomark_WHT.svg" alt="Primary logo color" style="width: 1em; height: 1em"></div>
    </div>
    <div class="color color-sm" style="--color: #ed2e20; color: white">
      <code>#ed2e20</code>
      <small style="font-size: 85%">Vermillion 400</small>
    </div>
    <div class="color color-sm" style="--color: #c22626; color: white">
      <code>#c22626</code>
      <small>Vermillion 500</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #ffdff5">
      <code>#ffdff5</code>
      <small>Cerise 100</small>
    </div>
    <div class="color color-sm" style="--color: #ffd1f2">
      <code>#ffd1f2</code>
      <small>Cerise 200</small>
    </div>
    <div class="color color-sm" style="--color: #e1449a">
      <code>#e1449a</code>
      <small>Cerise 300</small>
    </div>
    <div class="color color-sm" style="--color: #d62687; color: white">
      <code>#d62687</code>
      <small>Cerise 400</small>
    </div>
    <div class="color color-sm" style="--color: #c4147d; color: white">
      <code>#c4147d</code>
      <small>Cerise 500</small>
    </div>
    <div class="color color-sm" style="--color: #9e1769; color: white">
      <code>#9e1769</code>
      <small>Cerise 600</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #eedfff">
      <code>#eedfff</code>
      <small>Violet 100</small>
    </div>
    <div class="color color-sm" style="--color: #e8d1ff">
      <code>#e8d1ff</code>
      <small>Violet 200</small>
    </div>
    <div class="color color-sm" style="--color: #ce9cff">
      <code>#ce9cff</code>
      <small>Violet 300</small>
    </div>
    <div class="color color-sm" style="--color: var(--sg-vivid-violet); color: white">
      <code>#a112ff</code>
      <small>Violet 400</small>
      <div><img src="logo/versions/Sourcegraph_Logomark_WHT.svg" alt="Primary logo color" style="width: 1em; height: 1em"></div>
    </div>
    <div class="color color-sm" style="--color: #820dde; color: white">
      <code>#820dde</code>
      <small>Violet 500</small>
    </div>
    <div class="color color-sm" style="--color: #6112a3; color: white">
      <code>#6112a3</code>
      <small>Violet 600</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #dbdbff">
      <code>#dbdbff</code>
      <small>Blurple 100</small>
    </div>
    <div class="color color-sm" style="--color: #bfbfff">
      <code>#bfbfff</code>
      <small>Blurple 200</small>
    </div>
    <div class="color color-sm" style="--color: #6b59ed; color: white">
      <code>#6b59ed</code>
      <small>Blurple 300</small>
    </div>
    <div class="color color-sm" style="--color: #5033E1; color: white">
      <code>#5033E1</code>
      <small>Blurple 400</small>
    </div>
    <div class="color color-sm" style="--color: #3826cc; color: white">
      <code>#3826cc</code>
      <small>Blurple 500</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #dcfefe">
      <code>#dcfefe</code>
      <small>Blue 100</small>
    </div>
    <div class="color color-sm" style="--color: #c7ffff">
      <code>#c7ffff</code>
      <small>Blue 200</small>
    </div>
    <div class="color color-sm" style="--color: var(--sg-sky-blue)">
      <code>#00cbec</code>
      <small>Blue 300</small>
      <div><img src="logo/versions/Sourcegraph_Logomark_WHT.svg" alt="Primary logo color" style="width: 1em; height: 1em"></div>
    </div>
    <div class="color color-sm" style="--color: #00a1c7; color: white">
      <code>#00a1c7</code>
      <small>Blue 400</small>
    </div>
    <div class="color color-sm" style="--color: #005482; color: white">
      <code>#005482</code>
      <small>Blue 500</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #d2fff1">
      <code>#d2fff1</code>
      <small>Green 100</small>
    </div>
    <div class="color color-sm" style="--color: #c4ffe8">
      <code>#c4ffe8</code>
      <small>Green 200</small>
    </div>
    <div class="color color-sm" style="--color: #8fedcf">
      <code>#8fedcf</code>
      <small>Green 300</small>
    </div>
    <div class="color color-sm" style="--color: #17ab52; color: white">
      <code>#17ab52</code>
      <small>Green 400</small>
    </div>
    <div class="color color-sm" style="--color: #1f7d45; color: white">
      <code>#1f7d45</code>
      <small>Green 500</small>
    </div>
  </div>
  <div class="color-palette-column">
    <div class="color color-sm" style="--color: #ffffff">
      <code>#ffffff</code>
      <small>White</small>
    </div>
    <div class="color color-sm" style="--color: #f9fafb">
      <code>#f9fafb</code>
      <small>Grayscale 50</small>
    </div>
    <div class="color color-sm" style="--color: #F5F7FB">
      <code>#f5f7fb</code>
      <small>Grayscale 100</small>
    </div>
    <div class="color color-sm" style="--color: #dbe2f0;">
      <code>#dbe2f0</code>
      <small>Grayscale 200</small>
    </div>
    <div class="color color-sm" style="--color: #ABB3C1;">
      <code>#abb3c1</code>
      <small>Grayscale 300</small>
    </div>
    <div class="color color-sm" style="--color: #696B71; color: white">
      <code>#696b71</code>
      <small>Grayscale 400</small>
    </div>
    <div class="color color-sm" style="--color: #484b51; color: white">
      <code>#484b51</code>
      <small>Grayscale 500</small>
    </div>
    <div class="color color-sm" style="--color: #313131; color: white">
      <code>#313131</code>
      <small>Grayscale 600</small>
    </div>
    <div class="color color-sm" style="--color: #000000; color: white">
      <code>#000000</code>
      <small>Black</small>
    </div>
  </div>
</div>

### Colors for website UI

Use supporting colors for added tonality and awareness within website UI.

<!-- IF ANY OF THESE COLORS ARE UPDATED, THEY NEED TO BE UPDATED IN ./colors.scss -->
<div class="color-palette interactive" style="max-width: 54rem">
  <div class="color color-lg" style="--color: #f9fafb">
    <h5>Sourcegraph Light Gray</h5>
    <p>Our light gray can add tonality to and create space within layouts.</p>
    <div>
      <code>#f9fafb</code>
      <br />
      <small>Grayscale 50</small>
    </div>
  </div>
   <div class="color color-lg" style="--color: #DBE2F0; color: black">
    <h5>Sourcegraph Medium Gray</h5>
    <p>Our medium gray can be used for borders and lines.</p>
    <div>
      <code>#dbe2f0</code>
      <br />
      <small>Grayscale 200</small>
    </div>
  </div>
  <div class="color color-lg" style="--color: #484B51; color: white">
    <h5>Sourcegraph Dark Gray</h5>
    <p>Our dark gray can add tonality and depth to typographical layouts.</p>
    <div>
      <code>#484b51</code>
      <br />
      <small>Grayscale 500</small>
    </div>
  </div>
  <div class="color color-lg" style="--color: black; color: white">
    <h5>Sourcegraph Black</h5>
    <p>Our black is a true black to provide maximum contrast.</p>
    <div>
      <code>#000000</code>
      <br />
      <small>Black</small>
    </div>
  </div>
  <div class="color color-lg" style="--color: var(--sg-blurple); color: white">
    <h5>Sourcegraph Blurple</h5>
    <p>Use for button and CTA messages in website UI.</p>
    <div>
      <code>#5033e1</code>
      <br />
      <small>Blurple 400</small>
    </div>
  </div>
  <div class="color color-lg" style="--color: var(--sg-action-green); color: white">
    <h5>Sourcegraph Action Green</h5>
    <p>Use for check marks and to signal positive messages in website UI.</p>
    <div>
      <code>#17ab52</code>
      <br />
      <small>Green 400</small>
    </div>
  </div>
  <div class="color color-lg" style="--color: var(--sg-alert-red); color: white">
    <h5>Sourcegraph Alert Red</h5>
    <p>Use for alerts and to signal error messages in website UI.</p>
    <div>
      <code>#ed2e20</code>
      <br />
      <small>Vermillion 400</small>
    </div>
  </div>
</div>

## Color use

When creating a layout, the logo should be the primary object that informs the rest of the layout.
Once the logo is placed, add appropriate colors keeping in mind that our vibrant colors can quickly become visually overwhelming.

<object role="image" data="color/color_use_1.svg" style="max-width: 22rem" alt="Example 1 of Sourcegraph color usage in marketing material"></object>
<object role="image" data="color/color_use_2.svg" style="max-width: 22rem" alt="Example 2 of Sourcegraph color usage in marketing material"></object>

### Color use for website UI

When applying color to website UI elements use Sourcegraph Red, Green, Dark Gray, and Blurple from our secondary palette. Violet can be used for icons.

<style>
  .inline-color-box {
    background: var(--color);
    width: 0.9em;
    height: 0.9em;
    display: inline-block;
    border-radius: 2px;
  }
</style>

#### <span class="inline-color-box middle" style="--color: var(--sg-blurple)"></span> <span class="middle">SG Blurple</span>

Blurple is used for button elements and CTA text.

#### <span class="inline-color-box middle" style="--color: var(--sg-action-green)"></span> <span class="middle">SG Action Green</span>

Green is used for check mark elements and to signal positive messages.

#### <span class="inline-color-box middle" style="--color: var(--sg-alert-red)"></span> <span class="middle">SG Alert Red</span>

Red is used to signal serious alerts and error warnings.

### Color misuse

Color should be used consistently to communicate a cohesive system.<br>
Do not alter existing colors or add new colors to the palette. Use color to your advantage—and not to the detriment of a design.

<style>
  .color-misuse {
    font-size: smaller;
    font-weight: bold;
  }
  .color-misuse > figcaption {
    height: 4rem;
  }
  .color-misuse > img {
    border: 1px solid #aaa;
  }
</style>

<div style="display: grid; grid-template-columns: repeat(auto-fit, 16rem); gap: 1rem">
  <figure class="color-misuse">
    <figcaption>Do not add new colors to the brand palette.</figcaption>
    <object role="image" data="color/color_misuse_new_colors.svg"></object>
  </figure>
  <figure class="color-misuse">
    <figcaption>Do not use too many colors in a design.</figcaption>
    <object role="image" data="color/color_misuse_too_many_colors.svg"></object>
  </figure>
  <figure class="color-misuse">
    <figcaption>Do not set text in a color that does not meet ADA requirements.</figcaption>
    <object role="image" data="color/color_misuse_ada.svg"></object>
  </figure>
  <figure class="color-misuse">
    <figcaption>Do not use Sourcegraph primary blue, or any other brand colors that don’t meet ADA compliance for text or UI elements.</figcaption>
    <object role="image" data="color/color_misuse_ada_ui.svg"></object>
  </figure>
  <figure class="color-misuse">
    <figcaption>Do not saturate a design with color.</figcaption>
    <object role="image" data="color/color_misuse_saturate.svg"></object>
  </figure>
  <figure class="color-misuse">
    <figcaption>Do not set the logo on a color or gradient that does not have sufficient contrast.</figcaption>
    <object role="image" data="color/color_misuse_contrast.svg"></object>
  </figure>
</div>

### Gradients

Our gradients provide visual interest to backgrounds or container shapes. Gradients should be used sparingly.

<style>
  .color-gradient {
    display: flex;
    justify-content: space-between;
  }
  .color-gradient h5 {
    margin: 0;
  }
</style>
<div class="color-palette" style="max-width: 54rem">
  <div>
    <h4>Aquamarine</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-aquamarine); color: white">
      <div>
        <h5>Blue 300</h5>
        <div><code>#00cbec</code></div>
      </div>
      <div>
        <h5>Blurple 400</h5>
        <div><code>#5033e1</code></div>
      </div>
    </div>
  </div>
  <div>
    <h4>Infrared</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-infrared); color: white">
      <div>
        <h5>Violet 400</h5>
        <div><code>#a112ff</code></div>
      </div>
      <div>
        <h5>Vermillion 300</h5>
        <div><code>#ff5543</code></div>
      </div>
    </div>
  </div>
  <div>
    <h4>Aurora</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-aurora); color: white">
      <div>
        <h5>Blue 300</h5>
        <div><code>#00cbec</code></div>
      </div>
      <div>
        <h5>Violet 400</h5>
        <div><code>#a112ff</code></div>
      </div>
    </div>
  </div>
  <div>
    <h4>Mars</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-mars)">
      <div>
        <h5>Vermillion 200</h5>
        <div><code>#ffc9c9</code></div>
      </div>
      <div>
        <h5>Violet 100</h5>
        <div><code>#e8d1ff</code></div>
      </div>
    </div>
  </div>
  <div>
    <h4>Saturn</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-saturn)">
      <div>
        <h5>Violet 100</h5>
        <div><code>#e8d1ff</code></div>
      </div>
      <div>
        <h5>Blue 200</h5>
        <div><code>#c7ffff</code></div>
      </div>
    </div>
  </div>
  <div>
    <h4>Venus</h4>
    <div class="color color-lg color-gradient" style="--color: var(--sg-gradient-venus)">
      <div>
        <h5>Blue 200</h5>
        <div><code>#c7ffff</code></div>
      </div>
      <div>
        <h5>Green 200</h5>
        <div><code>#c4ffe8</code></div>
      </div>
    </div>
  </div>
</div>

### Gradient use

See [PDF](https://sourcegraphstatic.com/Sourcegraph_Brand_Guidelines.pdf#page=32)

### Gradient misuse

See [PDF](https://sourcegraphstatic.com/Sourcegraph_Brand_Guidelines.pdf#page=33)

### Accessibility

See [PDF](https://sourcegraphstatic.com/Sourcegraph_Brand_Guidelines.pdf#page=34)
