<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="App">
    <section id="hero">

      <div class="container max-w-6xl mx-auto px-6 py-12">

        <nav class="flex items-center justify-between font-bold text-white">
          <img src="../public/logo.svg" alt="logo" />

          <div class="hidden h-10 font-alata md:flex md:space-x-8">
            <div class="group">
              <a href="/">About</a>
              <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
              <a href="/">Careers</a>
              <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
              <a href="/">Events</a>
              <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
              <a href="/">Products</a>
              <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
            <div class="group">
              <a href="/">Support</a>
              <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
            </div>
          </div>

          <div class="md:hidden">
            <button id="menu-btn" type="button" class="z-40 block hamburger md:hidden focus:outline-none">
              <span class="hamburger-top"></span>
              <span class="hamburger-middle"></span>
              <span class="hamburger-bottom"></span>
            </button>
          </div>
        </nav>
        <div id="menu"
          class="absolute top-0 bottom-0 left-0 hidden flex-col self-end w-full min-h-screen py-1 pt-40 pl-12 space-y-3 text-lg text-white uppercase bg-black">
          <a href="/About" class="hover:text-pink-500">About</a>
          <a href="/Careers" class="hover:text-pink-500">Careers</a>
          <a href="/Events" class="hover:text-pink-500">Events</a>
          <a href="/Products" class="hover:text-pink-500">Products</a>
          <a href="/Support" class="hover:text-pink-500">Support</a>
        </div>

        <div
          class="max-w-lg mt-32 mb-32 p-4 font-sans text-4xl text-white uppercase border-2 md:p-10 md:m-32 md:mx-0 md:text-6xl">
          Impressive Experiences That Deliver
        </div>
      </div>
    </section>
    <section id="feature">
      <div class="relative container flex flex-col max-w-6xl mx-auto my-32 px-6 text-gray-900 md:flex-row md:px-0">
        <img src="desktop/image-interactive.jpg" alt="" />
        <div class="top-48 pr-0 bg-white md:absolute md:right-0 md:py-20 md:pl-20">
          <h2
            class="max-w-lg mt-10 mb-6 font-sans text-4xl text-center text-gray-900 uppercase md:text-5xl md:mt-0 md:text-left">
            The leader in interactive VR
          </h2>

          <p class="max-w-md text-center md:text-left">
            Founded in 2011, Loopstudios has been producing world-class virtual
            reality projects for some of the best companies around the globe.
            Our award-winning creations have transformed businesses through
            digital experiences that bind to their brand.
          </p>
        </div>
      </div>
    </section>
    <section id="creations">
      <div class="container max-w-6xl mx-auto my-32 px-6 text-gray-900 md:px-0">
        <div class="flex justify-center mb-20 md:justify-between">
          <h2 class="text-4xl text-center uppercase md:text-left md:text-5xl">
            Our Creations
          </h2>

          <button class="hidden btn md:block">See All</button>
        </div>
        <div class="item-container">

          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-deep-earth.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-deep-earth.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>Deep Earth</h5>
          </div>

          <!-- {/* Item 2 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-night-arcade.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-night-arcade.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>Night Arcade</h5>
          </div>

          <!-- {/* Item 3 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-soccer-team.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-soccer-team.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>Soccer Team VR</h5>
          </div>

          <!-- {/* Item 4 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-grid.jpg" alt="" class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-grid.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>The Grid</h5>
          </div>
        </div>

        <!-- {/* Item Container 2 */} -->
        <div class="item-container mt-10">

          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-from-above.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-from-above.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>From Up Above VR</h5>
          </div>

          <!-- {/* Item 2 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-pocket-borealis.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-pocket-borealis.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>Pocket Borealis</h5>
          </div>

          <!-- {/* Item 3 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-curiosity.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-curiosity.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>The Curiosity</h5>
          </div>

          <!-- {/* Item 4 */} -->
          <div class="group item">
            <!-- {/* Desktop Image */} -->
            <img src="desktop/image-fisheye.jpg" alt=""
              class="hidden w-full duration-200 md:block group-hover:scale-110" />
            <img src="mobile/image-fisheye.jpg" alt="" class="w-full md:hidden" />
            <!-- {/* Item Gradient */} -->
            <div class="item-gradient"></div>
            <!-- {/* Item Text */} -->
            <h5>Make It Fisheye</h5>
          </div>
        </div>
        <!-- {/* Bottom Button Container */} -->
        <div class="flex justify-center mt-10 md:hidden">
          <button class="btn w-full md:hidden">See All</button>
        </div>
      </div>

      <HelloWorld msg="Vite + Vue" />

    </section>

    <footer class="bg-black">
      <!-- {/* Container */} -->
      <div class="container max-w-6xl py-10 mx-auto">
        <!-- {/* Footer Flex Container */} -->
        <div class="flex flex-col items-center mb-8 space-y-6 md:flex-row md:space-y-0 md:justify-between md:items-start">
          <!-- {/* Menu & Logo Container */} -->
          <div class="flex flex-col items-center space-y-8 md:items-start md:space-y-4">

            <div class="h-8">
              <img src="logo.svg" alt="" class="w-44 md:ml-3" />
            </div>
            <!-- {/* Menu Container */} -->
            <div
              class="flex flex-col items-center space-y-4 font-bold text-white md:flex-row md:space-y-0 md:space-x-6 md:ml-3">

              <div class="h-10 group">
                <a href="/">About</a>
                <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
              </div>
              <!-- {/* Item 2 */} -->
              <div class="h-10 group">
                <a href="/">Careers</a>
                <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
              </div>
              <!-- {/* Item 3 */} -->
              <div class="h-10 group">
                <a href="/">Events</a>
                <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
              </div>
              <!-- {/* Item 4 */} -->
              <div class="h-10 group">
                <a href="/">Products</a>
                <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
              </div>
              <!-- {/* Item 5 */} -->
              <div class="h-10 group">
                <a href="/">Support</a>
                <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
              </div>
            </div>
          </div>

          <!-- {/* Social & Copy Container */} -->
          <div class="flex flex-col items-start justify-between space-y-4 text-gray-500">
            <!-- {/* icons Container */} -->
            <div class="flex items-center justify-center mx-auto space-x-4 md:justify-end md:mx-0">
              <!-- {/* Icon 1 */} -->
              <div class="h-8 group">
                <a href="/">
                  <img src="icon-facebook.svg" alt="" class="h-6" />
                </a>
              </div>
              <!-- {/* Icon 2 */} -->
              <div class="h-8 group">
                <a href="/">
                  <img src="icon-twitter.svg" alt="" class="h-6" />
                </a>
              </div>
              <!-- {/* Icon 3 */} -->
              <div class="h-8 group">
                <a href="/">
                  <img src="icon-pinterest.svg" alt="" class="h-6" />
                </a>
              </div>
              <!-- {/* Icon 4 */} -->
              <div class="h-8 group">
                <a href="/">
                  <img src="icon-instagram.svg" alt="" class="h-6" />
                </a>
              </div>
            </div>

            <!-- {/* Copy */} -->
            <div class="font-bold">
              &copy; 2020 Loopstudios. All Rights Reserved
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>
/*
! tailwindcss v3.0.24 | MIT License | https://tailwindcss.com
*/

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: '';
}

/*
1. Use a consistent sensible line-height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
3. Use a more readable tab size.
4. Use the user's configured `sans` font-family by default.
*/

html {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
  tab-size: 4;
  /* 3 */
  font-family: Josefin Sans, sans-serif;
  /* 4 */
}

/*
1. Remove the margin in all browsers.
2. Inherit line-height from `html` so users can set them as a class directly on the `html` element.
*/

body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

/*
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
3. Ensure horizontal rules are visible by default.
*/

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

/*
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
}

/*
Remove the default font size and weight for headings.
*/

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/*
Reset links to optimize for opt-in styling instead of opt-out.
*/

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/*
1. Use the user's configured `mono` font family by default.
2. Correct the odd `em` font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-size: 1em;
  /* 2 */
}

/*
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  line-height: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
[type='button'],
[type='reset'],
[type='submit'] {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder,
textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input:-ms-input-placeholder,
textarea:-ms-input-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

/*
Ensure the default browser behavior of the `hidden` attribute.
*/

[hidden] {
  display: none;
}

h5 {
  position: absolute;
  bottom: 1rem;
  width: 13rem;
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  transition-duration: 200ms;
}

.group:hover h5 {
  --tw-scale-x: 1.1;
  --tw-scale-y: 1.1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  --tw-text-opacity: 1;
  color: rgb(0 0 0 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  h5 {
    bottom: 2rem;
    padding-left: 2.5rem;
    padding-right: 2.5rem;
  }
}

*,
::before,
::after {
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x: ;
  --tw-pan-y: ;
  --tw-pinch-zoom: ;
  --tw-scroll-snap-strictness: proximity;
  --tw-ordinal: ;
  --tw-slashed-zero: ;
  --tw-numeric-figure: ;
  --tw-numeric-spacing: ;
  --tw-numeric-fraction: ;
  --tw-ring-inset: ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur: ;
  --tw-brightness: ;
  --tw-contrast: ;
  --tw-grayscale: ;
  --tw-hue-rotate: ;
  --tw-invert: ;
  --tw-saturate: ;
  --tw-sepia: ;
  --tw-drop-shadow: ;
  --tw-backdrop-blur: ;
  --tw-backdrop-brightness: ;
  --tw-backdrop-contrast: ;
  --tw-backdrop-grayscale: ;
  --tw-backdrop-hue-rotate: ;
  --tw-backdrop-invert: ;
  --tw-backdrop-opacity: ;
  --tw-backdrop-saturate: ;
  --tw-backdrop-sepia: ;
}

.container {
  width: 100%;
}

@media (min-width: 480px) {
  .container {
    max-width: 480px;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 768px;
  }
}

@media (min-width: 976px) {
  .container {
    max-width: 976px;
  }
}

@media (min-width: 1440px) {
  .container {
    max-width: 1440px;
  }
}

.btn {
  margin-top: 0px;
  margin-bottom: 0px;
  border-width: 2px;
  --tw-border-opacity: 1;
  border-color: rgb(0 0 0 / var(--tw-border-opacity));
  padding-left: 2.5rem;
  padding-right: 2.5rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  font-family: Alata;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: .3em;
}

.btn:hover {
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.absolute {
  position: absolute;
}

.relative {
  position: relative;
}

.top-48 {
  top: 12rem;
}

.top-0 {
  top: 0px;
}

.bottom-0 {
  bottom: 0px;
}

.left-0 {
  left: 0px;
}

.z-40 {
  z-index: 40;
}

.mx-auto {
  margin-left: auto;
  margin-right: auto;
}

.mx-2 {
  margin-left: 0.5rem;
  margin-right: 0.5rem;
}

.my-32 {
  margin-top: 8rem;
  margin-bottom: 8rem;
}

.mt-32 {
  margin-top: 8rem;
}

.mb-32 {
  margin-bottom: 8rem;
}

.mt-10 {
  margin-top: 2.5rem;
}

.mb-6 {
  margin-bottom: 1.5rem;
}

.mb-20 {
  margin-bottom: 5rem;
}

.mb-8 {
  margin-bottom: 2rem;
}

.block {
  display: block;
}

.flex {
  display: flex;
}

.hidden {
  display: none;
}

.h-10 {
  height: 2.5rem;
}

.h-8 {
  height: 2rem;
}

.h-6 {
  height: 1.5rem;
}

.min-h-screen {
  min-height: 100vh;
}

.w-full {
  width: 100%;
}

.w-44 {
  width: 11rem;
}

.max-w-6xl {
  max-width: 72rem;
}

.max-w-lg {
  max-width: 32rem;
}

.max-w-md {
  max-width: 28rem;
}

.flex-col {
  flex-direction: column;
}

.items-start {
  align-items: flex-start;
}

.items-center {
  align-items: center;
}

.justify-center {
  justify-content: center;
}

.justify-between {
  justify-content: space-between;
}

.space-y-6> :not([hidden])~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
}

.space-y-8> :not([hidden])~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(2rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(2rem * var(--tw-space-y-reverse));
}

.space-y-4> :not([hidden])~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(1rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1rem * var(--tw-space-y-reverse));
}

.space-x-4> :not([hidden])~ :not([hidden]) {
  --tw-space-x-reverse: 0;
  margin-right: calc(1rem * var(--tw-space-x-reverse));
  margin-left: calc(1rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-y-3> :not([hidden])~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.75rem * var(--tw-space-y-reverse));
}

.self-end {
  align-self: flex-end;
}

.border-2 {
  border-width: 2px;
}

.bg-white {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.bg-black {
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
}

.p-4 {
  padding: 1rem;
}

.px-6 {
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.py-12 {
  padding-top: 3rem;
  padding-bottom: 3rem;
}

.py-10 {
  padding-top: 2.5rem;
  padding-bottom: 2.5rem;
}

.py-1 {
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
}

.pr-0 {
  padding-right: 0px;
}

.pt-40 {
  padding-top: 10rem;
}

.pl-12 {
  padding-left: 3rem;
}

.text-center {
  text-align: center;
}

.font-alata {
  font-family: Alata;
}

.font-sans {
  font-family: Josefin Sans, sans-serif;
}

.text-4xl {
  font-size: 2.25rem;
  line-height: 2.5rem;
}

.text-lg {
  font-size: 1.125rem;
  line-height: 1.75rem;
}

.font-bold {
  font-weight: 700;
}

.uppercase {
  text-transform: uppercase;
}

.text-white {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.text-gray-900 {
  --tw-text-opacity: 1;
  color: rgb(17 24 39 / var(--tw-text-opacity));
}

.text-gray-500 {
  --tw-text-opacity: 1;
  color: rgb(107 114 128 / var(--tw-text-opacity));
}

.duration-200 {
  transition-duration: 200ms;
}

.item-container {
  display: flex;
  width: 100%;
  flex-direction: column;
  justify-content: space-between;
}

.item-container> :not([hidden])~ :not([hidden]) {
  --tw-space-y-reverse: 0;
  margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
}

.item-container {
  font-size: 1.5rem;
  line-height: 2rem;
  text-transform: uppercase;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  .item-container {
    flex-direction: row;
  }

  .item-container> :not([hidden])~ :not([hidden]) {
    --tw-space-y-reverse: 0;
    margin-top: calc(0px * calc(1 - var(--tw-space-y-reverse)));
    margin-bottom: calc(0px * var(--tw-space-y-reverse));
    --tw-space-x-reverse: 0;
    margin-right: calc(2rem * var(--tw-space-x-reverse));
    margin-left: calc(2rem * calc(1 - var(--tw-space-x-reverse)));
  }
}

.item {
  position: relative;
  overflow: hidden;
}

@media (min-width: 768px) {
  .item {
    width: 25%;
  }
}

.item-gradient {
  position: absolute;
  top: 0px;
  bottom: 0px;
  right: 0px;
  left: 0px;
  background-image: linear-gradient(to bottom, var(--tw-gradient-stops));
  --tw-gradient-from: transparent;
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to, rgb(0 0 0 / 0));
  --tw-gradient-to: #111827;
}

.group:hover .item-gradient {
  --tw-gradient-from: #f9fafb;
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to, rgb(249 250 251 / 0));
  --tw-gradient-to: #fff;
  opacity: 0.7;
}

#hero {
  background-image: url('../../desktop/image-hero.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  min-width: 80rem;
}

@media (max-width: 576px) {
  #hero {
    background-image: url('../../mobile/image-hero.jpg');
    background-position: center;
  }
}

/* Hamburger Menu */

.hamburger {
  cursor: pointer;
  width: 24px;
  height: 24px;
  transition: all 0.25s;
  position: relative;
}

.hamburger-top,
.hamburger-middle,
.hamburger-bottom {
  position: absolute;
  width: 24px;
  height: 2px;
  top: 0;
  left: 0;
  background: #fff;
  transform: rotate(0);
  transition: all 0.5s;
}

.hamburger-middle {
  transform: translateY(7px);
}

.hamburger-bottom {
  transform: translateY(14px);
}

.open {
  transform: rotate(90deg);
}

.open .hamburger-top {
  transform: rotate(45deg) translateY(6px) translateX(6px);
}

.open .hamburger-middle {
  display: none;
}

.open .hamburger-bottom {
  transform: rotate(-45deg) translateY(6px) translateX(-6px);
}

.hover\:text-pink-500:hover {
  --tw-text-opacity: 1;
  color: rgb(236 72 153 / var(--tw-text-opacity));
}

.focus\:outline-none:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.group:hover .group-hover\:scale-110 {
  --tw-scale-x: 1.1;
  --tw-scale-y: 1.1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.group:hover .group-hover\:border-b {
  border-bottom-width: 1px;
}

.group:hover .group-hover\:border-blue-50 {
  --tw-border-opacity: 1;
  border-color: rgb(239 246 255 / var(--tw-border-opacity));
}

@media (min-width: 768px) {
  .md\:absolute {
    position: absolute;
  }

  .md\:right-0 {
    right: 0px;
  }

  .md\:m-32 {
    margin: 8rem;
  }

  .md\:mx-0 {
    margin-left: 0px;
    margin-right: 0px;
  }

  .md\:mt-0 {
    margin-top: 0px;
  }

  .md\:ml-3 {
    margin-left: 0.75rem;
  }

  .md\:block {
    display: block;
  }

  .md\:flex {
    display: flex;
  }

  .md\:hidden {
    display: none;
  }

  .md\:flex-row {
    flex-direction: row;
  }

  .md\:items-start {
    align-items: flex-start;
  }

  .md\:justify-end {
    justify-content: flex-end;
  }

  .md\:justify-between {
    justify-content: space-between;
  }

  .md\:space-x-8> :not([hidden])~ :not([hidden]) {
    --tw-space-x-reverse: 0;
    margin-right: calc(2rem * var(--tw-space-x-reverse));
    margin-left: calc(2rem * calc(1 - var(--tw-space-x-reverse)));
  }

  .md\:space-y-0> :not([hidden])~ :not([hidden]) {
    --tw-space-y-reverse: 0;
    margin-top: calc(0px * calc(1 - var(--tw-space-y-reverse)));
    margin-bottom: calc(0px * var(--tw-space-y-reverse));
  }

  .md\:space-y-4> :not([hidden])~ :not([hidden]) {
    --tw-space-y-reverse: 0;
    margin-top: calc(1rem * calc(1 - var(--tw-space-y-reverse)));
    margin-bottom: calc(1rem * var(--tw-space-y-reverse));
  }

  .md\:space-x-6> :not([hidden])~ :not([hidden]) {
    --tw-space-x-reverse: 0;
    margin-right: calc(1.5rem * var(--tw-space-x-reverse));
    margin-left: calc(1.5rem * calc(1 - var(--tw-space-x-reverse)));
  }

  .md\:p-10 {
    padding: 2.5rem;
  }

  .md\:px-0 {
    padding-left: 0px;
    padding-right: 0px;
  }

  .md\:py-20 {
    padding-top: 5rem;
    padding-bottom: 5rem;
  }

  .md\:pl-20 {
    padding-left: 5rem;
  }

  .md\:text-left {
    text-align: left;
  }

  .md\:text-6xl {
    font-size: 3.75rem;
    line-height: 1;
  }

  .md\:text-5xl {
    font-size: 3rem;
    line-height: 1;
  }
}
</style>
