<script>
  import Webmock from './components/webmock.svelte'
</script>

<main>
  <Webmock/>
</main>

<style lang="postcss" global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  @font-face {
  font-family: swiper-icons;
  src: url("data:application/font-woff;charset=utf-8;base64, d09GRgABAAAAAAZgABAAAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABGRlRNAAAGRAAAABoAAAAci6qHkUdERUYAAAWgAAAAIwAAACQAYABXR1BPUwAABhQAAAAuAAAANuAY7+xHU1VCAAAFxAAAAFAAAABm2fPczU9TLzIAAAHcAAAASgAAAGBP9V5RY21hcAAAAkQAAACIAAABYt6F0cBjdnQgAAACzAAAAAQAAAAEABEBRGdhc3AAAAWYAAAACAAAAAj//wADZ2x5ZgAAAywAAADMAAAD2MHtryVoZWFkAAABbAAAADAAAAA2E2+eoWhoZWEAAAGcAAAAHwAAACQC9gDzaG10eAAAAigAAAAZAAAArgJkABFsb2NhAAAC0AAAAFoAAABaFQAUGG1heHAAAAG8AAAAHwAAACAAcABAbmFtZQAAA/gAAAE5AAACXvFdBwlwb3N0AAAFNAAAAGIAAACE5s74hXjaY2BkYGAAYpf5Hu/j+W2+MnAzMYDAzaX6QjD6/4//Bxj5GA8AuRwMYGkAPywL13jaY2BkYGA88P8Agx4j+/8fQDYfA1AEBWgDAIB2BOoAeNpjYGRgYNBh4GdgYgABEMnIABJzYNADCQAACWgAsQB42mNgYfzCOIGBlYGB0YcxjYGBwR1Kf2WQZGhhYGBiYGVmgAFGBiQQkOaawtDAoMBQxXjg/wEGPcYDDA4wNUA2CCgwsAAAO4EL6gAAeNpj2M0gyAACqxgGNWBkZ2D4/wMA+xkDdgAAAHjaY2BgYGaAYBkGRgYQiAHyGMF8FgYHIM3DwMHABGQrMOgyWDLEM1T9/w8UBfEMgLzE////P/5//f/V/xv+r4eaAAeMbAxwIUYmIMHEgKYAYjUcsDAwsLKxc3BycfPw8jEQA/gZBASFhEVExcQlJKWkZWTl5BUUlZRVVNXUNTQZBgMAAMR+E+gAEQFEAAAAKgAqACoANAA+AEgAUgBcAGYAcAB6AIQAjgCYAKIArAC2AMAAygDUAN4A6ADyAPwBBgEQARoBJAEuATgBQgFMAVYBYAFqAXQBfgGIAZIBnAGmAbIBzgHsAAB42u2NMQ6CUAyGW568x9AneYYgm4MJbhKFaExIOAVX8ApewSt4Bic4AfeAid3VOBixDxfPYEza5O+Xfi04YADggiUIULCuEJK8VhO4bSvpdnktHI5QCYtdi2sl8ZnXaHlqUrNKzdKcT8cjlq+rwZSvIVczNiezsfnP/uznmfPFBNODM2K7MTQ45YEAZqGP81AmGGcF3iPqOop0r1SPTaTbVkfUe4HXj97wYE+yNwWYxwWu4v1ugWHgo3S1XdZEVqWM7ET0cfnLGxWfkgR42o2PvWrDMBSFj/IHLaF0zKjRgdiVMwScNRAoWUoH78Y2icB/yIY09An6AH2Bdu/UB+yxopYshQiEvnvu0dURgDt8QeC8PDw7Fpji3fEA4z/PEJ6YOB5hKh4dj3EvXhxPqH/SKUY3rJ7srZ4FZnh1PMAtPhwP6fl2PMJMPDgeQ4rY8YT6Gzao0eAEA409DuggmTnFnOcSCiEiLMgxCiTI6Cq5DZUd3Qmp10vO0LaLTd2cjN4fOumlc7lUYbSQcZFkutRG7g6JKZKy0RmdLY680CDnEJ+UMkpFFe1RN7nxdVpXrC4aTtnaurOnYercZg2YVmLN/d/gczfEimrE/fs/bOuq29Zmn8tloORaXgZgGa78yO9/cnXm2BpaGvq25Dv9S4E9+5SIc9PqupJKhYFSSl47+Qcr1mYNAAAAeNptw0cKwkAAAMDZJA8Q7OUJvkLsPfZ6zFVERPy8qHh2YER+3i/BP83vIBLLySsoKimrqKqpa2hp6+jq6RsYGhmbmJqZSy0sraxtbO3sHRydnEMU4uR6yx7JJXveP7WrDycAAAAAAAH//wACeNpjYGRgYOABYhkgZgJCZgZNBkYGLQZtIJsFLMYAAAw3ALgAeNolizEKgDAQBCchRbC2sFER0YD6qVQiBCv/H9ezGI6Z5XBAw8CBK/m5iQQVauVbXLnOrMZv2oLdKFa8Pjuru2hJzGabmOSLzNMzvutpB3N42mNgZGBg4GKQYzBhYMxJLMlj4GBgAYow/P/PAJJhLM6sSoWKfWCAAwDAjgbRAAB42mNgYGBkAIIbCZo5IPrmUn0hGA0AO8EFTQAA")
    format("woff");
  font-weight: 400;
  font-style: normal;
}
:root {
  --swiper-theme-color: #007aff;
}
.swiper {
  margin-left: auto;
  margin-right: auto;
  position: relative;
  overflow: hidden;
  list-style: none;
  padding: 0;
  z-index: 1;
}
.swiper-vertical > .swiper-wrapper {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.swiper-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-transition-property: -webkit-transform;
  transition-property: -webkit-transform;
  transition-property: transform;
  transition-property: transform, -webkit-transform;
  -webkit-box-sizing: content-box;
  box-sizing: content-box;
}
.swiper-android .swiper-slide,
.swiper-wrapper {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
.swiper-pointer-events {
  -ms-touch-action: pan-y;
  touch-action: pan-y;
}
.swiper-pointer-events.swiper-vertical {
  -ms-touch-action: pan-x;
  touch-action: pan-x;
}
.swiper-slide {
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  width: 100%;
  height: 100%;
  position: relative;
  -webkit-transition-property: -webkit-transform;
  transition-property: -webkit-transform;
  transition-property: transform;
  transition-property: transform, -webkit-transform;
}
.swiper-slide-invisible-blank {
  visibility: hidden;
}
.swiper-autoheight,
.swiper-autoheight .swiper-slide {
  height: auto;
}
.swiper-autoheight .swiper-wrapper {
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  -webkit-transition-property: height, -webkit-transform;
  transition-property: height, -webkit-transform;
  transition-property: transform, height;
  transition-property: transform, height, -webkit-transform;
}
.swiper-3d,
.swiper-3d.swiper-css-mode .swiper-wrapper {
  -webkit-perspective: 1200px;
  perspective: 1200px;
}
.swiper-3d .swiper-cube-shadow,
.swiper-3d .swiper-slide,
.swiper-3d .swiper-slide-shadow,
.swiper-3d .swiper-slide-shadow-bottom,
.swiper-3d .swiper-slide-shadow-left,
.swiper-3d .swiper-slide-shadow-right,
.swiper-3d .swiper-slide-shadow-top,
.swiper-3d .swiper-wrapper {
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}
.swiper-3d .swiper-slide-shadow,
.swiper-3d .swiper-slide-shadow-bottom,
.swiper-3d .swiper-slide-shadow-left,
.swiper-3d .swiper-slide-shadow-right,
.swiper-3d .swiper-slide-shadow-top {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 10;
}
.swiper-3d .swiper-slide-shadow {
  background: rgba(0, 0, 0, 0.15);
}
.swiper-3d .swiper-slide-shadow-left {
  background-image: -webkit-gradient(
    linear,
    right top,
    left top,
    from(rgba(0, 0, 0, 0.5)),
    to(rgba(0, 0, 0, 0))
  );
  background-image: linear-gradient(
    to left,
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0)
  );
}
.swiper-3d .swiper-slide-shadow-right {
  background-image: -webkit-gradient(
    linear,
    left top,
    right top,
    from(rgba(0, 0, 0, 0.5)),
    to(rgba(0, 0, 0, 0))
  );
  background-image: linear-gradient(
    to right,
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0)
  );
}
.swiper-3d .swiper-slide-shadow-top {
  background-image: -webkit-gradient(
    linear,
    left bottom,
    left top,
    from(rgba(0, 0, 0, 0.5)),
    to(rgba(0, 0, 0, 0))
  );
  background-image: linear-gradient(
    to top,
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0)
  );
}
.swiper-3d .swiper-slide-shadow-bottom {
  background-image: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(rgba(0, 0, 0, 0.5)),
    to(rgba(0, 0, 0, 0))
  );
  background-image: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0)
  );
}
.swiper-css-mode > .swiper-wrapper {
  overflow: auto;
  scrollbar-width: none;
  -ms-overflow-style: none;
}
.swiper-css-mode > .swiper-wrapper::-webkit-scrollbar {
  display: none;
}
.swiper-css-mode > .swiper-wrapper > .swiper-slide {
  scroll-snap-align: start start;
}
.swiper-horizontal.swiper-css-mode > .swiper-wrapper {
  -webkit-scroll-snap-type: x mandatory;
  -ms-scroll-snap-type: x mandatory;
  scroll-snap-type: x mandatory;
}
.swiper-vertical.swiper-css-mode > .swiper-wrapper {
  -webkit-scroll-snap-type: y mandatory;
  -ms-scroll-snap-type: y mandatory;
  scroll-snap-type: y mandatory;
}
.swiper-centered > .swiper-wrapper::before {
  content: "";
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-box-ordinal-group: 10000;
  -webkit-order: 9999;
  -ms-flex-order: 9999;
  order: 9999;
}
.swiper-centered.swiper-horizontal
  > .swiper-wrapper
  > .swiper-slide:first-child {
  -webkit-margin-start: var(--swiper-centered-offset-before);
  margin-inline-start: var(--swiper-centered-offset-before);
}
.swiper-centered.swiper-horizontal > .swiper-wrapper::before {
  height: 100%;
  width: var(--swiper-centered-offset-after);
}
.swiper-centered.swiper-vertical > .swiper-wrapper > .swiper-slide:first-child {
  -webkit-margin-before: var(--swiper-centered-offset-before);
  margin-block-start: var(--swiper-centered-offset-before);
}
.swiper-centered.swiper-vertical > .swiper-wrapper::before {
  width: 100%;
  height: var(--swiper-centered-offset-after);
}
.swiper-centered > .swiper-wrapper > .swiper-slide {
  scroll-snap-align: center center;
} /*!normalize.css v8.0.0 | MIT License | github.com/necolas/normalize.css*/
html {
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
hr {
  -webkit-box-sizing: content-box;
  box-sizing: content-box;
  height: 0;
  overflow: visible;
}
pre {
  font-family: monospace, monospace;
  font-size: 1em;
}
a {
  background-color: transparent;
}
abbr[title] {
  border-bottom: none;
  text-decoration: underline;
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
}
b,
strong {
  font-weight: bolder;
}
code,
kbd,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
small {
  font-size: 80%;
}
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
img {
  border-style: none;
}
button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
  line-height: 1.15;
  margin: 0;
}
button,
input {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
[type="button"],
[type="reset"],
[type="submit"],
button {
  -webkit-appearance: button;
}
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner,
button::-moz-focus-inner {
  border-style: none;
  padding: 0;
}
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring,
button:-moz-focusring {
  outline: 1px dotted ButtonText;
}
fieldset {
  padding: 0.35em 0.75em 0.625em;
}
legend {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  color: inherit;
  display: table;
  max-width: 100%;
  padding: 0;
  white-space: normal;
}
progress {
  vertical-align: baseline;
}
textarea {
  overflow: auto;
}
[type="checkbox"],
[type="radio"] {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  padding: 0;
}
[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
[type="search"] {
  -webkit-appearance: textfield;
  outline-offset: -2px;
}
[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
::-webkit-file-upload-button {
  -webkit-appearance: button;
  font: inherit;
}
details {
  display: block;
}
summary {
  display: list-item;
}
template {
  display: none;
}
[hidden] {
  display: none;
}
.foundation-mq {
  font-family: "small=0em&medium=48.0625em&large=64.0625em&xlarge=75em&xxlarge=90em&375=23.4375em&600=37.5em&768=48em&1024=64em&1280=80em";
}
html {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-size: 100%;
}
*,
::after,
::before {
  -webkit-box-sizing: inherit;
  box-sizing: inherit;
}
body {
  margin: 0;
  padding: 0;
  background: #fff;
  font-family: "eina 02", Helvetica, Roboto, Arial, sans-serif;
  font-weight: 400;
  line-height: 1.5;
  color: #000c2c;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
img {
  display: inline-block;
  vertical-align: middle;
  max-width: 100%;
  height: auto;
  -ms-interpolation-mode: bicubic;
}
textarea {
  height: auto;
  min-height: 50px;
  border-radius: 0;
}
select {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  width: 100%;
  border-radius: 0;
}
.map_canvas embed,
.map_canvas img,
.map_canvas object,
.mqa-display embed,
.mqa-display img,
.mqa-display object {
  max-width: none !important;
}
button {
  padding: 0;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  border: 0;
  border-radius: 0;
  background: 0 0;
  line-height: 1;
  cursor: auto;
}
[data-whatinput="mouse"] button {
  outline: 0;
}
pre {
  overflow: auto;
}
button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
}
.is-visible {
  display: block !important;
}
.is-hidden {
  display: none !important;
}
blockquote,
dd,
div,
dl,
dt,
form,
h1,
h2,
h3,
h4,
h5,
h6,
li,
ol,
p,
pre,
td,
th,
ul {
  margin: 0;
  padding: 0;
}
p {
  margin-bottom: 1rem;
  font-size: inherit;
  line-height: 1.6;
  text-rendering: optimizeLegibility;
}
em,
i {
  font-style: italic;
  line-height: inherit;
}
b,
strong {
  font-weight: 700;
  line-height: inherit;
}
small {
  font-size: 80%;
  line-height: inherit;
}
.card--article .card-section .headline,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "eina 02", Helvetica, Roboto, Arial, sans-serif;
  font-style: normal;
  font-weight: 700;
  color: inherit;
  text-rendering: optimizeLegibility;
}
.card--article .card-section .headline small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small {
  line-height: 0;
  color: #f8f8f8;
}
.h1,
h1 {
  font-size: 2rem;
  line-height: 1.1875;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.h2,
h2 {
  font-size: 2rem;
  line-height: 1.1875;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.h3,
h3 {
  font-size: 1.5rem;
  line-height: 1.375;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.h4,
h4 {
  font-size: 1.125rem;
  line-height: 1.16667;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.card--article .card-section .headline,
.h5,
h5 {
  font-size: 1.0625rem;
  line-height: 1.4;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.h6,
h6 {
  font-size: 1rem;
  line-height: 1.4;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.h7,
h7 {
  font-size: 0.625rem;
  line-height: 1.2;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
@media print, screen and (min-width: 48.0625em) {
  .h1,
  h1 {
    font-size: 2.25rem;
    line-height: 1.19444;
  }
  .h2,
  h2 {
    font-size: 2rem;
    line-height: 1.1875;
  }
  .h3,
  h3 {
    font-size: 1.5rem;
    line-height: 1.375;
  }
  .h4,
  h4 {
    font-size: 1.125rem;
  }
  .card--article .card-section .headline,
  .h5,
  h5 {
    font-size: 1.0625rem;
  }
  .h6,
  h6 {
    font-size: 1rem;
  }
  .h7,
  h7 {
    font-size: 0.625rem;
    line-height: 1.2;
  }
}
@media screen and (min-width: 75em) {
  .h1,
  h1 {
    font-size: 3rem;
    line-height: 1.20833;
  }
  .h2,
  h2 {
    font-size: 2.25rem;
    line-height: 1.19444;
  }
  .h3,
  h3 {
    font-size: 1.5rem;
    line-height: 1.375;
  }
  .h4,
  h4 {
    font-size: 1.25rem;
  }
  .card--article .card-section .headline,
  .h5,
  h5 {
    font-size: 1.125rem;
  }
  .h6,
  h6 {
    font-size: 1rem;
  }
  .h7,
  h7 {
    font-size: 0.625rem;
    line-height: 1.2;
  }
}
a {
  line-height: inherit;
  color: #0569ff;
  text-decoration: none;
  cursor: pointer;
}
a:focus,
a:hover {
  color: #0059e0;
}
a img {
  border: 0;
}
hr {
  clear: both;
  max-width: 71rem;
  height: 0;
  margin: 1.25rem auto;
  border-top: 0;
  border-right: 0;
  border-bottom: 1px solid #f8f8f8;
  border-left: 0;
}
dl,
ol,
ul {
  margin-bottom: 1rem;
  list-style-position: outside;
  line-height: 1.6;
}
li {
  font-size: inherit;
}
ul {
  margin-left: 1.25rem;
  list-style-type: disc;
}
ol {
  margin-left: 1.25rem;
}
ol ol,
ol ul,
ul ol,
ul ul {
  margin-left: 1.25rem;
  margin-bottom: 0;
}
dl {
  margin-bottom: 1rem;
}
dl dt {
  margin-bottom: 0.3rem;
  font-weight: 700;
}
blockquote {
  margin: 0 0 1rem;
  padding: 0.5625rem 1.25rem 0 1.1875rem;
  border-left: 1px solid #f8f8f8;
}
blockquote,
blockquote p {
  line-height: 1.6;
  color: #11171f;
}
abbr,
abbr[title] {
  border-bottom: 1px dotted #000c2c;
  cursor: help;
  text-decoration: none;
}
figure {
  margin: 0;
}
kbd {
  margin: 0;
  padding: 0.125rem 0.25rem 0;
  background-color: #fafafb;
  font-family: Consolas, liberation mono, Courier, monospace;
  color: #000c2c;
}
.subheader {
  margin-top: 0.2rem;
  margin-bottom: 0.5rem;
  font-weight: 400;
  line-height: 1.4;
  color: #11171f;
}
.lead {
  font-size: 125%;
  line-height: 1.6;
}
.stat {
  font-size: 2.5rem;
  line-height: 1;
}
p + .stat {
  margin-top: -1rem;
}
ol.no-bullet,
ul.no-bullet {
  margin-left: 0;
  list-style: none;
}
.cite-block,
cite {
  display: block;
  color: #11171f;
  font-size: 0.8125rem;
}
.cite-block:before,
cite:before {
  content: "â€” ";
}
.code-inline,
code {
  border: 1px solid #cacaca;
  background-color: #e6e6e6;
  font-family: Consolas, liberation mono, Courier, monospace;
  font-weight: 400;
  color: #000c2c;
  display: inline;
  max-width: 100%;
  word-wrap: break-word;
  padding: 0.125rem 0.3125rem 0.0625rem;
}
.code-block {
  border: 1px solid #cacaca;
  background-color: #e6e6e6;
  font-family: Consolas, liberation mono, Courier, monospace;
  font-weight: 400;
  color: #000c2c;
  display: block;
  overflow: auto;
  white-space: pre;
  padding: 1rem;
  margin-bottom: 1.5rem;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
@media print, screen and (min-width: 48.0625em) {
  .medium-text-left {
    text-align: left;
  }
  .medium-text-right {
    text-align: right;
  }
  .medium-text-center {
    text-align: center;
  }
  .medium-text-justify {
    text-align: justify;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-text-left {
    text-align: left;
  }
  .large-text-right {
    text-align: right;
  }
  .large-text-center {
    text-align: center;
  }
  .large-text-justify {
    text-align: justify;
  }
}
.show-for-print {
  display: none !important;
}
@media print {
  * {
    background: 0 0 !important;
    color: #000 !important;
    -webkit-print-color-adjust: economy;
    color-adjust: economy;
    -webkit-box-shadow: none !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  .show-for-print {
    display: block !important;
  }
  .hide-for-print {
    display: none !important;
  }
  table.show-for-print {
    display: table !important;
  }
  thead.show-for-print {
    display: table-header-group !important;
  }
  tbody.show-for-print {
    display: table-row-group !important;
  }
  tr.show-for-print {
    display: table-row !important;
  }
  td.show-for-print {
    display: table-cell !important;
  }
  th.show-for-print {
    display: table-cell !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  .ir a:after,
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  blockquote,
  pre {
    border: 1px solid #11171f;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  img,
  tr {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  @page {
    margin: 0.5cm;
  }
  h2,
  h3,
  p {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .print-break-inside {
    page-break-inside: auto;
  }
}
.grid-container {
  padding-right: 0.9375rem;
  padding-left: 0.9375rem;
  max-width: 71rem;
  margin-left: auto;
  margin-right: auto;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-container {
    padding-right: 0.9375rem;
    padding-left: 0.9375rem;
  }
}
.grid-container.fluid {
  padding-right: 0.9375rem;
  padding-left: 0.9375rem;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-container.fluid {
    padding-right: 0.9375rem;
    padding-left: 0.9375rem;
  }
}
.grid-container.full {
  padding-right: 0;
  padding-left: 0;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
}
.grid-x {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-flow: row wrap;
  -ms-flex-flow: row wrap;
  flex-flow: row wrap;
}
.cell {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  min-height: 0;
  min-width: 0;
  width: 100%;
}
.cell.auto {
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 0;
  -ms-flex: 1 1 0;
  flex: 1 1 0px;
}
.cell.shrink {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}
.grid-x > .auto {
  width: auto;
}
.grid-x > .shrink {
  width: auto;
}
.grid-x > .small-1,
.grid-x > .small-10,
.grid-x > .small-11,
.grid-x > .small-12,
.grid-x > .small-2,
.grid-x > .small-3,
.grid-x > .small-4,
.grid-x > .small-5,
.grid-x > .small-6,
.grid-x > .small-7,
.grid-x > .small-8,
.grid-x > .small-9,
.grid-x > .small-full,
.grid-x > .small-shrink {
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-x > .medium-1,
  .grid-x > .medium-10,
  .grid-x > .medium-11,
  .grid-x > .medium-12,
  .grid-x > .medium-2,
  .grid-x > .medium-3,
  .grid-x > .medium-4,
  .grid-x > .medium-5,
  .grid-x > .medium-6,
  .grid-x > .medium-7,
  .grid-x > .medium-8,
  .grid-x > .medium-9,
  .grid-x > .medium-full,
  .grid-x > .medium-shrink {
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-x > .large-1,
  .grid-x > .large-10,
  .grid-x > .large-11,
  .grid-x > .large-12,
  .grid-x > .large-2,
  .grid-x > .large-3,
  .grid-x > .large-4,
  .grid-x > .large-5,
  .grid-x > .large-6,
  .grid-x > .large-7,
  .grid-x > .large-8,
  .grid-x > .large-9,
  .grid-x > .large-full,
  .grid-x > .large-shrink {
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }
}
.grid-x > .small-1,
.grid-x > .small-10,
.grid-x > .small-11,
.grid-x > .small-12,
.grid-x > .small-2,
.grid-x > .small-3,
.grid-x > .small-4,
.grid-x > .small-5,
.grid-x > .small-6,
.grid-x > .small-7,
.grid-x > .small-8,
.grid-x > .small-9 {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}
.grid-x > .small-1 {
  width: 8.33333%;
}
.grid-x > .small-2 {
  width: 16.66667%;
}
.grid-x > .small-3 {
  width: 25%;
}
.grid-x > .small-4 {
  width: 33.33333%;
}
.grid-x > .small-5 {
  width: 41.66667%;
}
.grid-x > .small-6 {
  width: 50%;
}
.grid-x > .small-7 {
  width: 58.33333%;
}
.grid-x > .small-8 {
  width: 66.66667%;
}
.grid-x > .small-9 {
  width: 75%;
}
.grid-x > .small-10 {
  width: 83.33333%;
}
.grid-x > .small-11 {
  width: 91.66667%;
}
.grid-x > .small-12 {
  width: 100%;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-x > .medium-auto {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
    width: auto;
  }
  .grid-x > .medium-1,
  .grid-x > .medium-10,
  .grid-x > .medium-11,
  .grid-x > .medium-12,
  .grid-x > .medium-2,
  .grid-x > .medium-3,
  .grid-x > .medium-4,
  .grid-x > .medium-5,
  .grid-x > .medium-6,
  .grid-x > .medium-7,
  .grid-x > .medium-8,
  .grid-x > .medium-9,
  .grid-x > .medium-shrink {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .grid-x > .medium-shrink {
    width: auto;
  }
  .grid-x > .medium-1 {
    width: 8.33333%;
  }
  .grid-x > .medium-2 {
    width: 16.66667%;
  }
  .grid-x > .medium-3 {
    width: 25%;
  }
  .grid-x > .medium-4 {
    width: 33.33333%;
  }
  .grid-x > .medium-5 {
    width: 41.66667%;
  }
  .grid-x > .medium-6 {
    width: 50%;
  }
  .grid-x > .medium-7 {
    width: 58.33333%;
  }
  .grid-x > .medium-8 {
    width: 66.66667%;
  }
  .grid-x > .medium-9 {
    width: 75%;
  }
  .grid-x > .medium-10 {
    width: 83.33333%;
  }
  .grid-x > .medium-11 {
    width: 91.66667%;
  }
  .grid-x > .medium-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-x > .large-auto {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
    width: auto;
  }
  .grid-x > .large-1,
  .grid-x > .large-10,
  .grid-x > .large-11,
  .grid-x > .large-12,
  .grid-x > .large-2,
  .grid-x > .large-3,
  .grid-x > .large-4,
  .grid-x > .large-5,
  .grid-x > .large-6,
  .grid-x > .large-7,
  .grid-x > .large-8,
  .grid-x > .large-9,
  .grid-x > .large-shrink {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .grid-x > .large-shrink {
    width: auto;
  }
  .grid-x > .large-1 {
    width: 8.33333%;
  }
  .grid-x > .large-2 {
    width: 16.66667%;
  }
  .grid-x > .large-3 {
    width: 25%;
  }
  .grid-x > .large-4 {
    width: 33.33333%;
  }
  .grid-x > .large-5 {
    width: 41.66667%;
  }
  .grid-x > .large-6 {
    width: 50%;
  }
  .grid-x > .large-7 {
    width: 58.33333%;
  }
  .grid-x > .large-8 {
    width: 66.66667%;
  }
  .grid-x > .large-9 {
    width: 75%;
  }
  .grid-x > .large-10 {
    width: 83.33333%;
  }
  .grid-x > .large-11 {
    width: 91.66667%;
  }
  .grid-x > .large-12 {
    width: 100%;
  }
}
.grid-margin-x:not(.grid-x) > .cell {
  width: auto;
}
.grid-margin-y:not(.grid-y) > .cell {
  height: auto;
}
.grid-margin-x {
  margin-left: -0.9375rem;
  margin-right: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-x {
    margin-left: -0.9375rem;
    margin-right: -0.9375rem;
  }
}
.grid-margin-x > .cell {
  width: calc(100% - 1.875rem);
  margin-left: 0.9375rem;
  margin-right: 0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-x > .cell {
    width: calc(100% - 1.875rem);
    margin-left: 0.9375rem;
    margin-right: 0.9375rem;
  }
}
.grid-margin-x > .auto {
  width: auto;
}
.grid-margin-x > .shrink {
  width: auto;
}
.grid-margin-x > .small-1 {
  width: calc(8.33333% - 1.875rem);
}
.grid-margin-x > .small-2 {
  width: calc(16.66667% - 1.875rem);
}
.grid-margin-x > .small-3 {
  width: calc(25% - 1.875rem);
}
.grid-margin-x > .small-4 {
  width: calc(33.33333% - 1.875rem);
}
.grid-margin-x > .small-5 {
  width: calc(41.66667% - 1.875rem);
}
.grid-margin-x > .small-6 {
  width: calc(50% - 1.875rem);
}
.grid-margin-x > .small-7 {
  width: calc(58.33333% - 1.875rem);
}
.grid-margin-x > .small-8 {
  width: calc(66.66667% - 1.875rem);
}
.grid-margin-x > .small-9 {
  width: calc(75% - 1.875rem);
}
.grid-margin-x > .small-10 {
  width: calc(83.33333% - 1.875rem);
}
.grid-margin-x > .small-11 {
  width: calc(91.66667% - 1.875rem);
}
.grid-margin-x > .small-12 {
  width: calc(100% - 1.875rem);
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-x > .auto {
    width: auto;
  }
  .grid-margin-x > .shrink {
    width: auto;
  }
  .grid-margin-x > .small-1 {
    width: calc(8.33333% - 1.875rem);
  }
  .grid-margin-x > .small-2 {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x > .small-3 {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x > .small-4 {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x > .small-5 {
    width: calc(41.66667% - 1.875rem);
  }
  .grid-margin-x > .small-6 {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x > .small-7 {
    width: calc(58.33333% - 1.875rem);
  }
  .grid-margin-x > .small-8 {
    width: calc(66.66667% - 1.875rem);
  }
  .grid-margin-x > .small-9 {
    width: calc(75% - 1.875rem);
  }
  .grid-margin-x > .small-10 {
    width: calc(83.33333% - 1.875rem);
  }
  .grid-margin-x > .small-11 {
    width: calc(91.66667% - 1.875rem);
  }
  .grid-margin-x > .small-12 {
    width: calc(100% - 1.875rem);
  }
  .grid-margin-x > .medium-auto {
    width: auto;
  }
  .grid-margin-x > .medium-shrink {
    width: auto;
  }
  .grid-margin-x > .medium-1 {
    width: calc(8.33333% - 1.875rem);
  }
  .grid-margin-x > .medium-2 {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x > .medium-3 {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x > .medium-4 {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x > .medium-5 {
    width: calc(41.66667% - 1.875rem);
  }
  .grid-margin-x > .medium-6 {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x > .medium-7 {
    width: calc(58.33333% - 1.875rem);
  }
  .grid-margin-x > .medium-8 {
    width: calc(66.66667% - 1.875rem);
  }
  .grid-margin-x > .medium-9 {
    width: calc(75% - 1.875rem);
  }
  .grid-margin-x > .medium-10 {
    width: calc(83.33333% - 1.875rem);
  }
  .grid-margin-x > .medium-11 {
    width: calc(91.66667% - 1.875rem);
  }
  .grid-margin-x > .medium-12 {
    width: calc(100% - 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-margin-x > .large-auto {
    width: auto;
  }
  .grid-margin-x > .large-shrink {
    width: auto;
  }
  .grid-margin-x > .large-1 {
    width: calc(8.33333% - 1.875rem);
  }
  .grid-margin-x > .large-2 {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x > .large-3 {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x > .large-4 {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x > .large-5 {
    width: calc(41.66667% - 1.875rem);
  }
  .grid-margin-x > .large-6 {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x > .large-7 {
    width: calc(58.33333% - 1.875rem);
  }
  .grid-margin-x > .large-8 {
    width: calc(66.66667% - 1.875rem);
  }
  .grid-margin-x > .large-9 {
    width: calc(75% - 1.875rem);
  }
  .grid-margin-x > .large-10 {
    width: calc(83.33333% - 1.875rem);
  }
  .grid-margin-x > .large-11 {
    width: calc(91.66667% - 1.875rem);
  }
  .grid-margin-x > .large-12 {
    width: calc(100% - 1.875rem);
  }
}
.grid-padding-x .grid-padding-x {
  margin-right: -0.9375rem;
  margin-left: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-padding-x .grid-padding-x {
    margin-right: -0.9375rem;
    margin-left: -0.9375rem;
  }
}
.grid-container:not(.full) > .grid-padding-x {
  margin-right: -0.9375rem;
  margin-left: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-container:not(.full) > .grid-padding-x {
    margin-right: -0.9375rem;
    margin-left: -0.9375rem;
  }
}
.grid-padding-x > .cell {
  padding-right: 0.9375rem;
  padding-left: 0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-padding-x > .cell {
    padding-right: 0.9375rem;
    padding-left: 0.9375rem;
  }
}
.small-up-1 > .cell {
  width: 100%;
}
.small-up-2 > .cell {
  width: 50%;
}
.small-up-3 > .cell {
  width: 33.33333%;
}
.small-up-4 > .cell {
  width: 25%;
}
.small-up-5 > .cell {
  width: 20%;
}
.small-up-6 > .cell {
  width: 16.66667%;
}
.small-up-7 > .cell {
  width: 14.28571%;
}
.small-up-8 > .cell {
  width: 12.5%;
}
@media print, screen and (min-width: 48.0625em) {
  .medium-up-1 > .cell {
    width: 100%;
  }
  .medium-up-2 > .cell {
    width: 50%;
  }
  .medium-up-3 > .cell {
    width: 33.33333%;
  }
  .medium-up-4 > .cell {
    width: 25%;
  }
  .medium-up-5 > .cell {
    width: 20%;
  }
  .medium-up-6 > .cell {
    width: 16.66667%;
  }
  .medium-up-7 > .cell {
    width: 14.28571%;
  }
  .medium-up-8 > .cell {
    width: 12.5%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-up-1 > .cell {
    width: 100%;
  }
  .large-up-2 > .cell {
    width: 50%;
  }
  .large-up-3 > .cell {
    width: 33.33333%;
  }
  .large-up-4 > .cell {
    width: 25%;
  }
  .large-up-5 > .cell {
    width: 20%;
  }
  .large-up-6 > .cell {
    width: 16.66667%;
  }
  .large-up-7 > .cell {
    width: 14.28571%;
  }
  .large-up-8 > .cell {
    width: 12.5%;
  }
}
.grid-margin-x.small-up-1 > .cell {
  width: calc(100% - 1.875rem);
}
.grid-margin-x.small-up-2 > .cell {
  width: calc(50% - 1.875rem);
}
.grid-margin-x.small-up-3 > .cell {
  width: calc(33.33333% - 1.875rem);
}
.grid-margin-x.small-up-4 > .cell {
  width: calc(25% - 1.875rem);
}
.grid-margin-x.small-up-5 > .cell {
  width: calc(20% - 1.875rem);
}
.grid-margin-x.small-up-6 > .cell {
  width: calc(16.66667% - 1.875rem);
}
.grid-margin-x.small-up-7 > .cell {
  width: calc(14.28571% - 1.875rem);
}
.grid-margin-x.small-up-8 > .cell {
  width: calc(12.5% - 1.875rem);
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-x.small-up-1 > .cell {
    width: calc(100% - 1.875rem);
  }
  .grid-margin-x.small-up-2 > .cell {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x.small-up-3 > .cell {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x.small-up-4 > .cell {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x.small-up-5 > .cell {
    width: calc(20% - 1.875rem);
  }
  .grid-margin-x.small-up-6 > .cell {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x.small-up-7 > .cell {
    width: calc(14.28571% - 1.875rem);
  }
  .grid-margin-x.small-up-8 > .cell {
    width: calc(12.5% - 1.875rem);
  }
  .grid-margin-x.medium-up-1 > .cell {
    width: calc(100% - 1.875rem);
  }
  .grid-margin-x.medium-up-2 > .cell {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x.medium-up-3 > .cell {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x.medium-up-4 > .cell {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x.medium-up-5 > .cell {
    width: calc(20% - 1.875rem);
  }
  .grid-margin-x.medium-up-6 > .cell {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x.medium-up-7 > .cell {
    width: calc(14.28571% - 1.875rem);
  }
  .grid-margin-x.medium-up-8 > .cell {
    width: calc(12.5% - 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-margin-x.large-up-1 > .cell {
    width: calc(100% - 1.875rem);
  }
  .grid-margin-x.large-up-2 > .cell {
    width: calc(50% - 1.875rem);
  }
  .grid-margin-x.large-up-3 > .cell {
    width: calc(33.33333% - 1.875rem);
  }
  .grid-margin-x.large-up-4 > .cell {
    width: calc(25% - 1.875rem);
  }
  .grid-margin-x.large-up-5 > .cell {
    width: calc(20% - 1.875rem);
  }
  .grid-margin-x.large-up-6 > .cell {
    width: calc(16.66667% - 1.875rem);
  }
  .grid-margin-x.large-up-7 > .cell {
    width: calc(14.28571% - 1.875rem);
  }
  .grid-margin-x.large-up-8 > .cell {
    width: calc(12.5% - 1.875rem);
  }
}
.small-margin-collapse {
  margin-right: 0;
  margin-left: 0;
}
.small-margin-collapse > .cell {
  margin-right: 0;
  margin-left: 0;
}
.small-margin-collapse > .small-1 {
  width: 8.33333%;
}
.small-margin-collapse > .small-2 {
  width: 16.66667%;
}
.small-margin-collapse > .small-3 {
  width: 25%;
}
.small-margin-collapse > .small-4 {
  width: 33.33333%;
}
.small-margin-collapse > .small-5 {
  width: 41.66667%;
}
.small-margin-collapse > .small-6 {
  width: 50%;
}
.small-margin-collapse > .small-7 {
  width: 58.33333%;
}
.small-margin-collapse > .small-8 {
  width: 66.66667%;
}
.small-margin-collapse > .small-9 {
  width: 75%;
}
.small-margin-collapse > .small-10 {
  width: 83.33333%;
}
.small-margin-collapse > .small-11 {
  width: 91.66667%;
}
.small-margin-collapse > .small-12 {
  width: 100%;
}
@media print, screen and (min-width: 48.0625em) {
  .small-margin-collapse > .medium-1 {
    width: 8.33333%;
  }
  .small-margin-collapse > .medium-2 {
    width: 16.66667%;
  }
  .small-margin-collapse > .medium-3 {
    width: 25%;
  }
  .small-margin-collapse > .medium-4 {
    width: 33.33333%;
  }
  .small-margin-collapse > .medium-5 {
    width: 41.66667%;
  }
  .small-margin-collapse > .medium-6 {
    width: 50%;
  }
  .small-margin-collapse > .medium-7 {
    width: 58.33333%;
  }
  .small-margin-collapse > .medium-8 {
    width: 66.66667%;
  }
  .small-margin-collapse > .medium-9 {
    width: 75%;
  }
  .small-margin-collapse > .medium-10 {
    width: 83.33333%;
  }
  .small-margin-collapse > .medium-11 {
    width: 91.66667%;
  }
  .small-margin-collapse > .medium-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .small-margin-collapse > .large-1 {
    width: 8.33333%;
  }
  .small-margin-collapse > .large-2 {
    width: 16.66667%;
  }
  .small-margin-collapse > .large-3 {
    width: 25%;
  }
  .small-margin-collapse > .large-4 {
    width: 33.33333%;
  }
  .small-margin-collapse > .large-5 {
    width: 41.66667%;
  }
  .small-margin-collapse > .large-6 {
    width: 50%;
  }
  .small-margin-collapse > .large-7 {
    width: 58.33333%;
  }
  .small-margin-collapse > .large-8 {
    width: 66.66667%;
  }
  .small-margin-collapse > .large-9 {
    width: 75%;
  }
  .small-margin-collapse > .large-10 {
    width: 83.33333%;
  }
  .small-margin-collapse > .large-11 {
    width: 91.66667%;
  }
  .small-margin-collapse > .large-12 {
    width: 100%;
  }
}
.small-padding-collapse {
  margin-right: 0;
  margin-left: 0;
}
.small-padding-collapse > .cell {
  padding-right: 0;
  padding-left: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .medium-margin-collapse {
    margin-right: 0;
    margin-left: 0;
  }
  .medium-margin-collapse > .cell {
    margin-right: 0;
    margin-left: 0;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .medium-margin-collapse > .small-1 {
    width: 8.33333%;
  }
  .medium-margin-collapse > .small-2 {
    width: 16.66667%;
  }
  .medium-margin-collapse > .small-3 {
    width: 25%;
  }
  .medium-margin-collapse > .small-4 {
    width: 33.33333%;
  }
  .medium-margin-collapse > .small-5 {
    width: 41.66667%;
  }
  .medium-margin-collapse > .small-6 {
    width: 50%;
  }
  .medium-margin-collapse > .small-7 {
    width: 58.33333%;
  }
  .medium-margin-collapse > .small-8 {
    width: 66.66667%;
  }
  .medium-margin-collapse > .small-9 {
    width: 75%;
  }
  .medium-margin-collapse > .small-10 {
    width: 83.33333%;
  }
  .medium-margin-collapse > .small-11 {
    width: 91.66667%;
  }
  .medium-margin-collapse > .small-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .medium-margin-collapse > .medium-1 {
    width: 8.33333%;
  }
  .medium-margin-collapse > .medium-2 {
    width: 16.66667%;
  }
  .medium-margin-collapse > .medium-3 {
    width: 25%;
  }
  .medium-margin-collapse > .medium-4 {
    width: 33.33333%;
  }
  .medium-margin-collapse > .medium-5 {
    width: 41.66667%;
  }
  .medium-margin-collapse > .medium-6 {
    width: 50%;
  }
  .medium-margin-collapse > .medium-7 {
    width: 58.33333%;
  }
  .medium-margin-collapse > .medium-8 {
    width: 66.66667%;
  }
  .medium-margin-collapse > .medium-9 {
    width: 75%;
  }
  .medium-margin-collapse > .medium-10 {
    width: 83.33333%;
  }
  .medium-margin-collapse > .medium-11 {
    width: 91.66667%;
  }
  .medium-margin-collapse > .medium-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .medium-margin-collapse > .large-1 {
    width: 8.33333%;
  }
  .medium-margin-collapse > .large-2 {
    width: 16.66667%;
  }
  .medium-margin-collapse > .large-3 {
    width: 25%;
  }
  .medium-margin-collapse > .large-4 {
    width: 33.33333%;
  }
  .medium-margin-collapse > .large-5 {
    width: 41.66667%;
  }
  .medium-margin-collapse > .large-6 {
    width: 50%;
  }
  .medium-margin-collapse > .large-7 {
    width: 58.33333%;
  }
  .medium-margin-collapse > .large-8 {
    width: 66.66667%;
  }
  .medium-margin-collapse > .large-9 {
    width: 75%;
  }
  .medium-margin-collapse > .large-10 {
    width: 83.33333%;
  }
  .medium-margin-collapse > .large-11 {
    width: 91.66667%;
  }
  .medium-margin-collapse > .large-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .medium-padding-collapse {
    margin-right: 0;
    margin-left: 0;
  }
  .medium-padding-collapse > .cell {
    padding-right: 0;
    padding-left: 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-margin-collapse {
    margin-right: 0;
    margin-left: 0;
  }
  .large-margin-collapse > .cell {
    margin-right: 0;
    margin-left: 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-margin-collapse > .small-1 {
    width: 8.33333%;
  }
  .large-margin-collapse > .small-2 {
    width: 16.66667%;
  }
  .large-margin-collapse > .small-3 {
    width: 25%;
  }
  .large-margin-collapse > .small-4 {
    width: 33.33333%;
  }
  .large-margin-collapse > .small-5 {
    width: 41.66667%;
  }
  .large-margin-collapse > .small-6 {
    width: 50%;
  }
  .large-margin-collapse > .small-7 {
    width: 58.33333%;
  }
  .large-margin-collapse > .small-8 {
    width: 66.66667%;
  }
  .large-margin-collapse > .small-9 {
    width: 75%;
  }
  .large-margin-collapse > .small-10 {
    width: 83.33333%;
  }
  .large-margin-collapse > .small-11 {
    width: 91.66667%;
  }
  .large-margin-collapse > .small-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-margin-collapse > .medium-1 {
    width: 8.33333%;
  }
  .large-margin-collapse > .medium-2 {
    width: 16.66667%;
  }
  .large-margin-collapse > .medium-3 {
    width: 25%;
  }
  .large-margin-collapse > .medium-4 {
    width: 33.33333%;
  }
  .large-margin-collapse > .medium-5 {
    width: 41.66667%;
  }
  .large-margin-collapse > .medium-6 {
    width: 50%;
  }
  .large-margin-collapse > .medium-7 {
    width: 58.33333%;
  }
  .large-margin-collapse > .medium-8 {
    width: 66.66667%;
  }
  .large-margin-collapse > .medium-9 {
    width: 75%;
  }
  .large-margin-collapse > .medium-10 {
    width: 83.33333%;
  }
  .large-margin-collapse > .medium-11 {
    width: 91.66667%;
  }
  .large-margin-collapse > .medium-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-margin-collapse > .large-1 {
    width: 8.33333%;
  }
  .large-margin-collapse > .large-2 {
    width: 16.66667%;
  }
  .large-margin-collapse > .large-3 {
    width: 25%;
  }
  .large-margin-collapse > .large-4 {
    width: 33.33333%;
  }
  .large-margin-collapse > .large-5 {
    width: 41.66667%;
  }
  .large-margin-collapse > .large-6 {
    width: 50%;
  }
  .large-margin-collapse > .large-7 {
    width: 58.33333%;
  }
  .large-margin-collapse > .large-8 {
    width: 66.66667%;
  }
  .large-margin-collapse > .large-9 {
    width: 75%;
  }
  .large-margin-collapse > .large-10 {
    width: 83.33333%;
  }
  .large-margin-collapse > .large-11 {
    width: 91.66667%;
  }
  .large-margin-collapse > .large-12 {
    width: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-padding-collapse {
    margin-right: 0;
    margin-left: 0;
  }
  .large-padding-collapse > .cell {
    padding-right: 0;
    padding-left: 0;
  }
}
.small-offset-0 {
  margin-left: 0;
}
.grid-margin-x > .small-offset-0 {
  margin-left: calc(0% + 0.9375rem);
}
.small-offset-1 {
  margin-left: 8.33333%;
}
.grid-margin-x > .small-offset-1 {
  margin-left: calc(8.33333% + 0.9375rem);
}
.small-offset-2 {
  margin-left: 16.66667%;
}
.grid-margin-x > .small-offset-2 {
  margin-left: calc(16.66667% + 0.9375rem);
}
.small-offset-3 {
  margin-left: 25%;
}
.grid-margin-x > .small-offset-3 {
  margin-left: calc(25% + 0.9375rem);
}
.small-offset-4 {
  margin-left: 33.33333%;
}
.grid-margin-x > .small-offset-4 {
  margin-left: calc(33.33333% + 0.9375rem);
}
.small-offset-5 {
  margin-left: 41.66667%;
}
.grid-margin-x > .small-offset-5 {
  margin-left: calc(41.66667% + 0.9375rem);
}
.small-offset-6 {
  margin-left: 50%;
}
.grid-margin-x > .small-offset-6 {
  margin-left: calc(50% + 0.9375rem);
}
.small-offset-7 {
  margin-left: 58.33333%;
}
.grid-margin-x > .small-offset-7 {
  margin-left: calc(58.33333% + 0.9375rem);
}
.small-offset-8 {
  margin-left: 66.66667%;
}
.grid-margin-x > .small-offset-8 {
  margin-left: calc(66.66667% + 0.9375rem);
}
.small-offset-9 {
  margin-left: 75%;
}
.grid-margin-x > .small-offset-9 {
  margin-left: calc(75% + 0.9375rem);
}
.small-offset-10 {
  margin-left: 83.33333%;
}
.grid-margin-x > .small-offset-10 {
  margin-left: calc(83.33333% + 0.9375rem);
}
.small-offset-11 {
  margin-left: 91.66667%;
}
.grid-margin-x > .small-offset-11 {
  margin-left: calc(91.66667% + 0.9375rem);
}
@media print, screen and (min-width: 48.0625em) {
  .medium-offset-0 {
    margin-left: 0;
  }
  .grid-margin-x > .medium-offset-0 {
    margin-left: calc(0% + 0.9375rem);
  }
  .medium-offset-1 {
    margin-left: 8.33333%;
  }
  .grid-margin-x > .medium-offset-1 {
    margin-left: calc(8.33333% + 0.9375rem);
  }
  .medium-offset-2 {
    margin-left: 16.66667%;
  }
  .grid-margin-x > .medium-offset-2 {
    margin-left: calc(16.66667% + 0.9375rem);
  }
  .medium-offset-3 {
    margin-left: 25%;
  }
  .grid-margin-x > .medium-offset-3 {
    margin-left: calc(25% + 0.9375rem);
  }
  .medium-offset-4 {
    margin-left: 33.33333%;
  }
  .grid-margin-x > .medium-offset-4 {
    margin-left: calc(33.33333% + 0.9375rem);
  }
  .medium-offset-5 {
    margin-left: 41.66667%;
  }
  .grid-margin-x > .medium-offset-5 {
    margin-left: calc(41.66667% + 0.9375rem);
  }
  .medium-offset-6 {
    margin-left: 50%;
  }
  .grid-margin-x > .medium-offset-6 {
    margin-left: calc(50% + 0.9375rem);
  }
  .medium-offset-7 {
    margin-left: 58.33333%;
  }
  .grid-margin-x > .medium-offset-7 {
    margin-left: calc(58.33333% + 0.9375rem);
  }
  .medium-offset-8 {
    margin-left: 66.66667%;
  }
  .grid-margin-x > .medium-offset-8 {
    margin-left: calc(66.66667% + 0.9375rem);
  }
  .medium-offset-9 {
    margin-left: 75%;
  }
  .grid-margin-x > .medium-offset-9 {
    margin-left: calc(75% + 0.9375rem);
  }
  .medium-offset-10 {
    margin-left: 83.33333%;
  }
  .grid-margin-x > .medium-offset-10 {
    margin-left: calc(83.33333% + 0.9375rem);
  }
  .medium-offset-11 {
    margin-left: 91.66667%;
  }
  .grid-margin-x > .medium-offset-11 {
    margin-left: calc(91.66667% + 0.9375rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-offset-0 {
    margin-left: 0;
  }
  .grid-margin-x > .large-offset-0 {
    margin-left: calc(0% + 0.9375rem);
  }
  .large-offset-1 {
    margin-left: 8.33333%;
  }
  .grid-margin-x > .large-offset-1 {
    margin-left: calc(8.33333% + 0.9375rem);
  }
  .large-offset-2 {
    margin-left: 16.66667%;
  }
  .grid-margin-x > .large-offset-2 {
    margin-left: calc(16.66667% + 0.9375rem);
  }
  .large-offset-3 {
    margin-left: 25%;
  }
  .grid-margin-x > .large-offset-3 {
    margin-left: calc(25% + 0.9375rem);
  }
  .large-offset-4 {
    margin-left: 33.33333%;
  }
  .grid-margin-x > .large-offset-4 {
    margin-left: calc(33.33333% + 0.9375rem);
  }
  .large-offset-5 {
    margin-left: 41.66667%;
  }
  .grid-margin-x > .large-offset-5 {
    margin-left: calc(41.66667% + 0.9375rem);
  }
  .large-offset-6 {
    margin-left: 50%;
  }
  .grid-margin-x > .large-offset-6 {
    margin-left: calc(50% + 0.9375rem);
  }
  .large-offset-7 {
    margin-left: 58.33333%;
  }
  .grid-margin-x > .large-offset-7 {
    margin-left: calc(58.33333% + 0.9375rem);
  }
  .large-offset-8 {
    margin-left: 66.66667%;
  }
  .grid-margin-x > .large-offset-8 {
    margin-left: calc(66.66667% + 0.9375rem);
  }
  .large-offset-9 {
    margin-left: 75%;
  }
  .grid-margin-x > .large-offset-9 {
    margin-left: calc(75% + 0.9375rem);
  }
  .large-offset-10 {
    margin-left: 83.33333%;
  }
  .grid-margin-x > .large-offset-10 {
    margin-left: calc(83.33333% + 0.9375rem);
  }
  .large-offset-11 {
    margin-left: 91.66667%;
  }
  .grid-margin-x > .large-offset-11 {
    margin-left: calc(91.66667% + 0.9375rem);
  }
}
.grid-y {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-flow: column nowrap;
  -ms-flex-flow: column nowrap;
  flex-flow: column nowrap;
}
.grid-y > .cell {
  height: auto;
  max-height: none;
}
.grid-y > .auto {
  height: auto;
}
.grid-y > .shrink {
  height: auto;
}
.grid-y > .small-1,
.grid-y > .small-10,
.grid-y > .small-11,
.grid-y > .small-12,
.grid-y > .small-2,
.grid-y > .small-3,
.grid-y > .small-4,
.grid-y > .small-5,
.grid-y > .small-6,
.grid-y > .small-7,
.grid-y > .small-8,
.grid-y > .small-9,
.grid-y > .small-full,
.grid-y > .small-shrink {
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-y > .medium-1,
  .grid-y > .medium-10,
  .grid-y > .medium-11,
  .grid-y > .medium-12,
  .grid-y > .medium-2,
  .grid-y > .medium-3,
  .grid-y > .medium-4,
  .grid-y > .medium-5,
  .grid-y > .medium-6,
  .grid-y > .medium-7,
  .grid-y > .medium-8,
  .grid-y > .medium-9,
  .grid-y > .medium-full,
  .grid-y > .medium-shrink {
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-y > .large-1,
  .grid-y > .large-10,
  .grid-y > .large-11,
  .grid-y > .large-12,
  .grid-y > .large-2,
  .grid-y > .large-3,
  .grid-y > .large-4,
  .grid-y > .large-5,
  .grid-y > .large-6,
  .grid-y > .large-7,
  .grid-y > .large-8,
  .grid-y > .large-9,
  .grid-y > .large-full,
  .grid-y > .large-shrink {
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }
}
.grid-y > .small-1,
.grid-y > .small-10,
.grid-y > .small-11,
.grid-y > .small-12,
.grid-y > .small-2,
.grid-y > .small-3,
.grid-y > .small-4,
.grid-y > .small-5,
.grid-y > .small-6,
.grid-y > .small-7,
.grid-y > .small-8,
.grid-y > .small-9 {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}
.grid-y > .small-1 {
  height: 8.33333%;
}
.grid-y > .small-2 {
  height: 16.66667%;
}
.grid-y > .small-3 {
  height: 25%;
}
.grid-y > .small-4 {
  height: 33.33333%;
}
.grid-y > .small-5 {
  height: 41.66667%;
}
.grid-y > .small-6 {
  height: 50%;
}
.grid-y > .small-7 {
  height: 58.33333%;
}
.grid-y > .small-8 {
  height: 66.66667%;
}
.grid-y > .small-9 {
  height: 75%;
}
.grid-y > .small-10 {
  height: 83.33333%;
}
.grid-y > .small-11 {
  height: 91.66667%;
}
.grid-y > .small-12 {
  height: 100%;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-y > .medium-auto {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
    height: auto;
  }
  .grid-y > .medium-1,
  .grid-y > .medium-10,
  .grid-y > .medium-11,
  .grid-y > .medium-12,
  .grid-y > .medium-2,
  .grid-y > .medium-3,
  .grid-y > .medium-4,
  .grid-y > .medium-5,
  .grid-y > .medium-6,
  .grid-y > .medium-7,
  .grid-y > .medium-8,
  .grid-y > .medium-9,
  .grid-y > .medium-shrink {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .grid-y > .medium-shrink {
    height: auto;
  }
  .grid-y > .medium-1 {
    height: 8.33333%;
  }
  .grid-y > .medium-2 {
    height: 16.66667%;
  }
  .grid-y > .medium-3 {
    height: 25%;
  }
  .grid-y > .medium-4 {
    height: 33.33333%;
  }
  .grid-y > .medium-5 {
    height: 41.66667%;
  }
  .grid-y > .medium-6 {
    height: 50%;
  }
  .grid-y > .medium-7 {
    height: 58.33333%;
  }
  .grid-y > .medium-8 {
    height: 66.66667%;
  }
  .grid-y > .medium-9 {
    height: 75%;
  }
  .grid-y > .medium-10 {
    height: 83.33333%;
  }
  .grid-y > .medium-11 {
    height: 91.66667%;
  }
  .grid-y > .medium-12 {
    height: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-y > .large-auto {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
    height: auto;
  }
  .grid-y > .large-1,
  .grid-y > .large-10,
  .grid-y > .large-11,
  .grid-y > .large-12,
  .grid-y > .large-2,
  .grid-y > .large-3,
  .grid-y > .large-4,
  .grid-y > .large-5,
  .grid-y > .large-6,
  .grid-y > .large-7,
  .grid-y > .large-8,
  .grid-y > .large-9,
  .grid-y > .large-shrink {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .grid-y > .large-shrink {
    height: auto;
  }
  .grid-y > .large-1 {
    height: 8.33333%;
  }
  .grid-y > .large-2 {
    height: 16.66667%;
  }
  .grid-y > .large-3 {
    height: 25%;
  }
  .grid-y > .large-4 {
    height: 33.33333%;
  }
  .grid-y > .large-5 {
    height: 41.66667%;
  }
  .grid-y > .large-6 {
    height: 50%;
  }
  .grid-y > .large-7 {
    height: 58.33333%;
  }
  .grid-y > .large-8 {
    height: 66.66667%;
  }
  .grid-y > .large-9 {
    height: 75%;
  }
  .grid-y > .large-10 {
    height: 83.33333%;
  }
  .grid-y > .large-11 {
    height: 91.66667%;
  }
  .grid-y > .large-12 {
    height: 100%;
  }
}
.grid-padding-y .grid-padding-y {
  margin-top: -0.9375rem;
  margin-bottom: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-padding-y .grid-padding-y {
    margin-top: -0.9375rem;
    margin-bottom: -0.9375rem;
  }
}
.grid-padding-y > .cell {
  padding-top: 0.9375rem;
  padding-bottom: 0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-padding-y > .cell {
    padding-top: 0.9375rem;
    padding-bottom: 0.9375rem;
  }
}
.grid-margin-y {
  margin-top: -0.9375rem;
  margin-bottom: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y {
    margin-top: -0.9375rem;
    margin-bottom: -0.9375rem;
  }
}
.grid-margin-y > .cell {
  height: calc(100% - 1.875rem);
  margin-top: 0.9375rem;
  margin-bottom: 0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y > .cell {
    height: calc(100% - 1.875rem);
    margin-top: 0.9375rem;
    margin-bottom: 0.9375rem;
  }
}
.grid-margin-y > .auto {
  height: auto;
}
.grid-margin-y > .shrink {
  height: auto;
}
.grid-margin-y > .small-1 {
  height: calc(8.33333% - 1.875rem);
}
.grid-margin-y > .small-2 {
  height: calc(16.66667% - 1.875rem);
}
.grid-margin-y > .small-3 {
  height: calc(25% - 1.875rem);
}
.grid-margin-y > .small-4 {
  height: calc(33.33333% - 1.875rem);
}
.grid-margin-y > .small-5 {
  height: calc(41.66667% - 1.875rem);
}
.grid-margin-y > .small-6 {
  height: calc(50% - 1.875rem);
}
.grid-margin-y > .small-7 {
  height: calc(58.33333% - 1.875rem);
}
.grid-margin-y > .small-8 {
  height: calc(66.66667% - 1.875rem);
}
.grid-margin-y > .small-9 {
  height: calc(75% - 1.875rem);
}
.grid-margin-y > .small-10 {
  height: calc(83.33333% - 1.875rem);
}
.grid-margin-y > .small-11 {
  height: calc(91.66667% - 1.875rem);
}
.grid-margin-y > .small-12 {
  height: calc(100% - 1.875rem);
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y > .auto {
    height: auto;
  }
  .grid-margin-y > .shrink {
    height: auto;
  }
  .grid-margin-y > .small-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .small-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .small-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .small-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .small-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .small-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .small-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .small-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .small-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .small-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .small-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .small-12 {
    height: calc(100% - 1.875rem);
  }
  .grid-margin-y > .medium-auto {
    height: auto;
  }
  .grid-margin-y > .medium-shrink {
    height: auto;
  }
  .grid-margin-y > .medium-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .medium-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .medium-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .medium-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-12 {
    height: calc(100% - 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-margin-y > .large-auto {
    height: auto;
  }
  .grid-margin-y > .large-shrink {
    height: auto;
  }
  .grid-margin-y > .large-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .large-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .large-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .large-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .large-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .large-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .large-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .large-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .large-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .large-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .large-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .large-12 {
    height: calc(100% - 1.875rem);
  }
}
.grid-frame {
  overflow: hidden;
  position: relative;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  width: 100vw;
}
.cell .grid-frame {
  width: 100%;
}
.cell-block {
  overflow-x: auto;
  max-width: 100%;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
}
.cell-block-y {
  overflow-y: auto;
  max-height: 100%;
  min-height: 100%;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar;
}
.cell-block-container {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  max-height: 100%;
}
.cell-block-container > .grid-x {
  max-height: 100%;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
}
@media print, screen and (min-width: 48.0625em) {
  .medium-grid-frame {
    overflow: hidden;
    position: relative;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    width: 100vw;
  }
  .cell .medium-grid-frame {
    width: 100%;
  }
  .medium-cell-block {
    overflow-x: auto;
    max-width: 100%;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar;
  }
  .medium-cell-block-container {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    max-height: 100%;
  }
  .medium-cell-block-container > .grid-x {
    max-height: 100%;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
  }
  .medium-cell-block-y {
    overflow-y: auto;
    max-height: 100%;
    min-height: 100%;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .large-grid-frame {
    overflow: hidden;
    position: relative;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    width: 100vw;
  }
  .cell .large-grid-frame {
    width: 100%;
  }
  .large-cell-block {
    overflow-x: auto;
    max-width: 100%;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar;
  }
  .large-cell-block-container {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    max-height: 100%;
  }
  .large-cell-block-container > .grid-x {
    max-height: 100%;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
  }
  .large-cell-block-y {
    overflow-y: auto;
    max-height: 100%;
    min-height: 100%;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar;
  }
}
.grid-y.grid-frame {
  width: auto;
  overflow: hidden;
  position: relative;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  height: 100vh;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-y.medium-grid-frame {
    width: auto;
    overflow: hidden;
    position: relative;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    height: 100vh;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-y.large-grid-frame {
    width: auto;
    overflow: hidden;
    position: relative;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    height: 100vh;
  }
}
.cell .grid-y.grid-frame {
  height: 100%;
}
@media print, screen and (min-width: 48.0625em) {
  .cell .grid-y.medium-grid-frame {
    height: 100%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .cell .grid-y.large-grid-frame {
    height: 100%;
  }
}
.grid-margin-y {
  margin-top: -0.9375rem;
  margin-bottom: -0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y {
    margin-top: -0.9375rem;
    margin-bottom: -0.9375rem;
  }
}
.grid-margin-y > .cell {
  height: calc(100% - 1.875rem);
  margin-top: 0.9375rem;
  margin-bottom: 0.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y > .cell {
    height: calc(100% - 1.875rem);
    margin-top: 0.9375rem;
    margin-bottom: 0.9375rem;
  }
}
.grid-margin-y > .auto {
  height: auto;
}
.grid-margin-y > .shrink {
  height: auto;
}
.grid-margin-y > .small-1 {
  height: calc(8.33333% - 1.875rem);
}
.grid-margin-y > .small-2 {
  height: calc(16.66667% - 1.875rem);
}
.grid-margin-y > .small-3 {
  height: calc(25% - 1.875rem);
}
.grid-margin-y > .small-4 {
  height: calc(33.33333% - 1.875rem);
}
.grid-margin-y > .small-5 {
  height: calc(41.66667% - 1.875rem);
}
.grid-margin-y > .small-6 {
  height: calc(50% - 1.875rem);
}
.grid-margin-y > .small-7 {
  height: calc(58.33333% - 1.875rem);
}
.grid-margin-y > .small-8 {
  height: calc(66.66667% - 1.875rem);
}
.grid-margin-y > .small-9 {
  height: calc(75% - 1.875rem);
}
.grid-margin-y > .small-10 {
  height: calc(83.33333% - 1.875rem);
}
.grid-margin-y > .small-11 {
  height: calc(91.66667% - 1.875rem);
}
.grid-margin-y > .small-12 {
  height: calc(100% - 1.875rem);
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y > .auto {
    height: auto;
  }
  .grid-margin-y > .shrink {
    height: auto;
  }
  .grid-margin-y > .small-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .small-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .small-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .small-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .small-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .small-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .small-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .small-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .small-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .small-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .small-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .small-12 {
    height: calc(100% - 1.875rem);
  }
  .grid-margin-y > .medium-auto {
    height: auto;
  }
  .grid-margin-y > .medium-shrink {
    height: auto;
  }
  .grid-margin-y > .medium-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .medium-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .medium-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .medium-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .medium-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .medium-12 {
    height: calc(100% - 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-margin-y > .large-auto {
    height: auto;
  }
  .grid-margin-y > .large-shrink {
    height: auto;
  }
  .grid-margin-y > .large-1 {
    height: calc(8.33333% - 1.875rem);
  }
  .grid-margin-y > .large-2 {
    height: calc(16.66667% - 1.875rem);
  }
  .grid-margin-y > .large-3 {
    height: calc(25% - 1.875rem);
  }
  .grid-margin-y > .large-4 {
    height: calc(33.33333% - 1.875rem);
  }
  .grid-margin-y > .large-5 {
    height: calc(41.66667% - 1.875rem);
  }
  .grid-margin-y > .large-6 {
    height: calc(50% - 1.875rem);
  }
  .grid-margin-y > .large-7 {
    height: calc(58.33333% - 1.875rem);
  }
  .grid-margin-y > .large-8 {
    height: calc(66.66667% - 1.875rem);
  }
  .grid-margin-y > .large-9 {
    height: calc(75% - 1.875rem);
  }
  .grid-margin-y > .large-10 {
    height: calc(83.33333% - 1.875rem);
  }
  .grid-margin-y > .large-11 {
    height: calc(91.66667% - 1.875rem);
  }
  .grid-margin-y > .large-12 {
    height: calc(100% - 1.875rem);
  }
}
.grid-frame.grid-margin-y {
  height: calc(100vh + 1.875rem);
}
@media print, screen and (min-width: 48.0625em) {
  .grid-frame.grid-margin-y {
    height: calc(100vh + 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-frame.grid-margin-y {
    height: calc(100vh + 1.875rem);
  }
}
@media print, screen and (min-width: 48.0625em) {
  .grid-margin-y.medium-grid-frame {
    height: calc(100vh + 1.875rem);
  }
}
@media print, screen and (min-width: 64.0625em) {
  .grid-margin-y.large-grid-frame {
    height: calc(100vh + 1.875rem);
  }
}
.hide {
  display: none !important;
}
.invisible {
  visibility: hidden;
}
@media print, screen and (max-width: 48.06125em) {
  .hide-for-small-only {
    display: none !important;
  }
}
@media screen and (max-width: 0em), screen and (min-width: 48.0625em) {
  .show-for-small-only {
    display: none !important;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .hide-for-medium {
    display: none !important;
  }
}
@media screen and (max-width: 48.06125em) {
  .show-for-medium {
    display: none !important;
  }
}
@media print, screen and (min-width: 48.0625em) and (max-width: 64.06125em) {
  .hide-for-medium-only {
    display: none !important;
  }
}
@media screen and (max-width: 48.06125em), screen and (min-width: 64.0625em) {
  .show-for-medium-only {
    display: none !important;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .hide-for-large {
    display: none !important;
  }
}
@media screen and (max-width: 64.06125em) {
  .show-for-large {
    display: none !important;
  }
}
@media print, screen and (min-width: 64.0625em) and (max-width: 74.99875em) {
  .hide-for-large-only {
    display: none !important;
  }
}
@media screen and (max-width: 64.06125em), screen and (min-width: 75em) {
  .show-for-large-only {
    display: none !important;
  }
}
.show-for-sr,
.show-on-focus {
  position: absolute !important;
  width: 1px !important;
  height: 1px !important;
  padding: 0 !important;
  overflow: hidden !important;
  clip: rect(0, 0, 0, 0) !important;
  white-space: nowrap !important;
  border: 0 !important;
}
.show-on-focus:active,
.show-on-focus:focus {
  position: static !important;
  width: auto !important;
  height: auto !important;
  overflow: visible !important;
  clip: auto !important;
  white-space: normal !important;
}
.hide-for-portrait,
.show-for-landscape {
  display: block !important;
}
@media screen and (orientation: landscape) {
  .hide-for-portrait,
  .show-for-landscape {
    display: block !important;
  }
}
@media screen and (orientation: portrait) {
  .hide-for-portrait,
  .show-for-landscape {
    display: none !important;
  }
}
.hide-for-landscape,
.show-for-portrait {
  display: none !important;
}
@media screen and (orientation: landscape) {
  .hide-for-landscape,
  .show-for-portrait {
    display: none !important;
  }
}
@media screen and (orientation: portrait) {
  .hide-for-landscape,
  .show-for-portrait {
    display: block !important;
  }
}
.menu {
  padding: 0;
  margin: 0;
  list-style: none;
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
[data-whatinput="mouse"] .menu li {
  outline: 0;
}
.menu .button,
.menu a {
  line-height: 1;
  text-decoration: none;
  display: block;
  padding: 0.7rem 1rem;
}
.menu a,
.menu button,
.menu input,
.menu select {
  margin-bottom: 0;
}
.menu input {
  display: inline-block;
}
.menu,
.menu.horizontal {
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
}
.menu.vertical {
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.menu.expanded li {
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 0;
  -ms-flex: 1 1 0;
  flex: 1 1 0px;
}
.menu.simple {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.menu.simple li + li {
  margin-left: 1rem;
}
.menu.simple a {
  padding: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .menu.medium-horizontal {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .menu.medium-vertical {
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
  .menu.medium-expanded li {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
  }
  .menu.medium-simple li {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .menu.large-horizontal {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .menu.large-vertical {
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
  .menu.large-expanded li {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
  }
  .menu.large-simple li {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 0;
    -ms-flex: 1 1 0;
    flex: 1 1 0px;
  }
}
.menu.nested {
  margin-right: 0;
  margin-left: 1rem;
}
.menu.icons a {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.menu.icon-bottom a,
.menu.icon-left a,
.menu.icon-right a,
.menu.icon-top a {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.menu.icon-left li a {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-flow: row nowrap;
  -ms-flex-flow: row nowrap;
  flex-flow: row nowrap;
}
.menu.icon-left li a i,
.menu.icon-left li a img,
.menu.icon-left li a svg {
  margin-right: 0.25rem;
}
.menu.icon-right li a {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-flow: row nowrap;
  -ms-flex-flow: row nowrap;
  flex-flow: row nowrap;
}
.menu.icon-right li a i,
.menu.icon-right li a img,
.menu.icon-right li a svg {
  margin-left: 0.25rem;
}
.menu.icon-top li a {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-flow: column nowrap;
  -ms-flex-flow: column nowrap;
  flex-flow: column nowrap;
}
.menu.icon-top li a i,
.menu.icon-top li a img,
.menu.icon-top li a svg {
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  align-self: stretch;
  margin-bottom: 0.25rem;
  text-align: center;
}
.menu.icon-bottom li a {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-flow: column nowrap;
  -ms-flex-flow: column nowrap;
  flex-flow: column nowrap;
}
.menu.icon-bottom li a i,
.menu.icon-bottom li a img,
.menu.icon-bottom li a svg {
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  align-self: stretch;
  margin-bottom: 0.25rem;
  text-align: center;
}
.menu .is-active > a {
  background: #0569ff;
  color: #fff;
}
.menu .active > a {
  background: #0569ff;
  color: #fff;
}
.menu.align-left {
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}
.menu.align-right li {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
}
.menu.align-right li .submenu li {
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}
.menu.align-right.vertical li {
  display: block;
  text-align: right;
}
.menu.align-right.vertical li .submenu li {
  text-align: right;
}
.menu.align-right .nested {
  margin-right: 1rem;
  margin-left: 0;
}
.menu.align-center li {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.menu.align-center li .submenu li {
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}
.menu .menu-text {
  padding: 0.7rem 1rem;
  font-weight: 700;
  line-height: 1;
  color: inherit;
}
.menu-centered > .menu {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.menu-centered > .menu li {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.menu-centered > .menu li .submenu li {
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}
.no-js [data-responsive-menu] ul {
  display: none;
}
body,
html {
  scroll-behavior: smooth;
}
html.is-site-nav-active,
html.is-site-nav-active body {
  overflow: hidden;
}
a {
  outline: 0;
}
figure {
  max-width: 100%;
}
svg:not([class]) {
  width: 100%;
  height: 100%;
  vertical-align: top;
}
.u-desktop-only {
  display: inherit;
}
@media print, screen and (max-width: 64em) {
  .u-desktop-only {
    display: none;
  }
}
.u-mobile-only {
  display: none;
}
@media print, screen and (max-width: 48em) {
  .u-mobile-only {
    display: inherit;
  }
}
@media (max-width: 768px) and (min-width: 600px) {
  .grid-margin-x.tablet-up-2 > .cell {
    width: calc(50% - 1.875rem);
  }
}
@media screen and (max-width: 79.375em) {
  .grid-container {
    padding-right: 3.75rem;
    padding-left: 3.75rem;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .grid-container {
    padding-right: 2.5rem;
    padding-left: 2.5rem;
  }
}
.try-now {
  text-align: center;
}
@media print, screen and (max-width: 64.06125em) {
  .try-now {
    padding-bottom: 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .try-now {
    padding-top: 8.125rem;
    text-align: left;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .try-now .reference {
    margin: 0 auto;
    text-align: left;
    display: inline-block;
  }
}
.try-now .button,
.try-now .headline {
  margin-bottom: 1.875rem;
}
@media print, screen and (min-width: 48.0625em) {
  .try-now .button,
  .try-now .headline {
    margin-bottom: 3.75rem;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .try-now .card--mainstory,
  .try-now .pb-img {
    margin-top: 3.75rem;
  }
}
.reference {
  font-weight: 700;
  position: relative;
  margin-left: 2.3125rem;
}
.reference:after,
.reference:before {
  right: calc(100% + 20px);
  top: 50%;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}
.reference:after {
  border-color: transparent;
  border-right-color: #ffc600;
  border-width: 17px;
  margin-top: -17px;
}
.reference__name {
  font-size: 1.125rem;
  line-height: 1.3125rem;
  margin-bottom: 0.25rem;
}
.reference__category {
  font-size: 0.875rem;
  line-height: 1rem;
  color: #000c2c;
  opacity: 0.6;
}
.customers__list {
  margin: 1.25rem 0 0;
  list-style: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}
.customers__item {
  width: 50%;
  max-width: 160px;
  padding: 1.25rem;
}
@media print, screen and (min-width: 48.0625em) {
  .customers__item {
    width: 20%;
    max-width: initial;
    padding: 0.625rem 1.875rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .customers__item {
    padding: 0.625rem 3.125rem;
  }
}
.page-resources__list-intro {
  margin: 0 auto;
  max-width: 33.75rem;
  margin-bottom: 11.25rem;
  text-align: center;
}
@media print, screen and (max-width: 48em) {
  .page-resources__list-intro {
    margin-bottom: 6.25rem;
  }
}
.page-resources__list-intro h2 {
  line-height: 1.2;
  font-size: 3rem;
  margin-bottom: 3.125rem;
}
@media print, screen and (max-width: 48em) {
  .page-resources__list-intro h2 {
    font-size: 2.25rem;
    margin-bottom: 2.5rem;
  }
}
.page-resources__list-intro h4 {
  font-size: 1.125rem;
  line-height: 1.4;
  font-weight: 400;
  margin-bottom: 0;
}
.grid-visual {
  top: 0;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  width: 71rem;
  height: 100%;
  z-index: 999;
  position: fixed;
  pointer-events: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}
@media print, screen and (max-width: 80em) {
  .grid-visual {
    width: 53.75rem;
  }
}
@media print, screen and (max-width: 64em) {
  .grid-visual {
    width: 40rem;
  }
}
@media print, screen and (max-width: 48em) {
  .grid-visual {
    width: calc(100% - 80px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .grid-visual {
    width: calc(100% - 80px);
  }
}
.grid-visual > div {
  width: 3.625rem;
  height: 100%;
  background-color: red;
  opacity: 0.1;
}
@media print, screen and (max-width: 80em) {
  .grid-visual > div {
    width: 6.875rem;
  }
  .grid-visual > div:nth-child(n + 7) {
    display: none;
  }
}
@media print, screen and (max-width: 64em) {
  .grid-visual > div {
    width: 8.125rem;
  }
  .grid-visual > div:nth-child(n + 5) {
    display: none;
  }
}
@media print, screen and (max-width: 48em) {
  .grid-visual > div {
    width: calc(25% - 15px);
  }
  .grid-visual > div:nth-child(n + 5) {
    display: none;
  }
}
.shadow-border {
  -webkit-box-shadow: 0 6px 10px rgba(71, 80, 89, 0.05);
  box-shadow: 0 6px 10px rgba(71, 80, 89, 0.05);
}
.cell.auto {
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
}
.button {
  border: 1px solid transparent;
  border-radius: 0.5rem;
  padding: 0.875rem 0.9375rem;
  font-size: 0.90625rem;
  min-width: 10rem;
  font-weight: 700;
  line-height: 1;
  color: #fff;
  display: inline-block;
  vertical-align: middle;
  font-family: inherit;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  text-align: center;
  cursor: pointer;
  position: relative;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-transition: background-color 0.25s ease-out, color 0.25s ease-out;
  transition: background-color 0.25s ease-out, color 0.25s ease-out;
  background-color: #0079f2;
}
.button:hover {
  color: #fff;
  background-color: #2693ff;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.button:focus {
  color: #fff;
  background-color: #0079f2;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
  -webkit-transition: none;
  transition: none;
}
.button:active {
  color: #fff;
  background-color: #0566c6;
  -webkit-box-shadow: none;
  box-shadow: none;
  -webkit-transition: none;
  transition: none;
}
.button--small {
  font-size: 0.75rem;
  padding: 0.625rem 1.25rem;
  min-width: auto;
}
.button--secondary {
  color: #0079f2;
  border-color: #0079f2;
  background-color: transparent;
}
.button--secondary:hover {
  color: #0079f2;
  border-color: #68b4ff;
  background-color: transparent;
}
.button--secondary:focus {
  color: #0079f2;
  border-color: #0566c6;
  background-color: transparent;
}
.button--secondary:active {
  color: #0079f2;
  border-color: #0079f2;
  background-color: #e2effd;
}
.button--tertiary {
  color: #30363c;
  border-color: #838c96;
  background-color: transparent;
}
.button--tertiary:hover {
  color: #30363c;
  border-color: #bcc4cc;
  background-color: transparent;
}
.button--tertiary:focus {
  color: #30363c;
  border-color: #30363c;
  background-color: transparent;
}
.button--tertiary:active {
  color: #30363c;
  border-color: #838c96;
  background-color: #f2f5f7;
}
.button--link {
  min-width: auto;
  padding: 0.5rem 1.5rem 0.5rem 0;
  color: #0079f2;
  background-color: transparent;
}
.button--link:hover {
  color: #0079f2;
  background-color: transparent;
}
.button--link:focus {
  color: #0079f2;
  background-color: transparent;
}
.button--link:active {
  color: #68b4ff;
  background-color: transparent;
}
.button--link:after,
.button--link:before {
  content: "";
  top: 50%;
  right: 0.625rem;
  width: 0.625rem;
  height: 0.1875rem;
  border-radius: 0.125rem;
  background-color: #0079f2;
  position: absolute;
}
.button--link:before {
  -webkit-transform: translateY(1px) rotate(45deg);
  -ms-transform: translateY(1px) rotate(45deg);
  transform: translateY(1px) rotate(45deg);
  -webkit-transform-origin: 100% 50%;
  -ms-transform-origin: 100% 50%;
  transform-origin: 100% 50%;
}
.button--link:after {
  -webkit-transform: translateY(-1px) rotate(-45deg);
  -ms-transform: translateY(-1px) rotate(-45deg);
  transform: translateY(-1px) rotate(-45deg);
  -webkit-transform-origin: 100% 50%;
  -ms-transform-origin: 100% 50%;
  transform-origin: 100% 50%;
}
.button--link:active:after,
.button--link:active:before {
  background-color: #68b4ff;
}
.button--icon-left {
  padding-left: 2.4375rem;
  padding-right: 0.9375rem;
}
.button--icon-right {
  text-align: left;
  padding-right: 2.4375rem;
}
.button--blog-see-all {
  margin: 10px auto 100px;
}
.button span {
  font-weight: 400;
}
.button svg {
  width: 1rem;
  height: 1rem;
}
.button__icon {
  width: 1.5rem;
  height: 1.5rem;
  padding: 0.25rem;
  left: 0.4375rem;
  top: 50%;
  margin-top: -0.75rem;
  border-radius: 100%;
  position: absolute;
}
.button--icon-right .button__icon {
  left: auto;
  right: 0.4375rem;
}
.button--icon-white .button__icon {
  background-color: #fff;
}
.button__icon img,
.button__icon svg {
  width: 1rem;
  height: 1rem;
  vertical-align: top;
}
@font-face {
  font-family: "eina 02";
  src: url(/wp-content/themes/productboard/public/font/eina02-regular.woff2)
    format("woff2");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: "eina 02";
  src: url(/wp-content/themes/productboard/public/font/eina02-regular-italic.woff2)
    format("woff2");
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: "eina 02";
  src: url(/wp-content/themes/productboard/public/font/eina02-semibold.woff2)
    format("woff2");
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
a {
  font-weight: 700;
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
}
.h1,
.h2,
h1,
h2 {
  letter-spacing: -1.3616px;
}
.card--article .card-section .headline,
.h5 {
  letter-spacing: 0;
}
.h6 {
  letter-spacing: 0;
}
.article__category,
.article__date,
.article__meta .author__name,
.card .author__name,
.card .menu,
.customer__category,
.customer__date,
.pre-headline {
  font-size: 10px;
  line-height: 12px;
  text-transform: uppercase;
  font-weight: 700;
  color: #000c2c;
  opacity: 0.4;
}
.article__meta .large.author__name,
.card .large.author__name,
.card .large.menu,
.large.article__category,
.large.article__date,
.large.customer__category,
.large.customer__date,
.pre-headline.large {
  font-size: 14px;
  line-height: 16px;
  opacity: 0.4;
  letter-spacing: 0;
}
.quote {
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.3125rem;
}
.bg-gray {
  background-color: #fafafb;
}
.color-gray {
  color: rgba(0, 12, 44, 0.4);
}
.color-blue {
  color: #0569ff;
}
.color-yellow {
  color: #ffc600;
}
.color-red {
  color: #ff2638;
}
.card--mainstory,
.pb-img {
  position: relative;
  display: inline-block;
}
.card--mainstory:hover:after,
.card--mainstory:hover:before,
.pb-img:hover:after,
.pb-img:hover:before {
  -webkit-transform: scale(1.05);
  -ms-transform: scale(1.05);
  transform: scale(1.05);
}
.card--mainstory:after,
.card--mainstory:before,
.pb-img:after,
.pb-img:before {
  content: "";
  position: absolute;
  bottom: -0.75rem;
  right: -0.75rem;
  background-color: #ffc600;
  display: block;
  width: 7.8125rem;
  height: 7.8125rem;
  z-index: 0;
  border-radius: 0.625rem;
  -webkit-transition: -webkit-transform 0.4s cubic-bezier(0.28, 0.84, 0.42, 1);
  transition: -webkit-transform 0.4s cubic-bezier(0.28, 0.84, 0.42, 1);
  transition: transform 0.4s cubic-bezier(0.28, 0.84, 0.42, 1);
  transition: transform 0.4s cubic-bezier(0.28, 0.84, 0.42, 1),
    -webkit-transform 0.4s cubic-bezier(0.28, 0.84, 0.42, 1);
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
}
.card--mainstory:before,
.pb-img:before {
  width: 40%;
  height: 60%;
  background-color: #ff2638;
  top: -0.75rem;
  left: -0.75rem;
  bottom: auto;
  right: auto;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory:before,
  .pb-img:before {
    width: 26.25rem;
  }
}
.card--mainstory img,
.pb-img img {
  position: relative;
  z-index: 2;
}
.has-overlay {
  position: relative;
}
.has-overlay:before {
  content: "";
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  background: -webkit-gradient(
    linear,
    left bottom,
    left top,
    color-stop(-12.75%, #000),
    to(rgba(0, 0, 0, 0))
  );
  background: linear-gradient(0deg, #000 -12.75%, rgba(0, 0, 0, 0) 100%);
  z-index: 1;
}
.box {
  border-radius: 1.375rem;
  padding: 1.875rem;
}
@media print, screen and (max-width: 64.06125em) {
  .box--newsletter {
    margin-bottom: 3.75rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .box--newsletter {
    padding: 3.125rem 3.75rem;
    margin-top: -3.4375rem;
  }
}
.box--newsletter .headline {
  margin-bottom: 1.25rem;
}
.box--newsletter label,
.box--newsletter p {
  color: rgba(0, 12, 44, 0.4);
}
.box--newsletter p {
  margin-bottom: 1.875rem;
}
.box--newsletter form button,
.box--newsletter form input {
  margin-bottom: 0;
}
@media print, screen and (max-width: 48.06125em) {
  .box--newsletter form .button {
    margin-top: 1.25rem;
  }
}
.box--newsletter .grid-x {
  margin-bottom: 2.8125rem;
}
.mb-100 {
  margin-bottom: 3.125rem;
}
@media print, screen and (min-width: 48.0625em) {
  .mb-100 {
    margin-bottom: 6.25rem;
  }
}
.pb-0 {
  padding-bottom: 0;
}
.icon-check {
  position: relative;
  width: 1.125rem;
  height: 0.875rem;
}
.icon-check:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.1875rem;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTInIGhlaWdodD0nOCcgdmlld0JveD0nMCAwIDEyIDgnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+PHBhdGggZmlsbC1ydWxlPSdldmVub2RkJyBjbGlwLXJ1bGU9J2V2ZW5vZGQnIGQ9J00xMS4yNTAxIDEuNDMzNDdMOS45OTA4MSAwLjI0ODQ3NEw0LjUzMDgxIDUuMzgyMjJMMi4wMTAwNiAzLjAxMjk3TDAuNzUwMDYxIDQuMTk3MjJMNC41MzAwNiA3Ljc1MTQ3TDUuNzkwODEgNi41NjY0N0wxMS4yNTAxIDEuNDMzNDdaJyBmaWxsPScjRkZDNjAwJy8+PC9zdmc+Cg==);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  width: 1.125rem;
  height: 0.875rem;
}
.icon-check.red:before {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTInIGhlaWdodD0nOCcgdmlld0JveD0nMCAwIDEyIDgnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+PHBhdGggZmlsbC1ydWxlPSdldmVub2RkJyBjbGlwLXJ1bGU9J2V2ZW5vZGQnIGQ9J00xMS4yNTAxIDEuNDMzNDdMOS45OTA4MSAwLjI0ODQ3NEw0LjUzMDgxIDUuMzgyMjJMMi4wMTAwNiAzLjAxMjk3TDAuNzUwMDYxIDQuMTk3MjJMNC41MzAwNiA3Ljc1MTQ3TDUuNzkwODEgNi41NjY0N0wxMS4yNTAxIDEuNDMzNDdaJyBmaWxsPScjRkYyNjM4Jy8+PC9zdmc+Cg==);
}
.icon-check.blue:before {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTInIGhlaWdodD0nOCcgdmlld0JveD0nMCAwIDEyIDgnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+PHBhdGggZmlsbC1ydWxlPSdldmVub2RkJyBjbGlwLXJ1bGU9J2V2ZW5vZGQnIGQ9J00xMS4yNSAxLjQzMzQ3TDkuOTkwNzUgMC4yNDg0NzRMNC41MzA3NSA1LjM4MjIyTDIuMDEgMy4wMTI5N0wwLjc1IDQuMTk3MjJMNC41MyA3Ljc1MTQ3TDUuNzkwNzUgNi41NjY0N0wxMS4yNSAxLjQzMzQ3WicgZmlsbD0nIzBGNkZGRicvPjwvc3ZnPgo=);
}
.icon-check.black:before {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTInIGhlaWdodD0nOCcgdmlld0JveD0nMCAwIDEyIDgnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+PHBhdGggZmlsbC1ydWxlPSdldmVub2RkJyBjbGlwLXJ1bGU9J2V2ZW5vZGQnIGQ9J00xMS4yNTAxIDEuNDMzNTRMOS45OTA4MSAwLjI0ODUzNUw0LjUzMDgxIDUuMzgyMjlMMi4wMTAwNiAzLjAxMzA0TDAuNzUwMDYxIDQuMTk3MjlMNC41MzAwNiA3Ljc1MTUzTDUuNzkwODEgNi41NjY1M0wxMS4yNTAxIDEuNDMzNTRaJyBmaWxsPScjMDAwQzJDJy8+PC9zdmc+Cg==);
}
.section--article .article {
  color: #475059;
}
@media print, screen and (min-width: 48.0625em) {
  .article .section__title {
    margin-bottom: 4.375rem;
  }
}
.article__meta {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64.06125em) {
  .article__meta {
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
}
.article__meta .author {
  margin-bottom: 0;
}
.article__meta .author img,
.article__meta .author p {
  margin-bottom: 0;
}
@media print, screen and (max-width: 64.06125em) {
  .article__meta .author__avatar {
    width: 2.25rem;
    height: 2.25rem;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 2.25rem;
    -ms-flex: 0 0 2.25rem;
    flex: 0 0 2.25rem;
  }
}
.article__meta .author__name {
  opacity: 0.4;
  margin-bottom: 0;
}
@media print, screen and (max-width: 64.06125em) {
  .article__meta .author__name {
    opacity: 1;
    margin-bottom: -7px;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .article__meta .author__info {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.article__meta li {
  margin-right: 1.25rem;
}
@media print, screen and (min-width: 64.0625em) {
  .article__meta li {
    width: 100%;
  }
}
.article__category,
.article__date {
  opacity: 0.4;
  margin-right: 0.625rem;
}
@media print, screen and (min-width: 64.0625em) {
  .article__category,
  .article__date {
    margin-left: 2.5rem;
  }
}
.article h1,
.article h2,
.article h3,
.article h4,
.article h5 {
  margin-bottom: 1.5625rem;
  margin-top: 2.8125rem;
}
.article h1 {
  color: #000c2c;
  margin-top: 0;
  margin-bottom: 1.875rem;
}
.article img,
.article ol,
.article p,
.article ul {
  margin-bottom: 1.25rem;
}
.article blockquote,
.article ol,
.article p,
.article ul {
  font-size: 1.125rem;
  line-height: 1.5625rem;
}
.article ol {
  margin-left: 0;
  list-style: none;
  counter-reset: item;
}
.article ol li {
  padding-bottom: 2.5rem;
  padding-left: 3.125rem;
  position: relative;
}
.article ol li:before {
  content: counter(item) ". ";
  counter-increment: item;
  opacity: 0.4;
  font-weight: 700;
  position: absolute;
  left: 0;
}
.aligncenter {
  display: block;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}
.alignright {
  display: block;
  margin-left: auto;
  text-align: right;
}
.article-share {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  left: 0;
  float: none;
  font-size: 0;
}
@media print, screen and (max-width: 48.06125em) {
  .article-share {
    margin-top: 1.25rem;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .article-share {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
@media screen and (min-width: 75em) {
  .article-share {
    padding-left: 7.5rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .article-share {
    top: 7.5rem;
    margin-top: 0.9375rem;
  }
}
.article-share__item {
  width: 2.25rem;
  height: 2.25rem;
  background: #fff;
  border: 1px solid #d5dde3;
  color: #475059;
  border-radius: 50%;
  display: block;
  position: relative;
  -webkit-transition: background 0.25s ease;
  transition: background 0.25s ease;
}
@media print, screen and (min-width: 64.0625em) {
  .article-share__item {
    margin-bottom: 1.25rem;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .article-share__item:not(:last-child) {
    margin-right: 0.625rem;
  }
}
.article-share__item:hover {
  background: #d5dde3;
}
.article-share__item svg {
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%) scale(0.75);
  -ms-transform: translate(-50%, -50%) scale(0.75);
  transform: translate(-50%, -50%) scale(0.75);
}
.blog-article--has-sidebar .article-share__item {
  margin-bottom: 1.25rem;
  margin-right: 0.625rem;
}
.container {
  margin: 0 auto;
  width: 100%;
  max-width: 71rem;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .container {
    max-width: 53.75rem;
  }
}
@media print, screen and (max-width: 64em) {
  .container {
    max-width: 40rem;
  }
}
@media print, screen and (max-width: 48em) {
  .container {
    max-width: 100%;
    padding: 0 2.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .container {
    padding: 0 2.5rem;
  }
}
@media screen and (min-width: 80em) {
  .container--indent {
    padding: 0 1.8125rem;
  }
}
@media screen and (min-width: 80em) {
  .container--indent-100 {
    padding: 0 6.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .container--feature-comparison {
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
  }
}
.site-footer {
  color: #fff;
  padding: 0;
  color: rgba(255, 255, 255, 0.5);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.site-footer p {
  font-size: 1rem;
  line-height: 1.375;
}
.site-footer a {
  font-weight: 400;
  color: rgba(255, 255, 255, 0.5);
}
.site-footer a:hover {
  color: #fff;
}
.site-footer strong {
  color: #fff;
  font-weight: 400;
}
.site-footer__block:nth-child(1) {
  width: 60%;
}
@media print, screen and (max-width: 64em) {
  .site-footer__block:nth-child(1) {
    width: 100%;
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
}
.site-footer__block:nth-child(2) {
  width: 40%;
  text-align: right;
}
@media print, screen and (max-width: 64em) {
  .site-footer__block:nth-child(2) {
    width: 100%;
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    text-align: left;
  }
}
.site-footer__block > :not(:last-child) {
  margin-bottom: 1.25rem;
}
.site-footer__summit-logo {
  right: 0;
  top: -14.375rem;
  width: 11.875rem;
  position: absolute;
}
@media print, screen and (max-width: 80em) {
  .site-footer__summit-logo {
    width: 8.75rem;
    top: -11.875rem;
  }
}
@media print, screen and (max-width: 64em) {
  .site-footer__summit-logo {
    display: none;
  }
}
.site-footer__summit-logo-image {
  width: 100%;
}
.site-header {
  top: 0;
  left: 0;
  padding-top: 1.25rem;
  height: 8.75rem;
  width: 100%;
  -webkit-transition: 0.25s height;
  transition: 0.25s height;
  z-index: 100;
  position: fixed;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .site-header {
    height: 6.25rem;
  }
}
@media print, screen and (max-width: 48em) {
  .site-header {
    height: 5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-header {
    padding-top: 0.625rem;
  }
}
.site-header.is-compact {
  height: 6.25rem;
}
@media print, screen and (max-width: 48em) {
  .site-header.is-compact {
    height: 5rem;
  }
}
.site-header.is-pushed {
  top: 5.375rem;
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .site-header.is-pushed {
    top: 8.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-header.is-pushed {
    top: 6.875rem;
  }
}
.site-header.is-pushed.is-compact {
  top: 0;
  position: fixed;
}
.is-site-nav-active .site-header.is-pushed {
  top: 0;
}
.site-header:before {
  content: "";
  left: 0;
  top: 0;
  width: 100%;
  height: 2.5rem;
  z-index: 10;
  background-color: #fff;
  position: absolute;
}
@media print, screen and (max-width: 37.5em) {
  .site-header:before {
    height: 1.25rem;
  }
}
.site-header:after {
  content: "";
  left: 1.25rem;
  top: 1.25rem;
  width: calc(100% - 40px);
  height: calc(100% - 20px);
  border-radius: 1.25rem;
  z-index: 20;
  background-color: #fafafb;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .site-header:after {
    -webkit-transition: 0.4s;
    transition: 0.4s;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-header:after {
    left: 0.625rem;
    top: 0.625rem;
    width: calc(100% - 20px);
    height: calc(100% - 10px);
  }
}
@media print, screen and (max-width: 64em) {
  .is-site-nav-active .site-header:after {
    left: 0;
    top: 0;
    width: 100%;
    height: 100vh;
    border-radius: 0;
  }
}
.site-header__container {
  height: 100%;
  z-index: 30;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  position: relative;
}
.site-header__logo {
  max-width: 11.125rem;
  left: -0.9375rem;
  padding: 0 0.9375rem;
  height: 100%;
  outline: 0;
  z-index: 3;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-right: auto;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .site-header__logo {
    max-width: 9.375rem;
  }
}
.site-header__logo-wrapper {
  overflow: hidden;
  height: 1.125rem;
}
@media print, screen and (max-width: 64em) {
  .site-header__logo-wrapper {
    width: 1.875rem;
    height: 1.25rem;
  }
}
.site-header__logo-image {
  vertical-align: top;
  width: auto;
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .site-header__logo-image {
    width: 10.25rem;
    height: 1.25rem;
    max-width: none;
  }
}
.site-header__nav {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.site-header__nav:before {
  content: "";
  left: 0;
  top: -1.25rem;
  width: 100%;
  height: 5.3125rem;
  z-index: 2;
  background-color: #fafafb;
  position: absolute;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .is-site-nav-active .site-header__nav:before {
    display: block;
  }
}
.site-header__try-link {
  margin-left: 1.5625rem;
  font-size: 0.8125rem;
  height: 2rem;
  padding: 0.625rem 1.875rem;
  border-radius: 0.5rem;
  color: #fff;
  background-color: #0071e1;
  -webkit-transition: 0.15s;
  transition: 0.15s;
  z-index: 3;
  display: none;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  white-space: nowrap;
  position: relative;
}
.site-header__try-link--nomenu {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 80em) {
  .site-header__try-link {
    font-size: 0.75rem;
  }
}
@media print, screen and (max-width: 64em) {
  .site-header__try-link {
    right: -0.75rem;
    margin-left: auto;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-header__try-link--desktop {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.site-header__try-link--mobile {
  padding: 0.625rem 1.25rem;
  z-index: 5;
}
@media print, screen and (max-width: 64em) {
  .site-header__try-link--mobile {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.site-header__nav-toggle {
  right: -1.0625rem;
  width: 3.75rem;
  height: 100%;
  outline: 0;
  z-index: 3;
  position: relative;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .site-header__nav-toggle {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.site-header__nav-toggle-icon {
  left: 50%;
  top: 50%;
  width: 1.5rem;
  height: 0.125rem;
  border-radius: 0.125rem;
  -webkit-transform: translate(-50%, 0);
  -ms-transform: translate(-50%, 0);
  transform: translate(-50%, 0);
  -webkit-transform-origin: 50% 50%;
  -ms-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  background-color: #afafb0;
  position: absolute;
}
.site-header__nav-toggle-icon:nth-child(1) {
  top: calc(50% - 7px);
  -webkit-transition: top 0.1s 0.1s, -webkit-transform 0.1s 0s;
  transition: top 0.1s 0.1s, -webkit-transform 0.1s 0s;
  transition: top 0.1s 0.1s, transform 0.1s 0s;
  transition: top 0.1s 0.1s, transform 0.1s 0s, -webkit-transform 0.1s 0s;
}
.is-site-nav-active .site-header__nav-toggle-icon:nth-child(1) {
  top: calc(50% - 1px);
  -webkit-transform: translate(-50%, 0) rotate(-45deg);
  -ms-transform: translate(-50%, 0) rotate(-45deg);
  transform: translate(-50%, 0) rotate(-45deg);
  -webkit-transition: top 0.1s, -webkit-transform 0.1s 0.1s;
  transition: top 0.1s, -webkit-transform 0.1s 0.1s;
  transition: top 0.1s, transform 0.1s 0.1s;
  transition: top 0.1s, transform 0.1s 0.1s, -webkit-transform 0.1s 0.1s;
  background-color: #666d80;
  width: 1.25rem;
}
.site-header__nav-toggle-icon:nth-child(2) {
  top: calc(50% - 1px);
  -webkit-transition: opacity 0s 0.1s;
  transition: opacity 0s 0.1s;
}
.is-site-nav-active .site-header__nav-toggle-icon:nth-child(2) {
  opacity: 0;
  -webkit-transition: opacity 0.1s 0.1s;
  transition: opacity 0.1s 0.1s;
  background-color: #666d80;
  width: 1.25rem;
}
.site-header__nav-toggle-icon:nth-child(3) {
  top: calc(50% + 5px);
  -webkit-transition: top 0.1s 0.1s, -webkit-transform 0.1s 0s;
  transition: top 0.1s 0.1s, -webkit-transform 0.1s 0s;
  transition: top 0.1s 0.1s, transform 0.1s 0s;
  transition: top 0.1s 0.1s, transform 0.1s 0s, -webkit-transform 0.1s 0s;
}
.is-site-nav-active .site-header__nav-toggle-icon:nth-child(3) {
  top: calc(50% - 1px);
  -webkit-transform: translate(-50%, 0) rotate(45deg);
  -ms-transform: translate(-50%, 0) rotate(45deg);
  transform: translate(-50%, 0) rotate(45deg);
  -webkit-transition: top 0.1s, -webkit-transform 0.1s 0.1s;
  transition: top 0.1s, -webkit-transform 0.1s 0.1s;
  transition: top 0.1s, transform 0.1s 0.1s;
  transition: top 0.1s, transform 0.1s 0.1s, -webkit-transform 0.1s 0.1s;
  background-color: #666d80;
  width: 1.25rem;
}
.site-header__nav-return {
  left: 0;
  width: 40%;
  height: 100%;
  -webkit-transition: 0.3s;
  transition: 0.3s;
  font-size: 0.875rem;
  line-height: 1.43;
  z-index: 4;
  background-color: #fafafb;
  color: #666d80;
  white-space: nowrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: absolute;
  overflow: hidden;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .site-header__nav-return {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    left: 0;
  }
}
@media print, screen and (max-width: 48em) {
  .site-header__nav-return {
    left: 2.5rem;
  }
}
.site-header__nav-return:before {
  content: "";
  width: 0.625rem;
  height: 0.625rem;
  margin-right: 0.9375rem;
  -webkit-transform: translate(5px, 1px) rotate(-45deg);
  -ms-transform: translate(5px, 1px) rotate(-45deg);
  transform: translate(5px, 1px) rotate(-45deg);
  border-left: 2px solid #666d80;
  border-top: 2px solid #666d80;
  position: relative;
}
.site-header__nav-return:active,
.site-header__nav-return:hover {
  color: #666d80;
}
.site-header__nav-return[data-site-nav-return="0"] {
  opacity: 0;
  pointer-events: none;
}
.site-nav {
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .site-nav {
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
    position: fixed;
    opacity: 0;
    -webkit-transition: 0.2s;
    transition: 0.2s;
    pointer-events: none;
  }
}
.is-site-nav-active .site-nav {
  opacity: 1;
  -webkit-transition: 0.2s 0.3s;
  transition: 0.2s 0.3s;
  pointer-events: all;
  overflow-y: scroll;
}
.site-nav .site-nav__try-link {
  display: none;
}
@media print, screen and (max-width: 37.5em) {
  .site-nav .site-nav__try-link {
    width: 100%;
    padding: 0.75rem 1.5rem;
    max-width: calc(100% - 80px);
    font-size: 0.875rem;
    line-height: 1.43;
    border-radius: 0.625rem;
    display: block;
    margin: 0 auto;
    background-color: #005ce6;
    color: #fff;
    font-weight: 700;
    text-align: center;
  }
}
.site-nav > ul {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  z-index: 10;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  list-style: none;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul {
    height: auto;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-transition: 0.25s ease-out;
    transition: 0.25s ease-out;
    padding: 7.5rem 2.5rem 0;
    margin: 0 auto;
    position: relative;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
@media print, screen and (max-width: 48em) {
  .site-nav > ul {
    padding-top: 6.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-nav > ul {
    padding-top: 5.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav[data-site-nav="1"] > ul {
    -webkit-transform: translateX(-100%);
    -ms-transform: translateX(-100%);
    transform: translateX(-100%);
  }
}
.site-nav > ul > li {
  z-index: 20;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li {
    width: 100%;
    margin-bottom: 0.9375rem;
    max-width: 40rem;
  }
}
.site-nav > ul > li.menu-item-has-children {
  z-index: 10;
}
.site-nav > ul > li.site-nav-link--try-now {
  display: none;
  margin-top: 1.875rem;
}
@media print, screen and (max-width: 37.5em) {
  .site-nav > ul > li.site-nav-link--try-now {
    display: block;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav > ul > li:hover {
    height: 100%;
  }
}
.site-nav > ul > li > a {
  font-size: 0.9375rem;
  padding: 0.75rem 1.5rem;
  height: 100%;
  z-index: 2;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
  color: #323c55;
}
@media print, screen and (max-width: 80em) {
  .site-nav > ul > li > a {
    padding: 0.75rem 1.25rem;
    font-size: 0.8125rem;
  }
}
.site-nav > ul > li > a:hover {
  color: #005ce6;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > a:hover {
    color: #323c55;
    background-color: #f2f3f4;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > a {
    width: 100%;
    line-height: 1.43;
    font-size: 0.875rem;
    padding: 0.75rem 1.5rem;
    border-radius: 0.625rem;
  }
}
.site-nav > ul > li.site-nav-link--try-now > a,
.site-nav > ul > li.site-nav-link--try-now > a:hover {
  background-color: #005ce6;
  color: #fff;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.site-nav > ul > li.menu-item-has-children > a:after,
.site-nav > ul > li.menu-item-has-children > a:before {
  content: "";
  position: absolute;
  display: none;
  right: 0.375rem;
  width: 0;
  height: 0;
  z-index: 10;
  opacity: 0;
  -webkit-transition: 0.3s;
  transition: 0.3s;
  border-style: solid;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.menu-item-has-children > a:after,
  .site-nav > ul > li.menu-item-has-children > a:before {
    display: none;
  }
}
.site-nav > ul > li.menu-item-has-children > a:before {
  bottom: 0.3125rem;
  border-width: 0 24px 14px;
  border-color: transparent transparent #ebecef transparent;
}
.site-nav > ul > li.menu-item-has-children > a:after {
  bottom: 0.25rem;
  border-width: 0 24px 14px;
  border-color: transparent transparent #fff transparent;
}
.site-nav > ul > li.menu-item-has-children:hover > a:after,
.site-nav > ul > li.menu-item-has-children:hover > a:before {
  opacity: 1;
  display: block;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.menu-item-has-children:hover > a:after,
  .site-nav > ul > li.menu-item-has-children:hover > a:before {
    display: none;
  }
}
.site-nav > ul > li.menu-item-has-children > a > i {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  width: 0.625rem;
  height: 0.625rem;
  margin-left: 0.4375rem;
  display: block;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.menu-item-has-children > a > i {
    display: none;
  }
}
.site-nav > ul > li.menu-item-has-children > a > i:after,
.site-nav > ul > li.menu-item-has-children > a > i:before {
  content: "";
  width: 0.0625rem;
  height: 0.375rem;
  background-color: #323c55;
  left: 50%;
  top: 50%;
  position: absolute;
  display: block;
}
.site-nav > ul > li.menu-item-has-children > a > i:before {
  -webkit-transform-origin: 0 100%;
  -ms-transform-origin: 0 100%;
  transform-origin: 0 100%;
  -webkit-transform: translate(-50%, -50%) rotate(45deg);
  -ms-transform: translate(-50%, -50%) rotate(45deg);
  transform: translate(-50%, -50%) rotate(45deg);
}
.site-nav > ul > li.menu-item-has-children > a > i:after {
  -webkit-transform-origin: 100% 100%;
  -ms-transform-origin: 100% 100%;
  transform-origin: 100% 100%;
  -webkit-transform: translate(-50%, -50%) rotate(-45deg);
  -ms-transform: translate(-50%, -50%) rotate(-45deg);
  transform: translate(-50%, -50%) rotate(-45deg);
}
.site-nav > ul > li.menu-item-has-children > a > span {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
}
.site-nav > ul > li > ul {
  left: 0;
  top: calc(100% - 5px);
  width: 100%;
  margin: 0;
  z-index: 1;
  border-radius: 1.25rem;
  background-color: #fff;
  border: 0.0625rem solid #ebecef;
  -webkit-box-shadow: 0 1.25rem 2.125rem rgba(0, 0, 0, 0.03);
  box-shadow: 0 1.25rem 2.125rem rgba(0, 0, 0, 0.03);
  position: absolute;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  list-style: none;
  -webkit-transition: 0.3s;
  transition: 0.3s;
  opacity: 0;
  pointer-events: none;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul {
    padding: 7.5rem 2.5rem 2.5rem;
    left: 100%;
    top: 0;
    border: 0;
    border-radius: 0;
    background: 0 0;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
@media print, screen and (max-width: 48em) {
  .site-nav > ul > li > ul {
    padding-top: 6.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-nav > ul > li > ul {
    padding-top: 5.625rem;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav > ul > li.is-hovering > ul,
  .site-nav > ul > li:hover > ul {
    opacity: 1;
    pointer-events: all;
    -webkit-transition-delay: 0s;
    transition-delay: 0s;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.is-active > ul {
    opacity: 1;
    pointer-events: all;
  }
}
.site-nav > ul > li > ul > li {
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  margin: 3.625rem 0 2.75rem;
  padding: 0 2.75rem;
  position: relative;
  border-left: 0.0625rem solid #ebecef;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 0;
    margin: 0;
    border: 0;
    background: 0 0;
    position: static;
  }
}
.site-nav > ul > li > ul > li:first-child {
  border: 0;
}
.site-nav > ul > li > ul > li > a {
  margin-bottom: 1.25rem;
  font-size: 1.125rem;
  line-height: 1;
  color: #000c2c;
  display: block;
}
.site-nav > ul > li > ul > li > a[href="#"] {
  pointer-events: none;
  cursor: default;
}
.is-site-nav-active .site-nav > ul > li > ul > li > a[href="#"] {
  cursor: default;
}
@media print, screen and (max-width: 64em) {
  .is-site-nav-active .site-nav > ul > li > ul > li > a[href="#"] {
    pointer-events: all;
  }
}
.site-nav > ul > li > ul > li > a > p:empty {
  display: none;
}
.site-nav > ul > li > ul > li > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul {
    padding: 7.5rem 2.5rem 2.5rem;
    width: 100%;
    left: 100%;
    top: 0;
    opacity: 0;
    -webkit-transition: opacity 0.3s;
    transition: opacity 0.3s;
    pointer-events: none;
    position: absolute;
    overflow: hidden;
  }
}
@media print, screen and (max-width: 48em) {
  .site-nav > ul > li > ul > li > ul {
    padding-top: 6.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .site-nav > ul > li > ul > li > ul {
    padding-top: 5.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li.is-active > ul {
    opacity: 1;
    pointer-events: all;
  }
}
.site-nav > ul > li > ul > li > ul > li {
  width: 100%;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul > li {
    margin: 0 auto 0.9375rem;
    max-width: 40rem;
  }
}
.site-nav > ul > li > ul > li > ul > li > a {
  padding: 0.625rem 0;
  font-size: 0.875rem;
  line-height: 1.35;
  font-weight: 400;
  color: #666d80;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-flex-wrap: inherit;
  -ms-flex-wrap: inherit;
  flex-wrap: inherit;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul > li > a {
    width: 100%;
    line-height: 1.43;
    font-size: 0.875rem;
    padding: 0.75rem 1.5rem;
    border-radius: 0.625rem;
    font-weight: 700;
    color: #323c55;
  }
}
.site-nav > ul > li > ul > li > ul > li.is-active > a,
.site-nav > ul > li > ul > li > ul > li > a:hover {
  color: #005ce6;
  -webkit-transition: background-color 0.2s, color 0.2s;
  transition: background-color 0.2s, color 0.2s;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul > li.is-active > a,
  .site-nav > ul > li > ul > li > ul > li > a:hover {
    color: #323232;
    background-color: #f2f3f4;
  }
}
.site-nav > ul > li > ul > li > ul > li > a > span {
  -webkit-transition: color 0.2s;
  transition: color 0.2s;
}
.site-nav > ul > li > ul > li > ul > li > a > i {
  width: 1rem;
  height: 1rem;
  margin-right: 0.75rem;
  display: block;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul > li > a > i {
    margin-right: 0.875rem;
  }
}
.site-nav > ul > li > ul > li > ul > li > a > i:empty {
  display: none;
}
.site-nav > ul > li > ul > li > ul > li > a > i > img {
  width: 100%;
  height: 100%;
  vertical-align: top;
}
.site-nav > ul > li > ul > li > ul > li > a > p {
  padding: 0.5rem 0 0 1.75rem;
  margin: 0;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  width: 100%;
  font-weight: 400;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li > ul > li > ul > li > a > p {
    padding-left: 1.875rem;
  }
}
.site-nav > ul > li > ul > li > ul > li > a > p:empty {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul {
    max-height: 0;
    overflow: hidden;
  }
}
.site-nav > ul > li.site-nav-subnav--product.is-active > ul {
  max-height: none;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul > li {
    padding: 0;
    margin: 0 auto;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    max-width: 40rem;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li.site-nav-item--features {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 67%;
  -ms-flex: 0 0 67%;
  flex: 0 0 67%;
  padding-right: 1.5625rem;
}
@media print, screen and (max-width: 64em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li.site-nav-item--features {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding-right: 0;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li.site-nav-item--platform {
  padding-left: 1.5625rem;
}
@media print, screen and (max-width: 64em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li.site-nav-item--platform {
    padding-left: 0;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li > a {
  padding: 0 1.25rem;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul > li > a {
    padding: 0 3.125rem;
    color: #879099;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul > li > ul {
    margin-bottom: 0.75rem;
    padding: 0;
    opacity: 1;
    pointer-events: all;
    position: relative;
    left: auto;
    top: auto;
  }
}
.site-nav
  > ul
  > li.site-nav-subnav--product
  > ul
  > li.site-nav-item--features
  > ul {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.site-nav
  > ul
  > li.site-nav-subnav--product
  > ul
  > li.site-nav-item--features
  > ul
  > li {
  margin: 0;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  width: 50%;
}
@media print, screen and (max-width: 64em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li.site-nav-item--features
    > ul
    > li {
    width: 100%;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-bottom: 0.5rem;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a {
  padding: 1.25rem;
  border-radius: 0.625rem;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a {
    background-color: #fff;
    margin-bottom: 0;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a:active,
.site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a:hover {
  background-color: #f7f7f9;
  color: inherit;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a:active,
  .site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a:hover {
    background-color: #f2f3f4;
  }
}
.site-nav > ul > li.site-nav-subnav--product > ul > li > ul > li > a > span {
  font-size: 1rem;
  font-weight: 700;
  color: #000c2c;
}
.site-nav
  > ul
  > li.site-nav-subnav--product
  > ul
  > li
  > ul
  > li
  > a:hover
  > span {
  color: #323232;
}
@media screen and (min-width: 64.0625em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li
    > ul
    > li.site-nav-item--insights
    > a:hover
    > span {
    color: #005ce6;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li
    > ul
    > li.site-nav-item--prioritization
    > a:hover
    > span {
    color: #ff2638;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li
    > ul
    > li.site-nav-item--roadmaps
    > a:hover
    > span {
    color: #ffc600;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li
    > ul
    > li.site-nav-item--engagement
    > a:hover
    > span {
    color: #7711de;
  }
}
@media screen and (min-width: 64.0625em) {
  .site-nav
    > ul
    > li.site-nav-subnav--product
    > ul
    > li
    > ul
    > li.site-nav-item--portal
    > a:hover
    > span {
    color: #7711de;
  }
}
.site-nav > ul > li.site-nav-subnav--more {
  margin-bottom: 0;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > a {
    display: none;
  }
}
.site-nav > ul > li.site-nav-subnav--more > ul {
  padding: 0.75rem;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul {
    left: auto;
    top: auto;
    position: static;
    display: block;
    background: 0 0;
    -webkit-box-shadow: none;
    box-shadow: none;
    padding: 0;
    border: 0;
    opacity: 1;
  }
}
@media print, screen and (max-width: 64em) {
  .is-site-nav-active .site-nav > ul > li.site-nav-subnav--more > ul {
    pointer-events: all;
  }
}
.site-nav > ul > li.site-nav-subnav--more > ul > li {
  margin: 0.75rem;
  padding: 2rem;
  border-radius: 0.625rem;
  border: 0.0625rem solid #ebecef;
  background-color: #fafafa;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul > li {
    padding: 0;
    margin: 0;
    border: 0;
    margin-bottom: 0.9375rem;
    background: 0 0;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul > li > a {
    line-height: 1.43;
    font-size: 0.875rem;
    padding: 0.75rem 1.5rem;
    margin-bottom: 0;
    border-radius: 0.625rem;
    color: #323c55;
  }
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul > li > a:hover {
    background-color: #f2f3f4;
  }
}
.site-nav > ul > li.site-nav-subnav--more > ul > li > ul > li > a {
  padding: 0.5rem 0;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul > li > ul > li > a {
    padding: 0.625rem 1.5625rem;
  }
}
.site-nav > ul > li.site-nav-subnav--more > ul > li > ul > li:last-child > a {
  padding-bottom: 0;
}
@media print, screen and (max-width: 64em) {
  .site-nav > ul > li.site-nav-subnav--more > ul > li > ul > li:last-child > a {
    padding: 0.625rem 1.5625rem;
  }
}
.layout {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.layout--sidebar .layout__block {
  position: relative;
}
.layout--sidebar .layout__block:nth-child(1) {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 15.875rem;
  -ms-flex: 0 0 15.875rem;
  flex: 0 0 15.875rem;
}
@media print, screen and (max-width: 80em) {
  .layout--sidebar .layout__block:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 16.25rem;
    -ms-flex: 0 0 16.25rem;
    flex: 0 0 16.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .layout--sidebar .layout__block:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.layout--sidebar .layout__block:nth-child(2) {
  margin-left: auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 52.625rem;
  -ms-flex: 0 0 52.625rem;
  flex: 0 0 52.625rem;
  max-width: 52.625rem;
}
@media print, screen and (max-width: 80em) {
  .layout--sidebar .layout__block:nth-child(2) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 35rem;
    -ms-flex: 0 0 35rem;
    flex: 0 0 35rem;
    max-width: 35rem;
  }
}
@media print, screen and (max-width: 64em) {
  .layout--sidebar .layout__block:nth-child(2) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    max-width: 100%;
  }
}
.layout--sidebar.layout--resources .layout__block--static {
  margin-top: 10.625rem;
}
@media print, screen and (max-width: 64em) {
  .layout--blog .layout__block:nth-child(1),
  .layout--resources .layout__block:nth-child(1) {
    display: none;
  }
}
.resources-home__sidebar {
  display: none;
  margin-top: 0;
  max-width: 16.25rem;
}
@media screen and (min-width: 64.0625em) {
  .resources-home__sidebar {
    display: block;
    margin-top: 13.75rem;
  }
}
@media screen and (min-width: 80em) {
  .resources-home__sidebar {
    margin-top: 11.875rem;
  }
}
.resources-home__sidebar--static {
  position: relative;
}
.layout--resources .resources-home__sidebar .layout__block--static {
  margin-top: 0;
}
.layout--sidebar .resources-home__sidebar .layout__block {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
}
@media screen and (min-width: 64em) {
  .layout--sidebar .resources-home__sidebar .layout__block {
    top: 8rem;
  }
}
.blog-article__sidebar .layout__block {
  padding-bottom: 3rem;
}
.blog-article__sidebar .layout__block.layout__block--sticky_marketo-inline {
  padding-bottom: 0;
}
.layout__block--sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 7rem;
  background: #fafafb;
  border-radius: 1.25rem;
  text-align: center;
  padding: 1.625rem;
}
.layout__block--sticky_marketo-cta {
  top: 9rem;
  padding: 0 1.625rem 1.625rem;
}
.layout__block--sticky_marketo-inline {
  padding: 0;
  margin-bottom: 2rem;
}
.intro {
  position: relative;
}
.intro.intro--layout-vertical {
  text-align: center;
  padding: 11rem 0 7rem;
}
@media print, screen and (max-width: 64em) {
  .intro.intro--layout-vertical {
    padding: 7rem 0 4rem;
  }
}
.intro.intro--layout-horizontal {
  padding: 11rem 0 8.25rem;
}
@media print, screen and (max-width: 64em) {
  .intro.intro--layout-horizontal {
    padding: 7rem 0 4rem;
  }
}
@media (max-height: 1024px) and (min-width: 1025px) {
  .intro.intro--layout-horizontal {
    padding: 11rem 0 4rem;
  }
}
.intro.intro--layout-vertical.intro--component {
  padding-bottom: 0;
  margin-bottom: 6rem;
}
@media print, screen and (max-width: 64em) {
  .intro.intro--layout-vertical.intro--component {
    padding-bottom: 0;
    margin-bottom: 3rem;
  }
}
@media print, screen and (max-width: 64em) {
  .intro.intro--layout-horizontal.intro--component {
    padding-bottom: 0;
    margin-bottom: 3rem;
  }
}
@media print, screen and (max-width: 64em) {
  .intro.intro--layout-horizontal.intro--component-wistia-no-image,
  .intro.intro--layout-vertical.intro--component-wistia-no-image {
    padding-bottom: 4rem;
  }
}
.intro:before {
  content: "";
  position: absolute;
  z-index: -1;
  left: 1.25rem;
  top: 1.25rem;
  width: calc(100% - 40px);
  height: calc(100% - 40px);
  border-radius: 1.25rem;
}
@media print, screen and (max-width: 37.5em) {
  .intro:before {
    left: 0.625rem;
    top: 0.625rem;
    width: calc(100% - 20px);
    height: calc(100% - 20px);
  }
}
.intro.intro--background-solid-grey:before {
  background-color: #fafafb;
}
.intro.intro--background-gradient-grey-white:before {
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(#fafafb),
    to(#fff)
  );
  background: linear-gradient(180deg, #fafafb 0, #fff 100%);
}
.intro--layout-horizontal .intro__container {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-horizontal .intro__container {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-align: normal;
    -webkit-align-items: normal;
    -ms-flex-align: normal;
    align-items: normal;
    text-align: center;
  }
}
.intro--layout-vertical .intro__content {
  text-align: center;
  margin: 0 auto;
  max-width: 46.25rem;
}
.intro--layout-horizontal .intro__content {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-horizontal .intro__content {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding-right: 0;
  }
}
.intro__content > :first-child {
  margin-top: 0;
}
.intro__content > :last-child {
  margin-bottom: 0;
}
.intro__heading {
  font-size: 0.75rem;
  letter-spacing: 0.0625rem;
  margin-bottom: 1rem;
  line-height: 1.5;
  font-weight: 700;
  color: #838c96;
  text-transform: uppercase;
  display: block;
}
.intro__title {
  margin-bottom: 1.5rem;
  font-size: 3rem;
  line-height: 1.1;
  display: block;
}
@media print, screen and (max-width: 80em) {
  .intro__title {
    font-size: 2.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .intro__title {
    font-size: 2rem;
  }
}
.intro__title--font-size-36 {
  font-size: 2.25rem;
}
@media print, screen and (max-width: 64em) {
  .intro__title--font-size-36 {
    font-size: 2rem;
  }
}
.intro__text {
  letter-spacing: 0;
  margin-bottom: 1rem;
  font-size: 1.25rem;
  line-height: 1.3;
  font-weight: 400;
  display: block;
}
@media print, screen and (max-width: 80em) {
  .intro__text {
    font-size: 1.125rem;
  }
}
.intro__text a {
  font-weight: 400;
  color: #0079f2;
}
.intro__text a:hover {
  text-decoration: underline;
}
.intro__text ul {
  margin: 0;
  list-style: none;
}
.intro__text ul li {
  margin-top: 0.25rem;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .intro__text ul li {
    display: inline-block;
  }
}
.intro__text ul li:first-child {
  margin-bottom: 0;
}
.intro__text ul li:first-child {
  margin-top: 0;
}
.intro__text ul li:before {
  content: "";
  display: inline-block;
  position: relative;
  top: -0.3125rem;
  margin-right: 0.5rem;
  width: 0.375rem;
  height: 0.375rem;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
  border-top: 0.125rem solid #000c2c;
  border-right: 0.125rem solid #000c2c;
}
.intro__microcopy {
  margin: 0;
  font-size: 0.8125rem;
  line-height: 1.5;
  color: #30363c;
  display: block;
}
.intro__actions {
  font-size: 0;
  margin-bottom: 1rem;
}
.intro__actions > * {
  margin: 1rem 1rem 0 0;
}
.intro__actions > :last-child {
  margin-right: 0;
}
.intro__actions-button {
  display: inline-block;
}
.intro__component {
  margin: 0;
  width: 100%;
  position: relative;
}
.intro--layout-vertical .intro__component {
  bottom: -4rem;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-vertical .intro__component {
    bottom: -3rem;
  }
}
.intro--layout-horizontal .intro__component {
  margin-left: 4rem;
  width: calc(50vw - 86px);
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 calc(50vw - 86px);
  -ms-flex: 0 0 calc(50vw - 86px);
  flex: 0 0 calc(50vw - 86px);
  padding: 0 0 2.5rem 2.5rem;
  overflow: hidden;
}
@media print, screen and (max-width: 80em) {
  .intro--layout-horizontal .intro__component {
    margin-left: 3rem;
    width: calc(50vw - 68px);
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 calc(50vw - 68px);
    -ms-flex: 0 0 calc(50vw - 68px);
    flex: 0 0 calc(50vw - 68px);
  }
}
@media print, screen and (max-width: 64em) {
  .intro--layout-horizontal .intro__component {
    margin: 0;
    padding: 0;
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 auto;
    -ms-flex: 1 1 auto;
    flex: 1 1 auto;
    width: auto;
    overflow: initial;
    bottom: -3rem;
  }
}
.intro__component-image {
  max-width: none;
  width: 100%;
  border-radius: 1rem;
  -webkit-box-shadow: 0 0.75rem 2rem rgba(0, 0, 0, 0.08);
  box-shadow: 0 0.75rem 2rem rgba(0, 0, 0, 0.08);
  overflow: hidden;
}
.intro--layout-horizontal .intro__component-image {
  width: 62.25rem;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-horizontal .intro__component-image {
    width: 100%;
  }
}
@media (max-height: 1024px) and (min-width: 1025px) {
  .intro--layout-horizontal .intro__component-image {
    width: 41.5rem;
  }
}
.intro__component-video {
  border-radius: 1rem;
  -webkit-box-shadow: 0 0.75rem 2rem rgba(0, 0, 0, 0.08);
  box-shadow: 0 0.75rem 2rem rgba(0, 0, 0, 0.08);
  overflow: hidden;
  position: relative;
}
.intro__component-video--overlay {
  cursor: pointer;
}
.intro--layout-vertical .intro__component-video {
  width: 100%;
  height: 0;
  padding-top: 56.25%;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-vertical .intro__component-video {
    width: 100%;
    height: auto;
    padding-top: 0;
  }
}
.intro--layout-horizontal .intro__component-video {
  width: 62.25rem;
  height: 35rem;
}
@media print, screen and (max-width: 64em) {
  .intro--layout-horizontal .intro__component-video {
    width: 100%;
    height: auto;
  }
}
.intro__component-play-overlay {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 10;
  position: absolute;
  pointer-events: none;
}
.intro--layout-horizontal .intro__component-play-overlay {
  width: calc(50vw - 116px);
  max-width: 62.25rem;
}
@media print, screen and (max-width: 64em) {
  .intro__component-play-overlay {
    display: none;
  }
}
.intro__component-play-overlay-button {
  left: 50%;
  top: 50%;
  width: 5rem;
  height: 5rem;
  border-radius: 100%;
  background-color: #fff;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: 0 0.25rem 0.75rem rgba(0, 0, 0, 0.08);
  box-shadow: 0 0.25rem 0.75rem rgba(0, 0, 0, 0.08);
  position: absolute;
}
.intro__component-play-overlay-button-icon {
  position: absolute;
  left: 2rem;
  top: 1.75rem;
  width: 1.125rem;
  height: 1.125rem;
  border-top-right-radius: 20%;
  background-color: #0079f2;
  text-align: left;
  -webkit-transform: rotate(30deg) skewX(-30deg) scale(1, 0.866);
  -ms-transform: rotate(30deg) skewX(-30deg) scale(1, 0.866);
  transform: rotate(30deg) skewX(-30deg) scale(1, 0.866);
  -webkit-transform-origin: 45% 75%;
  -ms-transform-origin: 45% 75%;
  transform-origin: 45% 75%;
}
.intro__component-play-overlay-button-icon:after,
.intro__component-play-overlay-button-icon:before {
  content: "";
  position: absolute;
  background-color: inherit;
  width: 100%;
  height: 100%;
  border-top-right-radius: 20%;
}
.intro__component-play-overlay-button-icon:before {
  -webkit-transform: rotate(-135deg) skewX(-45deg) scale(1.414, 0.707)
    translate(0, -50%);
  -ms-transform: rotate(-135deg) skewX(-45deg) scale(1.414, 0.707)
    translate(0, -50%);
  transform: rotate(-135deg) skewX(-45deg) scale(1.414, 0.707)
    translate(0, -50%);
}
.intro__component-play-overlay-button-icon:after {
  -webkit-transform: rotate(135deg) skewY(-45deg) scale(0.707, 1.414)
    translate(50%);
  -ms-transform: rotate(135deg) skewY(-45deg) scale(0.707, 1.414) translate(50%);
  transform: rotate(135deg) skewY(-45deg) scale(0.707, 1.414) translate(50%);
}
.intro__component-video-element {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .intro__component-video-element {
    display: none;
  }
}
.intro__component-video-image {
  display: none;
}
.intro__component-video-image[src=""] {
  visibility: hidden;
}
@media print, screen and (max-width: 64em) {
  .intro__component-video-image {
    display: block;
  }
}
.butter-bar {
  margin: 1.25rem;
  height: 4.125rem;
  padding: 0.9375rem;
  width: calc(100% - 40px);
  border-radius: 1.25rem;
  background-color: #fff2d0;
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  overflow: hidden;
}
@media print, screen and (max-width: 48em) {
  .butter-bar {
    height: 6.25rem;
    padding: 0.625rem 1.25rem;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    text-align: center;
  }
}
@media print, screen and (max-width: 37.5em) {
  .butter-bar {
    margin: 0.625rem;
    width: calc(100% - 20px);
    padding: 0.625rem 1.25rem;
  }
}
.butter-bar__text {
  font-size: 0.75rem;
  font-weight: 700;
}
.butter-bar__text > :first-child {
  margin-top: 0;
}
.butter-bar__text > :last-child {
  margin-bottom: 0;
}
@media print, screen and (max-width: 48em) {
  .butter-bar__text {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.butter-bar__button {
  margin: 0 0 0 0.9375rem;
  background-color: #ffc600;
  color: #30363c;
  white-space: nowrap;
}
.butter-bar__button:hover {
  color: #30363c;
  background-color: #ffd659;
}
.butter-bar__button:focus {
  color: #30363c;
  background-color: #ffc600;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.butter-bar__button:active {
  color: #30363c;
  background-color: #fab500;
  -webkit-box-shadow: none;
  box-shadow: none;
}
@media print, screen and (max-width: 48em) {
  .butter-bar__button {
    margin: 0.3125rem 0 0;
  }
}
.card {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border-radius: 0.625rem;
  color: #000c2c;
}
.card .card-image {
  min-height: 18.75rem;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: cover;
}
@media print, screen and (min-width: 48.0625em) {
  .card .card-image {
    min-height: 10.1875rem;
  }
}
.card .card-footer,
.card .card-section {
  padding: 1.25rem;
}
.card .card-section {
  padding-top: 1.875rem;
}
.card .card-section p:not(.quote):not(.author__info) {
  font-size: 0.875rem;
  line-height: 1.1875rem;
  opacity: 0.6;
  font-weight: 400;
}
.card .card-section .menu {
  opacity: 0.4;
}
.card .card-section .menu li:last-child {
  color: rgba(0, 12, 44, 0.5);
}
.card .card-footer {
  padding-bottom: 0.9375rem;
}
.card .card-footer .button {
  width: 100%;
}
.card .menu {
  font-weight: 700;
}
.card .menu li {
  margin-right: 1.25rem;
}
.card .author__info {
  margin-bottom: 0;
}
.card .author__name {
  font-size: 0.875rem;
  line-height: 16px;
  text-transform: none;
  opacity: 1;
}
.card.horizontal {
  width: 100%;
}
@media print, screen and (min-width: 48.0625em) {
  .card.horizontal {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-flow: row nowrap;
    -ms-flex-flow: row nowrap;
    flex-flow: row nowrap;
  }
  .card.horizontal .card-image {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .card.horizontal .card-section {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
}
a.card .headline {
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
}
a.card:hover {
  color: #000c2c;
}
a.card:hover .headline {
  color: #0569ff;
}
.card--article {
  border: 0;
  -webkit-box-shadow: 1px 7px 30px rgba(71, 80, 89, 0.09);
  box-shadow: 1px 7px 30px rgba(71, 80, 89, 0.09);
  margin-bottom: 1.875rem;
  -webkit-transition: -webkit-transform 0.25s ease,
    -webkit-box-shadow 0.25s ease;
  transition: -webkit-transform 0.25s ease, -webkit-box-shadow 0.25s ease;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
  transition: transform 0.25s ease, box-shadow 0.25s ease,
    -webkit-transform 0.25s ease, -webkit-box-shadow 0.25s ease;
}
.card--article:hover {
  -webkit-transform: translateY(-3px);
  -ms-transform: translateY(-3px);
  transform: translateY(-3px);
  -webkit-box-shadow: 1px 9px 35px rgba(71, 80, 89, 0.11);
  box-shadow: 1px 9px 35px rgba(71, 80, 89, 0.11);
}
.card--article .card-section .headline {
  margin-bottom: 0.3125rem;
}
.article__meta .card--article .card-section .author__name,
.card .card--article .card-section .author__name,
.card .card--article .card-section .menu,
.card--article .card-section .article__category,
.card--article .card-section .article__date,
.card--article .card-section .article__meta .author__name,
.card--article .card-section .card .author__name,
.card--article .card-section .card .menu,
.card--article .card-section .customer__category,
.card--article .card-section .customer__date,
.card--article .card-section .pre-headline {
  margin-bottom: 1.875rem;
  font-size: 0.625rem;
  opacity: 0.4;
}
.card--article.horizontal {
  -webkit-box-shadow: none;
  box-shadow: none;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 1.0625rem;
  color: #000c2c;
}
@media print, screen and (max-width: 74.99875em) {
  .card--article.horizontal {
    display: block;
  }
}
.card--article.horizontal .card-image {
  min-height: 12.5rem;
  background-size: cover;
  border-radius: 1.0625rem 1.0625rem 0 0;
}
@media screen and (min-width: 80em) {
  .card--article.horizontal .card-image {
    border-radius: 1.0625rem 0 0 1.0625rem;
  }
}
@media screen and (min-width: 75em) {
  .card--article.horizontal .card-image {
    width: 18.75rem;
  }
}
.card--article.horizontal .card-section {
  padding: 2.5rem 3.125rem 2.1875rem 1.875rem;
}
.card--article.horizontal .card-section p:not(.quote):not(.author__info) {
  line-height: 1.1875rem;
}
.card--article.horizontal .card-section .menu {
  margin-bottom: 0.5rem;
}
.card--article.horizontal .card-section .headline {
  margin-bottom: 0.9375rem;
}
.card--article.horizontal .card-section .author {
  margin-top: 1.25rem;
}
.card--resources {
  border: 0;
  overflow: visible;
}
.card--resources .card-image {
  background-color: #fafafb;
  position: relative;
}
.card--resources .card-image__image {
  z-index: 2;
  position: relative;
  border-radius: 1rem;
}
.card--resources .card-image__box {
  z-index: 1;
  height: 5.625rem;
  border-radius: 0.625rem;
  position: absolute;
}
.card--resources .card-image__box--color-red {
  background-color: #ff2638;
}
.card--resources .card-image__box--color-blue {
  background-color: #005ce6;
}
.card--resources .card-image__box--color-yellow {
  background-color: #ffc600;
}
.card--resources .card-image__box--position-vertical-top {
  top: -0.625rem;
}
.card--resources .card-image__box--position-vertical-bottom {
  bottom: -0.625rem;
}
.card--resources .card-image__box--position-horizontal-left {
  left: -0.625rem;
}
.card--resources .card-image__box--position-horizontal-left-center {
  left: 50%;
  -webkit-transform: translateX(-25%);
  -ms-transform: translateX(-25%);
  transform: translateX(-25%);
}
.card--resources .card-image__box--position-horizontal-center {
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
}
.card--resources .card-image__box--position-horizontal-right-center {
  right: 50%;
  -webkit-transform: translateX(75%);
  -ms-transform: translateX(75%);
  transform: translateX(75%);
}
.card--resources .card-image__box--position-horizontal-right {
  right: -0.625rem;
}
.card--resources .headline {
  margin-bottom: 1.25rem;
  font-size: 1.5rem;
  font-size: 24px;
  line-height: 33px;
  letter-spacing: -1.3616px;
  text-transform: capitalize;
  white-space: wrap;
}
.article__meta .card--resources .author__name,
.card .card--resources .author__name,
.card .card--resources .menu,
.card--resources .article__category,
.card--resources .article__date,
.card--resources .article__meta .author__name,
.card--resources .card .author__name,
.card--resources .card .menu,
.card--resources .customer__category,
.card--resources .customer__date,
.card--resources .pre-headline {
  line-height: 1.3;
  font-weight: 400;
  font-size: 1rem;
  text-transform: none;
}
.card--resources .card-section p,
.card--resources .card-section p:not(.quote):not(.author__info) {
  font-size: 1.125rem;
  line-height: 1.3;
  opacity: 1;
}
.card--pricing {
  padding: 2.25rem 2.5rem;
  border-radius: 1.0625rem;
  border: 1px solid rgba(0, 0, 0, 0.1);
  margin-bottom: 1.875rem;
}
@media screen and (min-width: 80em) {
  .card--pricing {
    padding: 2.75rem 3.625rem;
  }
}
@media print, screen and (max-width: 80em) {
  .card--pricing {
    padding: 2rem;
  }
}
.card--pricing .card-section {
  position: relative;
  padding: 0;
  margin-bottom: 1.25rem;
}
.card--pricing .card-footer .button {
  width: 100%;
}
.card--pricing .card-footer .button:last-child {
  margin-bottom: 0;
}
@media screen and (min-width: 80.0625em) {
  .card--pricing .card-footer.last {
    text-align: center;
  }
}
.article__meta .card--pricing .card-footer.last .author__name,
.card .card--pricing .card-footer.last .author__name,
.card .card--pricing .card-footer.last .menu,
.card--pricing .card-footer.last .article__category,
.card--pricing .card-footer.last .article__date,
.card--pricing .card-footer.last .article__meta .author__name,
.card--pricing .card-footer.last .card .author__name,
.card--pricing .card-footer.last .card .menu,
.card--pricing .card-footer.last .customer__category,
.card--pricing .card-footer.last .customer__date,
.card--pricing .card-footer.last .pre-headline,
.card--pricing .card-footer.last .price {
  display: none;
}
@media screen and (min-width: 80.0625em) {
  .article__meta .card--pricing .card-footer.last .author__name,
  .card .card--pricing .card-footer.last .author__name,
  .card .card--pricing .card-footer.last .menu,
  .card--pricing .card-footer.last .article__category,
  .card--pricing .card-footer.last .article__date,
  .card--pricing .card-footer.last .article__meta .author__name,
  .card--pricing .card-footer.last .card .author__name,
  .card--pricing .card-footer.last .card .menu,
  .card--pricing .card-footer.last .customer__category,
  .card--pricing .card-footer.last .customer__date,
  .card--pricing .card-footer.last .pre-headline,
  .card--pricing .card-footer.last .price {
    display: block;
    text-align: center;
  }
}
.card--pricing .headline,
.card--pricing .price {
  margin-bottom: 0.3125rem;
}
.card--pricing .price {
  position: relative;
}
.card--pricing .price span {
  opacity: 0;
  -webkit-transition: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
}
.card--pricing .price span[data-pricing-billing-price="monthly"] {
  left: 0;
  top: 0;
  position: absolute;
  -webkit-transform: translateY(-100%);
  -ms-transform: translateY(-100%);
  transform: translateY(-100%);
}
.card--pricing .price span.is-active,
.card--pricing .price span[data-pricing-billing-price="monthly"].is-active {
  opacity: 1;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
}
.article__meta .card--pricing .author__name,
.card .card--pricing .author__name,
.card .card--pricing .menu,
.card--pricing .article__category,
.card--pricing .article__date,
.card--pricing .article__meta .author__name,
.card--pricing .card .author__name,
.card--pricing .card .menu,
.card--pricing .customer__category,
.card--pricing .customer__date,
.card--pricing .list-styled,
.card--pricing .list-unstyled,
.card--pricing .pre-headline {
  margin-bottom: 2.1875rem;
}
.card--pricing .list-unstyled {
  font-size: 0.875rem;
  line-height: 1.1875rem;
}
.card--pricing .list-styled {
  font-size: 0.875rem;
  line-height: 1.1875rem;
  color: rgba(0, 12, 44, 0.4);
}
.card--pricing .card-header {
  position: relative;
}
.article__meta .card--pricing .card-header .last.author__name,
.card .card--pricing .card-header .last.author__name,
.card .card--pricing .card-header .last.menu,
.card--pricing .card-header .article__meta .last.author__name,
.card--pricing .card-header .card .last.author__name,
.card--pricing .card-header .card .last.menu,
.card--pricing .card-header .last.article__category,
.card--pricing .card-header .last.article__date,
.card--pricing .card-header .last.customer__category,
.card--pricing .card-header .last.customer__date,
.card--pricing .card-header .pre-headline.last,
.card--pricing .card-header .price.last {
  display: block;
}
@media screen and (min-width: 80.0625em) {
  .article__meta .card--pricing .card-header .last.author__name,
  .card .card--pricing .card-header .last.author__name,
  .card .card--pricing .card-header .last.menu,
  .card--pricing .card-header .article__meta .last.author__name,
  .card--pricing .card-header .card .last.author__name,
  .card--pricing .card-header .card .last.menu,
  .card--pricing .card-header .last.article__category,
  .card--pricing .card-header .last.article__date,
  .card--pricing .card-header .last.customer__category,
  .card--pricing .card-header .last.customer__date,
  .card--pricing .card-header .pre-headline.last,
  .card--pricing .card-header .price.last {
    display: none;
  }
}
.card--pricing .badge {
  position: absolute;
  right: 0;
  top: 0.125rem;
}
@media print, screen and (min-width: 64.0625em) {
  .card--pricing.large-auto {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-flow: row wrap;
    -ms-flex-flow: row wrap;
    flex-flow: row wrap;
  }
  .card--pricing.large-auto > div {
    -webkit-box-flex: 1;
    -webkit-flex: 1 0 auto;
    -ms-flex: 1 0 auto;
    flex: 1 0 auto;
    margin-right: 1.875rem;
    margin-bottom: 0;
  }
  .card--pricing.large-auto > div:last-child {
    margin-right: 0;
  }
  .card--pricing.large-auto .card-section {
    max-width: 29.375rem;
  }
  .card--pricing.large-auto .list-styled {
    margin-bottom: 0;
    -webkit-column-count: 2;
    -moz-column-count: 2;
    column-count: 2;
  }
  .card--pricing.large-auto .button {
    max-width: 10rem;
  }
}
@media screen and (min-width: 80.0625em) {
  .card--pricing.large-auto .button {
    max-width: 12.5rem;
  }
}
.card--mainstory {
  overflow: visible;
  border: 1px solid rgba(0, 0, 0, 0.1);
  width: 100%;
  height: auto;
  border-radius: 1.0625rem;
  -webkit-transition: -webkit-transform 0.25s ease,
    -webkit-box-shadow 0.25s ease;
  transition: -webkit-transform 0.25s ease, -webkit-box-shadow 0.25s ease;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
  transition: transform 0.25s ease, box-shadow 0.25s ease,
    -webkit-transform 0.25s ease, -webkit-box-shadow 0.25s ease;
}
.card--mainstory:not(.news):hover {
  -webkit-transform: translateY(-3px);
  -ms-transform: translateY(-3px);
  transform: translateY(-3px);
  -webkit-box-shadow: 1px 9px 35px rgba(71, 80, 89, 0.11);
  box-shadow: 1px 9px 35px rgba(71, 80, 89, 0.11);
}
.card--mainstory:before {
  background-color: #ffc600;
  height: 4.3125rem;
  border-radius: 20px 10px 10px 10px;
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory:before {
    width: 73%;
  }
}
.card--mainstory:after {
  background-color: #ff2638;
  right: -0.625rem;
  height: 6.25rem;
  width: 10.3125rem;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory:after {
    left: 12%;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory:after {
    top: 6.25rem;
  }
}
.card--mainstory > div {
  position: relative;
  z-index: 2;
  background-color: #fff;
}
.card--mainstory .card-image {
  overflow: hidden;
  border-radius: 0.625rem 0.625rem 0 0;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory .card-image {
    height: auto;
    width: 58%;
    border-radius: 1.0625rem 0 0 1.0625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .card--mainstory .card-image {
    width: 55%;
  }
}
.card--mainstory .card-section {
  border-radius: 0 0 0.625rem 0.625rem;
  padding: 2.5rem;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory .card-section {
    width: 33%;
    border-radius: 0 1.0625rem 1.0625rem 0;
    padding: 6.25rem 3.75rem 5rem 2.5rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .card--mainstory .card-section {
    width: 35%;
    border-radius: 0 1.0625rem 1.0625rem 0;
    padding: 6.25rem 3.75rem 5rem 4.375rem;
  }
}
.card--mainstory .card-section .quote {
  margin-top: 1.875rem;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory .card-section .quote {
    margin-bottom: 3.375rem;
  }
}
.card--mainstory .card-section .author {
  margin-bottom: 1.875rem;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory .card-section .author {
    margin-bottom: 3.1875rem;
  }
}
.card--mainstory .card-section .headline {
  margin-bottom: 0;
}
.article__meta .card--mainstory .card-section .author__name,
.card .card--mainstory .card-section .author__name,
.card .card--mainstory .card-section .menu,
.card--mainstory .card-section .article__category,
.card--mainstory .card-section .article__date,
.card--mainstory .card-section .article__meta .author__name,
.card--mainstory .card-section .card .author__name,
.card--mainstory .card-section .card .menu,
.card--mainstory .card-section .customer__category,
.card--mainstory .card-section .customer__date,
.card--mainstory .card-section .pre-headline {
  opacity: 0.4;
  font-size: 0.625rem;
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory .card-section .button {
    width: 100%;
  }
}
.card--mainstory.news {
  margin-bottom: 2.5rem;
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory.news {
    margin-bottom: 0;
    border: 0;
    background-color: transparent;
  }
}
.card--mainstory.news .card-image {
  padding: 2.1875rem;
  position: relative;
  font-weight: 400;
  display: block;
  z-index: 2;
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory.news .card-image {
    border-radius: 1.0625rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory.news .card-image {
    width: 50%;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .card--mainstory.news .card-image {
    width: 58%;
  }
}
.card--mainstory.news .card-image .menu {
  opacity: 1;
  color: #fff;
  letter-spacing: 0.05em;
}
.card--mainstory.news .card-image p {
  font-size: 0.875rem;
  line-height: 1.1875rem;
}
.card--mainstory.news .card-image .content {
  color: #fff;
  position: relative;
  z-index: 3;
  margin-top: 6.25rem;
}
@media print, screen and (min-width: 48.0625em) {
  .card--mainstory.news .card-image .content {
    position: absolute;
    bottom: 2.1875rem;
    left: 2.1875rem;
    right: 7vw;
  }
}
.card--mainstory.news .section__title {
  margin-bottom: 0.9375rem;
}
.card--mainstory.news .card-section {
  padding-top: 2.3125rem;
  padding-bottom: 2.3125rem;
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory.news .card-section {
    background-color: transparent;
    padding: 5rem 0 0;
  }
}
.card--mainstory.news .card-section__post {
  margin-bottom: 1.375rem;
  display: block;
  color: #000c2c;
}
.card--mainstory.news .card-section__post:hover {
  color: #0569ff;
}
.card--mainstory.news .card-section__post:last-child {
  margin-bottom: 0.3125rem;
}
.select {
  max-width: 13.75rem;
  min-width: 13.75rem;
  height: 2.5rem;
  border-radius: 0.375rem;
  padding: 0 2.5rem 0 1.25rem;
  font-size: 1rem;
  font-weight: 700;
  background-color: #fff;
  border: 0.0625rem solid #e1e6eb;
  text-align: left;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  display: inline-block;
  position: relative;
  background-image: url(/wp-content/themes/productboard/public//img/icons/icon-chevron-down.svg);
  background-repeat: no-repeat;
  background-position: 95% 50%;
}
.select:after {
  content: "";
  width: 10px;
  height: 10px;
  left: 50%;
  top: 50%;
  background-color: red;
  position: absolute;
}
.select:focus,
.select:hover {
  background-color: #fff;
  border: 0.0625rem solid #879099;
}
@media print, screen and (max-width: 37.5em) {
  .select {
    font-size: 0.875rem;
    padding: 0 1.25rem 0 0.625rem;
  }
}
.select--events,
.select--jobs {
  margin: 0.3125rem;
  line-height: 1.5;
}
.badge {
  border-radius: 2.25rem;
  padding: 0.5rem;
  text-transform: uppercase;
  color: #0569ff;
  background: #e7f1ff;
  font-size: 0.4375rem;
  line-height: 7px;
  letter-spacing: 0.013em;
}
.badge.plain {
  padding: 0;
  background: 0 0;
  color: rgba(0, 12, 44, 0.4);
}
.switch {
  color: rgba(0, 12, 44, 0.4);
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  margin-bottom: 6.25rem;
}
.switch .switch-paddle {
  border: 0.56694px solid rgba(0, 0, 0, 0.1);
}
.switch .switch-paddle:after {
  top: 3px;
}
.switch .switch-active,
.switch .switch-inactive {
  min-width: 6.25rem;
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
}
.switch .switch-inactive {
  right: 105%;
  color: #0569ff;
}
.switch .switch-active {
  left: 105%;
  display: block;
}
.switch .badge {
  position: absolute;
  left: 0;
  right: 0;
  top: 100%;
}
input:checked + label > .switch-active {
  color: #0569ff;
}
input:checked + label > .switch-inactive {
  color: rgba(0, 12, 44, 0.4);
  display: block;
}
.table {
  width: 100%;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 64em) {
  .table {
    width: 100vw;
    left: 50%;
    -webkit-transform: translateX(-50%);
    -ms-transform: translateX(-50%);
    transform: translateX(-50%);
    position: relative;
  }
}
@media print, screen and (max-width: 64em) {
  .table:after,
  .table:before {
    content: "";
    left: 0;
    top: 0;
    width: 2.5rem;
    height: 100%;
    position: absolute;
    background: -webkit-gradient(
      linear,
      right top,
      left top,
      from(rgba(255, 255, 255, 0)),
      to(#fff)
    );
    background: linear-gradient(270deg, rgba(255, 255, 255, 0) 0, #fff 100%);
  }
}
.table:after {
  left: auto;
  right: 0;
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.table__wrapper {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 64em) {
  .table__wrapper {
    overflow: auto;
    padding: 0 2.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .table__wrapper:after {
    content: "";
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 2.5rem;
    -ms-flex: 0 0 2.5rem;
    flex: 0 0 2.5rem;
    height: 200px;
    position: relative;
  }
}
.table__table {
  width: 100%;
  min-width: 40rem;
  border-collapse: collapse;
}
.table__cell {
  padding: 0.625rem;
  font-size: 1.125rem;
}
@media print, screen and (max-width: 64em) {
  .table__cell {
    font-size: 0.875rem;
  }
}
.table__cell:first-child {
  padding-left: 0;
}
.table__cell:last-child {
  padding-right: 0;
}
.table__body .table__row:first-child .table__cell {
  padding-top: 1.875rem;
}
.table__body .table__row:last-child .table__cell {
  padding-bottom: 1.875rem;
}
.table__cell--heading {
  padding-top: 2.8125rem;
  padding-bottom: 1.25rem;
  font-size: 1.5rem;
  font-weight: 700;
}
@media print, screen and (max-width: 64em) {
  .table__cell--heading {
    font-size: 1.125rem;
  }
}
.table__cell--header {
  font-weight: 700;
  font-size: 1.125rem;
  padding-top: 1.875rem;
  padding-bottom: 1.875rem;
  border-bottom: 2px solid rgba(0, 0, 0, 0.1);
  text-align: left;
}
@media print, screen and (max-width: 64em) {
  .table__cell--header {
    font-size: 0.875rem;
  }
}
.table__cell--header.table__cell--heading {
  padding-top: 1.875rem;
  padding-bottom: 1.875rem;
  font-size: 2.5rem;
  line-height: 1.2;
}
@media print, screen and (max-width: 64em) {
  .table__cell--header.table__cell--heading {
    font-size: 1.5rem;
  }
}
.table__cell--align-center {
  text-align: center;
}
.table__cell--align-right {
  text-align: right;
}
.table__cell-image {
  width: 2rem;
  height: 2rem;
}
.table__cell-image + .table__cell-text {
  margin-top: 0.3125rem;
}
[type="color"],
[type="date"],
[type="datetime-local"],
[type="datetime"],
[type="email"],
[type="month"],
[type="number"],
[type="password"],
[type="search"],
[type="tel"],
[type="text"],
[type="time"],
[type="url"],
[type="week"],
textarea {
  border: 0;
  height: 2.875rem;
  border-bottom: 1px solid #000c2c;
  font-weight: 700;
  -webkit-transition: border-color 0.25s ease;
  transition: border-color 0.25s ease;
}
[type="color"]:focus,
[type="date"]:focus,
[type="datetime-local"]:focus,
[type="datetime"]:focus,
[type="email"]:focus,
[type="month"]:focus,
[type="number"]:focus,
[type="password"]:focus,
[type="search"]:focus,
[type="tel"]:focus,
[type="text"]:focus,
[type="time"]:focus,
[type="url"]:focus,
[type="week"]:focus,
textarea:focus {
  border: 0;
  border-bottom: 1px solid #000c2c;
  -webkit-box-shadow: none;
  box-shadow: none;
  border-color: #0569ff;
}
.form-secondary [type="color"],
.form-secondary [type="date"],
.form-secondary [type="datetime-local"],
.form-secondary [type="datetime"],
.form-secondary [type="email"],
.form-secondary [type="month"],
.form-secondary [type="number"],
.form-secondary [type="password"],
.form-secondary [type="search"],
.form-secondary [type="tel"],
.form-secondary [type="text"],
.form-secondary [type="time"],
.form-secondary [type="url"],
.form-secondary [type="week"],
.form-secondary textarea {
  background-color: #fff;
  border: 1px solid rgba(0, 0, 0, 0.1);
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 0.9375rem;
  font-size: 1.125rem;
  line-height: 1.3125rem;
  padding: 1.25rem 1.25rem 1.25rem 3.0625rem;
  height: 3.6875rem;
}
.form-secondary [type="color"]::-webkit-input-placeholder,
.form-secondary [type="date"]::-webkit-input-placeholder,
.form-secondary [type="datetime-local"]::-webkit-input-placeholder,
.form-secondary [type="datetime"]::-webkit-input-placeholder,
.form-secondary [type="email"]::-webkit-input-placeholder,
.form-secondary [type="month"]::-webkit-input-placeholder,
.form-secondary [type="number"]::-webkit-input-placeholder,
.form-secondary [type="password"]::-webkit-input-placeholder,
.form-secondary [type="search"]::-webkit-input-placeholder,
.form-secondary [type="tel"]::-webkit-input-placeholder,
.form-secondary [type="text"]::-webkit-input-placeholder,
.form-secondary [type="time"]::-webkit-input-placeholder,
.form-secondary [type="url"]::-webkit-input-placeholder,
.form-secondary [type="week"]::-webkit-input-placeholder,
.form-secondary textarea::-webkit-input-placeholder {
  opacity: 0.4;
}
.form-secondary [type="color"]::-moz-placeholder,
.form-secondary [type="date"]::-moz-placeholder,
.form-secondary [type="datetime-local"]::-moz-placeholder,
.form-secondary [type="datetime"]::-moz-placeholder,
.form-secondary [type="email"]::-moz-placeholder,
.form-secondary [type="month"]::-moz-placeholder,
.form-secondary [type="number"]::-moz-placeholder,
.form-secondary [type="password"]::-moz-placeholder,
.form-secondary [type="search"]::-moz-placeholder,
.form-secondary [type="tel"]::-moz-placeholder,
.form-secondary [type="text"]::-moz-placeholder,
.form-secondary [type="time"]::-moz-placeholder,
.form-secondary [type="url"]::-moz-placeholder,
.form-secondary [type="week"]::-moz-placeholder,
.form-secondary textarea::-moz-placeholder {
  opacity: 0.4;
}
.form-secondary [type="color"]:-ms-input-placeholder,
.form-secondary [type="date"]:-ms-input-placeholder,
.form-secondary [type="datetime-local"]:-ms-input-placeholder,
.form-secondary [type="datetime"]:-ms-input-placeholder,
.form-secondary [type="email"]:-ms-input-placeholder,
.form-secondary [type="month"]:-ms-input-placeholder,
.form-secondary [type="number"]:-ms-input-placeholder,
.form-secondary [type="password"]:-ms-input-placeholder,
.form-secondary [type="search"]:-ms-input-placeholder,
.form-secondary [type="tel"]:-ms-input-placeholder,
.form-secondary [type="text"]:-ms-input-placeholder,
.form-secondary [type="time"]:-ms-input-placeholder,
.form-secondary [type="url"]:-ms-input-placeholder,
.form-secondary [type="week"]:-ms-input-placeholder,
.form-secondary textarea:-ms-input-placeholder {
  opacity: 0.4;
}
.form-secondary [type="color"]::-ms-input-placeholder,
.form-secondary [type="date"]::-ms-input-placeholder,
.form-secondary [type="datetime-local"]::-ms-input-placeholder,
.form-secondary [type="datetime"]::-ms-input-placeholder,
.form-secondary [type="email"]::-ms-input-placeholder,
.form-secondary [type="month"]::-ms-input-placeholder,
.form-secondary [type="number"]::-ms-input-placeholder,
.form-secondary [type="password"]::-ms-input-placeholder,
.form-secondary [type="search"]::-ms-input-placeholder,
.form-secondary [type="tel"]::-ms-input-placeholder,
.form-secondary [type="text"]::-ms-input-placeholder,
.form-secondary [type="time"]::-ms-input-placeholder,
.form-secondary [type="url"]::-ms-input-placeholder,
.form-secondary [type="week"]::-ms-input-placeholder,
.form-secondary textarea::-ms-input-placeholder {
  opacity: 0.4;
}
.form-secondary [type="color"]::placeholder,
.form-secondary [type="date"]::placeholder,
.form-secondary [type="datetime-local"]::placeholder,
.form-secondary [type="datetime"]::placeholder,
.form-secondary [type="email"]::placeholder,
.form-secondary [type="month"]::placeholder,
.form-secondary [type="number"]::placeholder,
.form-secondary [type="password"]::placeholder,
.form-secondary [type="search"]::placeholder,
.form-secondary [type="tel"]::placeholder,
.form-secondary [type="text"]::placeholder,
.form-secondary [type="time"]::placeholder,
.form-secondary [type="url"]::placeholder,
.form-secondary [type="week"]::placeholder,
.form-secondary textarea::placeholder {
  opacity: 0.4;
}
label {
  font-size: 0.875rem;
  line-height: 1.1875rem;
}
.checkbox {
  cursor: pointer;
  position: relative;
}
.checkbox > span {
  padding-left: 35px;
  display: block;
}
.checkbox > input {
  height: 20px;
  width: 20px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  border-radius: 4px;
  outline: 0;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  background-color: #ffc600;
  cursor: pointer;
  position: absolute;
  left: 0;
}
.checkbox > input:checked {
  border: 1px solid #ffc600;
  background-color: #ffc600;
}
.checkbox > input:checked + span::before {
  content: "";
  display: block;
  text-align: center;
  color: #ffc600;
  position: absolute;
  left: 0;
  top: 0;
  height: 20px;
  width: 20px;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTInIGhlaWdodD0nOCcgdmlld0JveD0nMCAwIDEyIDgnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+PHBhdGggZmlsbC1ydWxlPSdldmVub2RkJyBjbGlwLXJ1bGU9J2V2ZW5vZGQnIGQ9J00xMS4yNTAxIDEuNDMzNTRMOS45OTA4MSAwLjI0ODUzNUw0LjUzMDgxIDUuMzgyMjlMMi4wMTAwNiAzLjAxMzA0TDAuNzUwMDYxIDQuMTk3MjlMNC41MzAwNiA3Ljc1MTUzTDUuNzkwODEgNi41NjY1M0wxMS4yNTAxIDEuNDMzNTRaJyBmaWxsPScjMDAwQzJDJy8+PC9zdmc+Cg==);
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto;
}
.site-search {
  margin-bottom: 3.75rem;
  position: relative;
}
@media print, screen and (min-width: 64.0625em) {
  .site-search {
    margin-bottom: 4.6875rem;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .site-search {
    margin-top: 3.75rem;
  }
}
.site-search [type="search"] {
  width: 100%;
  margin-bottom: 0;
}
@media print, screen and (max-width: 48.06125em) {
  .site-search [type="search"] {
    padding-left: 2.5rem;
  }
}
.site-search__input-image {
  position: absolute;
  top: 1.1875rem;
  left: 1.1875rem;
}
@media print, screen and (max-width: 48.06125em) {
  .site-search__input-image {
    left: 0.625rem;
  }
}
@media screen and (min-width: 64em) {
  .site-search__input-image {
    left: 0.6875rem;
  }
}
.site-search__menu {
  position: absolute;
  z-index: 3;
  top: 0;
  width: 3.6875rem;
  height: 3.6875rem;
  display: none;
  outline: 0;
}
.site-search__menu:after {
  content: "";
  position: absolute;
  height: 1.1875rem;
  width: 1px;
  right: 8px;
  border-right: 1px solid rgba(0, 0, 0, 0.1);
}
@media print, screen and (max-width: 48.06125em) {
  .site-search__menu {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.site-search__menu .icon-close {
  display: none;
}
.site-search__menu .icon-open {
  display: block;
}
.site-search__menu.hover .icon-close {
  display: block;
}
.site-search__menu.hover .icon-open {
  display: none;
}
.site-search .dropdown-pane {
  border-radius: 0 0 0.9375rem 0.9375rem;
  border-top: 0;
  margin-top: -0.9375rem;
}
.dropdown-pane {
  background-color: #fff;
  border: 1px solid rgba(0, 0, 0, 0.1);
  padding: 1.125rem;
  border-radius: 0.9375rem;
  width: 100%;
}
.author {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  text-align: left;
  width: 100%;
  margin-bottom: 1.25rem;
}
.author--blockquote {
  margin: 2.5rem 0 0;
}
.author__avatar {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.8125rem;
  -ms-flex: 0 0 1.8125rem;
  flex: 0 0 1.8125rem;
  width: 1.8125rem;
  height: 1.8125rem;
  border-radius: 50%;
  margin-right: 0.9375rem;
  min-height: 0;
  min-width: 0;
  display: block;
}
.author--blockquote .author__avatar {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 2.5rem;
  -ms-flex: 0 0 2.5rem;
  flex: 0 0 2.5rem;
  height: 2.5rem;
}
.author__name {
  font-size: 0.875rem;
  margin-bottom: 0.3125rem;
  color: #000c2c;
}
.author--blockquote .author__name {
  font-size: 1.125rem;
}
.author__meta {
  font-weight: 700;
  font-size: 0.625rem;
}
.author--blockquote .author__meta {
  font-size: 0.875rem;
  text-transform: uppercase;
}
.pagination {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  list-style: none;
  font-size: 1.125rem;
  line-height: 1.3125rem;
  font-weight: 700;
}
.pagination li {
  width: 1.875rem;
  height: 1.875rem;
  padding: 0.3125rem;
  opacity: 0.2;
  -webkit-transition: opacity 0.25s ease;
  transition: opacity 0.25s ease;
  text-align: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.pagination li:hover {
  opacity: 1;
}
.pagination li.current {
  color: #0569ff;
  opacity: 1;
  cursor: default;
}
.pagination li a {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  color: #000c2c;
  width: 100%;
  height: 100%;
}
.pagination li svg {
  width: 0.375rem;
  height: 0.625rem;
}
.menu--taxonomy {
  font-size: 0.875rem;
  line-height: 1rem;
  margin-left: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .menu--taxonomy {
    margin-top: 0.625rem;
    font-size: 1.125rem;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .menu--taxonomy.menu {
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-flow: row wrap;
    -ms-flex-flow: row wrap;
    flex-flow: row wrap;
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
  .menu--taxonomy.menu > li {
    width: 50%;
    padding-right: 0.625rem;
  }
  .menu--taxonomy.menu > li:first-child {
    width: 100%;
  }
}
.menu--taxonomy li > ul {
  list-style: none;
  margin-left: 0;
}
.menu--taxonomy li a,
.menu--taxonomy li span {
  color: #7e8494;
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
  font-weight: 400;
  padding: 0.625rem 0.9375rem 0.625rem 0;
  display: block;
}
.menu--taxonomy li a.menu__title,
.menu--taxonomy li span.menu__title {
  color: #7e8494;
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
  font-weight: 700;
  padding: 0.625rem 0.9375rem 0.625rem 0;
  display: block;
}
.menu--taxonomy li a:hover,
.menu--taxonomy li.active a {
  color: #0569ff;
  background: 0 0;
}
.menu--taxonomy > li {
  margin-bottom: 0.625rem;
}
@media print, screen and (min-width: 48.0625em) {
  .menu--taxonomy > li {
    margin-bottom: 2.1875rem;
  }
}
.menu--taxonomy > li a.active {
  color: #0569ff;
  font-weight: 700;
}
.menu--social.small a:hover svg {
  fill: #0569ff;
}
.menu--social.small a svg {
  fill: #c4c8cb;
  -webkit-transition: fill 0.25s ease;
  transition: fill 0.25s ease;
}
.menu--glossary {
  left: 0;
  top: 6.875rem;
  padding-right: 1.25rem;
  max-height: calc(100vh - 110px);
  overflow: auto;
  position: -webkit-sticky;
  position: sticky;
}
.menu--glossary li > ul {
  list-style: none;
  margin-left: 0;
}
.menu--glossary li a,
.menu--glossary li span {
  color: #11171f;
  -webkit-transition: color 0.25s ease;
  transition: color 0.25s ease;
  font-weight: 400;
  padding: 0 0.9375rem 0 0;
  margin-bottom: 1.875rem;
  font-size: 1.125rem;
  line-height: 1.6;
  display: block;
}
@media print, screen and (max-width: 64em) {
  .menu--glossary li a,
  .menu--glossary li span {
    font-size: 1rem;
  }
}
.menu--glossary li a:hover,
.menu--glossary li.active a {
  color: #0569ff;
  background: 0 0;
}
.section {
  position: relative;
  padding: 7rem 0;
}
@media (max-height: 1024px) and (min-width: 1025px), (max-width: 1024px) {
  .section {
    padding: 4rem 0;
  }
}
.section.background-box {
  padding: 9.5rem 0;
}
@media (max-height: 1024px) and (min-width: 1025px), (max-width: 1024px) {
  .section.background-box {
    padding: 6.5rem 0;
  }
}
.section--overflow-hidden {
  overflow: hidden;
}
.section--site-footer {
  padding: 6.25rem 0;
}
@media print, screen and (max-width: 48em) {
  .section--site-footer {
    padding: 4.375rem 0;
  }
}
.section--offset-top {
  padding-top: 0;
  margin-top: -6.25rem;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .section--offset-top {
    margin-top: -5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section--offset-top {
    margin-top: -4.375rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .section__title {
    margin-bottom: 3.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section__title .shrink {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
    width: 100%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section__title .menu--social {
    margin-top: 0.625rem;
  }
}
.section__title .menu--social li:first-child a {
  padding-left: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .section__footer {
    margin-top: 1.875rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section--newsletter .cell.auto {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
  .section--newsletter .cell.shrink {
    width: calc(50% - 1.875rem);
  }
}
@media print, screen and (max-width: 48.06125em) {
  .section--newsletter .menu {
    margin-bottom: 2.5rem;
  }
}
.section--newsletter .menu li a {
  padding-left: 0;
  font-size: 0.875rem;
  color: rgba(0, 12, 44, 0.4);
}
.section--newsletter .menu li a:hover {
  color: #0569ff;
}
.section--newsletter .menu li.active a {
  color: #0569ff;
  background: 0 0;
}
@media print, screen and (min-width: 48.0625em) {
  .section--customers {
    padding: 8.75rem 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .section--customers {
    padding: 11.25rem 0;
  }
}
.section--article {
  padding-top: 1.875rem;
}
@media print, screen and (min-width: 48.0625em) {
  .section--article {
    padding-top: 4.75rem;
  }
}
.section--background-geometric:before {
  content: "";
  z-index: -1;
  left: 0;
  top: 0;
  width: 100%;
  height: 74.75rem;
  background-size: cover;
  background-position: center top;
  background-image: url(/wp-content/themes/productboard/public//img/other/background_geometric_01.png);
  position: absolute;
}
.section--product-content {
  overflow: hidden;
  padding: 7.8125rem 0;
}
@media (max-height: 1024px) and (min-width: 1025px), (max-width: 1024px) {
  .section--product-content {
    padding: 4rem 0;
  }
}
.section--summit {
  padding: 12.5rem 0;
}
@media print, screen and (max-width: 80em) {
  .section--summit {
    padding: 9.375rem 0;
  }
}
@media print, screen and (max-width: 64em) {
  .section--summit {
    padding: 6.25rem 0;
  }
}
.section--summit-first {
  padding-top: 6.25rem;
}
.section--home-roadmaps {
  padding-bottom: 0;
}
.section__header {
  margin-bottom: 2rem;
}
.section__header--center {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  max-width: 46.25rem;
}
@media print, screen and (max-width: 48em) {
  .section__header--center {
    max-width: 100%;
  }
}
.section__header--margin-top-60 {
  margin-top: 3.75rem;
}
@media print, screen and (max-width: 64em) {
  .section__header--margin-top-60 {
    margin-top: 1.875rem;
  }
}
.section__header--margin-bottom-60 {
  margin-bottom: 3.75rem;
}
@media print, screen and (max-width: 64em) {
  .section__header--margin-bottom-60 {
    margin-bottom: 1.875rem;
  }
}
.section__header > :first-child {
  margin-top: 0;
}
.section__header > :last-child {
  margin-bottom: 0;
}
.section__header-heading {
  margin-bottom: 0.5rem;
  font-size: 0.875rem;
  letter-spacing: 0.04688rem;
  font-weight: 700;
  text-transform: uppercase;
  color: #7e8494;
}
.section__header-title {
  margin: 0 0 1rem;
  font-size: 2.25rem;
  line-height: 1.2;
}
@media print, screen and (max-width: 80em) {
  .section__header-title {
    font-size: 2rem;
  }
}
h3.section__header-title {
  font-size: 1.5rem;
}
h5.section__header-title {
  color: #000c2c;
  font-size: 1.125rem;
  font-weight: 700;
}
.section__header-subtitle {
  margin: 0 0 1.875rem;
  font-size: 1.5rem;
  line-height: 1.2;
}
@media print, screen and (max-width: 80em) {
  .section__header-subtitle {
    font-size: 1.375rem;
  }
}
.section__header-text {
  margin: 0 0 1.875rem;
  font-size: 1.125rem;
  line-height: 1.38;
}
.section__header-buttons {
  width: 100%;
  margin-top: 1.875rem;
}
.section__header-icon {
  margin-bottom: 1.5rem;
}
.avatar {
  padding: 2.5rem 1.25rem;
  width: 100%;
  border-radius: 1.25rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: center;
  background-color: #fafafb;
}
.avatar > :first-child {
  margin-top: 0;
}
.avatar > :last-child {
  margin-bottom: 0;
}
.avatar__image-wrapper {
  margin-bottom: 1.25rem;
  width: 5rem;
  height: 5rem;
  border-radius: 50%;
  overflow: hidden;
}
.avatar__name {
  width: 100%;
  font-weight: 700;
}
.avatar__position {
  width: 100%;
  font-size: 0.875rem;
}
.avatar__button {
  margin-top: 1.25rem;
}
.popup {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2147483646;
  visibility: hidden;
  opacity: 0;
  font-size: 0;
  text-align: center;
}
.popup:before {
  content: "";
  display: inline-block;
  vertical-align: middle;
  height: 100%;
}
.popup.visible {
  opacity: 1;
  visibility: visible;
}
.popup__bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(48, 54, 60, 0.9);
}
.popup__content {
  position: relative;
  display: inline-block;
  vertical-align: middle;
  width: calc(100% - 60px);
  max-width: 1400px;
}
.popup__content:before {
  content: "";
  display: block;
  padding-top: 56.25%;
}
.popup__content:after {
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  width: 96px;
  height: 96px;
  margin-top: 100%/-2;
  margin-left: 100%/-2;
  background: #879099 url(../img/video/ajax.gif) 50% 50% no-repeat;
  border-radius: 10px;
  -webkit-box-shadow: 0 2px 20px rgba(0, 12, 44, 0.3);
  box-shadow: 0 2px 20px rgba(0, 12, 44, 0.3);
}
.popup iframe {
  border: 0;
  position: absolute;
  z-index: 2;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.toc {
  display: block;
}
.toc::after {
  content: "";
  display: block;
  width: 100%;
  margin: 3em 0;
  border: 0;
  height: 0.0625rem;
  background: #fff;
}
.toc:first-child .toc__headline {
  margin-top: 0;
}
.toc .toc__headline {
  display: block;
  margin-bottom: 1rem;
}
.toc .toc__list {
  counter-reset: number;
  padding-left: 0;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.5625;
  list-style: none;
}
.toc .toc__list .toc__item {
  counter-increment: number;
  position: relative;
  padding-left: 2.8125rem;
  margin-bottom: 0.625rem;
  padding-bottom: 0;
}
.toc .toc__list .toc__item::before {
  content: counter(number);
  display: block;
  width: 1.5625rem;
  height: 1.5625rem;
  line-height: 1.5625rem;
  border-radius: 1.5625rem;
  position: absolute;
  left: 0;
  top: 0;
  background: #ffc600;
  color: #000c2c;
  text-align: center;
  font-size: 0.875rem;
  font-weight: 600;
}
.toc .toc__link {
  color: #000c2c;
  text-decoration: none;
  -webkit-transition: color 0.15s ease-out;
  transition: color 0.15s ease-out;
  background: 0 0;
}
.toc .toc__link:hover {
  color: #005ce6;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.video {
  position: relative;
  width: 100%;
  max-width: 360px;
  margin: 30px auto 0;
}
.video:before {
  content: "";
  position: absolute;
  z-index: -1;
  top: 50%;
  left: 50%;
  max-width: 100%;
  width: 954px;
  height: 879px;
  margin-top: 100%/-2;
  margin-left: 100%/-2;
  background: url(../assets/img/video/decoration_why.svg);
  background-position: 0 0;
  background-size: 100% 100%;
  pointer-events: none;
  -webkit-transform: scale(0.5);
  -ms-transform: scale(0.5);
  transform: scale(0.5);
}
.video__placeholder {
  position: relative;
  display: block;
  background-image: url(../assets/img/video/video.png);
  background-position: 0 0;
  background-repeat: no-repeat;
  background-size: 100% auto;
  border-radius: 4px;
  -webkit-box-shadow: 0 20px 35px rgba(135, 144, 153, 0.15);
  box-shadow: 0 20px 35px rgba(135, 144, 153, 0.15);
  max-width: 940px;
  max-height: 420px;
  margin: auto;
}
.video__placeholder:before {
  content: "";
  display: block;
  padding-top: 62.5%;
}
.video__placeholder:hover .video__play {
  -webkit-transform: translate3d(-50%, -50%, 0) scale(1.1);
  transform: translate3d(-50%, -50%, 0) scale(1.1);
  opacity: 1;
  -webkit-transition: opacity 0.4s ease-out, -webkit-transform 0.2s ease-out;
  transition: opacity 0.4s ease-out, -webkit-transform 0.2s ease-out;
  transition: transform 0.2s ease-out, opacity 0.4s ease-out;
  transition: transform 0.2s ease-out, opacity 0.4s ease-out,
    -webkit-transform 0.2s ease-out;
}
.video__placeholder:hover .video__play--blue {
  -webkit-transform: translate3d(-50%, -50%, 0) scale(1);
  transform: translate3d(-50%, -50%, 0) scale(1);
}
.video__play {
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-transition: opacity 0.2s ease-out, -webkit-transform 0.2s ease-out;
  transition: opacity 0.2s ease-out, -webkit-transform 0.2s ease-out;
  transition: transform 0.2s ease-out, opacity 0.2s ease-out;
  transition: transform 0.2s ease-out, opacity 0.2s ease-out,
    -webkit-transform 0.2s ease-out;
  opacity: 0.6;
}
.video__play--blue {
  -webkit-transform: translate3d(-50%, -50%, 0) scale(0.95);
  transform: translate3d(-50%, -50%, 0) scale(0.95);
  opacity: 0.8;
}
.video__rocket {
  display: block;
  margin: 0 auto;
  width: 210px;
  height: 210px;
  background: url(../assets/images/rocket.png) 0 0 no-repeat;
  background-size: 100% 100%;
}
@media screen and (min-width: 48em) {
  .video {
    margin-top: 60px;
  }
  .video:before {
    -webkit-transform: scale(0.6);
    -ms-transform: scale(0.6);
    transform: scale(0.6);
  }
  .video__rocket {
    width: 252px;
    height: 252px;
  }
}
@media screen and (min-width: 64em) {
  .video {
    margin: -20px 0 0 auto;
  }
  .video:before {
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1);
  }
}
.video--reset {
  margin: 0;
}
.video--reset:before {
  display: none;
}
.video .wistia_embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
  z-index: 100;
}
.wysiwyg > :first-child {
  margin-top: 0;
}
.wysiwyg > :last-child {
  margin-bottom: 0;
}
.wysiwyg p {
  margin: 1.25rem 0;
}
.wysiwyg h1,
.wysiwyg h2 {
  margin: 3.75rem 0 1.25rem;
}
.wysiwyg h3 {
  margin: 3.125rem 0 1.25rem;
}
.wysiwyg h4 {
  margin: 2.5rem 0 1.25rem;
}
.wysiwyg h5 {
  margin: 1.25rem 0;
}
.wysiwyg h6 {
  margin: 1.25rem 0;
}
.wysiwyg ul {
  padding: 0;
  margin: 1.25rem 0 1.25rem 1.1875rem;
  list-style-type: square;
}
.wysiwyg ul li {
  margin: 0.625rem 0;
}
.wysiwyg ul li::marker {
  color: #005ce6;
}
.wysiwyg figure {
  margin-top: 2.5rem;
  margin-bottom: 2.5rem;
}
.wysiwyg figure.aligncenter figcaption:before {
  right: 0;
  margin-right: auto;
  margin-left: auto;
}
.wysiwyg figure.alignright figcaption:before {
  right: 0;
  margin-right: 0;
  margin-left: auto;
}
.wysiwyg figcaption {
  margin-top: 0.9375rem;
  padding-top: 0.625rem;
  font-size: 0.875rem;
  font-style: italic;
  position: relative;
}
.wysiwyg figcaption:before {
  content: "";
  left: 0;
  top: 0;
  width: 6.25rem;
  height: 0.0625rem;
  background-color: #005ce6;
  position: absolute;
}
.wysiwyg table {
  width: 100%;
  border-collapse: collapse;
}
.wysiwyg table tr th {
  padding: 0.625rem;
  font-weight: 700;
  background: #005ce6;
  color: #fff;
  vertical-align: top;
  text-align: left;
}
.wysiwyg table tr td {
  padding: 0.625rem;
  border-bottom: 1px solid #e1e6eb;
  vertical-align: top;
}
.wysiwyg blockquote {
  text-align: left;
  position: relative;
  border: 0;
  color: #879099;
  padding: 0.3125rem 0 0.3125rem 2.5rem;
  margin: 2.5rem 0;
  font-size: 1.5rem;
  line-height: 1.3;
}
@media print, screen and (max-width: 64em) {
  .wysiwyg blockquote {
    font-size: 1.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .wysiwyg blockquote {
    font-size: 1.125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .wysiwyg blockquote {
    font-size: 1.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .wysiwyg blockquote {
    font-size: 1.125rem;
  }
}
.wysiwyg blockquote:before {
  content: "";
  height: 100%;
  width: 6px;
  position: absolute;
  top: 0;
  left: 0;
  border-radius: 1.25rem;
  background-color: #ffc600;
}
.wysiwyg blockquote > p {
  font-size: inherit;
  line-height: inherit;
}
.wysiwyg blockquote > :first-child {
  margin-top: 0;
}
.wysiwyg blockquote > :last-child {
  margin-bottom: 0;
}
.swiper {
  width: 100%;
  position: relative;
}
.swiper-side {
  top: 0;
  left: 0;
  height: 100%;
  width: 4rem;
  z-index: 10;
  position: absolute;
  pointer-events: none;
  background: -webkit-gradient(
    linear,
    right top,
    left top,
    from(rgba(255, 255, 255, 0)),
    to(#fff)
  );
  background: linear-gradient(270deg, rgba(255, 255, 255, 0) 0, #fff 100%);
}
.swiper-side--right {
  left: auto;
  right: 0;
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
@media print, screen and (max-width: 64em) {
  .swiper-side {
    display: none;
  }
}
.swiper-nav {
  top: 0;
  left: 0;
  width: 5.25rem;
  padding: 0 1.375rem;
  height: 100%;
  z-index: 20;
  position: absolute;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  cursor: pointer;
}
@media print, screen and (max-width: 64em) {
  .swiper-nav {
    display: none;
  }
}
.swiper-nav--prev {
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.swiper-nav--next {
  left: auto;
  right: 0;
}
.swiper-nav-icon {
  padding: 0.75rem;
  width: 2.5rem;
  height: 2.5rem;
  background-color: #ebecef;
  border-radius: 50%;
}
.swiper-nav:hover .swiper-nav-icon {
  background-color: #0079f2;
}
.swiper-nav:focus:hover .swiper-nav-icon svg,
.swiper-nav:hover .swiper-nav-icon svg {
  fill: #fff;
}
.swiper-nav:focus .swiper-nav-icon {
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.swiper-nav:focus .swiper-nav-icon svg {
  fill: #000c2c;
}
.swiper-nav:active .swiper-nav-icon {
  background-color: #0566c6;
}
.swiper-nav:active .swiper-nav-icon svg {
  fill: #fff;
}
.swiper-slide {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
.swiper--simple {
  margin: -1.5rem 0;
  padding: 1.5rem 0;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  width: 100vw;
}
.swiper--simple .swiper-slide {
  height: 14rem;
  width: 14rem;
  margin: 0 1rem;
}
@media print, screen and (max-width: 64em) {
  .swiper--simple .swiper-slide {
    margin: 0 0.5rem;
  }
}
.swiper--simple .swiper-slide-inner {
  height: 100%;
  width: 100%;
  border-radius: 1rem;
  padding: 1.5rem;
  border: 0.0625rem solid #e0e2e5;
  color: #000c2c;
  font-weight: 400;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  display: block;
  overflow: hidden;
}
.swiper--simple a.swiper-slide-inner:hover {
  -webkit-box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
  box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
}
.swiper--simple a.swiper-slide-inner:focus {
  border-color: #0079f2;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.swiper--simple a.swiper-slide-inner:active {
  opacity: 0.64;
  border-color: #e0e2e5;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.swiper--simple .swiper-image-wrapper {
  width: 100%;
  height: 3.125rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
}
.swiper--simple .swiper-image {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 100%;
}
.swiper--simple .swiper-text {
  margin-top: 1rem;
  font-size: 0.9375rem;
}
.swiper--simple .swiper-link {
  font-weight: 700;
  color: #0079f2;
  margin-top: 0.5rem;
}
.swiper--medium {
  margin: -1.5rem 0;
  padding: 1.5rem 0;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  width: 100vw;
}
.swiper--medium .swiper-slide {
  min-height: 23.75rem;
  width: 27.5rem;
  margin: 0.1875rem 1rem;
}
@media print, screen and (max-width: 64em) {
  .swiper--medium .swiper-slide {
    margin: 0.1875rem 0.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .swiper--medium .swiper-slide {
    min-height: auto;
    width: 17.5rem;
  }
}
.swiper--medium .swiper-slide-inner {
  height: 100%;
  width: 100%;
  border-radius: 1rem;
  color: #000c2c;
  font-weight: 400;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  display: block;
  position: relative;
}
.swiper--medium .swiper-slide-inner:before {
  content: "";
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  border-radius: 1rem;
  position: absolute;
  -webkit-box-shadow: 0 0.5rem 1.5rem rgba(0, 0, 0, 0.04);
  box-shadow: 0 0.5rem 1.5rem rgba(0, 0, 0, 0.04);
}
.swiper--medium a.swiper-slide-inner:hover {
  opacity: 1;
  -webkit-transform: translateY(-10px);
  -ms-transform: translateY(-10px);
  transform: translateY(-10px);
}
.swiper--medium a.swiper-slide-inner:focus {
  opacity: 1;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
}
.swiper--medium a.swiper-slide-inner:active {
  opacity: 0.64;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.swiper--medium .swiper-image-wrapper {
  width: 100%;
  height: 15.625rem;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .swiper--medium .swiper-image-wrapper {
    height: 0;
    padding-top: 56.25%;
  }
}
.swiper--medium .swiper-image {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}
@media print, screen and (max-width: 48em) {
  .swiper--medium .swiper-image {
    left: 0;
    top: 0;
    position: absolute;
  }
}
.swiper--medium .swiper-content {
  min-height: 8rem;
  padding: 1.5rem;
  border: 0.0625rem solid #e0e2e5;
  border-top: 0;
  border-bottom-left-radius: 1rem;
  border-bottom-right-radius: 1rem;
}
.swiper--medium a.swiper-slide-inner:focus .swiper-content {
  border-color: #0079f2;
}
.swiper--medium .swiper-title {
  font-size: 1.125rem;
  margin: 0;
}
.swiper--medium .swiper-text {
  margin-top: 0.5rem;
  color: #5f677b;
}
.swiper--textual {
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  width: calc(100% + 84px);
}
@media print, screen and (max-width: 64em) {
  .swiper--textual {
    width: 100vw;
  }
}
.swiper--textual:before {
  content: "";
  position: absolute;
  top: 0;
  left: 50%;
  height: 100%;
  width: calc(100% - 84px);
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  border-radius: 1.25rem;
  background: #fef0f0;
  transform: translateX(-50%);
}
@media print, screen and (max-width: 64em) {
  .swiper--textual:before {
    display: none;
  }
}
.swiper--textual .swiper-side {
  width: 2.625rem;
  background: #fff;
}
.swiper--textual .swiper-wrapper {
  z-index: 5;
}
.swiper--textual .swiper-slide {
  width: 100%;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-slide {
    width: 27.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .swiper--textual .swiper-slide {
    width: 20rem;
  }
}
.swiper--textual .swiper-slide-inner {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  padding: 8.875rem 6.625rem 4rem;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-slide-inner {
    padding: 2rem;
    margin: 0 0.5rem;
    border-radius: 1.25rem;
    background: #fef0f0;
  }
}
@media print, screen and (max-width: 48em) {
  .swiper--textual .swiper-slide-inner {
    padding: 1.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-slide-inner {
    padding: 2rem;
  }
}
.swiper--textual .swiper-title {
  font-weight: 700;
  margin-bottom: 2rem;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-title {
    display: block;
  }
}
.swiper--textual .swiper-text {
  font-size: 2.25rem;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-text {
    font-size: 1.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .swiper--textual .swiper-text {
    font-size: 1.125rem;
  }
}
.swiper--textual .swiper-pagination {
  z-index: 30;
  left: 50%;
  top: 2.5rem;
  width: calc(100% - 84px);
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-pagination {
    top: 1.5rem;
    display: none;
  }
}
.swiper--textual .swiper-pagination:after,
.swiper--textual .swiper-pagination:before {
  content: "";
  top: 0;
  height: 100%;
  left: 0;
  width: 4rem;
  z-index: 20;
  position: absolute;
  pointer-events: none;
  background: -webkit-gradient(
    linear,
    right top,
    left top,
    from(rgba(255, 255, 255, 0)),
    to(#fef0f0)
  );
  background: linear-gradient(270deg, rgba(255, 255, 255, 0) 0, #fef0f0 100%);
}
.swiper--textual .swiper-pagination:after {
  left: auto;
  right: 0;
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.swiper--textual .swiper-pagination-wrapper {
  padding: 1rem 4rem;
  overflow: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-pagination-wrapper {
    padding: 0.5rem 2rem;
  }
}
.swiper--textual .swiper-pagination-bullet {
  margin-right: 2.5rem;
  padding: 0.5rem 0;
  line-height: 1;
  font-size: 1.125rem;
  font-weight: 700;
  white-space: nowrap;
  color: #000c2c;
  border-bottom: 0.125rem solid transparent;
  z-index: 10;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
@media print, screen and (max-width: 64em) {
  .swiper--textual .swiper-pagination-bullet {
    font-size: 1rem;
  }
}
.swiper--textual .swiper-pagination-bullet:last-child {
  margin-right: 0;
}
.swiper--textual .swiper-pagination-bullet-active,
.swiper--textual .swiper-pagination-bullet:hover {
  color: #0079f2;
  border-color: #0079f2;
}
.banner-book {
  border-radius: 1.25rem;
  min-height: 24.625rem;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .banner-book {
    min-height: auto;
  }
}
.banner-book__content {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 60%;
  -ms-flex: 0 0 60%;
  flex: 0 0 60%;
  padding: 4rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .banner-book__content {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 2rem;
  }
}
.banner-book__content-wrapper > :first-child {
  margin-top: 0;
}
.banner-book__content-wrapper > :last-child {
  margin-bottom: 0;
}
.banner-book__label {
  padding: 0.25rem 1rem;
  font-size: 0.75rem;
  font-weight: 700;
  border-radius: 1rem;
  color: #fff;
  background-color: #ffc600;
  display: inline-block;
}
.banner-book__title {
  margin: 0.5rem 0 0;
  font-size: 3rem;
}
@media print, screen and (max-width: 80em) {
  .banner-book__title {
    font-size: 2rem;
  }
}
.banner-book__text {
  font-size: 1.125rem;
  margin-top: 1rem;
}
.banner-book__button {
  margin-top: 1.5rem;
}
.banner-book__image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 40%;
  -ms-flex: 0 0 40%;
  flex: 0 0 40%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .banner-book__image-wrapper {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    height: 0;
    padding-top: 56.25%;
  }
}
.banner-book__image {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}
@media print, screen and (max-width: 64em) {
  .banner-book__image {
    left: 0;
    top: 0;
    position: absolute;
  }
}
.hero {
  position: relative;
  text-align: center;
  padding: 15.625rem 0;
}
@media print, screen and (max-width: 80em) {
  .hero {
    padding: 12.5rem 0;
  }
}
@media print, screen and (max-width: 64em) {
  .hero {
    padding: 9.375rem 0;
  }
}
.hero--offset {
  margin-bottom: 7.8125rem;
}
.hero--pricing {
  margin-bottom: 0;
  padding-top: 12.5rem;
}
.hero--left-bottom {
  padding: 15.625rem 0 5.625rem;
  text-align: left;
}
@media print, screen and (max-width: 64em) {
  .hero--left-bottom {
    padding: 12.5rem 0 4.375rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .hero--left-bottom {
    padding: 9.375rem 0 3.125rem;
  }
}
.hero--webinar {
  padding-bottom: 5.625rem;
}
.hero--product-integrations:before {
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(#fafafb),
    to(#fff)
  );
  background: linear-gradient(180deg, #fafafb 0, #fff 100%);
}
.hero.lp {
  padding-bottom: 7rem;
}
.hero.lp .hero__content {
  max-width: 32.5rem;
}
@media print, screen and (min-width: 64.0625em) {
  .hero.lp .hero__content {
    max-width: 37.5rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .hero.lp .hero__content.large-5 {
    text-align: left;
    padding-right: 1rem;
  }
}
.hero.lp .hero__text {
  font-size: 1.125rem;
  line-height: 1.5625rem;
  max-width: 28.125rem;
}
@media screen and (min-width: 48em) {
  .hero--roadmap .hero__offset {
    margin: 0 0 -40%;
  }
}
.hero--roadmap .hero__media {
  margin-top: 6rem;
  border-radius: 1.25rem;
  -webkit-box-shadow: -10px 27px 48px -17px rgba(0, 12, 44, 0.1);
  box-shadow: -10px 27px 48px -17px rgba(0, 12, 44, 0.1);
}
.hero--roadmap .hero__content {
  margin: 0 auto;
}
@media screen and (min-width: 80.0625em) {
  .hero--roadmap .hero__content {
    margin: 0 116px;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }
}
.hero--roadmap .hero__content--left_column {
  text-align: center;
}
@media print, screen and (min-width: 64.0625em) {
  .hero--roadmap .hero__content--left_column {
    text-align: left;
  }
}
.hero--roadmap .hero__content--right_column {
  text-align: center;
}
@media print, screen and (min-width: 64.0625em) {
  .hero--roadmap .hero__content--right_column {
    text-align: right;
  }
}
.hero--roadmap .hero__title {
  font-style: normal;
  font-weight: 600;
  font-size: 3rem;
  line-height: 3.625rem;
}
@media screen and (max-width: 47.9375em) {
  .hero--roadmap .hero__title {
    font-size: 2rem;
    line-height: 2.375rem;
  }
}
.hero--roadmap .hero__subtitle {
  font-style: normal;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  color: #666d80;
}
@media screen and (max-width: 47.9375em) {
  .hero--roadmap .hero__subtitle {
    max-width: 80%;
    margin: auto;
  }
}
.hero--roadmap .hero__buttons {
  padding-top: 0;
  margin: 1.875rem auto 0;
}
@media print, screen and (min-width: 64.0625em) {
  .hero--roadmap .hero__buttons {
    padding-top: 2.5rem;
    margin: 3.75rem auto 0;
  }
}
@media screen and (min-width: 80.0625em) {
  .hero--roadmap .hero__buttons {
    position: absolute;
    padding-top: 0;
    top: 40px;
    right: 116px;
  }
}
.hero--webinar .hero__container {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 64em) {
  .hero--webinar .hero__container {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.hero__content {
  max-width: 46.25rem;
  margin: 0 auto;
}
.hero__content--full {
  max-width: 100%;
}
.hero--pricing .hero__content {
  max-width: 100%;
}
.hero--left-bottom .hero__content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  max-width: 100%;
  margin: 0;
}
.hero--webinar .hero__content {
  padding-right: 5.625rem;
  text-align: left;
}
@media print, screen and (max-width: 64em) {
  .hero--webinar .hero__content {
    padding-right: 0;
    text-align: center;
  }
}
@media print, screen and (max-width: 48em) {
  .hero--webinar .hero__content {
    max-width: 100%;
  }
}
.hero__heading {
  font-size: 1.125rem;
  letter-spacing: 0.0125rem;
  margin-bottom: 1rem;
  color: #b3b7c1;
}
@media print, screen and (max-width: 80em) {
  .hero__heading {
    font-size: 1rem;
  }
}
.hero__title {
  font-size: 3rem;
  margin-bottom: 1.5625rem;
  line-height: 1.1;
}
.hero__title:last-child {
  margin-bottom: 0;
}
@media print, screen and (min-width: 64.0625em) {
  .hero__title--horizontal {
    font-style: normal;
    font-weight: 600;
    font-size: 2.25rem;
    line-height: 2.6875rem;
    letter-spacing: -1.3616px;
    margin-bottom: 2rem;
  }
}
@media print, screen and (max-width: 80em) {
  .hero__title {
    font-size: 2.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .hero__title br {
    display: none;
  }
}
.hero--left-bottom .hero__title {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  width: 100%;
  font-size: 2.25rem;
  margin-bottom: 0.9375rem;
}
@media print, screen and (max-width: 80em) {
  .hero--left-bottom .hero__title {
    font-size: 2rem;
  }
}
.hero--webinar .hero__title {
  font-size: 2.25rem;
}
.hero--pricing .hero__title {
  font-size: 3rem;
  line-height: 3.625rem;
  margin-bottom: 1rem;
}
@media print, screen and (max-width: 64em) {
  .hero--pricing .hero__title {
    font-size: 2.375rem;
    line-height: 3rem;
  }
}
@media print, screen and (max-width: 64em) {
  .hero--pricing .hero__title {
    font-size: 2.375rem;
    line-height: 3rem;
  }
}
.page-template-template-landing-v3 .hero__subtitle,
.page-template-template-landing-v3 .hero__subtitle h1,
.page-template-template-landing-v3 .hero__subtitle h2 {
  font-size: 1.1875rem;
}
.hero__subtitle {
  font-size: 2.25rem;
  margin-bottom: 1.5625rem;
  line-height: 1.2;
  color: #7e8494;
}
.hero__subtitle:last-child {
  margin-bottom: 0;
}
@media print, screen and (max-width: 80em) {
  .hero__subtitle {
    font-size: 1.875rem;
  }
}
.hero__media {
  width: 100%;
  border-radius: 1.875rem;
  margin-top: 12.5rem;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 64em) {
  .hero__media {
    margin-top: 6.25rem;
    border-radius: 0.9375rem;
  }
}
.hero .hero__media--lp {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
  margin-top: 6.25rem;
  text-align: center;
}
@media print, screen and (max-width: 64em) {
  .hero .hero__media--lp {
    margin-top: 3.125rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .hero .hero__media--lp-horizontal {
    margin-top: 0;
  }
}
.hero--left-bottom .hero__media {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  width: 100%;
  margin-bottom: 0.625rem;
  font-size: 0.625rem;
  color: #879099;
  text-transform: uppercase;
  letter-spacing: 0;
}
.hero--home .hero__media {
  margin-top: 0;
}
.hero--product-integrations .hero__media {
  margin: 0 0 -30.625rem;
}
.hero__text {
  margin: 0 auto;
  font-size: 1.5rem;
  letter-spacing: -0.08125rem;
  line-height: 1.3;
  font-weight: 400;
}
.hero__text:last-child {
  margin-bottom: 0;
}
@media print, screen and (min-width: 64.0625em) {
  .hero__text--horizontal {
    margin-bottom: 0;
  }
}
@media print, screen and (max-width: 80em) {
  .hero__text {
    font-size: 1.25rem;
  }
}
.hero.lp .hero__text {
  letter-spacing: 0;
}
.hero--left-bottom .hero__text {
  max-width: 100%;
  -webkit-box-ordinal-group: 4;
  -webkit-order: 3;
  -ms-flex-order: 3;
  order: 3;
  width: 100%;
  margin: 0;
  font-size: 1.125rem;
  line-height: 1.38;
}
.hero--pricing .hero__text {
  font-size: 1.25rem;
  line-height: 1.875rem;
  font-weight: 500;
  letter-spacing: initial;
  text-align: center;
  color: #000c2c;
}
.hero__media-image {
  width: 100%;
  height: auto;
  vertical-align: top;
}
.hero .hero__media-image--lp {
  width: auto;
}
@media print, screen and (min-width: 64.0625em) {
  .hero .hero__media-image--lp-horizontal {
    max-width: 500px;
    max-height: 480px;
    border-radius: 15px;
  }
}
.hero--webinar .hero__media-image {
  font-size: 1.125rem;
  line-height: 1.38;
}
.hero__buttons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  font-size: 0;
  margin: 3.75rem auto 0;
}
@media print, screen and (min-width: 64.0625em) {
  .hero__buttons--horizontal {
    -webkit-box-pack: left;
    -webkit-justify-content: left;
    -ms-flex-pack: left;
    justify-content: left;
    margin-top: 3rem;
  }
}
.hero__buttons > .button {
  margin: 0.625rem;
}
@media print, screen and (min-width: 64.0625em) {
  .hero__buttons > .button {
    min-width: 9.25rem;
  }
}
@media screen and (min-width: 80em) {
  .hero__buttons > .button {
    min-width: 10.125rem;
  }
}
.hero__image {
  margin-top: 3.125rem;
}
.hero--product-integrations .hero__image {
  margin-top: 6.25rem;
}
.hero__livestorm {
  border: 0;
  background-color: #fff;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  padding: 0.9375rem;
  border-radius: 0.625rem;
  min-height: 500px;
  margin-bottom: -50%;
  z-index: 29;
  min-width: 380px;
  min-height: 500px;
}
@media print, screen and (max-width: 80em) {
  .hero__livestorm {
    margin-right: -6rem;
  }
}
@media print, screen and (max-width: 64em) {
  .hero__livestorm {
    margin-right: auto;
    margin: 3.75rem auto -7.5rem;
  }
}
@media screen and (max-width: 29.6875em) {
  .hero__livestorm {
    margin: 2.75rem auto -7.5rem -1.5rem;
    min-width: 375px;
    min-height: 610px;
  }
}
@media screen and (max-width: 25.9375em) {
  .hero__livestorm {
    margin: 2.75rem auto -7.5rem -2.5rem;
  }
}
@media screen and (max-width: 20em) {
  .hero__livestorm {
    min-width: 320px;
  }
}
.hero__marketo {
  min-height: 200px;
  display: inline-table;
  border: 0;
  background-color: transparent;
  margin-bottom: -50%;
  min-width: 400px;
  z-index: 29;
}
@media print, screen and (max-width: 64em) {
  .hero__marketo {
    margin: 48px auto -150px;
  }
}
@media screen and (max-width: 29.6875em) {
  .hero__marketo {
    min-width: 375px;
  }
}
@media screen and (max-width: 20em) {
  .hero__marketo {
    min-width: 320px;
  }
}
.hero__offset {
  width: 100%;
  margin: 9.375rem 0 -18.75rem;
  position: relative;
  text-align: left;
}
@media print, screen and (max-width: 80em) {
  .hero__offset {
    margin: 7.8125rem 0 -15.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .hero__offset {
    margin: 6.25rem 0 -12.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .hero__offset {
    margin: 3.125rem 0 -12.5rem;
  }
}
.hero--pricing .hero__offset {
  margin: 0;
}
.hero .hero__offset--lp {
  margin-bottom: -6rem;
}
@media screen and (min-width: 48em) {
  .hero .hero__offset--lp {
    margin-bottom: -7.5rem;
  }
}
@media screen and (min-width: 64em) {
  .hero .hero__offset--lp {
    margin-bottom: -12.5rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .hero .hero__offset--lp.large-6 {
    margin-top: 0;
    margin-bottom: 0;
  }
}
.hero .hero__offset--lp-vertical {
  margin-bottom: 0;
}
.hero__media {
  z-index: 1;
  width: 100%;
  border-radius: 1.875rem;
  position: relative;
  overflow: hidden;
}
.hero--product .hero__media {
  -webkit-box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.05);
  box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.05);
}
@media print, screen and (max-width: 64em) {
  .hero__media {
    margin-top: 6.25rem;
    border-radius: 1.0625rem;
  }
}
.hero__media-wistia {
  width: 100%;
  height: 400px;
}
@media print, screen and (max-width: 64em) {
  .hero__media-wistia {
    display: none;
  }
}
@media screen and (min-width: 75em) {
  .hero__media-wistia {
    height: 528px;
  }
}
.hero__media-wistia--overlay {
  width: 100%;
  height: 100%;
  position: absolute;
  z-index: 20;
}
@media print, screen and (max-width: 64em) {
  .hero__media-wistia--overlay {
    display: none;
  }
}
.hero--product .hero__media-wistia {
  width: 100%;
  height: 0;
  padding-top: 56.25%;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .hero--product .hero__media-wistia {
    display: block;
    height: 0;
  }
}
.hero--product .hero__media-wistia + .hero__media-image {
  display: none;
}
.hero__media-wistia-video {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: #fafafb;
  position: absolute;
}
.hero__media-wistia-overlay {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
  cursor: pointer;
}
.hero__media-wistia-overlay.is-hidden {
  display: none;
}
.hero__media-wistia-button {
  left: 50%;
  top: 50%;
  outline: 0;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
  pointer-events: none;
}
.hero__media-wistia-overlay:hover .hero__media-wistia-button {
  background-color: #005ce6;
}
.hero__media-wistia-button svg {
  width: 1rem;
  height: 1rem;
  margin-right: 0.75rem;
}
.hero__media-video {
  width: 100%;
  vertical-align: top;
}
@media print, screen and (max-width: 64em) {
  .hero__media-video {
    display: none;
  }
}
.hero__media-video + .hero__media-image {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .hero__media-video + .hero__media-image {
    display: block;
  }
}
.hero__media-image {
  width: 100%;
  height: auto;
  vertical-align: top;
}
.hero--home .hero__media {
  margin-top: 0;
  -webkit-box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.05);
  box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.05);
}
@media print, screen and (max-width: 64em) {
  .hero--home .hero__media {
    -webkit-box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.1);
    box-shadow: 0 1.875rem 3.75rem rgba(0, 0, 0, 0.1);
  }
}
.hero--home .hero__media-wistia {
  width: 100%;
  height: 0;
  padding-top: 56.25%;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .hero--home .hero__media-wistia {
    display: none;
  }
}
.hero--home .hero__media-wistia + .hero__media-image {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .hero--home .hero__media-wistia + .hero__media-image {
    display: block;
  }
}
.double {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.double__block {
  width: 50%;
}
@media print, screen and (max-width: 48em) {
  .double__block {
    width: 100%;
    max-width: 25.625rem;
    margin: 0 auto;
  }
}
.double--text-first .double__block--text {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  padding-right: 10%;
}
@media print, screen and (max-width: 48em) {
  .double--text-first .double__block--text {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    padding: 0;
  }
}
.double--image-first .double__block--text {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  padding-left: 10%;
}
@media print, screen and (max-width: 48em) {
  .double--image-first .double__block--text {
    padding: 0;
  }
}
.double__block--image {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 48em) {
  .double__block--image {
    margin-bottom: 4.375rem;
  }
}
.double--text-first .double__block--image {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
}
@media print, screen and (max-width: 48em) {
  .double--text-first .double__block--image {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
}
.double--image-first .double__block--image {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
}
.testimonial {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .testimonial {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.testimonial.isquote .testimonial__arrow {
  display: none;
}
.testimonial.isquote .testimonial__content-wrapper {
  max-width: 100%;
}
.testimonial.isquote .testimonial__quotation p {
  font-size: 18px;
  line-height: 25px;
}
.testimonial.isquote .testimonial__author {
  font-size: 16px;
  line-height: 24px;
}
.testimonial__image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  margin-right: 6.25rem;
  height: 10rem;
  width: 10rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .testimonial__image-wrapper {
    width: 7.5rem;
    height: 7.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .testimonial__image-wrapper {
    margin: 3.75rem 0 7.5rem;
  }
}
.testimonial__image-wrapper img {
  width: 100%;
  height: 100%;
}
.testimonial__arrow {
  width: 12.8125rem;
  height: 12.8125rem;
  left: 50%;
  top: 50%;
  z-index: 1;
  fill: #eee;
  position: absolute;
}
@media screen and (max-width: 77.5em) {
  .testimonial__arrow {
    width: 9.375rem;
    height: 9.375rem;
  }
}
.testimonial__arrow:nth-child(1) {
  -webkit-transform: translate(-50%, -100%);
  -ms-transform: translate(-50%, -100%);
  transform: translate(-50%, -100%);
}
.testimonial__arrow:nth-child(2) {
  -webkit-transform: translate(-50%, 0) rotate(180deg);
  -ms-transform: translate(-50%, 0) rotate(180deg);
  transform: translate(-50%, 0) rotate(180deg);
}
.testimonial__arrow > svg {
  width: 100%;
  height: 100%;
}
.testimonial__image-mask {
  z-index: 2;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  overflow: hidden;
  position: relative;
}
.testimonial__content-wrapper {
  max-width: 38.75rem;
}
@media print, screen and (max-width: 64em) {
  .testimonial__content-wrapper {
    width: calc(100% - rem-calc(220));
  }
}
@media print, screen and (max-width: 64em) {
  .testimonial__content-wrapper {
    max-width: 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .testimonial__content-wrapper {
    text-align: center;
  }
}
.testimonial__quotation {
  font-size: 1.5rem;
  letter-spacing: -0.01875rem;
}
@media print, screen and (max-width: 80em) {
  .testimonial__quotation {
    font-size: 1.125rem;
  }
}
.testimonial__author {
  margin-top: 2.8125rem;
  color: #879099;
}
.testimonial__author:before {
  content: "â€“ ";
}
@media print, screen and (max-width: 80em) {
  .testimonial__author {
    font-size: 0.875rem;
    margin-top: 1.875rem;
  }
}
.testimonial__author-name {
  display: inline-block;
}
.testimonial__author-role {
  display: inline-block;
}
#testimonial-dots {
  display: none;
  font-family: a;
  font-size: 0;
  line-height: 0;
  color: transparent;
  text-shadow: none;
  position: relative;
  top: 100%;
  left: 0;
  width: 100%;
  margin-top: 50px;
  text-align: center;
}
#testimonial-dots .dot {
  display: inline-block;
  vertical-align: top;
  width: 10px;
  height: 10px;
  margin: 0 4px;
  background: 0 0;
  border-radius: 20px;
  background: #c5c5c5;
  opacity: 0.3;
}
#testimonial-dots .dot.active {
  opacity: 1;
}
.social-share {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  position: relative;
}
.social-share--article {
  -webkit-box-pack: right;
  -webkit-justify-content: right;
  -ms-flex-pack: right;
  justify-content: right;
  margin-top: 3.75rem;
  padding-top: 0.625rem;
  border-top: 0.0625rem solid rgba(0, 0, 0, 0.1);
}
.social-share--footer {
  right: -0.5rem;
  margin-top: 3.125rem;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
}
@media print, screen and (max-width: 64em) {
  .social-share--footer {
    right: auto;
    left: -0.8125rem;
    margin: 3.75rem 0;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
}
.social-share__clipboard-confim {
  color: #000c2c;
  position: absolute;
  top: -1.5rem;
  left: 0;
}
.social-share__item {
  fill: #000c2c;
  opacity: 0.2;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  width: 2.5rem;
  height: 2.5rem;
  padding: 0.625rem;
}
.social-share--article .social-share__item {
  padding: 0.6875rem;
}
.social-share--glossary .social-share__item {
  padding: 0.6875rem;
}
.social-share--footer .social-share__item {
  opacity: 1;
  padding: 0.5rem;
  margin-left: 1.5rem;
}
@media print, screen and (max-width: 64em) {
  .social-share--footer .social-share__item {
    margin: 0 1.5rem 0 0;
  }
}
.social-share__item svg {
  width: 100%;
  height: 100%;
}
.social-share--footer .social-share__item > svg {
  fill: #fff;
}
.social-share__item:hover {
  opacity: 1;
}
.social-share__item--facebook:hover {
  fill: #4267b2;
}
.social-share__item--twitter:hover {
  fill: #1da1f2;
}
.social-share__item--linkedin:hover {
  fill: #0072b1;
}
.glossary-list__item {
  width: 100%;
  margin-bottom: 6.25rem;
  position: relative;
}
.glossary-list__item.is-hidden {
  display: none;
}
.glossary-list__item--not-found {
  text-align: center;
}
.glossary-list__item-anchor {
  top: -6.875rem;
  left: 0;
  width: 100%;
  height: 0.0625rem;
  position: absolute;
}
.glossary-list__item-header {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 2.1875rem;
}
@media print, screen and (max-width: 48em) {
  .glossary-list__item-header {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.glossary-list__item-social {
  margin-left: auto;
}
@media print, screen and (max-width: 48em) {
  .glossary-list__item-social {
    width: 100%;
    margin: 0.625rem 0 0 -0.625rem;
  }
}
.glossary-list__item-content {
  font-size: 1.125rem;
  line-height: 1.6;
}
.brands__header {
  margin: 0 auto 1rem;
}
.brands__title {
  margin-bottom: 1.25rem;
  font-size: 0.875rem;
  color: #879099;
  text-transform: uppercase;
  text-align: center;
  letter-spacing: -0.03125rem;
  color: #2b334a;
}
@media print, screen and (max-width: 48em) {
  .brands__title {
    font-size: 0.875rem;
    line-height: 1.25rem;
  }
}
.brands {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  position: relative;
  width: calc(100% + 40px);
  left: -1.25rem;
}
@media print, screen and (max-width: 48em) {
  .brands {
    width: 100%;
    left: auto;
  }
}
.brands__item {
  width: auto;
  text-align: center;
  height: 1.875rem;
  margin: 1.875rem 0;
  padding: 0 1.25rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 20%;
  -ms-flex: 0 0 20%;
  flex: 0 0 20%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
@media print, screen and (max-width: 64em) {
  .brands__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 25%;
    -ms-flex: 0 0 25%;
    flex: 0 0 25%;
  }
}
@media print, screen and (max-width: 48em) {
  .brands__item {
    padding: 0 0.625rem;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 50%;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
  }
}
.brands__item img {
  height: auto;
  max-width: 100%;
}
@media print, screen and (max-width: 48em) {
  .brands__item img {
    max-width: 100%;
    height: auto;
  }
}
.nav {
  position: relative;
}
.nav--site-header {
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .nav--site-header {
    display: none;
  }
}
@media print, screen and (max-width: 37.5em) {
  .nav--copyright {
    margin-top: 2.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .nav--sidebar {
    z-index: 10;
    left: 0;
    top: 0;
    width: 100%;
    border-radius: 0.9375rem;
    border: 0.0625rem solid rgba(0, 0, 0, 0.1);
    background-color: #fff;
    position: absolute;
    padding: 3.75rem 1.25rem 1.25rem;
    opacity: 0;
    pointer-events: none;
    -webkit-transition: 0.3s;
    transition: 0.3s;
  }
}
.nav--sidebar.is-active {
  opacity: 1;
  pointer-events: all;
}
.nav--search {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .nav--search {
    display: block;
  }
}
.nav--sidebar .nav__title {
  padding: 0.625rem 0;
  margin-top: 1.875rem;
  font-size: 1.125rem;
  font-weight: 700;
}
@media print, screen and (max-width: 64em) {
  .nav--sidebar .nav__title {
    font-size: 1rem;
  }
}
.nav--sidebar .nav__title:first-child {
  margin-top: 0;
  padding-top: 0;
}
.nav--sidebar .nav__title:not(a) {
  color: #879099;
}
.nav__close {
  left: 0;
  top: 0;
  width: 3.75rem;
  height: 3.75rem;
  padding: 1.25rem;
  position: absolute;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .nav__close {
    display: block;
  }
}
.nav__close:after,
.nav__close:before {
  content: "";
  left: 50%;
  top: 50%;
  width: 1.25rem;
  height: 0.125rem;
  border-radius: 0.125rem;
  -webkit-transform: translate(-50%, -50%) rotate(45deg);
  -ms-transform: translate(-50%, -50%) rotate(45deg);
  transform: translate(-50%, -50%) rotate(45deg);
  background-color: #999eab;
  position: absolute;
}
.nav__close:after {
  -webkit-transform: translate(-50%, -50%) rotate(-45deg);
  -ms-transform: translate(-50%, -50%) rotate(-45deg);
  transform: translate(-50%, -50%) rotate(-45deg);
}
.nav__list {
  width: 100%;
  margin: 0;
  padding: 0;
  list-style: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.nav--site-header .nav__list {
  height: 100%;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
}
.nav--site-header .nav__item {
  height: 100%;
}
.nav--copyright .nav__item {
  margin-right: 1.875rem;
  font-size: 1rem;
  line-height: 1.375;
}
@media print, screen and (max-width: 37.5em) {
  .nav--copyright .nav__item {
    width: 100%;
    margin: 1.25rem 0 0;
  }
}
.nav--footer-crossroad .nav__item {
  width: 100%;
}
.nav--sidebar .nav__item {
  width: 100%;
}
@media print, screen and (max-width: 64em) {
  .nav--sidebar .nav__item {
    width: 50%;
  }
}
.nav__link {
  color: #000c2c;
}
.nav--site-header .nav__link {
  font-size: 0.75rem;
  padding: 0 1.5625rem;
  height: 100%;
  opacity: 0.8;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.nav--site-header .nav__link:hover {
  color: #005ce6;
}
.nav--footer-crossroad .nav__link {
  color: #879099;
  font-size: 0.875rem;
  padding: 0.625rem 0;
  line-height: 1.2;
  width: 100%;
  display: block;
}
.nav--footer-crossroad .nav__link:hover {
  color: #005ce6;
}
.nav--sidebar .nav__link {
  width: 100%;
  font-weight: 400;
  padding: 0.625rem 0;
  color: #879099;
  display: block;
}
@media print, screen and (max-width: 64em) {
  .nav--sidebar .nav__link {
    font-size: 0.875rem;
    padding-right: 0.625rem;
  }
}
.nav--sidebar .nav__link:hover {
  color: #005ce6;
}
.nav--sidebar .nav__item.is-active .nav__link {
  font-weight: 700;
  color: #005ce6;
}
.nav--site-footer {
  left: -0.3125rem;
  position: relative;
}
.nav--site-footer a:hover {
  color: #0079f2;
}
.nav--site-footer a:hover span {
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
}
.nav--site-footer a[href=""],
.nav--site-footer a[href="#"],
.nav--site-footer a[href="#"]:hover {
  color: #000c2c;
  cursor: default;
  pointer-events: none;
  font-size: 1rem;
  line-height: 1.5rem;
}
.nav--site-footer > ul > li {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 25%;
  -ms-flex: 0 0 25%;
  flex: 0 0 25%;
  padding: 0 0.3125rem;
}
@media print, screen and (max-width: 64em) {
  .nav--site-footer > ul > li {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 50%;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
    margin-top: 2rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .nav--site-footer > ul > li {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.nav--site-footer > ul > li:first-child:nth-last-child(5),
.nav--site-footer > ul > li:first-child:nth-last-child(5) ~ li {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 20%;
  -ms-flex: 0 0 20%;
  flex: 0 0 20%;
}
@media print, screen and (max-width: 64em) {
  .nav--site-footer > ul > li:first-child:nth-last-child(5),
  .nav--site-footer > ul > li:first-child:nth-last-child(5) ~ li {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 33%;
    -ms-flex: 0 0 33%;
    flex: 0 0 33%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .nav--site-footer > ul > li:first-child:nth-last-child(5),
  .nav--site-footer > ul > li:first-child:nth-last-child(5) ~ li {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.nav--site-footer > ul > li > a {
  margin-bottom: 0.375rem;
  display: block;
}
.nav--site-footer > ul > li > ul {
  padding: 0;
  margin: 0;
  list-style: none;
}
.nav--site-footer > ul > li > ul > li > a {
  padding: 0.1875rem 0;
  margin-bottom: 0.25rem;
  font-size: 0.875rem;
  line-height: 1.5rem;
  font-weight: 400;
  color: #5f677b;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.nav--site-footer > ul > li > ul > li.new a:after {
  content: "new";
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 2.5rem;
  -ms-flex: 0 0 2.5rem;
  flex: 0 0 2.5rem;
  font-size: 0.625rem;
  margin-left: 0.375rem;
  border-radius: 0.625rem;
  letter-spacing: 0.0625rem;
  line-height: 1.5;
  font-weight: 600;
  text-align: center;
  text-decoration: none;
  text-transform: uppercase;
  color: #fff;
  background: #000c2c;
}
.nav--site-footer > ul > li > ul > li > a > i {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1rem;
  -ms-flex: 0 0 1rem;
  flex: 0 0 1rem;
  height: 1rem;
  margin-right: 0.625rem;
  display: block;
  position: relative;
}
.nav--site-footer > ul > li > ul > li > a > i:empty {
  display: none;
}
.nav--site-footer > ul > li > ul > li > a > i svg {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
}
.nav--site-footer > ul > li > ul > li > a > i.nav__link-icon--external {
  top: 0.1875rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 0.625rem;
  -ms-flex: 0 0 0.625rem;
  flex: 0 0 0.625rem;
  margin-left: 0.375rem;
  margin-right: 0;
}
.nav--site-footer > ul > li > ul > li > a > i.nav__link-icon--external svg {
  width: 0.625rem;
  height: 0.625rem;
}
.nav--site-footer
  > ul
  > li
  > ul
  > li
  > a
  > i.nav__link-icon--external
  svg
  path {
  fill: #666d80;
}
.nav--site-footer > ul > li > ul > li > a > i svg + svg {
  display: none;
}
.background-box {
  position: relative;
}
.background-box:before {
  content: "";
  position: absolute;
  z-index: -1;
  left: 1.25rem;
  top: 1.25rem;
  width: calc(100% - 40px);
  height: calc(100% - 40px);
  border-radius: 1.25rem;
  background-color: #fafafb;
}
@media print, screen and (max-width: 37.5em) {
  .background-box:before {
    width: calc(100% - 20px);
    height: calc(100% - 20px);
    left: 0.625rem;
    top: 0.625rem;
    border-radius: 1.6875rem;
  }
}
.background-box--blue:before {
  background-color: #0569ff;
}
.background-box__top {
  position: relative;
}
.background-box__top:before {
  content: "";
  position: absolute;
  z-index: -1;
  left: 1.25rem;
  top: 0;
  width: calc(100% - 40px);
  height: calc(100%);
  border-radius: 1.25rem;
  background-color: #fafafb;
}
@media print, screen and (max-width: 37.5em) {
  .background-box__top:before {
    width: calc(100% - 20px);
    height: calc(100% - 20px);
    left: 0.625rem;
    top: 0;
    border-radius: 1.6875rem;
  }
}
.background-box--short.hero {
  padding-bottom: 0;
}
.background-box--short.hero:before {
  height: calc(80% - 40px);
}
@media print, screen and (max-width: 37.5em) {
  .background-box--short.hero:before {
    height: calc(70% - 20px);
    background-color: #fff;
  }
}
.background-box--short.hero .section {
  padding-bottom: 0;
}
.footer-crossroad__container {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.footer-crossroad__block {
  width: 50%;
}
@media print, screen and (max-width: 80em) {
  .footer-crossroad__block {
    width: 37.5rem;
    margin: 0 auto;
  }
}
.footer-crossroad__block:nth-child(1) {
  width: 100%;
}
@media print, screen and (max-width: 80em) {
  .footer-crossroad__block:nth-child(1) {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    padding: 0 2.5rem;
    margin-bottom: 1.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .footer-crossroad__block:nth-child(1) {
    width: 100%;
  }
}
.footer-crossroad__block:nth-child(2) {
  padding-right: 1.25rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 80em) {
  .footer-crossroad__block:nth-child(2) {
    -webkit-box-ordinal-group: 4;
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
    padding: 0 2.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .footer-crossroad__block:nth-child(2) {
    padding: 0;
    width: 100%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .footer-crossroad__block:nth-child(2) {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.footer-crossroad__block:nth-child(3) {
  padding-left: 1.25rem;
}
@media print, screen and (max-width: 80em) {
  .footer-crossroad__block:nth-child(3) {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    margin-bottom: 5rem;
    padding: 0;
  }
}
@media print, screen and (max-width: 48em) {
  .footer-crossroad__block:nth-child(3) {
    width: 100%;
  }
}
.footer-crossroad__nav:nth-child(1) {
  width: 30%;
}
@media print, screen and (max-width: 37.5em) {
  .footer-crossroad__nav:nth-child(1) {
    width: 60%;
  }
}
.footer-crossroad__nav:nth-child(2) {
  width: 30%;
}
@media print, screen and (max-width: 37.5em) {
  .footer-crossroad__nav:nth-child(2) {
    width: 40%;
  }
}
.footer-crossroad__nav:nth-child(3) {
  width: 40%;
}
@media print, screen and (max-width: 37.5em) {
  .footer-crossroad__nav:nth-child(3) {
    margin-top: 2.5rem;
    width: 100%;
  }
}
.footer-crossroad__nav-title {
  font-size: 1rem;
  margin-bottom: 1.25rem;
}
.footer-crossroad__newsletter {
  margin-top: -2.5rem;
  padding: 2.5rem 3.75rem;
  border-radius: 1.375rem;
  background-color: #fafafb;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .footer-crossroad__newsletter {
    padding: 2.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .footer-crossroad__newsletter {
    left: -1.25rem;
    padding: 2.5rem 1.25rem;
    width: calc(100% + 40px);
  }
}
.footer-crossroad__newsletter-title {
  font-size: 1rem;
  margin-bottom: 1.25rem;
}
.footer-crossroad__newsletter-text {
  color: #879099;
  font-size: 0.875rem;
  margin-bottom: 2.5rem;
}
.footer-crossroad__form {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.footer-crossroad__form-input {
  max-width: calc(100% - 220px);
  margin-right: 2.5rem;
  height: 2.75rem;
}
@media print, screen and (max-width: 37.5em) {
  .footer-crossroad__form-input {
    max-width: 100%;
    width: 100%;
    margin: 0 0 1.875rem;
  }
}
.footer-crossroad__form-button {
  width: 11.25rem;
}
.footer-crossroad__form-consent {
  margin-top: 1.25rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.footer-crossroad__form-consent-checkbox {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.25rem;
  -ms-flex: 0 0 1.25rem;
  flex: 0 0 1.25rem;
  height: 1.25rem;
  margin-right: 0.9375rem;
  border-radius: 0.3125rem;
  background-color: #ffc600;
  overflow: hidden;
  position: relative;
}
.footer-crossroad__form-consent-checkbox input {
  left: 0;
  top: -100%;
  position: absolute;
}
.footer-crossroad__form-consent-checkbox-icon {
  left: 50%;
  top: 50%;
  width: 0.625rem;
  height: 0.3125rem;
  border-bottom: 0.125rem solid #000c2c;
  border-left: 0.125rem solid #000c2c;
  -webkit-transform: translate(-50%, -50%) rotate(-45deg);
  -ms-transform: translate(-50%, -50%) rotate(-45deg);
  transform: translate(-50%, -50%) rotate(-45deg);
  position: absolute;
  display: none;
}
.footer-crossroad__form-consent-checkbox
  input:checked
  + .footer-crossroad__form-consent-checkbox-icon {
  display: block;
}
.footer-crossroad__form-consent-label {
  color: #879099;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.principles__list {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.principles--center .principles__list {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.principles__item {
  width: calc(33.3% - 40px);
  margin: 3.75rem 0 0 3.75rem;
  color: #000c2c;
  font-weight: 400;
  outline: 0;
}
.principles__item:hover {
  color: #000c2c;
}
@media print, screen and (max-width: 64em) {
  .principles__item {
    width: calc(50% - 20px);
    margin: 3.75rem 0 0 2.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .principles__item {
    width: 100%;
    margin: 3.75rem 0 0;
  }
}
.principles__item:nth-child(3n + 1) {
  margin-left: 0;
}
@media print, screen and (max-width: 64em) {
  .principles__item:nth-child(3n + 1) {
    margin: 3.75rem 0 0 2.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .principles__item:nth-child(3n + 1) {
    margin: 3.75rem 0 0;
  }
}
@media print, screen and (max-width: 64em) {
  .principles__item:nth-child(2n + 1) {
    margin: 3.75rem 0 0;
  }
}
.principles__item-icon-wrapper {
  width: 3.625rem;
  height: 3.625rem;
  padding: 1rem;
  margin-bottom: 1.875rem;
  border-radius: 50%;
  background-color: #ddd;
  position: relative;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.principles__item:nth-child(6n + 1) .principles__item-icon-wrapper {
  background-color: #005ce6;
}
.principles__item:nth-child(6n + 2) .principles__item-icon-wrapper {
  background-color: #ffc600;
}
.principles__item:nth-child(6n + 3) .principles__item-icon-wrapper {
  background-color: #ff2638;
}
.principles__item:nth-child(6n + 4) .principles__item-icon-wrapper {
  background-color: #ff7a00;
}
.principles__item:nth-child(6n + 5) .principles__item-icon-wrapper {
  background-color: #7711de;
}
.principles__item:nth-child(6n + 6) .principles__item-icon-wrapper {
  background-color: #3eaa08;
}
.principles__item-icon-wrapper:before {
  content: "";
  width: 100%;
  height: 150%;
  left: 25%;
  bottom: 0;
  opacity: 0.2;
  -webkit-transform-origin: 0 100%;
  -ms-transform-origin: 0 100%;
  transform-origin: 0 100%;
  -webkit-transform: rotate(28deg);
  -ms-transform: rotate(28deg);
  transform: rotate(28deg);
  background-color: #fff;
  position: absolute;
}
.principles__item-icon {
  z-index: 2;
  position: relative;
}
.principles__item-title {
  font-size: 1.5rem;
  margin-bottom: 1.25rem;
  line-height: 1.2;
}
.principles__item-text {
  font-size: 0.9375rem;
  margin-bottom: 1.25rem;
}
.principles__item-link {
  color: #005ce6;
  font-weight: 400;
  font-size: 0.875rem;
}
.benefits {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
  width: calc(100% + 40px);
  left: -1.25rem;
  margin-top: -1.25rem;
}
@media print, screen and (max-width: 37.5em) {
  .benefits {
    width: 100%;
    left: auto;
  }
}
.benefits--center {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.benefits__item {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 calc(33.3% - 40px);
  -ms-flex: 0 0 calc(33.3% - 40px);
  flex: 0 0 calc(33.3% - 40px);
  margin: 1.25rem;
  padding: 2.1875rem;
  font-weight: 400;
  outline: 0;
  border-radius: 0.625rem;
  background-color: #fafafb;
}
.benefits__item:nth-child(5n + 1) {
  color: #005ce6;
}
.benefits__item:nth-child(5n + 2) {
  color: #ff7a00;
}
.benefits__item:nth-child(5n + 3) {
  color: #7711de;
}
.benefits__item:nth-child(5n + 4) {
  color: #3eaa08;
}
.benefits__item:nth-child(5n + 5) {
  color: #ff2638;
}
@media print, screen and (max-width: 64em) {
  .benefits__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 calc(50% - 40px);
    -ms-flex: 0 0 calc(50% - 40px);
    flex: 0 0 calc(50% - 40px);
    max-width: 100%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .benefits__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 1.25rem 0;
  }
}
.benefits__item-icon-wrapper {
  width: 2.25rem;
  height: 2.25rem;
  margin-bottom: 1.5625rem;
  position: relative;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.benefits__item:nth-child(5n + 1) .benefits__item-icon-wrapper > svg {
  fill: #005ce6;
}
.benefits__item:nth-child(5n + 2) .benefits__item-icon-wrapper > svg {
  fill: #ff7a00;
}
.benefits__item:nth-child(5n + 3) .benefits__item-icon-wrapper > svg {
  fill: #7711de;
}
.benefits__item:nth-child(5n + 4) .benefits__item-icon-wrapper > svg {
  fill: #3eaa08;
}
.benefits__item:nth-child(5n + 5) .benefits__item-icon-wrapper > svg {
  fill: #ff2638;
}
.benefits__item-text {
  font-weight: 700;
  font-size: 0.875rem;
  line-height: 1.5;
}
.slideshow {
  width: 100%;
  height: 35.9375rem;
  border-radius: 1.25rem;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .slideshow {
    height: 33.75rem;
    width: calc(100% + 50px);
    left: -1.5625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .slideshow {
    height: 25.625rem;
  }
}
@media print, screen and (max-width: 48em) {
  .slideshow {
    width: 100%;
    height: 20rem;
    left: auto;
  }
}
@media print, screen and (max-width: 37.5em) {
  .slideshow {
    width: calc(100% + 40px);
    height: 16rem;
    left: -1.25rem;
  }
}
.slideshow__item {
  opacity: 0;
  -webkit-transition: 1s;
  transition: 1s;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  border-radius: 1.25rem;
  position: absolute;
}
.slideshow__item.is-active {
  opacity: 1;
}
.cards__header {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
  margin-bottom: 2.5rem;
}
@media print, screen and (max-width: 48em) {
  .cards__header {
    margin-bottom: 1.25rem;
  }
}
.blog-index .cards__header {
  display: none;
}
.cards__header-title {
  margin-bottom: 0;
}
.cards__header-link {
  margin: 0 0 0.625rem auto;
  color: #879099;
}
@media print, screen and (max-width: 37.5em) {
  .cards__header-link {
    display: none;
  }
}
.cards__items {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.cards--center .cards__items {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.cards__item {
  color: #000c2c;
}
.cards__item-category {
  margin-bottom: 0.3125rem;
  font-size: 0.625rem;
  font-weight: 700;
  text-transform: uppercase;
}
.cards__item-author {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 0;
}
.cards__item-author-image {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.5625rem;
  -ms-flex: 0 0 1.5625rem;
  flex: 0 0 1.5625rem;
  height: 1.5625rem;
  border-radius: 50%;
  margin-right: 0.625rem;
}
.cards__item-author-name {
  font-weight: 700;
  color: #879099;
  font-size: 0.625rem;
  text-transform: uppercase;
}
.cards--small .cards__items {
  left: -1.25rem;
  width: calc(100% + 40px);
  position: relative;
}
@media print, screen and (max-width: 37.5em) {
  .cards--small .cards__items {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.cards--small .cards__item {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 15.875rem;
  -ms-flex: 0 0 15.875rem;
  flex: 0 0 15.875rem;
  margin: 1.25rem;
  background-color: #fff;
  border-top: 0;
  border: 0.0625rem solid #e3e3e3;
  border-radius: 1.0625rem;
  overflow: hidden;
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
@media print, screen and (max-width: 80em) {
  .cards--small .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 16.25rem;
    -ms-flex: 0 0 16.25rem;
    flex: 0 0 16.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cards--small .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 18.75rem;
    -ms-flex: 0 0 18.75rem;
    flex: 0 0 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--small .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 calc(50% - 40px);
    -ms-flex: 0 0 calc(50% - 40px);
    flex: 0 0 calc(50% - 40px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--small .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 18.4375rem;
    -ms-flex: 0 0 18.4375rem;
    flex: 0 0 18.4375rem;
    margin: 0.625rem;
    max-width: 100%;
  }
}
.cards--small .cards__item:hover .cards__item-title {
  color: #005ce6;
}
.cards--small .cards__item--cta-module {
  display: block;
}
.cards--small .cards__item--cta-module .cards__item-image-wrapper {
  position: static;
  height: 100%;
}
.cards--small .cards__item--cta-module .cards__item-content {
  display: none;
}
.cards--small .cards__item-image-wrapper {
  width: calc(100% + 2px);
  left: -0.0625rem;
  top: -0.0625rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 8.875rem;
  -ms-flex: 0 0 8.875rem;
  flex: 0 0 8.875rem;
  border-top-left-radius: 1.0625rem;
  border-top-right-radius: 1.0625rem;
  overflow: hidden;
  position: relative;
}
.cards--small .cards__item-image-wrapper--empty {
  background-color: #f8f8f8;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.cards--small .cards__item-image-wrapper--empty .cards__item-image {
  max-width: 30%;
  height: auto;
}
.cards--small .cards__item-image {
  -o-object-fit: cover;
  object-fit: cover;
  width: 100%;
  height: 100%;
}
.cards--small .cards__item-content {
  padding: 1.25rem 1.875rem;
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 100%;
  -ms-flex: 1 1 100%;
  flex: 1 1 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.cards--small .cards__item-category {
  margin-bottom: 0.3125rem;
  color: #879099;
}
.cards--small .cards__item-title {
  font-size: 1rem;
  margin-bottom: 0.9375rem;
}
.cards--small .cards__item-author {
  margin-top: auto;
}
.cards--medium .cards__item {
  margin: 2.5rem 0 0 2.5rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 22rem;
  -ms-flex: 0 0 22rem;
  flex: 0 0 22rem;
}
@media print, screen and (max-width: 80em) {
  .cards--medium .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 16.25rem;
    -ms-flex: 0 0 16.25rem;
    flex: 0 0 16.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cards--medium .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 18.75rem;
    -ms-flex: 0 0 18.75rem;
    flex: 0 0 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--medium .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 14.75rem;
    -ms-flex: 0 0 14.75rem;
    flex: 0 0 14.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--medium .cards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-left: 0;
  }
}
.cards--medium .cards__item:hover {
  color: #005ce6;
}
.cards--medium .cards__item-image-wrapper {
  width: 100%;
  height: 13.4375rem;
  margin-bottom: 1.875rem;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .cards--medium .cards__item-image-wrapper {
    height: 9.875rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cards--medium .cards__item-image-wrapper {
    height: 9.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--medium .cards__item-image-wrapper {
    height: 9.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--medium .cards__item-image-wrapper {
    height: auto;
  }
}
.cards--medium .cards__item-image {
  z-index: 2;
  border-radius: 0.5rem;
  overflow: hidden;
  position: relative;
  vertical-align: top;
}
.cards--medium .cards__item-image-box {
  z-index: 1;
  height: 5.625rem;
  border-radius: 0.5rem;
  position: absolute;
}
.cards--medium .cards__item-image-box--color-red {
  background-color: #ff2638;
}
.cards--medium .cards__item-image-box--color-blue {
  background-color: #005ce6;
}
.cards--medium .cards__item-image-box--color-yellow {
  background-color: #ffc600;
}
.cards--medium .cards__item-image-box--position-vertical-top {
  top: -0.5rem;
}
.cards--medium .cards__item-image-box--position-vertical-bottom {
  bottom: -0.5rem;
}
.cards--medium .cards__item-image-box--position-horizontal-left {
  left: -0.5rem;
}
.cards--medium .cards__item-image-box--position-horizontal-right {
  right: -0.5rem;
}
.cards--medium .cards__item-image-box--position-horizontal-left-center {
  left: 50%;
  -webkit-transform: translateX(-25%);
  -ms-transform: translateX(-25%);
  transform: translateX(-25%);
}
.cards--medium .cards__item-image-box--position-horizontal-center {
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
}
.cards--medium .cards__item-image-box--position-horizontal-right-center {
  right: 50%;
  -webkit-transform: translateX(75%);
  -ms-transform: translateX(75%);
  transform: translateX(75%);
}
.cards--medium .cards__item-category {
  margin-bottom: 0.3125rem;
  font-size: 0.875rem;
  font-weight: 700;
}
.cards__item--color-red .cards--medium .cards__item-category {
  color: #ff2638;
}
.cards__item--color-blue .cards--medium .cards__item-category {
  color: #005ce6;
}
.cards__item--color-yellow .cards--medium .cards__item-category {
  color: #ffc600;
}
.cards--medium .cards__item-title {
  font-size: 1.125rem;
  line-height: 1.38;
}
.cards--large .cards__item {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  height: 22.5rem;
  margin: 0 0 2.5rem;
  border-radius: 1.0625rem;
  border: 0.0625rem solid #e3e3e3;
  background-color: #fff;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 64em) {
  .cards--large .cards__item {
    height: 17.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--large .cards__item {
    height: auto;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.cards--large .cards__item:hover {
  color: inherit;
}
.cards--large .cards__item-image-wrapper {
  height: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 18.375rem;
  -ms-flex: 0 0 18.375rem;
  flex: 0 0 18.375rem;
  background: #e3e3e3;
  overflow: hidden;
}
@media print, screen and (max-width: 64em) {
  .cards--large .cards__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 14.625rem;
    -ms-flex: 0 0 14.625rem;
    flex: 0 0 14.625rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--large .cards__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    height: auto;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--large .cards__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    height: auto;
  }
}
.cards--large .cards__item-image {
  border-radius: 0;
}
.cards--large .cards__item-content {
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 100%;
  -ms-flex: 1 1 100%;
  flex: 1 1 100%;
  padding: 2.5rem 3.75rem;
  border-left: 0;
  max-height: 100%;
}
@media print, screen and (max-width: 64em) {
  .cards--large .cards__item-content {
    padding: 1.5rem 1.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--large .cards__item-content {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 2.8125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--large .cards__item-content {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 1.875rem;
  }
}
.cards--large .cards__item-content .author {
  margin-top: 1.875rem;
}
.cards--large .cards__item-title {
  font-size: 1.5rem;
  line-height: 1.35;
}
.cards--large .cards__item-text {
  margin-top: 0.9375rem;
  font-size: 0.875rem;
  font-weight: 400;
}
.cards--large .cards__item-author {
  margin-top: 1.25rem;
}
.cards--large .cards__item-button {
  margin-top: 1.875rem;
}
@media print, screen and (max-width: 37.5em) {
  .cards--large .cards__item-button {
    width: 100%;
  }
}
.cards--large .cards__item:hover .cards__item-button {
  background-color: #005ce6;
  color: #fff;
}
@media print, screen and (max-width: 48em) {
  .cards--scrollable .cards__items {
    width: 100vw;
    left: -2.5rem;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    overflow: auto;
    position: relative;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  .cards--scrollable .cards__items:after,
  .cards--scrollable .cards__items:before {
    content: "";
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 1rem;
    -ms-flex: 0 0 1rem;
    flex: 0 0 1rem;
    height: 0.0625rem;
  }
}
.cards--careers .cards__item:nth-child(3n + 1) {
  margin-left: 0;
}
@media print, screen and (max-width: 64em) {
  .cards--careers .cards__item:nth-child(3n + 1) {
    margin-left: 2.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--careers .cards__item:nth-child(3n + 1) {
    margin-left: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .cards--careers .cards__item:nth-child(2n + 1) {
    margin-left: 0;
  }
}
@media screen and (min-width: 64em) {
  .cards--careers .cards__item:nth-child(4) {
    display: none;
  }
}
.cards--resources {
  margin-bottom: 1.875rem;
  margin-top: 0;
}
@media screen and (min-width: 64.0625em) {
  .cards--resources {
    margin-top: 12.5rem;
  }
}
@media screen and (min-width: 80em) {
  .cards--resources {
    margin-top: 10.75rem;
  }
}
.cards--blog-featured,
.cards--resources-featured {
  margin: -15.625rem 0 0;
  position: absolute;
  width: 100%;
}
@media print, screen and (max-width: 80em) {
  .cards--blog-featured,
  .cards--resources-featured {
    left: -18.75rem;
    width: 53.75rem;
    margin: -12.5rem 0 0;
    position: absolute;
  }
}
@media print, screen and (max-width: 64em) {
  .cards--blog-featured,
  .cards--resources-featured {
    left: 0;
    width: 100%;
    margin: -10.625rem 0 0;
    position: relative;
  }
}
@media print, screen and (max-width: 48em) {
  .cards--blog-featured,
  .cards--resources-featured {
    margin: -7.5rem 0 0;
  }
}
.cards--blog-featured .cards__item-image,
.cards--resources-featured .cards__item-image {
  height: auto;
  width: 100%;
  max-width: none;
}
@media screen and (min-width: 48em) {
  .cards--blog-featured .cards__item-image,
  .cards--resources-featured .cards__item-image {
    height: 100%;
    width: auto;
  }
}
@media screen and (min-width: 48em) {
  .cards--blog-featured__blog .cards__item-text,
  .cards--resources-featured__blog .cards__item-text {
    display: none;
  }
}
@media screen and (min-width: 64em) {
  .cards--blog-featured__blog .cards__item-text,
  .cards--resources-featured__blog .cards__item-text {
    display: block;
  }
}
.cards--blog-featured__noimage .cards__item-image-wrapper,
.cards--resources-featured__noimage .cards__item-image-wrapper {
  display: none;
}
.cards--blog-featured__noimage .cards__item-content,
.cards--resources-featured__noimage .cards__item-content {
  border-left: 0.0625rem solid #e3e3e3;
  border-top-left-radius: 1.0625rem;
  border-bottom-left-radius: 1.0625rem;
}
.cards--blog {
  margin-top: 2rem;
}
@media screen and (min-width: 64em) {
  .cards--blog {
    margin-top: 4rem;
  }
}
@media screen and (min-width: 80em) {
  .cards--blog .cards__header {
    margin-left: 9.375rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .cards--blog .cards__header-title {
    margin: auto;
  }
}
.search-form-wrapper {
  position: relative;
}
.search-form {
  height: 3.75rem;
  border: 0.0625rem solid rgba(0, 0, 0, 0.1);
  border-radius: 0.9375rem;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.search-form--blog,
.search-form--customers,
.search-form--resources {
  margin: 0 0 2rem;
  background-color: #fff;
}
.search-form__icon {
  padding: 1.25rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 3.75rem;
  -ms-flex: 0 0 3.75rem;
  flex: 0 0 3.75rem;
  height: 100%;
  position: relative;
}
@media screen and (min-width: 64.0625em) {
  .search-form__icon {
    padding: 0;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 2.75rem;
    -ms-flex: 0 0 2.75rem;
    flex: 0 0 2.75rem;
  }
}
.search-form__icon svg {
  height: auto;
  fill: #999eab;
}
.search-form__icon--hamburger {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .search-form__icon--hamburger {
    display: block;
  }
}
.search-form__icon--hamburger:after {
  content: "";
  right: 0;
  top: 50%;
  height: 1.25rem;
  width: 0.0625rem;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
  background-color: rgba(0, 0, 0, 0.1);
  position: absolute;
}
.search-form__icon--customers {
  display: none;
}
@media print, screen and (max-width: 48em) {
  .search-form__icon--customers {
    display: block;
  }
}
.search-form__input {
  border: 0;
  margin: 0;
  height: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  padding: 0 1.25rem;
  color: #000c2c;
  max-width: calc(100% - 60px);
}
@media print, screen and (max-width: 64em) {
  .search-form__input {
    max-width: calc(100% - 120px);
  }
}
.search-form__input:active,
.search-form__input:focus {
  border: 0;
}
.search-form__input::-webkit-search-cancel-button {
  cursor: pointer;
}
.perks {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.perks__item {
  width: 33.3%;
  padding: 0 2.5rem;
  text-align: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
@media print, screen and (max-width: 48em) {
  .perks__item:first-child {
    margin-top: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .perks__item {
    padding: 0 1.25rem;
  }
}
@media print, screen and (max-width: 48em) {
  .perks__item {
    padding: 0;
    width: 100%;
    margin-top: 5.625rem;
  }
}
.perks__image-wrapper {
  width: 2.5rem;
  height: 2.5rem;
  margin-bottom: 1.25rem;
  border-radius: 50%;
  display: inline-block;
  overflow: hidden;
}
.perks--home .perks__image-wrapper {
  width: 10.9375rem;
  height: 10.9375rem;
  padding: 3.125rem;
  margin-bottom: 3.125rem;
  border: 2px solid rgba(0, 0, 0, 0.03);
}
@media print, screen and (max-width: 64em) {
  .perks--home .perks__image-wrapper {
    width: 7.5rem;
    height: 7.5rem;
    padding: 2.1875rem;
    margin-bottom: 2.1875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .perks--home .perks__image-wrapper {
    margin-bottom: 1.25rem;
  }
}
.perks__image-wrapper img {
  width: 100%;
}
.perks--product .perks__image-wrapper {
  height: auto;
  width: 100%;
  -webkit-box-ordinal-group: 6;
  -webkit-order: 5;
  -ms-flex-order: 5;
  order: 5;
  margin: 2.5rem 0 0;
  border-radius: 0;
}
.perks--product .perks__image-wrapper img {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 6.25rem;
}
.perks__content {
  width: 100%;
}
.perks__title {
  width: 100%;
  margin: 0 0 1.25rem;
  font-size: 1.375rem;
  line-height: 1.2;
}
@media print, screen and (max-width: 64em) {
  .perks__title {
    font-size: 1.125rem;
  }
}
.perks--product .perks__title {
  font-size: 1.5rem;
}
@media print, screen and (max-width: 64em) {
  .perks--product .perks__title {
    font-size: 1.375rem;
  }
}
.perks__text {
  width: 100%;
}
@media print, screen and (max-width: 64em) {
  .perks__text {
    font-size: 1rem;
  }
}
.nav-product {
  width: 100%;
  max-width: 35.5rem;
  margin: 0 auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.nav-product__item {
  padding: 1.25rem;
  width: calc(50% - 20px);
  margin: 0.625rem;
  border-radius: 0.625rem;
  background-color: #fafafb;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 48em) {
  .nav-product__item {
    width: 100%;
    margin: 0.625rem 0;
  }
}
.nav-product__item:hover {
  background-color: #f8f8f8;
}
.nav-product__item--highlight {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  padding: 2.5rem;
  width: 100%;
}
@media print, screen and (max-width: 48em) {
  .nav-product__item--highlight {
    padding: 1.25rem;
  }
}
.nav-product__item-content {
  font-size: 1rem;
  color: #879099;
}
.nav-product__item--highlight .nav-product__item-content:before {
  content: "Continue to";
  display: block;
  text-transform: uppercase;
  width: 100%;
  font-weight: 700;
  margin-bottom: 0.3125rem;
  font-size: 0.625rem;
  letter-spacing: 0.03125rem;
  color: #879099;
}
.nav-product__item-title {
  font-size: 1rem;
  color: #879099;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.nav-product__item:hover .nav-product__item-title {
  color: #000c2c;
}
.nav-product__item--highlight .nav-product__item-title {
  font-size: 1.375rem;
  color: #000c2c;
}
.nav-product__item-icon {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.875rem;
  -ms-flex: 0 0 1.875rem;
  flex: 0 0 1.875rem;
  height: 1.875rem;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  margin-left: auto;
  margin-right: 0.625rem;
  position: relative;
}
.nav-product__item--highlight .nav-product__item-icon {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 3.125rem;
  -ms-flex: 0 0 3.125rem;
  flex: 0 0 3.125rem;
  height: 3.125rem;
}
@media print, screen and (max-width: 48em) {
  .nav-product__item--highlight .nav-product__item-icon {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 1.875rem;
    -ms-flex: 0 0 1.875rem;
    flex: 0 0 1.875rem;
    height: 1.875rem;
  }
}
.nav-product__item-icon-image {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  position: absolute;
}
.nav-product__item-icon-image:nth-child(2),
.nav-product__item:hover .nav-product__item-icon-image:nth-child(1) {
  opacity: 0;
}
.nav-product__item:hover .nav-product__item-icon-image:nth-child(2) {
  opacity: 1;
}
.media-text {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
.media-text--layout-text-left,
.media-text--layout-text-right {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.media-text--layout-text-bottom,
.media-text--layout-text-top {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.media-text__block {
  color: #879099;
  position: relative;
}
.media-text--layout-text-left .media-text__block {
  width: 50%;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-left .media-text__block {
    width: 100%;
  }
}
.media-text--layout-text-left .media-text__block--media {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-left .media-text__block--media {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    margin-bottom: 1.875rem;
  }
}
.media-text--layout-text-left .media-text__block--text {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  padding: 0 6.25rem;
}
@media print, screen and (max-width: 80em) {
  .media-text--layout-text-left .media-text__block--text {
    padding: 0 3.125rem 0 0;
  }
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-left .media-text__block--text {
    padding: 0;
    text-align: center;
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
}
.media-text--layout-text-right .media-text__block {
  width: 50%;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-right .media-text__block {
    width: 100%;
  }
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-right .media-text__block--media {
    margin-bottom: 1.875rem;
  }
}
.media-text--layout-text-right .media-text__block--text {
  padding: 0 6.25rem;
}
@media print, screen and (max-width: 80em) {
  .media-text--layout-text-right .media-text__block--text {
    padding: 0 0 0 3.125rem;
  }
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-right .media-text__block--text {
    padding: 0;
    text-align: center;
  }
}
.media-text--layout-text-top .media-text__block {
  width: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: center;
}
.media-text--layout-text-top .media-text__block--media {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-top .media-text__block--media {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    margin-bottom: 1.875rem;
  }
}
.media-text--layout-text-top .media-text__block--text {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  margin-bottom: 4.375rem;
  max-width: 34.25rem;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-top .media-text__block--text {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    margin: 0;
  }
}
.media-text--layout-text-bottom .media-text__block {
  width: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: center;
}
.media-text--layout-text-bottom .media-text__block--media {
  margin-bottom: 4.375rem;
}
@media print, screen and (max-width: 48em) {
  .media-text--layout-text-bottom .media-text__block--media {
    margin-bottom: 1.875rem;
  }
}
.media-text--layout-text-bottom .media-text__block--text {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  max-width: 34.25rem;
}
.media-text__media-wrapper {
  text-align: center;
}
.media-text--layout-text-bottom .media-text__media-wrapper,
.media-text--layout-text-top .media-text__media-wrapper {
  width: 100vw;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .media-text--layout-text-bottom .media-text__media-wrapper,
  .media-text--layout-text-top .media-text__media-wrapper {
    width: calc(100vw - 40px);
  }
}
.media-text__image {
  max-width: 100%;
}
.media-text__title {
  margin-bottom: 1.875rem;
  color: #000c2c;
}
.newsletter-subscription {
  padding: 3.75rem;
  border-radius: 1.25rem;
  background-color: #fafafb;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .newsletter-subscription {
    padding: 2.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .newsletter-subscription {
    padding: 2.5rem 1.25rem;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.newsletter-subscription .mktoForm .mktoField {
  background-color: transparent;
}
.blog-article .newsletter-subscription {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  max-width: 85%;
  margin-top: 2rem;
  margin-bottom: 2rem;
  margin-left: auto;
  margin-right: auto;
}
.newsletter-subscription__background {
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -45%);
  -ms-transform: translate(-50%, -45%);
  transform: translate(-50%, -45%);
  position: absolute;
  pointer-events: none;
}
.blog-article .newsletter-subscription__background {
  left: 0;
  top: 0;
  -webkit-transform: none;
  -ms-transform: none;
  transform: none;
  height: 100%;
}
.newsletter-subscription__background svg {
  width: auto;
  height: auto;
}
.blog-article .newsletter-subscription__background svg {
  height: 100%;
}
.newsletter-subscription__title {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  margin: 0;
  font-size: 1.5rem;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .newsletter-subscription__title {
    font-size: 1.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .newsletter-subscription__title {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-bottom: 1.875rem;
    text-align: center;
  }
}
.blog-article .newsletter-subscription__title {
  font-weight: 600;
  font-size: 1.375rem;
  line-height: 1.875rem;
  margin: 0;
}
.newsletter-subscription__title u {
  text-decoration: none;
  position: relative;
}
.newsletter-subscription__title u:before {
  content: "";
  position: absolute;
  background-color: #ffc600;
  height: 0.25rem;
  border-radius: 0.125rem;
  width: 106%;
  left: -3%;
  bottom: -0.125rem;
}
@media print, screen and (max-width: 64em) {
  .newsletter-subscription__title br {
    display: none;
  }
}
.newsletter-subscription__form-wrapper {
  position: relative;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  padding-left: 4.375rem;
}
@media print, screen and (max-width: 80em) {
  .newsletter-subscription__form-wrapper {
    padding-left: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .newsletter-subscription__form-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.blog-article .newsletter-subscription__form-wrapper {
  padding-left: 2rem;
}
@media print, screen and (max-width: 80em) {
  .blog-article .newsletter-subscription__form-wrapper {
    padding-left: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .blog-article .newsletter-subscription__form-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.subscription-form {
  width: 100%;
  padding: 0 6.25rem;
  border-radius: 1.25rem;
  background-color: #fff;
  -webkit-box-shadow: 0 20px 25px rgba(63, 71, 79, 0.1);
  box-shadow: 0 20px 25px rgba(63, 71, 79, 0.1);
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 80em) {
  .subscription-form {
    padding: 0 3.125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .subscription-form {
    padding: 1.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .subscription-form {
    padding: 1.25rem;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.subscription-form__image-wrapper {
  max-width: 18.75rem;
  margin: -1.5625rem 4.375rem -1.5625rem 0;
}
@media print, screen and (max-width: 80em) {
  .subscription-form__image-wrapper {
    max-width: 16.875rem;
    margin-right: 3.125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .subscription-form__image-wrapper {
    margin: 0 1.875rem 0 0;
  }
}
@media print, screen and (max-width: 48em) {
  .subscription-form__image-wrapper {
    margin: 0 auto 1.875rem;
  }
}
.subscription-form__title {
  margin-bottom: 1.5625rem;
}
@media print, screen and (max-width: 80em) {
  .subscription-form__title {
    font-size: 1.25rem;
  }
}
.summit-videos {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  margin: 0 auto;
  max-width: 55rem;
  width: 100%;
}
.summit-videos__item {
  width: 25rem;
  margin: 1.25rem;
}
@media print, screen and (max-width: 80em) {
  .summit-videos__item {
    width: 24.375rem;
  }
}
@media print, screen and (max-width: 64em) {
  .summit-videos__item {
    width: calc(50% - 40px);
  }
}
@media print, screen and (max-width: 64em) {
  .summit-videos__item {
    width: 100%;
    margin: 1.25rem 0;
  }
}
.summit-videos__image-wrapper {
  height: 0;
  width: 100%;
  border-radius: 0.625rem;
  padding-top: 55.65%;
  margin-bottom: 0.625rem;
  position: relative;
  overflow: hidden;
  display: block;
}
.summit-videos__image {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  -o-object-position: 50% 50%;
  object-position: 50% 50%;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  -o-object-fit: cover;
  object-fit: cover;
  position: absolute;
}
.summit-videos__item:hover .summit-videos__image {
  -webkit-transform: scale(1.1);
  -ms-transform: scale(1.1);
  transform: scale(1.1);
}
.summit-videos__content {
  padding: 0.625rem;
}
.summit-videos__title {
  display: block;
  font-size: 1.125rem;
  margin-bottom: 0.625rem;
  font-weight: 700;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  color: #000c2c;
}
.summit-videos__item:hover .summit-videos__title {
  color: #005ce6;
}
.summit-videos__info {
  font-size: 0.6875rem;
  margin-bottom: 0.625rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.summit-videos__info-item {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.summit-videos__info-item--duration {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 4.375rem;
  -ms-flex: 0 0 4.375rem;
  flex: 0 0 4.375rem;
  font-weight: 700;
}
.summit-videos__info-icon {
  margin: 0.125rem 0;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 0.75rem;
  -ms-flex: 0 0 0.75rem;
  flex: 0 0 0.75rem;
  height: 0.75rem;
  margin-right: 0.625rem;
}
.summit-videos__text {
  font-size: 0.8125rem;
  line-height: 1.4;
  color: #879099;
}
.summit-videos__text > :first-child {
  margin-top: 0;
}
.summit-videos__text > :last-child {
  margin-bottom: 0;
}
.roadmap_templates__title {
  font-weight: 600;
  font-size: 3rem;
  line-height: 3.625rem;
  text-align: center;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin: auto;
  margin-bottom: 2rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__title {
    max-width: 560px;
  }
}
.roadmap_templates__subtitle {
  font-size: 1.5rem;
  line-height: 1.9375rem;
  text-align: center;
  letter-spacing: -0.435px;
  color: #7e8494;
  margin: auto;
  margin-bottom: 5.3125rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__subtitle {
    max-width: 550px;
  }
}
.roadmap_templates__items {
  max-width: 940px;
  margin: auto;
}
.roadmap_templates__item {
  padding: 0;
  margin-bottom: 2.5rem;
  position: relative;
  top: 0;
  -webkit-transition: top 0.3s ease 0s;
  transition: top 0.3s ease 0s;
  cursor: pointer;
  border-radius: 16px;
  -webkit-box-shadow: 0 8px 32px rgba(63, 71, 79, 0.08);
  box-shadow: 0 8px 32px rgba(63, 71, 79, 0.08);
  width: auto;
  max-width: 100%;
}
@media print, screen and (max-width: 48.06125em) {
  .roadmap_templates__item {
    margin: 0 auto 2.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item {
    width: 47%;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:hover {
    top: -10px;
    -webkit-box-shadow: 0 20px 32px rgba(63, 71, 79, 0.1);
    box-shadow: 0 20px 32px rgba(63, 71, 79, 0.1);
  }
}
.roadmap_templates__item[data-is-hidden] {
  position: absolute;
  -webkit-transform: scaleY(0);
  -ms-transform: scaleY(0);
  transform: scaleY(0);
  -webkit-transition: -webkit-transform 0.4s ease 0s;
  transition: -webkit-transform 0.4s ease 0s;
  transition: transform 0.4s ease 0s;
  transition: transform 0.4s ease 0s, -webkit-transform 0.4s ease 0s;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:nth-child(odd) {
    margin-right: 0.625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap_templates__item:nth-child(odd) {
    margin-right: 1.25rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:nth-child(even) {
    margin-left: 0.625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap_templates__item:nth-child(even) {
    margin-left: 1.25rem;
  }
}
.roadmap_templates__item--image-wrapper {
  overflow: hidden;
}
.roadmap_templates__item--image {
  position: relative;
  display: block;
  overflow: hidden;
  max-width: 450px;
  max-height: 256px;
  margin: auto;
  border: none;
  border-radius: 16px 16px 0 0;
  padding: 24px 24px 0;
  background-color: pink;
  cursor: pointer;
}
.roadmap_templates__item--image img {
  width: 100%;
  height: auto;
  background: #fafafb;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 10px 10px 0 0;
  -webkit-transform-origin: center;
  -ms-transform-origin: center;
  transform-origin: center;
  -webkit-transition: visibility 0.25s ease-in, -webkit-transform 0.25s;
  transition: visibility 0.25s ease-in, -webkit-transform 0.25s;
  transition: transform 0.25s, visibility 0.25s ease-in;
  transition: transform 0.25s, visibility 0.25s ease-in, -webkit-transform 0.25s;
}
.roadmap_templates__item--content {
  position: relative;
  display: block;
  margin: auto;
  max-width: 450px;
  padding: 1.5rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item--content {
    margin: 0;
  }
}
.roadmap_templates__item--title {
  font-weight: 600;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  color: #000c2c;
  font-style: normal;
  font-weight: 600;
  margin-bottom: 0.75rem;
  cursor: pointer;
  -webkit-transition: 0.3s;
  transition: 0.3s;
}
.roadmap_templates__item--text {
  font-size: 1rem;
  line-height: 1.5rem;
  color: #5f677b;
  font-style: normal;
  font-weight: 400;
  margin-bottom: 1.5rem;
}
.roadmap_templates__item--link {
  font-size: 0.875rem;
  line-height: 1.1875rem;
  color: #0079f2;
  font-style: normal;
  font-weight: 400;
  cursor: pointer;
}
.roadmap_templates__cta {
  padding-top: 0;
  display: block;
}
.roadmap_templates__cta[data-is-hidden] {
  display: none;
}
.roadmap_templates__explore {
  color: #000c2c;
  background: #f8f8f8;
  border-radius: 14.8465px;
  font-weight: 600;
  font-size: 1rem;
  line-height: 1.375rem;
  text-align: center;
  padding: 0.875rem 3.40625rem;
  margin: auto;
  max-width: 273px;
  display: block;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__explore {
    margin-top: 3.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__explore {
    margin-top: 3.5rem;
  }
}
.roadmap_templates__explore:hover {
  color: #000c2c;
  background: #e3e3e3;
}
.roadmap-usage--wrapper {
  -webkit-box-align: baseline;
  -webkit-align-items: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
}
@media print, screen and (max-width: 64em) {
  .roadmap-usage--wrapper {
    text-align: center;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap-usage--wrapper {
    padding: 0 116px;
  }
}
@media print, screen and (max-width: 64em) {
  .roadmap-usage--parent {
    margin: auto;
    margin-bottom: 2rem;
  }
}
.roadmap-usage--title {
  margin-bottom: 3rem;
}
.roadmap-usage--content {
  font-style: normal;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  color: #666d80;
  padding: 3.625rem;
}
@media print, screen and (max-width: 64.06125em) {
  .roadmap-usage--content {
    width: 100%;
    text-align: center;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap-usage--content {
    width: 309px;
  }
}
.roadmap-usage--content-block {
  min-width: 11.125rem;
  margin-bottom: 1.5rem;
}
.roadmap-usage--content-block:last-of-type {
  margin-bottom: 0;
}
.roadmap-usage--content-gray-box-title {
  font-style: normal;
  font-weight: 600;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #202428;
}
.roadmap-usage--content-gray-box-text {
  font-style: normal;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #666d80;
}
.roadmap-usage--content-text {
  max-width: 440px;
  margin-bottom: 2rem;
}
@media print, screen and (max-width: 64em) {
  .roadmap-usage--content-text {
    max-width: 80%;
    margin-left: auto;
    margin-right: auto;
  }
}
.roadmap-usage--content-text:last-of-type {
  margin-bottom: 3rem;
}
.roadmap-usage--content-text__title p {
  margin-bottom: 0.5rem;
}
.roadmap-usage--content-text__copy {
  color: #666d80;
}
.carousel-awards__items {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
  -webkit-justify-content: space-around;
  -ms-flex-pack: distribute;
  justify-content: space-around;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__items {
    width: 100vw;
    left: 50%;
    -webkit-transform: translateX(-50%);
    -ms-transform: translateX(-50%);
    transform: translateX(-50%);
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    overflow: auto;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-scroll-snap-type: x mandatory;
    -ms-scroll-snap-type: x mandatory;
    scroll-snap-type: x mandatory;
  }
}
.carousel-awards__items:after,
.carousel-awards__items:before {
  content: "";
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1px;
  -ms-flex: 0 0 1px;
  flex: 0 0 1px;
  height: 100px;
  display: none;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__items:after,
  .carousel-awards__items:before {
    display: block;
  }
}
.carousel-awards__item {
  padding: 0 1.25rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 15.875rem;
  -ms-flex: 0 0 15.875rem;
  flex: 0 0 15.875rem;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  text-align: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 55%;
    -ms-flex: 0 0 55%;
    flex: 0 0 55%;
    scroll-snap-align: center;
  }
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item:nth-child(1) {
    margin-left: 22.5%;
  }
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item:nth-last-child(1) {
    margin-right: 22.5%;
  }
}
@media print, screen and (max-width: 80em) {
  .carousel-awards__item:nth-child(n + 4) {
    margin-top: 2.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item:nth-child(n + 4) {
    margin-top: 0;
  }
}
.carousel-awards__item:nth-child(n + 5) {
  margin-top: 2.5rem;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item:nth-child(n + 5) {
    margin-top: 0;
  }
}
.carousel-awards__item-image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  width: 100%;
  height: 8.125rem;
  position: relative;
  overflow: hidden;
}
.carousel-awards__item-image {
  width: 100%;
  height: 100%;
  -o-object-fit: contain;
  object-fit: contain;
  -o-object-position: 50% 50%;
  object-position: 50% 50%;
}
.carousel-awards__item-text {
  max-width: 15.875rem;
  font-size: 0.875rem;
  margin-top: 1.875rem;
  color: #666d80;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__item-text {
    display: none;
  }
}
.carousel-awards__item-text > :first-child {
  margin-top: 0;
}
.carousel-awards__item-text > :last-child {
  margin-bottom: 0;
}
.carousel-awards__texts {
  width: 100%;
  min-height: 5.625rem;
  margin-top: 1.875rem;
  position: relative;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .carousel-awards__texts {
    display: block;
  }
}
.carousel-awards__text {
  width: 15.875rem;
  font-size: 0.875rem;
  -webkit-transition: 0.1s;
  transition: 0.1s;
  opacity: 0;
  top: 0;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  position: absolute;
  color: #666d80;
  text-align: center;
}
.carousel-awards__text.is-active {
  opacity: 1;
  -webkit-transition: 0.1s 0.1s;
  transition: 0.1s 0.1s;
  position: relative;
}
.carousel-awards__text > :first-child {
  margin-top: 0;
}
.carousel-awards__text > :last-child {
  margin-bottom: 0;
}
.blog-index.cards--blog {
  margin-top: 0;
}
@media screen and (min-width: 64.0625em) {
  .blog-index.cards--blog {
    margin-top: 12.5rem;
  }
}
@media screen and (min-width: 80em) {
  .blog-index.cards--blog {
    margin-top: 9.375rem;
  }
}
.blog-archive__sidebar,
.blog-home__sidebar {
  display: none;
  margin-top: 0;
}
@media screen and (min-width: 64.0625em) {
  .blog-archive__sidebar,
  .blog-home__sidebar {
    display: block;
    margin-top: 13.75rem;
  }
}
@media screen and (min-width: 80em) {
  .blog-archive__sidebar,
  .blog-home__sidebar {
    margin-top: 10.625rem;
  }
}
.blog-archive__sidebar--static,
.blog-home__sidebar--static {
  position: relative;
}
.layout--sidebar .blog-archive__sidebar .layout__block,
.layout--sidebar .blog-home__sidebar .layout__block {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
}
@media screen and (min-width: 64em) {
  .layout--sidebar .blog-archive__sidebar .layout__block,
  .layout--sidebar .blog-home__sidebar .layout__block {
    top: 8rem;
  }
}
@media screen and (min-width: 64em) {
  .blog-archive__sidebar {
    margin-top: 0;
  }
}
.blog-archive__main {
  margin-left: auto;
  margin-right: auto;
}
@media screen and (min-width: 64em) {
  .blog-archive__main {
    padding-left: 2rem;
  }
}
@media screen and (min-width: 64.0625em) {
  .layout__block--main .search-form-wrapper {
    display: none;
  }
}
.blog-article {
  margin-top: 12.5rem;
  padding: 0 11.25rem 0 17.5rem;
  position: relative;
}
@media (max-height: 1000px) and (min-width: 1025px) {
  .blog-article {
    margin-top: 8.75rem;
  }
}
@media print, screen and (max-width: 80em) {
  .blog-article {
    padding: 0 6.25rem;
  }
}
@media print, screen and (max-width: 64em) {
  .blog-article {
    padding: 0;
    margin-top: 6.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .blog-article {
    padding: 0;
    margin-top: 5rem;
  }
}
@media screen and (min-width: 64em) {
  .blog-article--has-sidebar .blog-article {
    padding: 0 0 0 3rem;
    width: 80%;
  }
}
@media screen and (min-width: 64em) {
  .blog-article--has-sidebar .blog-article__container {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.blog-article__thumbnail {
  margin-bottom: 3.75rem;
  border-radius: 0.625rem;
}
.blog-article__sidebar {
  display: none;
}
@media screen and (min-width: 64em) {
  .blog-article--has-sidebar .blog-article__sidebar {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    margin-top: 12.5rem;
    max-width: 16.25rem;
    min-height: 15.625rem;
  }
}
.blog-article--has-sidebar .blog-article__sidebar .menu--taxonomy li a {
  white-space: nowrap;
}
.blog-article__share-wrapper {
  left: 6.25rem;
  top: 0;
  height: 100%;
  position: absolute;
  margin: 2rem auto;
}
@media screen and (min-width: 80em) {
  .blog-article__share-wrapper {
    left: 0;
    margin-left: auto;
    position: relative;
  }
}
@media print, screen and (max-width: 80em) {
  .blog-article__share-wrapper {
    left: 0;
    margin-left: auto;
    position: relative;
  }
}
@media print, screen and (max-width: 37.5em) {
  .blog-article__share-wrapper {
    margin: 0.9375rem auto 0 0;
  }
}
@media screen and (min-width: 64em) {
  .blog-article--has-sidebar .blog-article__share-wrapper {
    display: none;
  }
}
.blog-article__sidebar .blog-article__share-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  position: relative;
  top: 0;
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .blog-article__sidebar .blog-article__share-wrapper {
    left: 0;
    margin-left: auto;
    position: relative;
  }
}
@media print, screen and (max-width: 37.5em) {
  .blog-article__sidebar .blog-article__share-wrapper {
    margin: 0.9375rem auto 0 0;
  }
}
.blog-article__sidebar .blog-article__share-wrapper--marketo-cta {
  top: 4rem;
  margin-bottom: 6rem;
}
.blog-article__sidebar .blog-article__share-wrapper--30 {
  height: 30%;
}
.blog-article__sidebar .blog-article__share-wrapper--50 {
  height: 50%;
}
.blog-article__sidebar .blog-article__share-wrapper--100 {
  height: 100%;
}
.blog-article__share {
  padding: 0;
  position: relative;
  top: 0;
}
@media print, screen and (max-width: 64em) {
  .blog-article__share {
    margin: 0;
  }
}
@media screen and (min-width: 64em) {
  .blog-article--has-sidebar .blog-article__share {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
.blog-article__author {
  color: #7e8494;
  font-size: 0.75rem;
  margin: 1.875rem 0 3.75rem;
  font-weight: 700;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  text-transform: uppercase;
}
@media print, screen and (max-width: 64em) {
  .blog-article__author {
    font-size: 0.6875rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .blog-article__author {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.blog-article__author-image-wrapper {
  margin-right: 0.9375rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.625rem;
  -ms-flex: 0 0 1.625rem;
  flex: 0 0 1.625rem;
  height: 1.625rem;
  border-radius: 50%;
  -o-object-fit: cover;
  object-fit: cover;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .blog-article__author-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 2.25rem;
    -ms-flex: 0 0 2.25rem;
    flex: 0 0 2.25rem;
    height: 2.25rem;
  }
}
.blog-article__author-image {
  width: 100%;
  height: 100%;
}
.blog-article__author-info {
  line-height: 1;
}
@media print, screen and (max-width: 64em) {
  .blog-article__author-info {
    line-height: 1.3;
    height: 100%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
}
@media print, screen and (max-width: 37.5em) {
  .blog-article__author-info {
    -webkit-box-flex: 1;
    -webkit-flex: 1 1 auto;
    -ms-flex: 1 1 auto;
    flex: 1 1 auto;
    max-width: calc(100% - 51px);
  }
}
.blog-article__author-info-name {
  margin-right: 2.5rem;
}
@media print, screen and (max-width: 64em) {
  .blog-article__author-info-name {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 0;
  }
}
.blog-article__author-info-date {
  margin-right: 2.5rem;
}
@media print, screen and (max-width: 64em) {
  .blog-article__author-info-date {
    margin-right: 0.625rem;
    opacity: 0.6;
  }
}
@media print, screen and (max-width: 64em) {
  .blog-article__author-info-categories {
    opacity: 0.6;
  }
}
.sidebar-widget__image {
  margin: 0 auto 2rem;
}
.layout__block--sticky_marketo-cta .sidebar-widget__image {
  margin: -2rem auto 2rem;
}
.sidebar-widget__title {
  display: block;
  font-size: 1.25rem;
  line-height: 1.1875rem;
  font-weight: 600;
  letter-spacing: -0.03125rem;
  color: #000c2c;
  margin-bottom: 2rem;
}
.blog-article__share-wrapper--marketo-inline .sidebar-widget__title {
  padding: 2rem 1rem 0;
  margin-bottom: 0;
}
.sidebar-widget__button {
  margin-bottom: 0;
}
.sidebar-widget__marketo.mktoForm {
  min-width: auto;
  background: 0 0;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.sidebar-widget__marketo.mktoForm .mktoFieldWrap {
  width: auto;
  min-width: auto;
}
.sidebar-widget__marketo.mktoForm .mktoFieldWrap.checkboxed .mktoLabel {
  font-size: 0.5625rem;
}
.sidebar-widget__marketo.mktoForm .mktoField {
  background: 0 0;
}
.sidebar-widget__marketo.mktoForm
  .mktoField.mktoEmailField::-webkit-input-placeholder {
  opacity: 0;
}
.sidebar-widget__marketo.mktoForm .mktoField.mktoEmailField::-moz-placeholder {
  opacity: 0;
}
.sidebar-widget__marketo.mktoForm
  .mktoField.mktoEmailField:-ms-input-placeholder {
  opacity: 0;
}
.sidebar-widget__marketo.mktoForm
  .mktoField.mktoEmailField::-ms-input-placeholder {
  opacity: 0;
}
.sidebar-widget__marketo.mktoForm .mktoField.mktoEmailField::placeholder {
  opacity: 0;
}
.sidebar-widget__marketo.mktoForm .mktoLabel {
  background-color: transparent;
}
@font-face {
  font-family: TablePress;
  src: url(data:application/font-woff2;charset=utf-8;base64,d09GMgABAAAAAAPUAA0AAAAACZAAAAN+AAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP0ZGVE0cGh4GYACCUhEICoQIgnILFgABNgIkAygEIAWGcgeBARv6B8iuBzK53oAhKg2KWDsrezjalSefocfD9/uZ575PSbYEqJHAIdo6tMDGdCprFIHd+F9r+rZE46O2iHBJfoAuxwW0yfgKS8KGVFE4dHX1gPmgVhzwhcJbReQ9RWXcraeutbmNHE7T7B1sex8stfMfnkvv0XsgUZrYO1hirXme9TnUkBvQ22RGX50VAr48H54Cn9b8GD73edAAhjboBpIQ6kKOhCz7GA8V5HfzyeA6h0mnrFTJnPjxC7KCrl9caqIUg0EAYACGDBn6YGCxeIE+EkwANTWJX/brZpNfyE5o/7r9uPZjS4tESbCTExLCjxOEbxGi2dQeNEAXUMMlvADkqSV0IHXtkQXNOnI2ctJpRIPt8+HjNivx3rlQYA8FqGwdCxF2aZrdJluMnaqFvy+yngVKbBcn0fSOd1xTpnW4HTkptV8Gi2kvCeUHC0BD+D0VKMIqXniZPJyPya9D7gT6DvUpwJER6avgKDsOfW9jU+YGc/ng6MhA3VSar3NdtvrD9WHZurKVKYOi0RwlY9500YSuWDE084F+jMinu4sTudD5yBTTozA9Horpmb+M3TwIBHempnzdpu1/raWypX0JND/ki4p71CQQlFqnAvkijABrVFIq5BdNJbFncoBOF03/h3IINPQRBxJCYDoAOnkRIDR0w0BSmYiBzDinAuQ6eROg0DEGY6DUiEUYqKyILwFq2qS9GKhrpFsykdeFLmDjknYG4jKbNeNyQ1zhCoP840pdYiqu8jTW4mp6pMXH1HVJp8wRmHmQKTKiUOBVSMHrlKuBlYidxkMgw6/bMoG5RD6qfs8yO8LVqFCFa8ELrcVLEqTaS7UG5aqVq1GlWi28k3rRgCjbiU+qqOItvDEqXjkvwF/dUF595jB8LSqqgwIWAWsRmcJJ5GsHbYUqVbirBi5IpRMxLso/i2oSA6ZYDoMFCiknI7ZkGacSVYUjlLSXyG8n08nOQcXTeyzU5ozbiGRQZRt0vu/TMoEV8RLI3DiBSiVzMtNKAPgErlwLoqiAY2fJ9UbRMU/0rz38UP5FQtH3i8V3KYSHYJdSYRnwW8XazUAUop3gQY19hkEH98OA2QQ6wg0S+FjtwOwdOvF5J2VXBBLQmo2EAxsIKVJkkUcRZVRRa7NrP+my6Ns8cKszHYJf+fPPLPTq5vFcmYKZNL+fn1CZDgoYecKZHwA=)
      format("woff2"),
    url(tablepress.woff) format("woff");
  font-weight: 400;
  font-style: normal;
  font-display: block;
}
.tablepress-table-description {
  clear: both;
  display: block;
}
.tablepress {
  border-collapse: collapse;
  border-spacing: 0;
  width: 100%;
  margin-bottom: 1em;
  border: none;
  font-size: 0.9em;
}
.tablepress td,
.tablepress th {
  padding: 8px;
  border: none;
  background: 0 0;
  text-align: left;
  float: none !important;
}
.tablepress tbody td {
  vertical-align: top;
}
.tablepress tbody td,
.tablepress tfoot th {
  border-top: 1px solid #ddd;
}
.tablepress tbody tr:first-child td {
  border-top: 0;
}
.tablepress thead th {
  border-bottom: 1px solid #ddd;
}
.tablepress tfoot th,
.tablepress thead th {
  background-color: #d9edf7;
  font-weight: 700;
  vertical-align: middle;
}
.tablepress .odd td {
  background-color: #f9f9f9;
}
.tablepress .even td {
  background-color: #fff;
}
.tablepress .row-hover tr:hover td {
  background-color: #f3f3f3;
}
.tablepress img {
  margin: 0;
  padding: 0;
  border: none;
  max-width: none;
}
.dataTables_wrapper {
  clear: both;
  margin-bottom: 1em;
}
.dataTables_wrapper .tablepress {
  clear: both;
  margin: 0 !important;
}
.dataTables_length {
  float: left;
  white-space: nowrap;
}
.dataTables_filter {
  float: right;
  white-space: nowrap;
}
.dataTables_wrapper .dataTables_filter input {
  margin-left: 0.5em;
}
.dataTables_info {
  clear: both;
  float: left;
  margin: 4px 0 0;
}
.dataTables_paginate {
  float: right;
  margin: 4px 0 0;
}
.dataTables_paginate a {
  color: #111 !important;
  display: inline-block;
  outline: 0;
  position: relative;
  text-decoration: underline;
  margin: 0 5px;
}
.dataTables_paginate a:first-child {
  margin-left: 0;
}
.dataTables_paginate a:last-child {
  margin-right: 0;
}
.paginate_button:hover {
  cursor: pointer;
  text-decoration: none;
}
.paginate_button.disabled {
  color: #999 !important;
  text-decoration: none;
  cursor: default;
}
.paginate_button.current {
  font-weight: 700;
  text-decoration: none;
  cursor: default;
}
.dataTables_paginate.paging_simple {
  padding: 0 15px;
}
.paging_simple .paginate_button.next:after,
.paging_simple .paginate_button.previous:before {
  text-align: left;
  font-family: TablePress;
  font-size: 14px;
  font-weight: 700;
  -webkit-font-smoothing: antialiased;
  content: "\f053";
  text-shadow: 0.1em 0.1em #666;
  position: absolute;
  top: 0;
  right: auto;
  bottom: 0;
  left: -14px;
  margin: auto;
  height: 14px;
  width: 14px;
  line-height: 1;
}
.paging_simple .paginate_button.next:after {
  text-align: right;
  content: "\f054";
  left: auto;
}
.paginate_button:after,
.paginate_button:before {
  color: #d9edf7;
}
.paginate_button:hover:after,
.paginate_button:hover:before {
  color: #049cdb;
}
.paginate_button.disabled:after,
.paginate_button.disabled:before {
  color: #f9f9f9;
}
.dataTables_processing {
  display: none;
}
.dataTables_scroll {
  clear: both;
}
.dataTables_scrollBody {
  -webkit-overflow-scrolling: touch;
}
.dataTables_wrapper
  .dataTables_scroll
  div.dataTables_scrollBody
  td
  > div.dataTables_sizing,
.dataTables_wrapper
  .dataTables_scroll
  div.dataTables_scrollBody
  th
  > div.dataTables_sizing {
  height: 0;
  overflow: hidden;
  margin: 0 !important;
  padding: 0 !important;
}
.tablepress .sorting,
.tablepress .sorting_asc,
.tablepress .sorting_desc {
  position: relative;
  padding-right: 20px;
  cursor: pointer;
  outline: 0;
}
.tablepress .sorting:after,
.tablepress .sorting_asc:after,
.tablepress .sorting_desc:after {
  font-family: TablePress;
  font-weight: 400;
  font-size: 14px;
  -webkit-font-smoothing: antialiased;
  position: absolute;
  top: 0;
  bottom: 0;
  left: auto;
  right: 6px;
  margin: auto;
  height: 14px;
  line-height: 1;
}
.tablepress .sorting:after {
  content: "\f0dc";
}
.tablepress .sorting_asc:after {
  content: "\f0d8";
  padding: 0 0 2px;
}
.tablepress .sorting_desc:after {
  content: "\f0d7";
}
.tablepress .sorting:hover,
.tablepress .sorting_asc,
.tablepress .sorting_desc {
  background-color: #049cdb;
}
.dataTables_scrollBody .tablepress thead th:after {
  content: "";
}
.dataTables_wrapper:after {
  content: "";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}
.dataTables_wrapper label input,
.dataTables_wrapper label select {
  display: inline;
  margin: 2px;
  width: auto;
}
.section-cards .page-cards__list-intro {
  max-width: 100%;
  margin-bottom: 4rem;
}
.section-cards .page-cards__list-title {
  margin-bottom: 3.5rem;
}
.section-cards .page-cards__list-subtitle {
  margin-bottom: 4rem;
  font-weight: 400;
}
.section-cards .page-cards__list {
  left: -1.25rem;
  width: calc(100% + 40px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__list {
    left: -10px;
    width: calc(100% + 20px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .section-cards .page-cards__list {
    left: auto;
    width: 100%;
  }
}
.section-cards .page-cards__item {
  width: 22rem;
  margin: 2.5rem 1.25rem 0;
  color: #000c2c;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 80em) {
  .section-cards .page-cards__item {
    width: 25.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .section-cards .page-cards__item {
    width: 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item {
    width: calc(50% - 20px);
    margin: 1.25rem 0.625rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section-cards .page-cards__item {
    width: 100%;
    margin: 2.5rem 0 0;
  }
}
.section-cards .page-cards__item-image-wrapper {
  width: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 11.25rem;
  -ms-flex: 0 0 11.25rem;
  flex: 0 0 11.25rem;
  border-top-left-radius: 1.0625rem;
  border-top-right-radius: 1.0625rem;
  background-color: #f8f8f8;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
}
.section-cards .page-cards__item-image {
  width: 100%;
  height: auto;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item-image {
    top: auto;
    left: auto;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    position: relative;
  }
}
.page-cards__item.is-dimmed .section-cards .page-cards__item-image {
  opacity: 1;
}
.section-cards .page-cards__item-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  padding: 1.5rem;
  border-bottom-left-radius: 1.0625rem;
  border-bottom-right-radius: 1.0625rem;
  border: 0.0625rem solid #eee;
  border-top: 0;
}
.section-cards .page-cards__item-title {
  margin-bottom: 0.9375rem;
  font-size: 1.125rem;
  letter-spacing: 0.01875rem;
}
.section-cards .page-cards__item-info {
  margin-top: auto;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  color: #879099;
}
.pricing-plans {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  background-color: #fff;
  border-radius: 1.125rem;
  border: 1px solid rgba(0, 0, 0, 0.1);
}
.pricing-plans__item {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 25%;
  -ms-flex: 0 0 25%;
  flex: 0 0 25%;
  padding: 2.5rem;
  border-left: 1px solid rgba(0, 0, 0, 0.1);
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .pricing-plans__item {
    padding: 2.5rem 1.875rem;
  }
}
@media print, screen and (max-width: 64em) {
  .pricing-plans__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 50%;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    border-left: 0;
  }
}
.pricing-plans__item:nth-child(1) {
  border-left: 0;
}
@media print, screen and (max-width: 64em) {
  .pricing-plans__item:nth-child(2) {
    border-bottom: 1px solid rgba(0, 0, 0, 0.1);
  }
}
.pricing-plans__item--switch {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  border-left: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  padding: 2rem;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__item--switch {
    padding: 2rem 0.625rem;
  }
}
.pricing-plans__item--maker {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  border-left: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background: #fafafb;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 0 0 16px 16px;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__item--maker {
    padding: 2.5rem 0.625rem;
  }
}
.pricing-plans__item--scale {
  -webkit-box-shadow: 0 0 0 3px #0071e1;
  box-shadow: 0 0 0 3px #0071e1;
  margin-bottom: 3px;
}
.pricing-plans__label {
  left: 50%;
  top: 0;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  line-height: 1.5rem;
  font-size: 0.75rem;
  padding: 0 0.9375rem;
  border-radius: 3.75rem;
  font-weight: 700;
  color: #fff;
  position: absolute;
  white-space: nowrap;
}
@media print, screen and (max-width: 64em) {
  .pricing-plans__label {
    left: 0;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    -webkit-transform: translate(0, 10px);
    -ms-transform: translate(0, 10px);
    transform: translate(0, 10px);
  }
}
.pricing-plans__header {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 1.875rem;
}
.pricing-plans__title {
  margin: 0;
  letter-spacing: 0.00625rem;
  font-size: 1.25rem;
}
.pricing-plans__icon {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.125rem;
  -ms-flex: 0 0 1.125rem;
  flex: 0 0 1.125rem;
  height: 1.125rem;
  margin-left: auto;
}
.pricing-plans__icon img {
  vertical-align: top;
}
.pricing-plans__text {
  font-size: 0.9375rem;
  height: 3rem;
  margin-bottom: 1.875rem;
}
@media print, screen and (max-width: 80em) {
  .pricing-plans__text {
    font-size: 0.8125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__text {
    height: auto;
  }
}
.pricing-plans__price {
  height: 4.125rem;
  margin-bottom: 1rem;
  position: relative;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__price {
    height: auto;
  }
}
.pricing-plans__price-amount {
  font-size: 1.75rem;
  font-weight: 700;
  -webkit-transition: 0.25s;
  transition: 0.25s;
  pointer-events: none;
  left: 0;
  top: 0;
  opacity: 0;
  -webkit-transform: translateY(-25px);
  -ms-transform: translateY(-25px);
  transform: translateY(-25px);
  position: absolute;
}
.pricing-plans__price-amount.is-active {
  opacity: 1;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
  pointer-events: all;
  position: relative;
}
.pricing-plans__price-text {
  font-size: 12px;
  line-height: 14px;
  color: #000c2c;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.pricing-plans__price-text_tooltip {
  border-bottom: 1px dashed #0071e1;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  display: initial;
  cursor: default;
}
.pricing-plans__price-text_tooltip:hover
  .pricing-plans__price-text_tooltip--popup {
  visibility: visible;
  bottom: 1.875rem;
  opacity: 1;
}
.pricing-plans__price-text_tooltip--popup {
  position: absolute;
  z-index: 1;
  min-width: 14.375rem;
  width: auto;
  bottom: 3.75rem;
  opacity: 0;
  left: 0;
  visibility: hidden;
  -webkit-box-shadow: 0 12px 24px rgba(0, 0, 0, 0.04);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.04);
  background: #000c2c;
  color: #fff;
  text-align: left;
  font-weight: 600;
  padding: 1rem;
  border-radius: 0.375rem;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__price-text_tooltip--popup {
    bottom: 1.25rem;
  }
}
.pricing-plans__price-text_tooltip--popup:after {
  content: "";
  position: absolute;
  top: 100%;
  left: 3.125rem;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #000c2c transparent transparent transparent;
}
.pricing-plans__price-text_tooltip--popup__question {
  position: absolute;
  z-index: 1;
  width: auto;
  min-width: 14.375rem;
  left: -5.625rem;
  bottom: 3.75rem;
  opacity: 0;
  visibility: hidden;
  -webkit-box-shadow: 0 12px 24px rgba(0, 0, 0, 0.04);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.04);
  background: #000c2c;
  color: #fff;
  text-align: left;
  font-weight: 600;
  padding: 1rem;
  border-radius: 0.375rem;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__price-text_tooltip--popup__question {
    bottom: 1.25rem;
  }
}
.pricing-plans__price-text_tooltip--popup__question:after {
  content: "";
  position: absolute;
  top: 100%;
  left: 6.0625rem;
  margin-left: -0.3125rem;
  border-width: 0.3125rem;
  border-style: solid;
  border-color: #000c2c transparent transparent transparent;
}
.pricing-plans__price-tooltip {
  margin-left: 0.25rem;
  position: relative;
}
.pricing-plans__price-tooltip:hover .pricing-plans__price-text_tooltip--popup {
  visibility: visible;
  bottom: 1.875rem;
  opacity: 1;
}
.pricing-plans__price-tooltip:after {
  content: "?";
  font-size: 0.6875rem;
  font-weight: 700;
  width: 0.875rem;
  height: 0.875rem;
  line-height: 0.8125rem;
  border-radius: 50%;
  display: block;
  text-align: center;
  color: #fff;
  background: #666d80;
  position: absolute;
}
.pricing-plans__button {
  width: 100%;
  margin-bottom: 1.875rem;
  min-width: auto;
}
.pricing-plans__features {
  margin: 0;
  padding: 0;
  list-style: none;
}
.pricing-plans__features-item {
  padding-left: 1.5625rem;
  margin-top: 0.9375rem;
  font-size: 0.9375rem;
  position: relative;
}
.pricing-plans__features-item:first-child {
  margin-top: 0;
}
.pricing-plans__features-item:before {
  content: "";
  left: 0;
  top: 0.5625rem;
  width: 0.75rem;
  height: 0.375rem;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  border-left: 2px solid #4b8ced;
  border-bottom: 2px solid #4b8ced;
  position: absolute;
}
.pricing-plans__features-item--heading {
  margin-top: 1.875rem;
  font-size: 0.8125rem;
  padding-left: 0;
  font-weight: 700;
}
.pricing-plans__features-item--heading:before {
  display: none;
}
.pricing-plans__switch {
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__switch {
    width: 100%;
    text-align: center;
  }
}
.pricing-plans__switch-title {
  font-weight: 700;
  color: #879099;
  font-size: 1rem;
  margin-bottom: 0.9375rem;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__switch-title {
    font-size: 0.875rem;
  }
}
.pricing-plans__switch-input {
  position: absolute;
  opacity: 0;
  left: 0;
  top: 0;
}
.pricing-plans__switch-input:not(:checked)
  + .pricing-plans__switch-inner
  .pricing-plans__switch-text:first-child {
  color: #0569ff;
}
.pricing-plans__switch-input:checked
  + .pricing-plans__switch-inner
  .pricing-plans__switch-text:first-child {
  color: #879099;
}
.pricing-plans__switch-input:not(:checked)
  + .pricing-plans__switch-inner
  .pricing-plans__switch-text:last-child {
  color: #879099;
}
.pricing-plans__switch-input:checked
  + .pricing-plans__switch-inner
  .pricing-plans__switch-text:last-child {
  color: #0569ff;
}
.pricing-plans__switch-input:not(:checked)
  + .pricing-plans__switch-inner
  .pricing-plans__switch-control:after {
  -webkit-transform: translateX(-55%);
  -ms-transform: translateX(-55%);
  transform: translateX(-55%);
}
.pricing-plans__switch-input:checked
  + .pricing-plans__switch-inner
  .pricing-plans__switch-control:after {
  -webkit-transform: translateX(40%);
  -ms-transform: translateX(40%);
  transform: translateX(40%);
}
.pricing-plans__switch-inner {
  cursor: pointer;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__switch-inner {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.pricing-plans__switch-inner:hover .pricing-plans__switch-control:after {
  background-color: #005ce6;
}
.pricing-plans__switch-text {
  font-size: 0.75rem;
  font-weight: 700;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  position: relative;
  min-width: 12.5rem;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__switch-text {
    min-width: auto;
  }
}
.pricing-plans__switch-text:first-child {
  text-align: right;
}
.pricing-plans__switch-text:last-child {
  text-align: left;
}
.pricing-plans__switch-text small {
  display: inline-block;
  font-style: italic;
  font-size: 12px;
  line-height: 18px;
  font-weight: 500;
  white-space: nowrap;
}
@media print, screen and (max-width: 37.5em) {
  .pricing-plans__switch-text small {
    left: 0;
    top: 100%;
    margin: 0;
    position: absolute;
  }
}
.pricing-plans__switch-control {
  z-index: 1;
  width: 3.125rem;
  height: 1.25rem;
  margin: 0 0.9375rem;
  border-radius: 0.625rem;
  position: relative;
  overflow: hidden;
}
.pricing-plans__switch-control:before {
  content: "";
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  border-radius: 0.625rem;
  border: 1px solid rgba(0, 0, 0, 0.1);
  background-color: rgba(0, 0, 0, 0.05);
  position: absolute;
}
.pricing-plans__switch-control:after {
  content: "";
  left: 0;
  top: 0;
  width: 120%;
  height: 100%;
  border-radius: 0.625rem;
  background-color: #0569ff;
  position: absolute;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.pricing-plans__maker {
  margin: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__maker {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.pricing-plans__maker-label {
  font-size: 1rem;
  line-height: 1.5rem;
  font-weight: 500;
  text-align: center;
  max-width: 45rem;
}
.pricing-plans__maker-tooltip {
  position: relative;
  margin-right: 0.625rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1rem;
  -ms-flex: 0 0 1rem;
  flex: 0 0 1rem;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__maker-tooltip {
    position: static;
  }
}
.pricing-plans__maker-tooltip:after {
  content: "?";
  font-size: 0.6875rem;
  font-weight: 700;
  width: 1rem;
  height: 1rem;
  line-height: 0.8125rem;
  border-radius: 50%;
  border: 1px solid #000c2c;
  display: block;
  text-align: center;
}
.pricing-plans__maker-tooltip-content {
  left: 50%;
  bottom: 100%;
  border-radius: 0.625rem;
  background-color: #fff;
  font-size: 0.8125rem;
  width: 18.75rem;
  padding: 1.25rem;
  -webkit-transform: translate(-50%, 10px);
  -ms-transform: translate(-50%, 10px);
  transform: translate(-50%, 10px);
  border: 1px solid rgba(0, 0, 0, 0.07);
  -webkit-box-shadow: 0 0 0.625rem rgba(0, 0, 0, 0.1);
  box-shadow: 0 0 0.625rem rgba(0, 0, 0, 0.1);
  -webkit-transition: 0.2s;
  transition: 0.2s;
  opacity: 0;
  position: absolute;
  pointer-events: none;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__maker-tooltip-content {
    -webkit-transform: translate(-50%, 20px);
    -ms-transform: translate(-50%, 20px);
    transform: translate(-50%, 20px);
  }
}
.pricing-plans__maker-tooltip-content:after {
  content: "";
  bottom: -13px;
  left: 49%;
  width: 0.875rem;
  height: 0.875rem;
  -webkit-transform: rotate(45deg) translate(-50%, 0);
  -ms-transform: rotate(45deg) translate(-50%, 0);
  transform: rotate(45deg) translate(-50%, 0);
  border-bottom: 1px solid rgba(0, 0, 0, 0.07);
  border-right: 1px solid rgba(102, 64, 64, 0.07);
  background-color: #fff;
  position: absolute;
}
.pricing-plans__maker-tooltip-content > :first-child {
  margin-top: 0;
}
.pricing-plans__maker-tooltip-content > :last-child {
  margin-bottom: 0;
}
.pricing-plans__maker:hover .pricing-plans__maker-tooltip-content {
  opacity: 1;
  -webkit-transform: translate(-50%, -12px);
  -ms-transform: translate(-50%, -12px);
  transform: translate(-50%, -12px);
  pointer-events: all;
}
@media print, screen and (max-width: 48em) {
  .pricing-plans__maker:hover .pricing-plans__maker-tooltip-content {
    -webkit-transform: translate(-50%, 10px);
    -ms-transform: translate(-50%, 10px);
    transform: translate(-50%, 10px);
  }
}
.pricing-plans__cta-features {
  width: 100%;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  bottom: -3.75rem;
  max-width: 18.75rem;
  text-align: center;
  position: absolute;
  text-decoration: underline;
}
.feature-table {
  width: 100%;
  margin-bottom: 2.5rem;
  position: relative;
}
.feature-table:last-child {
  margin-bottom: 0;
}
.feature-table tr td {
  width: 15%;
  padding: 0.625rem;
  font-size: 1.125rem;
  line-height: 1.4;
  text-align: center;
  vertical-align: top;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .feature-table tr td {
    font-size: 0.875rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .feature-table tr td {
    font-size: 0.625rem;
    padding: 0.625rem 0.3125rem;
  }
}
.feature-table tr td:hover {
  z-index: 1;
}
.feature-table tr th {
  line-height: 1.4;
  font-size: 1.5rem;
  padding: 0 0 1.25rem;
  text-align: left;
}
@media print, screen and (max-width: 64em) {
  .feature-table tr th {
    font-size: 1.125rem;
  }
}
.feature-table tr th:nth-child(1) {
  width: 40%;
  padding-left: 0;
  text-align: left;
}
@media print, screen and (max-width: 37.5em) {
  .feature-table tr th:nth-child(1) {
    font-weight: 700;
    width: 100%;
    font-size: 1rem;
  }
}
.feature-table tr td:nth-child(1) {
  width: 40%;
  padding-left: 0;
  text-align: left;
}
@media print, screen and (max-width: 37.5em) {
  .feature-table tr td:nth-child(1) {
    font-size: 0.75rem;
  }
}
.feature-table tr td:nth-child(5),
.feature-table tr th:nth-child(5) {
  padding-right: 0;
}
.feature-table--header {
  z-index: 2;
  top: 6.25rem;
  margin-bottom: 3.75rem;
  background-color: #fff;
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
  position: -webkit-sticky;
  position: sticky;
}
@media print, screen and (max-width: 64em) {
  .feature-table--header {
    margin-bottom: 1.875rem;
    top: 5rem;
  }
}
.feature-table--header tr th {
  width: 15%;
  padding: 1.25rem 0;
  font-size: 1.125rem;
  line-height: 1;
  text-align: center;
  vertical-align: bottom;
}
@media print, screen and (max-width: 64em) {
  .feature-table--header tr th {
    font-size: 0.875rem;
    line-height: 1.6;
  }
}
@media print, screen and (max-width: 37.5em) {
  .feature-table--header tr th {
    padding: 0.625rem 0;
    font-size: 0.6875rem;
  }
}
.feature-table--header tr th:nth-child(1) {
  width: 40%;
  font-size: 2.25rem;
}
@media print, screen and (max-width: 80em) {
  .feature-table--header tr th:nth-child(1) {
    font-size: 1.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .feature-table--header tr th:nth-child(1) {
    font-size: 0.875rem;
    line-height: 1.4;
  }
}
@media print, screen and (max-width: 37.5em) {
  .feature-table--header tr th:nth-child(1) {
    white-space: nowrap;
    font-size: 0;
  }
}
.feature-table--header tr th:nth-child(1):after {
  content: "Features";
  font-size: 0.875rem;
  display: none;
}
@media print, screen and (max-width: 37.5em) {
  .feature-table--header tr th:nth-child(1):after {
    display: table-cell;
  }
}
.feature-table__tick {
  width: 1rem;
  height: 1rem;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  display: inline-block;
  position: relative;
}
.feature-table__tick:after,
.feature-table__tick:before {
  content: "";
  left: 0;
  border-radius: 0.0625rem;
  background-color: #000c2c;
  position: absolute;
}
.feature-table__tick:before {
  top: 0.125rem;
  width: 0.125rem;
  height: 0.5rem;
}
.feature-table__tick:after {
  top: 0.5625rem;
  width: 1rem;
  height: 0.125rem;
}
.feature-table__tooltip {
  width: 1rem;
  height: 1rem;
  border-radius: 50%;
  line-height: 0.6875rem;
  font-size: 0.75rem;
  font-weight: 700;
  border: 2px solid #879099;
  color: #879099;
  text-align: center;
  position: relative;
  display: inline-block;
  top: -0.125rem;
  margin: 0 -1.5rem 0 0.5rem;
}
.feature-table__tooltip:before {
  content: "?";
}
@media print, screen and (max-width: 37.5em) {
  .feature-table__tooltip {
    top: auto;
    border-width: 0.0625rem;
    width: 0.625rem;
    height: 0.625rem;
    line-height: 0.5rem;
    font-size: 0.5rem;
    margin: 0 -0.75rem 0 0.125rem;
  }
}
.feature-table__tooltip-text {
  color: #fff;
  left: 50%;
  opacity: 0;
  line-height: 1.2;
  padding: 0.5rem;
  min-width: 8.75rem;
  max-width: 11.25rem;
  font-size: 0.75rem;
  background-color: #222;
  border-radius: 0.3125rem;
  bottom: calc(100% + 10px);
  -webkit-transform: translate(-50%, 10%);
  -ms-transform: translate(-50%, 10%);
  transform: translate(-50%, 10%);
  position: absolute;
  pointer-events: none;
  -webkit-transition: 0.2s ease-in-out;
  transition: 0.2s ease-in-out;
}
.feature-table__tooltip-text:before {
  content: "";
  left: 50%;
  width: 0.625rem;
  height: 0.625rem;
  bottom: -0.25rem;
  border-radius: 0.1875rem;
  -webkit-transform: translate(-50%, 0) rotate(45deg);
  -ms-transform: translate(-50%, 0) rotate(45deg);
  transform: translate(-50%, 0) rotate(45deg);
  background-color: #222;
  position: absolute;
}
td:hover .feature-table__tooltip-text {
  opacity: 1;
  -webkit-transform: translate(-50%, 0);
  -ms-transform: translate(-50%, 0);
  transform: translate(-50%, 0);
}
@media print, screen and (max-width: 48em) {
  td:nth-child(4) .feature-table__tooltip-text,
  td:nth-child(5) .feature-table__tooltip-text {
    left: auto;
    right: -0.3125rem;
    -webkit-transform: translate(0, 10%);
    -ms-transform: translate(0, 10%);
    transform: translate(0, 10%);
  }
}
@media print, screen and (max-width: 48em) {
  td:nth-child(4) .feature-table__tooltip-text:before,
  td:nth-child(5) .feature-table__tooltip-text:before {
    left: auto;
    right: 0;
  }
}
.button-set {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.button-set__item {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  margin: 1.25rem 0;
  padding: 1.25rem 2.5rem;
  text-align: center;
}
@media print, screen and (max-width: 48em) {
  .button-set__item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 1.875rem 0 0;
    padding: 1.875rem 0 0;
    border-top: 1px solid rgba(0, 0, 0, 0.1);
  }
}
@media print, screen and (max-width: 48em) {
  .button-set__item:nth-child(1) {
    border-top: 0;
    margin-top: 0;
    padding-top: 0;
  }
}
.button-set__item:nth-child(2n) {
  border-left: 1px solid rgba(0, 0, 0, 0.1);
}
@media print, screen and (max-width: 48em) {
  .button-set__item:nth-child(2n) {
    border-left: 0;
  }
}
.button-set__item-title {
  margin-bottom: 1.25rem;
  font-size: 1.125rem;
  line-height: 1.3;
}
.button-set__item-button {
  min-width: auto;
  margin: 0;
  font-size: 0.75rem;
  padding: 0.625rem 2.1875rem;
}
.faq {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.faq__column {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
}
@media print, screen and (max-width: 48em) {
  .faq__column {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.faq__column:nth-child(1) {
  padding-right: 6.25rem;
}
@media print, screen and (max-width: 80em) {
  .faq__column:nth-child(1) {
    padding-right: 3.125rem;
  }
}
@media print, screen and (max-width: 48em) {
  .faq__column:nth-child(1) {
    padding-right: 0;
  }
}
.faq__column:nth-child(2) {
  padding-left: 6.25rem;
}
@media print, screen and (max-width: 80em) {
  .faq__column:nth-child(2) {
    padding-left: 3.125rem;
  }
}
@media print, screen and (max-width: 48em) {
  .faq__column:nth-child(2) {
    padding-left: 0;
  }
}
.faq__item {
  width: 100%;
  margin: 2.5rem 0;
  line-height: 1.4;
}
@media print, screen and (max-width: 48em) {
  .faq__item:last-child {
    margin-bottom: 0;
  }
}
.faq__item-question {
  font-weight: 700;
  margin-bottom: 1.25rem;
  font-size: 1.125rem;
  line-height: 1.4;
}
@media print, screen and (max-width: 48em) {
  .faq__item-question {
    font-size: 1rem;
  }
}
.faq__item-answer {
  font-size: 1.125rem;
  line-height: 1.4;
}
@media print, screen and (max-width: 48em) {
  .faq__item-answer {
    font-size: 1rem;
  }
}
.faq__item-answer > :first-child {
  margin-top: 0;
}
.faq__item-answer > :last-child {
  margin-bottom: 0;
}
.faq__cta {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  margin-top: 4rem;
  text-align: center;
}
.faq__cta-title {
  margin: 0;
  letter-spacing: 0;
  font-size: 1.5rem;
}
.faq__cta-text {
  margin-top: 0.625rem;
  letter-spacing: initial;
  font-size: 1.25rem;
  font-weight: 400;
}
.universe {
  height: 68.75rem;
  position: relative;
  overflow: hidden;
}
.universe svg {
  width: 100%;
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .universe {
    height: 56.25rem;
    background-size: 100% auto;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe {
    padding-bottom: 10.625rem;
    height: auto;
  }
}
.universe--404 {
  height: 100vh;
  min-height: 62.5rem;
}
@media print, screen and (max-width: 64em) {
  .universe--404 {
    min-height: 50rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe--404 {
    min-height: 37.5rem;
    padding: 8.75rem 0;
  }
}
.universe__container {
  z-index: 5;
  height: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
}
@media print, screen and (max-width: 37.5em) {
  .universe__container {
    -webkit-box-align: start;
    -webkit-align-items: start;
    -ms-flex-align: start;
    align-items: start;
  }
}
.universe__content {
  width: 100%;
  padding-right: 34.375rem;
  font-size: 1.125rem;
}
.universe__content h2 {
  margin-bottom: 1.5625rem;
}
@media print, screen and (max-width: 80em) {
  .universe__content {
    padding-right: 28.125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .universe__content {
    padding-right: 13.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__content {
    padding-right: 8.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__content {
    padding-right: 0;
  }
}
.universe--404 .universe__content {
  padding-right: 0;
  color: #879099;
  text-align: center;
}
.universe__visual,
.universe__visual-container {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
  pointer-events: none;
}
@media print, screen and (max-width: 37.5em) {
  .universe__visual,
  .universe__visual-container {
    top: auto;
    bottom: 0;
    height: 31.25rem;
  }
}
.universe__earth {
  left: 0;
  bottom: 0;
  width: 100%;
  height: 23.625rem;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .universe__earth {
    height: 13.75rem;
    background-image: url(/wp-content/themes/productboard/public//img/universe/planet.png);
    background-repeat: no-repeat;
    background-position: center bottom;
    background-size: contain;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__earth {
    height: 10rem;
  }
}
.universe__earth:after {
  content: "";
  left: 0;
  bottom: 0;
  width: 100%;
  height: 75%;
  z-index: 2;
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(rgba(255, 255, 255, 0)),
    to(#fff)
  );
  background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0, #fff 100%);
  position: absolute;
}
.universe__earth-video {
  opacity: 0.1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  outline: 0;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .universe__earth-video {
    display: none;
  }
}
.universe__rocket {
  left: 70%;
  top: 50%;
  width: 25rem;
  height: 4.375rem;
  position: absolute;
  -webkit-transform-origin: 0 50%;
  -ms-transform-origin: 0 50%;
  transform-origin: 0 50%;
  z-index: 3;
  -webkit-animation: universe-rocket-flight 30s infinite linear;
  animation: universe-rocket-flight 30s infinite linear;
}
@media print, screen and (max-width: 80em) {
  .universe__rocket {
    width: 18.75rem;
    height: 3.4375rem;
  }
}
@media print, screen and (max-width: 64em) {
  .universe__rocket {
    left: 80%;
    width: 13.75rem;
    height: 2.8125rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__rocket {
    top: 20%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__rocket {
    left: 70%;
    top: 50%;
  }
}
@-webkit-keyframes universe-rocket-flight {
  0% {
    width: 6.25rem;
    -webkit-transform: rotate(0);
    transform: rotate(0);
  }
  50% {
    width: 15.625rem;
    -webkit-transform: rotate(-180deg);
    transform: rotate(-180deg);
  }
  100% {
    width: 6.25rem;
    -webkit-transform: rotate(-360deg);
    transform: rotate(-360deg);
  }
}
@keyframes universe-rocket-flight {
  0% {
    width: 6.25rem;
    -webkit-transform: rotate(0);
    transform: rotate(0);
  }
  50% {
    width: 15.625rem;
    -webkit-transform: rotate(-180deg);
    transform: rotate(-180deg);
  }
  100% {
    width: 6.25rem;
    -webkit-transform: rotate(-360deg);
    transform: rotate(-360deg);
  }
}
.universe__rocket-icon {
  top: 0;
  right: 0;
  width: 4.375rem;
  height: 4.375rem;
  position: absolute;
}
@media print, screen and (max-width: 80em) {
  .universe__rocket-icon {
    width: 3.4375rem;
    height: 3.4375rem;
  }
}
@media print, screen and (max-width: 64em) {
  .universe__rocket-icon {
    width: 2.8125rem;
    height: 2.8125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__rocket-icon {
    width: 2.1875rem;
    height: 2.1875rem;
  }
}
.universe__rocket-icon-fire {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
}
@media print, screen and (max-width: 80em) {
  .universe__rocket-icon-fire {
    left: -0.4375rem;
    top: 0.3125rem;
    -webkit-transform: scale(0.8);
    -ms-transform: scale(0.8);
    transform: scale(0.8);
  }
}
@media print, screen and (max-width: 64em) {
  .universe__rocket-icon-fire {
    left: -0.625rem;
    top: 0.3125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__rocket-icon-fire {
    left: -0.75rem;
    -webkit-transform: scale(0.7);
    -ms-transform: scale(0.7);
    transform: scale(0.7);
  }
}
.universe__rocket-icon-fire i {
  width: 0.125rem;
  border-radius: 0.0625rem;
  background-color: #ddd;
  position: absolute;
}
.universe__rocket-icon-fire i:nth-child(1) {
  left: 1.375rem;
  bottom: -0.375rem;
  height: 1rem;
  -webkit-animation: universe-rocket-fire 1.7s 0.4s linear infinite;
  animation: universe-rocket-fire 1.7s 0.4s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(2) {
  left: 1.6875rem;
  bottom: -1.25rem;
  height: 1.25rem;
  -webkit-animation: universe-rocket-fire 1.4s 0.2s linear infinite;
  animation: universe-rocket-fire 1.4s 0.2s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(3) {
  left: 2.125rem;
  bottom: -0.625rem;
  height: 0.5rem;
  -webkit-animation: universe-rocket-fire 1.8s linear infinite;
  animation: universe-rocket-fire 1.8s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(4) {
  left: 2.125rem;
  bottom: -1.75rem;
  height: 0.875rem;
  -webkit-animation: universe-rocket-fire 1.1s 0.4s linear infinite;
  animation: universe-rocket-fire 1.1s 0.4s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(5) {
  left: 2.5625rem;
  bottom: -1.3125rem;
  height: 1.375rem;
  -webkit-animation: universe-rocket-fire 1.9s linear infinite;
  animation: universe-rocket-fire 1.9s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(6) {
  left: 3rem;
  bottom: -0.8125rem;
  height: 0.75rem;
  -webkit-animation: universe-rocket-fire 2s 0.5s linear infinite;
  animation: universe-rocket-fire 2s 0.5s linear infinite;
}
.universe__rocket-icon-fire i:nth-child(7) {
  left: 3rem;
  bottom: 0.125rem;
  height: 0.375rem;
  -webkit-animation: universe-rocket-fire 1.2s 0.6s linear infinite;
  animation: universe-rocket-fire 1.2s 0.6s linear infinite;
}
@-webkit-keyframes universe-rocket-fire {
  0% {
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
    opacity: 0;
  }
  75% {
    opacity: 0.75;
  }
  90% {
    opacity: 0;
  }
  100% {
    -webkit-transform: translate(0, 10px);
    transform: translate(0, 10px);
    opacity: 0;
  }
}
@keyframes universe-rocket-fire {
  0% {
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
    opacity: 0;
  }
  75% {
    opacity: 0.75;
  }
  90% {
    opacity: 0;
  }
  100% {
    -webkit-transform: translate(0, 10px);
    transform: translate(0, 10px);
    opacity: 0;
  }
}
.universe__star {
  left: 50%;
  top: 50%;
  width: 2rem;
  height: 2rem;
  fill: #ddd;
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .universe__star {
    width: 1rem;
    height: 1rem;
  }
}
.universe__star:nth-child(1) {
  left: 20%;
  top: 20%;
  -webkit-animation: universe-star-blink 4s linear infinite;
  animation: universe-star-blink 4s linear infinite;
}
.universe__star:nth-child(2) {
  width: 2.625rem;
  height: 2.625rem;
  left: 40%;
  top: 10%;
  -webkit-animation: universe-star-blink 8s linear infinite;
  animation: universe-star-blink 8s linear infinite;
}
@media print, screen and (max-width: 48em) {
  .universe__star:nth-child(2) {
    width: 1.25rem;
    height: 1.25rem;
  }
}
.universe__star:nth-child(3) {
  left: 70%;
  top: 35%;
  -webkit-animation: universe-star-blink 5s 0.5s linear infinite;
  animation: universe-star-blink 5s 0.5s linear infinite;
}
.universe__star:nth-child(4) {
  width: 2.875rem;
  height: 2.875rem;
  left: 90%;
  top: 40%;
  -webkit-animation: universe-star-blink 11s alternate linear infinite;
  animation: universe-star-blink 11s alternate linear infinite;
}
@media print, screen and (max-width: 48em) {
  .universe__star:nth-child(4) {
    width: 1.5rem;
    height: 1.5rem;
  }
}
.universe__star:nth-child(5) {
  left: 50%;
  top: 50%;
  -webkit-animation: universe-star-blink 3s 1s linear infinite;
  animation: universe-star-blink 3s 1s linear infinite;
}
.universe__star:nth-child(5) {
  left: 75%;
  top: 70%;
  -webkit-animation: universe-star-blink 5s 0.75s alternate linear infinite;
  animation: universe-star-blink 5s 0.75s alternate linear infinite;
}
@-webkit-keyframes universe-star-blink {
  0% {
    opacity: 1;
    -webkit-transform: translate(0, 0) scale(1);
    transform: translate(0, 0) scale(1);
  }
  25% {
    opacity: 0.75;
    -webkit-transform: translate(0, -10%) scale(0.7);
    transform: translate(0, -10%) scale(0.7);
  }
  50% {
    opacity: 0.5;
    -webkit-transform: translate(-10%, -10%) scale(0.6);
    transform: translate(-10%, -10%) scale(0.6);
  }
  75% {
    opacity: 0.5;
    -webkit-transform: translate(-10%, 0) scale(0.8);
    transform: translate(-10%, 0) scale(0.8);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0, 0) scale(1);
    transform: translate(0, 0) scale(1);
  }
}
@keyframes universe-star-blink {
  0% {
    opacity: 1;
    -webkit-transform: translate(0, 0) scale(1);
    transform: translate(0, 0) scale(1);
  }
  25% {
    opacity: 0.75;
    -webkit-transform: translate(0, -10%) scale(0.7);
    transform: translate(0, -10%) scale(0.7);
  }
  50% {
    opacity: 0.5;
    -webkit-transform: translate(-10%, -10%) scale(0.6);
    transform: translate(-10%, -10%) scale(0.6);
  }
  75% {
    opacity: 0.5;
    -webkit-transform: translate(-10%, 0) scale(0.8);
    transform: translate(-10%, 0) scale(0.8);
  }
  100% {
    opacity: 1;
    -webkit-transform: translate(0, 0) scale(1);
    transform: translate(0, 0) scale(1);
  }
}
.universe__planet {
  fill: #f2f2f2;
  position: absolute;
}
.universe__planet:nth-child(1) {
  right: 2%;
  top: 50%;
  width: 12.5rem;
  height: 12.5rem;
  -webkit-animation: universe-planet-float-1 20s ease-in-out alternate infinite;
  animation: universe-planet-float-1 20s ease-in-out alternate infinite;
}
@media print, screen and (max-width: 80em) {
  .universe__planet:nth-child(1) {
    width: 10.625rem;
    height: 10.625rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__planet:nth-child(1) {
    width: 8.75rem;
    height: 8.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__planet:nth-child(1) {
    width: 6.25rem;
    height: 6.25rem;
  }
}
.universe__planet:nth-child(2) {
  right: 10%;
  top: 20%;
  width: 8.75rem;
  height: 8.75rem;
  -webkit-animation: universe-planet-float-2 32s ease-in-out alternate infinite;
  animation: universe-planet-float-2 32s ease-in-out alternate infinite;
}
@media print, screen and (max-width: 80em) {
  .universe__planet:nth-child(2) {
    width: 7.5rem;
    height: 7.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__planet:nth-child(2) {
    width: 5.625rem;
    height: 5.625rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__planet:nth-child(2) {
    top: 15%;
    width: 3.75rem;
    height: 3.75rem;
  }
}
.universe__planet:nth-child(3) {
  right: 25%;
  top: 5%;
  width: 6.25rem;
  height: 6.25rem;
  -webkit-animation: universe-planet-float-2 19s ease-in-out alternate infinite;
  animation: universe-planet-float-2 19s ease-in-out alternate infinite;
}
@media print, screen and (max-width: 80em) {
  .universe__planet:nth-child(3) {
    right: 15%;
    width: 5rem;
    height: 5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__planet:nth-child(3) {
    width: 3.75rem;
    height: 3.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__planet:nth-child(3) {
    top: 5%;
    right: 40%;
    width: 3.125rem;
    height: 3.125rem;
  }
}
.universe__planet:nth-child(4) {
  right: 45%;
  top: 15%;
  width: 12.5rem;
  height: 12.5rem;
  -webkit-animation: universe-planet-float-3 25s ease-in-out alternate infinite;
  animation: universe-planet-float-3 25s ease-in-out alternate infinite;
}
@media print, screen and (max-width: 80em) {
  .universe__planet:nth-child(4) {
    width: 10rem;
    height: 10rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__planet:nth-child(4) {
    width: 7.5rem;
    height: 7.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__planet:nth-child(4) {
    top: 20%;
    right: 45%;
    width: 5.625rem;
    height: 5.625rem;
  }
}
.universe__planet:nth-child(5) {
  left: 10%;
  top: 10%;
  width: 7.5rem;
  height: 7.5rem;
  -webkit-animation: universe-planet-float-2 23s ease-in-out alternate infinite;
  animation: universe-planet-float-2 23s ease-in-out alternate infinite;
}
@media print, screen and (max-width: 80em) {
  .universe__planet:nth-child(5) {
    width: 6.25rem;
    height: 6.25rem;
  }
}
@media print, screen and (max-width: 48em) {
  .universe__planet:nth-child(5) {
    width: 5rem;
    height: 5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .universe__planet:nth-child(5) {
    top: 50%;
    width: 4.375rem;
    height: 4.375rem;
  }
}
@-webkit-keyframes universe-planet-float-1 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(0, 50px) rotate(20deg);
    transform: translate(0, 50px) rotate(20deg);
  }
}
@keyframes universe-planet-float-1 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(0, 50px) rotate(20deg);
    transform: translate(0, 50px) rotate(20deg);
  }
}
@-webkit-keyframes universe-planet-float-2 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(-100px, 50px) rotate(360deg);
    transform: translate(-100px, 50px) rotate(360deg);
  }
}
@keyframes universe-planet-float-2 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(-100px, 50px) rotate(360deg);
    transform: translate(-100px, 50px) rotate(360deg);
  }
}
@-webkit-keyframes universe-planet-float-3 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(30px, -50px) rotate(-360deg);
    transform: translate(30px, -50px) rotate(-360deg);
  }
}
@keyframes universe-planet-float-3 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  100% {
    -webkit-transform: translate(30px, -50px) rotate(-360deg);
    transform: translate(30px, -50px) rotate(-360deg);
  }
}
.universe__path {
  position: absolute;
}
.universe__path svg {
  fill: none;
  stroke: #eee;
  stroke-width: 0.125rem;
  stroke-dasharray: 1000;
  stroke-dashoffset: 2100;
  display: block;
}
.universe__path:nth-child(1) {
  right: 0;
  top: 0;
  -webkit-animation: universe-path-movement-1 42s 10s ease-in-out infinite;
  animation: universe-path-movement-1 42s 10s ease-in-out infinite;
}
.universe__path:nth-child(1) svg {
  -webkit-animation: universe-path-flow-1 25s infinite;
  animation: universe-path-flow-1 25s infinite;
}
.universe__path:nth-child(2) {
  right: -12.5rem;
  top: 8.75rem;
  -webkit-animation: universe-path-movement-2 60s ease-in-out infinite;
  animation: universe-path-movement-2 60s ease-in-out infinite;
}
.universe__path:nth-child(2) svg {
  -webkit-animation: universe-path-flow-2 32s infinite;
  animation: universe-path-flow-2 32s infinite;
}
.universe__path:nth-child(3) {
  right: 0;
  top: 0;
  -webkit-animation: universe-path-movement-3 39s ease-in-out infinite;
  animation: universe-path-movement-3 39s ease-in-out infinite;
}
.universe__path:nth-child(3) svg {
  -webkit-animation: universe-path-flow-3 21s infinite;
  animation: universe-path-flow-3 21s infinite;
}
@-webkit-keyframes universe-path-flow-1 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@keyframes universe-path-flow-1 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@-webkit-keyframes universe-path-movement-1 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  50% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
  100% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
}
@keyframes universe-path-movement-1 {
  0% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
  50% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
  100% {
    -webkit-transform: translate(0, 0) rotate(0);
    transform: translate(0, 0) rotate(0);
  }
}
@-webkit-keyframes universe-path-flow-2 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@keyframes universe-path-flow-2 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@-webkit-keyframes universe-path-movement-2 {
  0% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
  50% {
    -webkit-transform: translate(-40%, 10%) rotate(20deg);
    transform: translate(-40%, 10%) rotate(20deg);
  }
  100% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
}
@keyframes universe-path-movement-2 {
  0% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
  50% {
    -webkit-transform: translate(-40%, 10%) rotate(20deg);
    transform: translate(-40%, 10%) rotate(20deg);
  }
  100% {
    -webkit-transform: translate(-20%, -10%) rotate(10deg);
    transform: translate(-20%, -10%) rotate(10deg);
  }
}
@-webkit-keyframes universe-path-flow-3 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@keyframes universe-path-flow-3 {
  0% {
    stroke-dashoffset: 2100;
  }
  50% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: -2100;
  }
}
@-webkit-keyframes universe-path-movement-3 {
  0% {
    -webkit-transform: translate(-40%, 20%) rotate(10deg);
    transform: translate(-40%, 20%) rotate(10deg);
  }
  50% {
    -webkit-transform: translate(-75%, 40%) rotate(-10deg);
    transform: translate(-75%, 40%) rotate(-10deg);
  }
  100% {
    -webkit-transform: translate(-40%, 20%) rotate(10deg);
    transform: translate(-40%, 20%) rotate(10deg);
  }
}
@keyframes universe-path-movement-3 {
  0% {
    -webkit-transform: translate(-40%, 20%) rotate(10deg);
    transform: translate(-40%, 20%) rotate(10deg);
  }
  50% {
    -webkit-transform: translate(-75%, 40%) rotate(-10deg);
    transform: translate(-75%, 40%) rotate(-10deg);
  }
  100% {
    -webkit-transform: translate(-40%, 20%) rotate(10deg);
    transform: translate(-40%, 20%) rotate(10deg);
  }
}
.statistics {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.statistics__item {
  margin-top: 4.375rem;
}
@media print, screen and (max-width: 48em) {
  .statistics__item {
    width: 50%;
    padding: 0 3.125rem;
  }
}
.statistics__item:nth-child(3n + 1) {
  width: 40%;
}
@media print, screen and (max-width: 48em) {
  .statistics__item:nth-child(3n + 1) {
    width: 50%;
  }
}
.statistics__item:nth-child(3n + 2) {
  width: 40%;
}
@media print, screen and (max-width: 48em) {
  .statistics__item:nth-child(3n + 2) {
    width: 50%;
  }
}
.statistics__item:nth-child(3n + 3) {
  width: 20%;
}
@media print, screen and (max-width: 48em) {
  .statistics__item:nth-child(3n + 3) {
    width: 50%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .statistics__item:nth-child(2n + 1) {
    padding: 0 1.875rem 0 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .statistics__item:nth-child(2n) {
    padding: 0 0 0 1.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .statistics__item:nth-child(1),
  .statistics__item:nth-child(2) {
    margin-top: 0;
  }
}
.statistics__item-icon {
  width: 1.125rem;
  height: 1.125rem;
  left: 0.1875rem;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  overflow: hidden;
  position: relative;
}
.statistics__item-icon:after,
.statistics__item-icon:before {
  content: "";
  width: 100%;
  height: 150%;
  bottom: 0;
  -webkit-transform-origin: 0 100%;
  -ms-transform-origin: 0 100%;
  transform-origin: 0 100%;
  position: absolute;
}
.statistics__item-icon:before {
  left: 0;
  opacity: 0.5;
}
.statistics__item-icon:after {
  left: 100%;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
}
.statistics__item:nth-child(1) .statistics__item-icon:after,
.statistics__item:nth-child(1) .statistics__item-icon:before {
  background-color: #005ce6;
}
.statistics__item:nth-child(2) .statistics__item-icon:after,
.statistics__item:nth-child(2) .statistics__item-icon:before {
  background-color: #ffc600;
}
.statistics__item:nth-child(3) .statistics__item-icon:after,
.statistics__item:nth-child(3) .statistics__item-icon:before {
  background-color: #ff2638;
}
.statistics__item:nth-child(4) .statistics__item-icon:after,
.statistics__item:nth-child(4) .statistics__item-icon:before {
  background-color: #ff7a00;
}
.statistics__item:nth-child(5) .statistics__item-icon:after,
.statistics__item:nth-child(5) .statistics__item-icon:before {
  background-color: #7711de;
}
.statistics__item-number {
  margin: 0.625rem 0;
  font-weight: 700;
  line-height: 1.2;
  font-size: 5.25rem;
  left: -0.25rem;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .statistics__item-number {
    font-size: 3.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .statistics__item-number {
    font-size: 2.8125rem;
  }
}
.statistics__item-label {
  color: #879099;
  font-size: 1.125rem;
  left: -0.125rem;
  position: relative;
}
.offices__intro {
  max-width: 31.25rem;
  margin: 0 auto;
  text-align: center;
}
.offices__map {
  width: 48.125rem;
  height: 25rem;
  margin: 5.3125rem auto 4.375rem;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .offices__map {
    width: 40rem;
    height: 20.6875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .offices__map {
    width: 32.5rem;
    height: 16.875rem;
    margin: 3.125rem auto 1.875rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .offices__map {
    width: 18.4375rem;
    height: 9.5625rem;
  }
}
.offices__map-pin {
  position: absolute;
  border-radius: 50%;
  background-color: #005ce6;
}
.offices__map-pin:after,
.offices__map-pin:before {
  content: "";
  width: 100%;
  height: 0;
  border-radius: 50%;
  padding-top: 100%;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
  background-color: #005ce6;
  -webkit-animation: offices-map-pin-pulse 5s ease-out infinite;
  animation: offices-map-pin-pulse 5s ease-out infinite;
}
.offices__map-pin:before {
  -webkit-animation: none;
  animation: none;
}
.offices__map-pin:nth-child(1) {
  top: 12%;
  left: 11%;
  width: 4.54%;
}
.offices__map-pin:nth-child(2) {
  top: 21%;
  left: 9%;
  width: 2.33%;
  opacity: 0.6;
}
.offices__map-pin:nth-child(2):after {
  -webkit-animation-delay: 3s;
  animation-delay: 3s;
}
.offices__map-pin:nth-child(3) {
  top: 27%;
  left: 7%;
  width: 1.94%;
  opacity: 0.6;
}
.offices__map-pin:nth-child(3):after {
  -webkit-animation-delay: 4s;
  animation-delay: 4s;
}
.offices__map-pin:nth-child(4) {
  top: 22%;
  left: 19%;
  width: 4.54%;
}
.offices__map-pin:nth-child(4):after {
  -webkit-animation-delay: 4s;
  animation-delay: 4s;
}
.offices__map-pin:nth-child(5) {
  top: 29%;
  left: 16%;
  width: 2.34%;
  opacity: 0.6;
}
.offices__map-pin:nth-child(5):after {
  -webkit-animation-delay: 1s;
  animation-delay: 1s;
}
.offices__map-pin:nth-child(6) {
  top: 32%;
  left: 7%;
  width: 4.94%;
}
.offices__map-pin:nth-child(6):after {
  -webkit-animation-delay: 2s;
  animation-delay: 2s;
}
.offices__map-pin:nth-child(7) {
  top: 48%;
  left: 16%;
  width: 1.55%;
  opacity: 0.6;
}
.offices__map-pin:nth-child(7):after {
  -webkit-animation-delay: 1s;
  animation-delay: 1s;
}
.offices__map-pin:nth-child(8) {
  top: 25%;
  left: 45%;
  width: 2.1%;
  opacity: 0.6;
}
.offices__map-pin:nth-child(8):after {
  -webkit-animation-delay: 5s;
  animation-delay: 5s;
}
.offices__map-pin:nth-child(9) {
  top: 19%;
  left: 47%;
  width: 4.4%;
}
.offices__map-pin:nth-child(9):after {
  -webkit-animation-delay: 8s;
  animation-delay: 8s;
}
.offices__map-pin:nth-child(10) {
  top: 18%;
  left: 52%;
  width: 1.42%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(10):after {
  -webkit-animation-delay: 3s;
  animation-delay: 3s;
}
.offices__map-pin:nth-child(11) {
  top: 25%;
  left: 53%;
  width: 1.42%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(11):after {
  -webkit-animation-delay: 2s;
  animation-delay: 2s;
}
.offices__map-pin:nth-child(12) {
  top: 20%;
  left: 55%;
  width: 1.42%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(13) {
  top: 15%;
  left: 60%;
  width: 1.04%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(13):after {
  -webkit-animation-delay: 4s;
  animation-delay: 4s;
}
.offices__map-pin:nth-child(14) {
  top: 75%;
  left: 89%;
  width: 2.07%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(14):after {
  -webkit-animation-delay: 6s;
  animation-delay: 6s;
}
.offices__map-pin:nth-child(15) {
  top: 73%;
  left: 97%;
  width: 1.56%;
  opacity: 0.7;
}
.offices__map-pin:nth-child(15):after {
  -webkit-animation-delay: 7s;
  animation-delay: 7s;
}
@-webkit-keyframes offices-map-pin-pulse {
  0% {
    opacity: 1;
    -webkit-transform: translate(-50%, -50%) scale(1);
    transform: translate(-50%, -50%) scale(1);
  }
  30% {
    opacity: 0;
    -webkit-transform: translate(-50%, -50%) scale(1.5);
    transform: translate(-50%, -50%) scale(1.5);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate(-50%, -50%) scale(1);
    transform: translate(-50%, -50%) scale(1);
  }
}
@keyframes offices-map-pin-pulse {
  0% {
    opacity: 1;
    -webkit-transform: translate(-50%, -50%) scale(1);
    transform: translate(-50%, -50%) scale(1);
  }
  30% {
    opacity: 0;
    -webkit-transform: translate(-50%, -50%) scale(1.5);
    transform: translate(-50%, -50%) scale(1.5);
  }
  100% {
    opacity: 0;
    -webkit-transform: translate(-50%, -50%) scale(1);
    transform: translate(-50%, -50%) scale(1);
  }
}
.offices__list {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.offices__item {
  width: 100%;
  max-width: 25rem;
  padding: 2.125rem;
  border-radius: 1.0625rem;
  border: 0.0625rem solid #eee;
  margin: 0.9375rem 0 0.9375rem 1.875rem;
  background-color: #fff;
  color: #879099;
}
.offices__item:nth-child(2n + 1) {
  margin-left: 0;
}
@media print, screen and (max-width: 64em) {
  .offices__item {
    max-width: 18.75rem;
    padding: 1.875rem;
  }
}
@media print, screen and (max-width: 48em) {
  .offices__item {
    max-width: 100%;
    margin: 0.9375rem 0;
    text-align: center;
  }
}
.offices__item-title {
  display: block;
  color: #000c2c;
  margin-bottom: 0.625rem;
  font-size: 1.5rem;
  line-height: 1.2;
}
.offices__item-text {
  font-size: 1rem;
  line-height: 1.375rem;
}
.offices__item-link {
  color: #000c2c;
  font-weight: 400;
  display: -webkit-inline-box;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.offices__item-link-icon {
  width: 0.875rem;
  height: 0.875rem;
  margin-left: 0.625rem;
  top: 0.125rem;
  position: relative;
  display: inline-block;
}
.offices__item-link-icon svg {
  fill: #879099;
}
.offices__item-link:hover .offices__item-link-icon svg {
  fill: #005ce6;
}
.team {
  text-align: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.team__item {
  width: 11.5625rem;
  margin: 3rem 3rem 0;
  font-size: 1.125rem;
  font-weight: 400;
  line-height: 1.2;
  color: #000c2c;
  text-align: center;
}
@media print, screen and (max-width: 80em) {
  .team__item {
    width: 9.25rem;
    margin: 1.875rem 1.875rem 0;
  }
}
@media print, screen and (max-width: 64em) {
  .team__item {
    width: 9.25rem;
    margin: 2.8125rem 2.8125rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item {
    width: 100%;
    margin: 2.8125rem 0 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item > :first-child {
    margin-top: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item > :last-child {
    margin-bottom: 0;
  }
}
.team__item:nth-child(-n + 4) {
  margin-top: 0;
}
@media print, screen and (max-width: 64em) {
  .team__item:nth-child(-n + 4) {
    margin-top: 2.8125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item:nth-child(-n + 4) {
    margin-top: 2.8125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .team__item:nth-child(-n + 2) {
    margin-top: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item:nth-child(-n + 2) {
    margin-top: 2.8125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .team__item:nth-child(-n + 1) {
    margin-top: 0;
  }
}
.team__item-image {
  width: 11.5625rem;
  height: 11.5625rem;
  margin-bottom: 2rem;
  border-radius: 50%;
  overflow: hidden;
  display: inline-block;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .team__item-image {
    width: 9.25rem;
    height: 9.25rem;
    margin-bottom: 1.25rem;
  }
}
.team__item-image img {
  max-width: 100%;
}
.team__item-name {
  font-weight: 700;
  margin-bottom: 0.3125rem;
}
@media print, screen and (max-width: 80em) {
  .team__item-name {
    font-size: 1.125rem;
  }
}
.team__item-position {
  color: #879099;
  font-size: 0.875rem;
  margin-bottom: 0.9375rem;
}
.team__item-position:empty {
  display: none;
}
.team__item-link {
  color: #005ce6;
  font-weight: 700;
}
.team__item-link:empty {
  display: none;
}
@media print, screen and (max-width: 80em) {
  .team__item-link {
    font-size: 1rem;
  }
}
.event {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.event__image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  height: 26.875rem;
  border-radius: 1.25rem;
  margin: -40% 0 5.625rem;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .event__image-wrapper {
    height: auto;
    margin: -60% 0 3.125rem;
  }
}
.event__image {
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
  vertical-align: top;
}
@media print, screen and (max-width: 64em) {
  .event__image {
    position: relative;
    left: auto;
    top: auto;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
  }
}
.event__info {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 12.25rem;
  -ms-flex: 0 0 12.25rem;
  flex: 0 0 12.25rem;
  position: relative;
}
.event__info:before {
  content: "";
  width: calc(100% + 60px);
  height: calc(100% + 60px);
  left: -1.875rem;
  top: -1.875rem;
  border-radius: 1.25rem;
  background-color: #fafafb;
  position: absolute;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .event__info:before {
    display: block;
  }
}
@media print, screen and (max-width: 64em) {
  .event__info {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-top: 3.75rem;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.event__info-item {
  margin-bottom: 1.875rem;
  font-size: 1.125rem;
  color: #879099;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .event__info-item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 50%;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
    font-size: 1rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .event__info-item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .event__info-item:nth-child(2n + 1) {
    padding-right: rem-cac(20);
  }
}
@media print, screen and (max-width: 37.5em) {
  .event__info-item:nth-child(2n + 1) {
    padding-right: 0;
  }
}
.event__info-item:last-child {
  margin-bottom: 0;
}
@media print, screen and (max-width: 64em) {
  .event__info-item p {
    font-size: 1rem;
  }
}
.event__info-item > :first-child {
  margin-top: 0;
}
.event__info-item > :last-child {
  margin-bottom: 0;
}
.event__info-title {
  font-weight: 700;
  margin-bottom: 0.3125rem;
}
.event__content {
  margin-left: auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 40.25rem;
  -ms-flex: 0 0 40.25rem;
  flex: 0 0 40.25rem;
}
@media print, screen and (max-width: 64em) {
  .event__content {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    margin-left: 0;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.event__title {
  margin-bottom: 1.25rem;
}
.event__article-info {
  margin-bottom: 2.5rem;
  font-size: 0.625rem;
  font-weight: 700;
  color: #879099;
  text-transform: uppercase;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.event__article-info-image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.625rem;
  -ms-flex: 0 0 1.625rem;
  flex: 0 0 1.625rem;
  height: 1.625rem;
  border-radius: 50%;
  overflow: hidden;
}
.event__article-info-name {
  margin-left: 0.625rem;
  word-break: break-all;
}
.event__article-info-date {
  margin-left: 1.25rem;
}
.events__title {
  font-size: 2.25rem;
  margin-bottom: 0.625rem;
}
@media print, screen and (max-width: 80em) {
  .events__title {
    font-size: 2rem;
  }
}
.events__list {
  left: -1.25rem;
  width: calc(100% + 40px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .events__list {
    left: -10px;
    width: calc(100% + 20px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__list {
    left: auto;
    width: 100%;
  }
}
.events__item {
  width: 22rem;
  margin: 2.5rem 1.25rem 0;
  color: #000c2c;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  position: relative;
  overflow: hidden;
}
.events__item.is-hidden {
  display: none;
}
.events__item--not-found {
  font-size: 1.125rem;
  margin: 1.25rem;
}
@media print, screen and (max-width: 48em) {
  .events__item--not-found {
    margin: 1.25rem 0.625rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__item--not-found {
    margin: 1.25rem 0;
  }
}
@media print, screen and (max-width: 80em) {
  .events__item {
    width: 25.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .events__item {
    width: 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .events__item {
    width: calc(50% - 20px);
    margin: 1.25rem 0.625rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__item {
    width: 100%;
    margin: 2.5rem 0 0;
  }
}
.events__item-image-wrapper {
  width: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 11.25rem;
  -ms-flex: 0 0 11.25rem;
  flex: 0 0 11.25rem;
  border-top-left-radius: 1.0625rem;
  border-top-right-radius: 1.0625rem;
  background-color: #f8f8f8;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 48em) {
  .events__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
}
.events__item-image {
  width: 100%;
  height: auto;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .events__item-image {
    top: auto;
    left: auto;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    position: relative;
  }
}
.events__item.is-dimmed .events__item-image {
  opacity: 1;
}
.events__item-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  padding: 1.5rem;
  border-bottom-left-radius: 1.0625rem;
  border-bottom-right-radius: 1.0625rem;
  border: 0.0625rem solid #eee;
  border-top: 0;
}
.events__item-label {
  margin-bottom: 0.3125rem;
  font-size: 0.875rem;
  font-weight: 700;
}
.events__item--type-webinar .events__item-label {
  color: #3eaa08;
}
.events__item--type-attend .events__item-label {
  color: #ff7a00;
}
.events__item--type-sponsor .events__item-label {
  color: #7711de;
}
.events__item--type-host .events__item-label {
  color: #005ce6;
}
.events__item-title {
  margin-bottom: 0.9375rem;
  font-size: 1.125rem;
  letter-spacing: 0.01875rem;
}
.events__item-info {
  margin-top: auto;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  color: #879099;
}
.events__item-date {
  padding-right: 0.625rem;
  margin-right: 0.625rem;
  position: relative;
}
.events__item-date:after {
  content: "";
  top: 0.625rem;
  right: -0.125rem;
  width: 0.25rem;
  height: 0.25rem;
  border-radius: 50%;
  background-color: #879099;
  position: absolute;
}
.section-events .container .section {
  padding: 3.75rem 0;
}
@media print, screen and (max-width: 64em) {
  .page-webinar {
    padding-top: 3.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .page-webinar .grid-container {
    padding: 0;
  }
}
@media screen and (min-width: 64em) {
  .page-webinar .hero--offset {
    margin-bottom: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .page-webinar .webinar__container {
    padding: 0 0.5rem;
  }
}
@media screen and (min-width: 64em) {
  .page-webinar .webinar__container {
    text-align: left;
    -webkit-box-pack: left;
    -webkit-justify-content: left;
    -ms-flex-pack: left;
    justify-content: left;
  }
}
.page-webinar .webinar__content {
  margin-bottom: 5rem;
}
@media print, screen and (max-width: 37.5em) {
  .page-webinar .webinar__content {
    width: 100%;
    text-align: left;
    margin-bottom: 5rem;
    padding: 0 2rem;
  }
}
@media screen and (min-width: 37.5em) {
  .page-webinar .webinar__content {
    text-align: center;
  }
}
@media screen and (min-width: 64em) {
  .page-webinar .webinar__content {
    text-align: left;
  }
}
.page-webinar .webinar__content .webinar__title {
  margin-bottom: 20px;
}
.page-webinar .webinar__content .webinar__text {
  font-size: 18px;
  line-height: 21px;
}
.page-webinar .webinar__content-meta {
  margin-bottom: 43px;
}
.page-webinar .webinar__content-title {
  font-size: 18px;
  line-height: 21px;
  color: #000c2c;
}
.page-webinar .webinar__content-company,
.page-webinar .webinar__content-position {
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.05em;
  color: #acb6bf;
  text-transform: uppercase;
}
.page-webinar .webinar__form {
  position: relative;
}
@media print, screen and (max-width: 37.5em) {
  .page-webinar .webinar__form {
    width: 100%;
  }
}
@media screen and (min-width: 64em) {
  .page-webinar .webinar__form {
    padding: 0 52px;
  }
}
.page-webinar .webinar-section h3 {
  margin-bottom: 20px;
}
.page-webinar .webinar-section ul {
  list-style-type: none;
  padding-left: 2rem;
}
.page-webinar .webinar-section ul li {
  margin-bottom: 1rem;
}
.page-webinar .webinar-section ul li::before {
  content: "\2022";
  color: #0079f2;
  margin-left: -1rem;
  position: absolute;
  font-size: 21px;
  margin-top: -0.1rem;
}
@media screen and (min-width: 37.5em) {
  .page-webinar .webinar-section .feature-item__text {
    padding: 0 1rem;
  }
}
@media screen and (min-width: 64em) {
  .page-webinar .webinar-section .feature-item__text {
    padding: 0 2rem;
  }
}
.page-webinar .webinar-section .feature-item__text.image-right {
  padding: 0;
}
.embedded-portal-iframe {
  width: 100%;
  border-radius: 1rem;
}
.section-image-text_columns .section__title {
  margin-bottom: 3.5rem;
}
.section-image-text_columns .imagetextcolumns__items {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}
.section-image-text_columns .imagetextcolumns__item {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  color: inherit;
  font-weight: inherit;
}
@media print, screen and (max-width: 48em) {
  .section-image-text_columns .imagetextcolumns__item {
    margin-bottom: 2.5rem;
  }
}
.section-image-text_columns .imagetextcolumns__image {
  height: 12.5rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.section-image-text_columns .imagetextcolumns__image img {
  max-width: 100%;
  max-height: 100%;
}
.section-image-text_columns .imagetextcolumns__title {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  margin: 2rem 0;
}
.section-image-text_columns .imagetextcolumns__text {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
}
.section-success_stories .success-stories__title {
  max-width: 51.75rem;
  margin: auto;
  margin-bottom: 3.5rem;
  font-size: 2.25rem;
  line-height: 2.6875rem;
  font-weight: 700;
  font-style: normal;
  color: #000c2c;
  text-align: center;
  letter-spacing: -0.10948rem;
}
@media screen and (min-width: 48em) {
  .section-success_stories .success-stories__title {
    font-size: 3rem;
    line-height: 3.875rem;
  }
}
.section-success_stories .success-stories__cta {
  margin: 0 auto 4.6875rem;
}
@media screen and (min-width: 48em) {
  .section-success_stories .success-stories__cta {
    margin: 0 auto 9.6875rem;
  }
}
.section-success_stories .card--mainstory {
  border: 0.6402px solid rgba(0, 0, 0, 0.1);
  border-radius: 0.625rem;
  margin-bottom: 2.25rem;
}
@media screen and (min-width: 48em) {
  .section-success_stories .card--mainstory {
    margin-bottom: 4.8125rem;
  }
}
.section-success_stories .card--mainstory .card-image {
  background-size: cover;
  background-position: left top;
  border-radius: 0.625rem 0.625rem 0 0;
}
@media screen and (min-width: 48.0625em) {
  .section-success_stories .card--mainstory .card-image {
    border-radius: 0.625rem 0 0 0.625rem;
  }
}
.section-success_stories .card--mainstory .card-section {
  padding-top: 3.625rem;
  padding-bottom: 3.875rem;
}
.section-success_stories .card--mainstory .card-section .headline {
  font-weight: 700;
  font-style: normal;
  font-size: 1.5rem;
  line-height: 1.75rem;
  color: #000c2c;
  margin-bottom: 0.375rem;
}
.article__meta
  .section-success_stories
  .card--mainstory
  .card-section
  .author__name,
.card .section-success_stories .card--mainstory .card-section .author__name,
.card .section-success_stories .card--mainstory .card-section .menu,
.section-success_stories .card--mainstory .card-section .article__category,
.section-success_stories .card--mainstory .card-section .article__date,
.section-success_stories
  .card--mainstory
  .card-section
  .article__meta
  .author__name,
.section-success_stories .card--mainstory .card-section .card .author__name,
.section-success_stories .card--mainstory .card-section .card .menu,
.section-success_stories .card--mainstory .card-section .customer__category,
.section-success_stories .card--mainstory .card-section .customer__date,
.section-success_stories .card--mainstory .card-section .pre-headline {
  font-weight: 700;
  font-style: normal;
  font-size: 0.625rem;
  line-height: 0.75rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #000c2c;
  opacity: 0.4;
}
.section-success_stories .card--mainstory .card-section .quote {
  font-weight: 400;
  font-style: normal;
}
.section-success_stories .card--mainstory .card-section .author .author__info {
  display: grid;
}
.section-success_stories .card--mainstory .card-section .author .author__name {
  font-weight: 700;
  font-style: normal;
  font-size: 0.875rem;
  line-height: 1rem;
  color: #000c2c;
  opacity: 1;
}
.section-success_stories .card--mainstory .card-section .author .author__meta {
  font-weight: 700;
  font-style: normal;
  font-size: 0.625rem;
  line-height: 0.75rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #000c2c;
  opacity: 0.4;
}
.section-success_stories .main-story__introduction {
  color: #000c2c;
}
.section-success_stories .stories__wrapper {
  display: block;
  -webkit-column-count: 1;
  -moz-column-count: 1;
  column-count: 1;
  margin: 0 auto;
  width: 100%;
  text-align: center;
}
@media screen and (min-width: 48em) {
  .section-success_stories .stories__wrapper {
    -webkit-column-count: 2;
    -moz-column-count: 2;
    column-count: 2;
    padding: 0 0.75rem 0 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .section-success_stories .stories__wrapper {
    -webkit-column-count: 3;
    -moz-column-count: 3;
    column-count: 3;
    padding: 0 0.75rem;
  }
}
@media screen and (min-width: 75em) {
  .section-success_stories .stories__wrapper {
    max-width: 61.125rem;
  }
}
.section-success_stories .story-testimonial__block {
  display: inline-block;
  width: 100%;
  max-width: 100%;
  margin: 0.625rem 0;
  padding: 1.5rem;
  background-color: #fff;
  text-align: left;
  border: 0.04001rem solid rgba(0, 0, 0, 0.1);
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 0.625rem;
}
@media print, screen and (max-width: 48em) {
  .section-success_stories .story-testimonial__block:nth-child(n + 4) {
    display: none;
  }
}
@media print, screen and (max-width: 64em) {
  .section-success_stories .story-testimonial__block:nth-child(n + 5) {
    display: none;
  }
}
@media screen and (min-width: 48em) {
  .section-success_stories .story-testimonial__block {
    max-width: 95%;
    margin: 0.9375rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .section-success_stories .story-testimonial__block {
    margin: 1.25rem auto;
    max-width: 17.875rem;
  }
}
.section-success_stories .story-testimonial__image {
  width: 3rem;
  height: 3rem;
  border-radius: 100%;
  margin-bottom: 1rem;
}
.section-success_stories .story-testimonial__content {
  font-size: 0.875rem;
  line-height: 1.5;
  font-weight: 400;
  font-style: normal;
  color: #666d80;
  margin-bottom: 1.5rem;
}
.section-success_stories .story-testimonial__name {
  font-size: 0.875rem;
  line-height: 1rem;
  font-weight: 700;
  font-style: normal;
  color: #000c2c;
  margin-bottom: 0.25rem;
}
.section-success_stories .story-testimonial__position {
  font-size: 0.625rem;
  line-height: 0.75rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  font-weight: 700;
  font-style: normal;
  color: #000c2c;
  opacity: 0.4;
  margin: 0;
}
.steps {
  left: -1.875rem;
  width: calc(100% + 60px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .steps {
    width: calc(100% + 40px);
    left: -1.25rem;
  }
}
.steps--center {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: center;
}
.steps__item {
  width: 33.3%;
  padding: 0 2.1875rem;
  margin-top: 4.375rem;
}
@media print, screen and (max-width: 64em) {
  .steps__item {
    width: 50%;
    margin-top: 2.5rem;
    padding: 0 1.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .steps__item {
    width: 100%;
    padding: 1.25rem 0;
  }
}
.steps__item:nth-child(-n + 3) {
  margin-top: 0;
}
@media print, screen and (max-width: 64em) {
  .steps__item:nth-child(-n + 3) {
    margin-top: 2.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .steps__item:nth-child(-n + 3) {
    margin-top: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .steps__item:nth-child(-n + 2) {
    margin-top: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .steps__item:nth-child(-n + 2) {
    margin-top: 0;
  }
}
.steps__image-wrapper {
  max-width: 100%;
  margin-bottom: 1.25rem;
  display: inline-block;
  position: relative;
  overflow: hidden;
}
.steps__image-wrapper img {
  max-width: 100%;
  height: auto;
  vertical-align: top;
}
.steps__title {
  font-size: 1.125rem;
  margin-bottom: 1.25rem;
  line-height: 1.2;
}
.steps__text {
  font-size: 0.9375rem;
  color: #879099;
}
.steps__text > :first-child {
  margin-top: 0;
}
.steps__text > :last-child {
  margin-bottom: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .section-media .cell:nth-child(1) {
    padding-right: 64px;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .section-media .cell:nth-child(2) {
    padding-left: 64px;
  }
}
.media {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.media__block {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
}
@media print, screen and (max-width: 64em) {
  .media__block {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.media__block--content {
  padding-right: 4rem;
}
@media print, screen and (max-width: 64em) {
  .media__block--content {
    padding: 0;
  }
}
@media print, screen and (max-width: 64em) {
  .media__block--content {
    margin-bottom: 2.1875rem;
  }
}
.media__block--content > :first-child {
  margin-top: 0;
}
.media__block--content > :last-child {
  margin-bottom: 0;
}
.media--layout-vertical .media__block--content {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  padding: 0;
  margin-bottom: 4.375rem;
}
@media print, screen and (max-width: 64em) {
  .media--layout-vertical .media__block--content {
    margin-bottom: 2.1875rem;
    padding: 0;
  }
}
.media--layout-horizontal .media__block--content {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  padding: 0 4rem 0 0;
}
@media print, screen and (max-width: 64em) {
  .media--layout-horizontal .media__block--content {
    margin-bottom: 2.1875rem;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 0;
  }
}
.media__block--media {
  padding-left: 4rem;
}
@media print, screen and (max-width: 64em) {
  .media__block--media {
    padding: 0;
  }
}
.media--layout-vertical .media__block--media {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  padding: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.media--layout-horizontal .media__block--media {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  padding: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
@media print, screen and (max-width: 64em) {
  .media--layout-horizontal .media__block--media {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.media__image-wrapper {
  border-radius: 0.625rem;
  margin: 0 auto;
  overflow: hidden;
  display: block;
  position: relative;
}
.media--type-video .media__image-wrapper:before {
  content: "";
  left: 50%;
  top: 50%;
  width: 5.625rem;
  height: 5.625rem;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  border-radius: 50%;
  -webkit-box-shadow: 0 0 0.625rem rgba(0, 0, 0, 0.2);
  box-shadow: 0 0 0.625rem rgba(0, 0, 0, 0.2);
  background-color: #fff;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  position: absolute;
}
.media--type-video .media__image-wrapper:hover:before {
  -webkit-transform: translate(-50%, -50%) scale(1.1);
  -ms-transform: translate(-50%, -50%) scale(1.1);
  transform: translate(-50%, -50%) scale(1.1);
}
.media--type-video .media__image-wrapper:after {
  content: "";
  left: 50%;
  top: 50%;
  width: 0;
  height: 0;
  border-top: 20px solid transparent;
  border-bottom: 20px solid transparent;
  border-left: 30px solid #879099;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  -webkit-transform: translate(-40%, -50%);
  -ms-transform: translate(-40%, -50%);
  transform: translate(-40%, -50%);
  position: absolute;
}
.media--type-video .media__image-wrapper:hover:after {
  -webkit-transform: translate(-40%, -50%) scale(1.1);
  -ms-transform: translate(-40%, -50%) scale(1.1);
  transform: translate(-40%, -50%) scale(1.1);
}
.media__image {
  vertical-align: top;
}
.media__wistia-wrapper {
  width: 100%;
  height: 0;
  padding-top: 56.25%;
  position: relative;
}
.media__wistia-wistia-video {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
}
.media__wistia-wistia-overlay {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  position: absolute;
  cursor: pointer;
}
.media__wistia-wistia-overlay.is-hidden {
  display: none;
}
.media__wistia-wistia-button {
  left: 50%;
  top: 50%;
  outline: 0;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
  pointer-events: none;
}
.media__wistia-wistia-overlay:hover .media__wistia-wistia-button {
  background-color: #005ce6;
}
.media__wistia-wistia-button svg {
  width: 1rem;
  height: 1rem;
  margin-right: 0.75rem;
}
.media__wistia-video {
  width: 100%;
  vertical-align: top;
}
@media print, screen and (max-width: 64em) {
  .media__wistia-video {
    display: none;
  }
}
.media__wistia-video + .media__wistia-image {
  display: none;
}
@media print, screen and (max-width: 64em) {
  .media__wistia-video + .media__wistia-image {
    display: block;
  }
}
.media__wistia-image {
  width: 100%;
  height: auto;
  vertical-align: top;
  background-color: #fff;
}
.section-content .content-wrapper {
  padding: 0 2rem;
}
.section-content .content-wrapper .content-title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  letter-spacing: -1.3616px;
  margin-bottom: 2.25rem;
}
.section-content .content-wrapper .description {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
}
.section-content .content-image {
  margin: 4rem 0 3rem;
}
.section-content .swipe-image {
  border-radius: 1rem;
}
.section-content .use-cases__illust {
  max-width: 16px;
}
.section-content .use-cases__title {
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 25px;
  margin-bottom: 1rem;
}
.section-content .use-cases__description {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 19px;
}
.section-customers .customers__list {
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}
@media print, screen and (min-width: 48.0625em) {
  .section-customers .customers__list {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.section-customers svg {
  fill: #000c2c;
}
.section-customers .section__title {
  font-style: normal;
  font-weight: 600;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  text-align: center;
  letter-spacing: -0.03125rem;
  color: #2b334a;
  margin-bottom: 1rem;
}
@media print, screen and (max-width: 48em) {
  .section-customers .section__title {
    font-size: 0.875rem;
    line-height: 1.25rem;
  }
}
.section-media .media-image {
  border-radius: 1rem;
}
.section-quote.background-box {
  padding: 8.75rem 0;
  margin: 4.375rem 0;
}
@media print, screen and (max-width: 64em) {
  .section-quote.background-box {
    padding: 4.375rem 0;
    margin: 2.1875rem 0;
  }
}
@media screen and (min-width: 48em) {
  .section-cta .grid-container {
    max-width: 35.625rem;
  }
}
@media screen and (min-width: 64em) {
  .section-cta .grid-container {
    max-width: 38.125rem;
  }
}
@media screen and (min-width: 75em) {
  .section-cta .grid-container {
    max-width: 32.5rem;
  }
}
@media print, screen and (max-width: 48em) {
  .section-cta .cta-buttons__column:nth-child(2) {
    margin-top: 1.875rem;
  }
}
@media screen and (min-width: 48em) {
  .section-cta .cta-buttons__column {
    margin-top: 1.875rem;
    -webkit-box-flex: 1;
    -webkit-flex-grow: 1;
    -ms-flex-positive: 1;
    flex-grow: 1;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    flex-grow: 1;
  }
}
.section-cta .cta-buttons__title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  text-align: center;
  letter-spacing: -1.3616px;
  margin-bottom: 2rem;
}
.section-cta .cta-buttons__subtitle {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  text-align: center;
  max-width: 90%;
  margin-left: auto;
  margin-right: auto;
}
@media screen and (min-width: 48em) {
  .section-cta .cta-buttons__subtitle {
    -webkit-box-flex: 1;
    -webkit-flex-grow: 1;
    -ms-flex-positive: 1;
    flex-grow: 1;
  }
}
@media screen and (min-width: 48em) {
  .section-cta .button {
    margin: auto;
  }
}
.section-resources .page-resources__list-intro {
  max-width: 100%;
  margin-bottom: 4rem;
}
.section-resources .page-resources__list-title {
  margin-bottom: 3.5rem;
}
.section-resources .page-resources__list-subtitle {
  margin-bottom: 6rem;
}
.section-resources .card--resources {
  position: relative;
}
.section-resources .card--resources .card-section {
  padding-top: 2.5rem;
}
.section-resources .card--resources .card-section .headline {
  margin-bottom: 2rem;
}
.article__meta .section-resources .card--resources .card-section .author__name,
.card .section-resources .card--resources .card-section .author__name,
.card .section-resources .card--resources .card-section .menu,
.section-resources .card--resources .card-section .article__category,
.section-resources .card--resources .card-section .article__date,
.section-resources .card--resources .card-section .article__meta .author__name,
.section-resources .card--resources .card-section .card .author__name,
.section-resources .card--resources .card-section .card .menu,
.section-resources .card--resources .card-section .customer__category,
.section-resources .card--resources .card-section .customer__date,
.section-resources .card--resources .card-section .pre-headline {
  position: absolute;
  bottom: 0;
}
.section-resources .card--resources .card-image {
  border-radius: 0.75rem;
}
.section-resources .card--resources .card-image__image {
  border-radius: 0.75rem;
}
.section-features .feature__item {
  margin-bottom: 5rem;
}
@media print, screen and (min-width: 48.0625em) {
  .section-features .feature__item {
    margin-bottom: 6.25rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .section-features .feature__item {
    margin-bottom: 8rem;
  }
}
.section-features .feature__item:last-child {
  margin-bottom: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .section-features
    .feature__item
    .cell.small-12:nth-child(1):not(.medium-order-2) {
    padding-right: 2.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .section-features
    .feature__item
    .cell.small-12:nth-child(2):not(.medium-order-1) {
    padding-left: 2.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .section-features .feature__item .cell.small-12.medium-order-2 {
    padding-left: 2.5rem;
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .section-features .feature__item .cell.small-12.medium-order-1 {
    padding-right: 2.5rem;
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
  }
}
.section-features .feature__item .feature__image {
  border-radius: 1rem;
}
.section-features .feature__item .features__title {
  font-style: normal;
  font-weight: 600;
  font-size: 2.25rem;
  line-height: 2.6875rem;
  letter-spacing: -1.3616px;
  margin-bottom: 0.4375rem;
}
.section-features .feature__item .features__title--no_subtitle {
  margin-bottom: 2.25rem;
}
.section-features .feature__item .features__subtitle {
  font-style: normal;
  font-weight: 600;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  margin-bottom: 2.25rem;
}
.section-features .feature__item .features__text {
  font-style: normal;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  padding: 0;
}
.section-features .feature__item .button {
  margin: 1rem 0;
}
@media print, screen and (max-width: 48.06125em) {
  .section-features .feature__item .button {
    margin: 3rem auto;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .ebook__container {
    max-width: 100%;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .ebook__image {
    width: 100%;
    text-align: center;
    margin-bottom: 5rem;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .ebook__image {
    margin-bottom: 32px;
  }
}
.ebook__image--src {
  max-width: 70%;
}
@media print, screen and (min-width: 48.0625em) {
  .ebook__image--src {
    max-width: 380px;
  }
}
@media print, screen and (max-width: 37.5em) {
  .ebook__content {
    width: 100%;
  }
}
@media screen and (min-width: 64em) {
  .ebook__content {
    padding: 0 0 0 9%;
  }
}
@media screen and (min-width: 80em) {
  .ebook__content {
    padding: 0 9%;
  }
}
.ebook__content .ebook__title {
  margin-bottom: 18px;
}
@media print, screen and (max-width: 64.06125em) {
  .ebook__content .ebook__title {
    text-align: center;
  }
}
.ebook__content .ebook__text {
  margin-bottom: 70px;
}
@media print, screen and (max-width: 37.5em) {
  .ebook__content .ebook__button {
    width: 100%;
  }
}
.ebook__content .confirmform p {
  text-align: left;
}
@media print, screen and (max-width: 64.06125em) {
  .ebook__form {
    max-width: 70%;
    margin: auto;
  }
}
@media print, screen and (max-width: 37.5em) {
  .ebook__form {
    max-width: 90%;
  }
}
@media print, screen and (max-width: 23.4375em) {
  .ebook__form {
    max-width: 100%;
  }
}
.ebook-section h3 {
  margin-bottom: 20px;
}
.ebook-section ul {
  list-style-type: none;
  padding-left: 2rem;
}
.ebook-section ul li {
  margin-bottom: 1rem;
}
.ebook-section ul li::before {
  content: "\2022";
  color: #0079f2;
  margin-left: -1rem;
  position: absolute;
  font-size: 21px;
  margin-top: -0.1rem;
}
@media screen and (min-width: 37.5em) {
  .ebook-section .feature-item__text {
    padding: 0 1rem;
  }
}
@media screen and (min-width: 64em) {
  .ebook-section .feature-item__text {
    padding: 0 2rem;
  }
}
.mktoForm {
  text-align: left;
  visibility: hidden;
  width: 100%;
  max-width: 26.25rem;
  padding: 2.5rem;
  border-radius: 0.625rem;
  -webkit-box-shadow: 0 0.3125rem 0.625rem #eee;
  box-shadow: 0 0.3125rem 0.625rem #eee;
  background-color: #fff;
}
@media print, screen and (min-width: 64.0625em) {
  .mktoForm {
    min-width: 400px;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .mktoForm {
    min-width: 370px;
  }
}
@media print, screen and (max-width: 37.5em) {
  .mktoForm {
    padding: 1.5625rem;
  }
}
.mktoForm[data-styles-ready="true"] {
  visibility: visible;
}
.hero__container--vertical .mktoForm {
  margin: 30px auto 0;
}
@media print, screen and (min-width: 48.0625em) {
  .hero__container--vertical .mktoForm {
    margin: 30px auto 0;
  }
}
.mktoForm div,
.mktoForm label,
.mktoForm p,
.mktoForm span {
  text-align: left;
  margin: 0;
  padding: 0;
}
.mktoForm select,
.mktoForm select:focus {
  border: 0;
}
.mktoForm .mktoClear {
  clear: both;
  float: none;
}
.mktoForm .mktoAsterix,
.mktoForm .mktoGutter,
.mktoForm .mktoOffset {
  display: none;
}
.mktoForm .mktoFormRow {
  width: 100%;
}
.mktoForm .mktoFieldWrap {
  width: 100%;
  margin-bottom: 1.875rem;
  min-width: 20rem;
  position: relative;
  float: left;
}
@media print, screen and (max-width: 80em) {
  .mktoForm .mktoFieldWrap {
    min-width: 9.375rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .mktoForm .mktoFieldWrap {
    min-width: 15rem;
  }
}
.mktoForm .mktoFieldWrap .mktoInstruction {
  display: none;
}
.mktoForm .mktoFormCol {
  position: relative;
  width: 100%;
}
.mktoForm .mktoError {
  left: auto !important;
  top: auto !important;
  right: 0 !important;
  bottom: 0 !important;
  -webkit-transform: translateY(120%);
  -ms-transform: translateY(120%);
  transform: translateY(120%);
  font-size: 0.75rem;
  line-height: 1.2;
  z-index: 99;
  color: #ff2638;
  position: absolute;
}
.mktoForm .mktoError .mktoErrorArrowWrap {
  display: none;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription) {
  display: -webkit-box !important;
  display: -webkit-flex !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoLabel {
  left: 0;
  top: 0;
  font-size: 0.625rem;
  line-height: 0.9375rem;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #5f677b;
  width: 100% !important;
  z-index: 20;
  position: relative;
  display: block;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoField {
  width: 100% !important;
  height: 2rem;
  font-family: "eina 02", Helvetica, Roboto, Arial, sans-serif;
  font-size: 1rem;
  line-height: 2rem;
  font-weight: 400;
  padding: 0 0 0 0.5625rem;
  margin: 0.25rem 0 0;
  color: #000c2c;
  z-index: 10;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  white-space: nowrap;
  position: relative;
  background: #fff;
  border: 1px solid #bcc4cc;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 0.1875rem;
  outline: 0;
}
@media print, screen and (max-width: 37.5em) {
  .mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
    .mktoField {
    max-width: 90%;
  }
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoField[multiple] {
  height: 7.5rem;
  line-height: 2rem;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoField:focus {
  border: 0.0625rem solid #0079f2;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoField:hover {
  border: 0.0625rem solid #0079f2;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoHtmlText
  h3 {
  font-size: 1.5rem;
  line-height: 1.75rem;
  color: #000c2c;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoHtmlText
  p {
  font-size: 1.125rem;
  line-height: 1.3125rem;
  color: #000c2c;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoButtonRow {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  margin: 0.5rem 0 1rem;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoButton {
  width: 100%;
  background-color: #0079f2;
  -webkit-transition: background 0.24s ease-in-out;
  transition: background 0.24s ease-in-out;
  border-radius: 0.625rem;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoButton:hover {
  background-color: #2693ff;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoButton:focus {
  text-decoration: none;
  background-color: #0079f2;
  -webkit-box-shadow: 0 0 0 3px #cce4fc;
  box-shadow: 0 0 0 3px #cce4fc;
  -webkit-transition: none;
  transition: none;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoFormRow.checkboxed {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoFormRow.hidden {
  -webkit-box-ordinal-group: 6;
  -webkit-order: 5;
  -ms-flex-order: 5;
  order: 5;
  width: 0;
  height: 0;
}
.mktoForm:not(.marketo-form--newsletter-subscription):not(.marketo-form--subscription)
  .mktoFormRow:not(.hidden) {
  margin-bottom: 1.5rem;
}
.mktoForm .mktoFieldWrap {
  margin-bottom: 0;
}
.mktoForm .mktoFieldWrap.checkboxed {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 0;
}
.mktoForm .mktoFieldWrap.checkboxed {
  width: 100%;
  height: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.mktoForm .mktoFieldWrap.checkboxed .mktoLabel {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  position: relative;
  height: auto;
  font-weight: 400;
  font-size: 0.75rem;
  line-height: 0.875rem;
  color: #5f677b;
  text-transform: none;
  top: 0;
  letter-spacing: normal;
}
.mktoForm .mktoFieldWrap.checkboxed .mktoCheckboxList {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  margin-right: 0.5rem;
  width: 1.5rem;
  height: 1.5rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.5rem;
  -ms-flex: 0 0 1.5rem;
  flex: 0 0 1.5rem;
  position: relative;
}
.mktoForm .mktoFieldWrap.checkboxed .mktoCheckboxList input {
  position: absolute;
  opacity: 0;
  top: 0;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
}
.mktoForm .mktoFieldWrap.checkboxed .mktoCheckboxList label {
  width: 100%;
  height: 100%;
  border-radius: 0.375rem;
  display: block;
  position: relative;
  overflow: hidden;
}
.mktoForm .mktoFieldWrap.checkboxed .mktoCheckboxList label:before {
  content: "";
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  border: 2px solid #5f677b;
  position: absolute;
}
.mktoForm
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:before {
  background-color: #5f677b;
}
.mktoForm
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:after {
  content: "";
  height: 7px;
  width: 11px;
  left: 50%;
  top: 50%;
  border-left: 2px solid #fff;
  border-bottom: 2px solid #fff;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  -webkit-transform: translate(-50%, -70%) rotate(-45deg);
  -ms-transform: translate(-50%, -70%) rotate(-45deg);
  transform: translate(-50%, -70%) rotate(-45deg);
  position: absolute;
  display: none;
}
.mktoForm
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:after {
  display: block;
}
.mktoForm .mktoButton {
  font-size: 0.90625rem;
  font-weight: 700;
  line-height: 1;
  color: #fff;
  background-color: #0079f2;
  color: #fff;
  min-width: 8rem;
  padding: 0.875rem 1.8125rem;
  border-radius: 0.5rem;
  border: 1px solid transparent;
  display: inline-block;
  text-align: center;
  cursor: pointer;
  text-decoration: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-family: inherit;
}
.mktoForm .mktoButton:focus,
.mktoForm .mktoButton:hover {
  text-decoration: none;
  color: #fff;
  background-color: #2693ff;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.confirmform {
  display: none;
  background-color: #fff;
  padding: 1rem;
  border-radius: 10px;
}
.confirmform h2,
.confirmform p {
  text-align: center;
}
p.confirmform-text {
  text-align: center;
}
.mktoModal {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  z-index: 100001;
}
.mktoModal .mktoModalMask {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  z-index: 10000;
  zoom: 1;
  background: rgba(0, 0, 0, 0.5);
}
.mktoModal .mktoForm {
  width: 100%;
  max-width: 27.0625rem;
  -webkit-box-shadow: none;
  box-shadow: none;
  padding: 0;
}
.mktoModal .mktoModalClose {
  position: absolute;
  text-align: center;
  color: #fff;
  top: 0.75rem;
  right: 0.75rem;
  border-radius: 0;
  width: 1rem;
  height: 1rem;
  border: 0;
  cursor: pointer;
}
.mktoModal .mktoModalClose:after {
  content: "\D7";
  right: 0.125rem;
  top: -1.625rem;
  width: 100%;
  height: 100%;
  font-size: 2.25rem;
  color: #5f677b;
  position: absolute;
  text-align: center;
}
.mktoModal .mktoModalContent {
  position: absolute;
  z-index: 10001;
  background: #fff;
  padding: 3.5rem;
  top: 50% !important;
  left: 50% !important;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  border-radius: 0.625rem;
  max-height: 100%;
  overflow: hidden;
  overflow-y: scroll;
  -ms-overflow-style: none;
  scrollbar-width: none;
}
.mktoModal .mktoModalContent::-webkit-scrollbar {
  display: none;
}
@media (max-width: 560px) {
  .mktoModal .mktoModalContent {
    max-height: calc(100% - 40px);
    width: calc(100% - 40px);
    padding: 40px 20px;
  }
}
.mktoModal .mktoModalContentThanks {
  width: 400px;
  text-align: center;
  padding-bottom: 10px;
}
.mktoModal .mktoModalContentThanks > :last-child {
  margin-bottom: 0;
}
.layout__block--sticky_marketo-inline .mktoModal .mktoModalContentThanks {
  padding: 1rem;
}
.mktoModal .mktoModalMain {
  width: auto !important;
  text-align: center;
}
@media (max-width: 560px) {
  .mktoModal .mktoModalMain {
    width: 100% !important;
  }
}
.marketo-form--subscription {
  width: 100% !important;
  max-width: 100%;
  padding: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-shadow: none;
  box-shadow: none;
  background-color: transparent;
}
.marketo-form--subscription .mktoFieldWrap {
  margin-bottom: 0;
  min-width: 0;
}
.marketo-form--subscription .mktoFieldWrap.field-focus .mktoLabel,
.marketo-form--subscription .mktoFieldWrap.field-not-empty .mktoLabel {
  opacity: 0;
}
.marketo-form--subscription .mktoLabel {
  left: 0;
  top: 0;
  font-size: 1rem;
  line-height: 1.2;
  font-weight: 700;
  color: #000c2c;
  width: 100% !important;
  line-height: 2.4375rem;
  height: 2.4375rem;
  background-color: #fff;
  z-index: 20;
  position: absolute;
  pointer-events: none;
}
.marketo-form--subscription .mktoField {
  width: 100% !important;
  height: 2.5rem;
  font-family: "eina 02", Helvetica, Roboto, Arial, sans-serif;
  font-size: 1rem;
  font-weight: 400;
  padding: 0;
  margin: 0;
  color: #000c2c;
  z-index: 10;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  white-space: nowrap;
  position: relative;
  border-bottom: 1px solid #999eab;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--subscription .mktoField {
    max-width: 90%;
  }
}
.marketo-form--subscription .mktoField[multiple] {
  height: 120px;
  line-height: 32px;
}
.marketo-form--subscription .mktoField:focus {
  border: 0;
  border-bottom: 1px solid #000c2c;
}
.marketo-form--subscription .mktoFormRow:nth-child(1) {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 21.25rem;
  -ms-flex: 0 0 21.25rem;
  flex: 0 0 21.25rem;
}
@media print, screen and (max-width: 80em) {
  .marketo-form--subscription .mktoFormRow:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 60%;
    -ms-flex: 0 0 60%;
    flex: 0 0 60%;
  }
}
@media print, screen and (max-width: 64em) {
  .marketo-form--subscription .mktoFormRow:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-bottom: 0;
  }
}
.marketo-form--subscription .mktoFormRow:nth-child(1) .mktoLabel {
  background-color: transparent;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--subscription .mktoFormRow:nth-child(1) .mktoLabel {
    text-align: center;
  }
}
.marketo-form--subscription .mktoFormRow:nth-child(1) .mktoField {
  font-weight: 700;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--subscription .mktoFormRow:nth-child(1) .mktoField {
    text-align: center;
  }
}
.marketo-form--subscription .mktoFormRow:nth-child(2) {
  -webkit-box-ordinal-group: 4;
  -webkit-order: 3;
  -ms-flex-order: 3;
  order: 3;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  margin-top: 1.25rem;
}
.marketo-form--subscription .mktoFormRow:nth-child(2) .mktoFormCol {
  max-width: 100%;
  margin-bottom: 0 !important;
}
.marketo-form--subscription
  .mktoFormRow:nth-child(2)
  .mktoFieldWrap.checkboxed {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.marketo-form--subscription
  .mktoFormRow:nth-child(2)
  .mktoFieldWrap.checkboxed
  .mktoLabel {
  margin-top: 0;
  color: #000c2c;
  opacity: 1;
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  font-size: 0.75rem;
  line-height: 1.2;
  text-align: right;
  background-color: transparent;
}
.marketo-form--subscription .mktoFormRow:nth-child(2) .mktoCheckboxList {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  margin: 0 0 0 1.125rem;
}
.marketo-form--subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  label:before {
  border-color: #ffc600;
}
.marketo-form--subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:before {
  border-color: #ffc600;
  background-color: #ffc600;
}
.marketo-form--subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:after {
  border-color: #000c2c;
}
.marketo-form--subscription .mktoButtonRow {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  margin: 0 0 0 auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 10rem;
  -ms-flex: 0 0 10rem;
  flex: 0 0 10rem;
  text-align: right;
}
@media print, screen and (max-width: 80em) {
  .marketo-form--subscription .mktoButtonRow {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 35%;
    -ms-flex: 0 0 35%;
    flex: 0 0 35%;
  }
}
@media print, screen and (max-width: 64em) {
  .marketo-form--subscription .mktoButtonRow {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-top: 1.25rem;
    text-align: center;
  }
}
.marketo-form--subscription .mktoButton {
  white-space: nowrap;
  background-color: #ffc600;
  color: #000c2c;
}
.marketo-form--subscription .mktoButton:hover {
  background-color: #ffc600;
  color: #000c2c;
}
@media print, screen and (max-width: 80em) {
  .marketo-form--subscription .mktoButton {
    padding: 0.9375rem 1.875rem;
    min-width: auto;
  }
}
@media print, screen and (max-width: 64em) {
  .marketo-form--subscription .mktoButton {
    width: 100%;
  }
}
.marketo-form--newsletter-subscription {
  width: 100% !important;
  max-width: 100%;
  padding: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-shadow: none;
  box-shadow: none;
  background-color: transparent;
}
.marketo-form--newsletter-subscription .mktoFieldWrap {
  margin-bottom: 0;
  min-width: 0;
}
.marketo-form--newsletter-subscription .mktoFieldWrap.field-focus .mktoLabel,
.marketo-form--newsletter-subscription
  .mktoFieldWrap.field-not-empty
  .mktoLabel {
  opacity: 0;
}
.marketo-form--newsletter-subscription .mktoLabel {
  left: 0;
  top: 0;
  font-size: 1rem;
  line-height: 1.2;
  font-weight: 700;
  color: #000c2c;
  width: 100% !important;
  line-height: 2.4375rem;
  height: 2.4375rem;
  background-color: #fff;
  z-index: 20;
  position: absolute;
  pointer-events: none;
}
.marketo-form--newsletter-subscription .mktoField {
  width: 100% !important;
  height: 2.5rem;
  font-family: "eina 02", Helvetica, Roboto, Arial, sans-serif;
  font-size: 1rem;
  font-weight: 400;
  padding: 0;
  margin: 0;
  color: #000c2c;
  z-index: 10;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  white-space: nowrap;
  position: relative;
  border-bottom: 1px solid #999eab;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--newsletter-subscription .mktoField {
    max-width: 90%;
  }
}
.marketo-form--newsletter-subscription .mktoField[multiple] {
  height: 120px;
  line-height: 32px;
}
.marketo-form--newsletter-subscription .mktoField:focus {
  border: 0;
  border-bottom: 1px solid #000c2c;
}
.marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) {
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 13.75rem;
  -ms-flex: 0 0 13.75rem;
  flex: 0 0 13.75rem;
}
@media print, screen and (max-width: 80em) {
  .marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 60%;
    -ms-flex: 0 0 60%;
    flex: 0 0 60%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
.marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) .mktoLabel {
  background-color: transparent;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) .mktoLabel {
    text-align: center;
  }
}
.marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) .mktoField {
  font-weight: 700;
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--newsletter-subscription .mktoFormRow:nth-child(1) .mktoField {
    text-align: center;
  }
}
.marketo-form--newsletter-subscription .mktoFormRow:nth-child(2) {
  -webkit-box-ordinal-group: 4;
  -webkit-order: 3;
  -ms-flex-order: 3;
  order: 3;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  margin-top: 0.9375rem;
}
.marketo-form--newsletter-subscription .mktoFormRow:nth-child(2) .mktoFormCol {
  max-width: 100%;
  margin-bottom: 0 !important;
}
.marketo-form--newsletter-subscription
  .mktoFormRow:nth-child(2)
  .mktoFieldWrap.checkboxed {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.marketo-form--newsletter-subscription
  .mktoFormRow:nth-child(2)
  .mktoFieldWrap.checkboxed
  .mktoLabel {
  margin-top: 0;
  color: #000c2c;
  opacity: 1;
  -webkit-box-ordinal-group: 2;
  -webkit-order: 1;
  -ms-flex-order: 1;
  order: 1;
  font-size: 0.75rem;
  line-height: 1.2;
  text-align: right;
  background-color: transparent;
}
.marketo-form--newsletter-subscription
  .mktoFormRow:nth-child(2)
  .mktoCheckboxList {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  margin: 0 0 0 1.125rem;
}
.marketo-form--newsletter-subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  label:before {
  border-color: #ffc600;
}
.marketo-form--newsletter-subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:before {
  border-color: #ffc600;
  background-color: #ffc600;
}
.marketo-form--newsletter-subscription
  .mktoFieldWrap.checkboxed
  .mktoCheckboxList
  input:checked
  + label:after {
  border-color: #000c2c;
}
.marketo-form--newsletter-subscription .mktoButtonRow {
  -webkit-box-ordinal-group: 3;
  -webkit-order: 2;
  -ms-flex-order: 2;
  order: 2;
  margin: 0 0 0 auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 10rem;
  -ms-flex: 0 0 10rem;
  flex: 0 0 10rem;
  text-align: right;
}
@media print, screen and (max-width: 80em) {
  .marketo-form--newsletter-subscription .mktoButtonRow {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 35%;
    -ms-flex: 0 0 35%;
    flex: 0 0 35%;
  }
}
@media print, screen and (max-width: 37.5em) {
  .marketo-form--newsletter-subscription .mktoButtonRow {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin-top: 1.25rem;
    text-align: center;
  }
}
.marketo-form--newsletter-subscription .mktoButton {
  background-color: #ffc600;
  color: #30363c;
}
.marketo-form--newsletter-subscription .mktoButton:hover {
  color: #30363c;
  background-color: #ffd659;
}
.marketo-form--newsletter-subscription .mktoButton:focus {
  color: #30363c;
  background-color: #ffc600;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.marketo-form--newsletter-subscription .mktoButton:active {
  color: #30363c;
  background-color: #fab500;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.section-marketo_form {
  text-align: center;
}
.section-marketo_form .mktoForm {
  margin: auto;
  background: #fafafb;
  border-radius: 16px;
}
.section-marketo_form .mktoForm .mktoFieldWrap,
.section-marketo_form .mktoForm .mktoLabel {
  background: #fafafb;
}
.section-marketo_form .mktoForm .mktoButtonRow {
  text-align: center;
}
.mktoForm[data-formMode="popup"] {
  pointer-events: none;
  visibility: hidden;
  position: absolute;
  left: 0;
  max-width: 100%;
}
.mktoModal .mktoForm[data-formMode="popup"] {
  pointer-events: all;
  visibility: visible;
  position: static;
  max-width: 26.25rem;
}
.success-stories-legacy .section__subtitle {
  color: #000c2c;
  text-transform: uppercase;
}
.success-stories-legacy .section__title {
  color: #000c2c;
  line-height: 28px;
}
.success-stories-legacy .section__description {
  color: #475059;
}
.success-stories-legacy .testimonial-wrap {
  position: relative;
  width: 100%;
  margin: auto;
  padding: 0 0.625rem;
}
@media screen and (min-width: 37.5em) {
  .success-stories-legacy .testimonial-wrap {
    width: 97%;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonial-wrap {
    width: 96%;
    padding: 0;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonial-wrap {
    width: 97%;
  }
}
.success-stories-legacy .stories__wrapper {
  margin-top: 70px;
  width: 100%;
  overflow-x: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-flex: 10;
  -webkit-flex: 10 0 auto;
  -ms-flex: 10 0 auto;
  flex: 10 0 auto;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
}
.success-stories-legacy .stories__wrapper--horizontal_scroll {
  overflow-x: auto;
  -ms-overflow-style: none;
  scrollbar-width: none;
}
.success-stories-legacy
  .stories__wrapper--horizontal_scroll::-webkit-scrollbar {
  display: none;
}
.success-stories-legacy .stories__wrapper:after {
  content: "";
  height: 0.0625rem;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 1.875rem;
  -ms-flex: 0 0 1.875rem;
  flex: 0 0 1.875rem;
  pointer-events: none;
}
.success-stories-legacy .testimonial__parent {
  -webkit-scroll-snap-type: x mandatory;
  -ms-scroll-snap-type: x mandatory;
  scroll-snap-type: x mandatory;
}
.success-stories-legacy .testimonial__block {
  scroll-snap-align: end;
  display: inline-block;
  max-width: 270px;
  background: #fff;
  margin-right: 0;
  margin-left: 24px;
}
@media screen and (min-width: 37.5em) {
  .success-stories-legacy .testimonial__block {
    margin-right: 15px;
    margin-left: 15px;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonial__block {
    margin-left: 0;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonial__block {
    margin-right: 40px;
  }
}
.success-stories-legacy .testimonial__block.invisible-block:first-child {
  display: none;
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonial__block.invisible-block:first-child {
    display: inline-block;
  }
}
.success-stories-legacy .testimonial__block.invisible-block:last-child {
  opacity: 0;
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonial__block.invisible-block:last-child {
    opacity: 1;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonial__block.invisible-block {
    display: inline-block;
    width: 0;
    margin-right: 20px;
    opacity: 0;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonial__block.invisible-block {
    width: 8%;
    margin-right: 40px;
  }
}
.success-stories-legacy .testimonial__image {
  width: 48px;
  height: 48px;
  border-radius: 100%;
  margin-bottom: 16px;
}
.success-stories-legacy .testimonial__name {
  color: #2693ff;
  font-size: 14px;
  line-height: 16px;
}
.success-stories-legacy .testimonial__position {
  text-transform: uppercase;
  letter-spacing: 0.05em;
  font-size: 10px;
  line-height: 12px;
  color: #acb6bf;
}
.success-stories-legacy .testimonial__content {
  color: #475059;
  margin-top: 13px;
  font-size: 14px;
  line-height: 16px;
}
.success-stories-legacy .testimonials__arrow {
  display: none;
}
@media screen and (min-width: 64.0625em) {
  .success-stories-legacy .testimonials__arrow {
    display: block;
    font-family: a;
    font-size: 0;
    line-height: 0;
    color: transparent;
    text-shadow: none;
    position: absolute;
    z-index: 3;
    top: 60%;
    width: 54px;
    height: 54px;
    margin-top: -10px;
    background: #ffc926;
    -webkit-box-shadow: 0 1px 6px rgba(255, 201, 38, 0.4);
    box-shadow: 0 1px 6px rgba(255, 201, 38, 0.4);
    border-radius: 50%;
    -webkit-transition: background 0.3s, opacity 0.2s;
    transition: background 0.3s, opacity 0.2s;
    text-decoration: none;
  }
  .success-stories-legacy .testimonials__arrow img,
  .success-stories-legacy .testimonials__arrow svg {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: -7px;
    margin-left: -7px;
  }
  .success-stories-legacy .testimonials__arrow svg {
    width: 14px;
    height: 14px;
  }
}
.success-stories-legacy #testimonials__arrow-left {
  left: 60px;
}
.success-stories-legacy #testimonials__arrow-left img,
.success-stories-legacy #testimonials__arrow-left svg {
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
  width: 14px;
  height: 14px;
}
.success-stories-legacy #testimonials__arrow-right {
  right: 60px;
}
.success-stories-legacy #testimonials__arrow-right img,
.success-stories-legacy #testimonials__arrow-right svg {
  width: 14px;
  height: 14px;
}
.success-stories-legacy .testimonials__overlay-left {
  display: block;
  position: absolute;
  top: 0;
  height: 100%;
  width: 20px;
  left: 10px;
  background: -webkit-gradient(
    linear,
    left top,
    right top,
    from(#fafafb),
    color-stop(40%, #fafafb),
    color-stop(60%, rgba(250, 250, 251, 0.5)),
    color-stop(75%, rgba(250, 250, 251, 0))
  );
  background: linear-gradient(
    to right,
    #fafafb,
    #fafafb 40%,
    rgba(250, 250, 251, 0.5) 60%,
    rgba(250, 250, 251, 0) 75%
  );
  z-index: 2;
}
@media screen and (min-width: 48em) {
  .success-stories-legacy .testimonials__overlay-left {
    width: 20px;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonials__overlay-left {
    width: 120px;
    left: 0;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonials__overlay-left {
    width: 200px;
  }
}
.success-stories-legacy .testimonials__overlay-right {
  display: block;
  position: absolute;
  top: 0;
  height: 100%;
  width: 20px;
  right: 10px;
  background: -webkit-gradient(
    linear,
    right top,
    left top,
    from(#fafafb),
    color-stop(40%, #fafafb),
    color-stop(60%, rgba(250, 250, 251, 0.6)),
    color-stop(75%, rgba(250, 250, 251, 0))
  );
  background: linear-gradient(
    to left,
    #fafafb,
    #fafafb 40%,
    rgba(250, 250, 251, 0.6) 60%,
    rgba(250, 250, 251, 0) 75%
  );
  z-index: 2;
}
@media screen and (min-width: 48em) {
  .success-stories-legacy .testimonials__overlay-right {
    width: 20px;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonials__overlay-right {
    width: 150px;
    right: 0;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonials__overlay-right {
    width: 200px;
  }
}
.success-stories-legacy .testimonials_headline {
  margin-left: 1.25rem;
  margin-bottom: 1.6875rem;
  font-size: 36px;
  line-height: 43px;
  letter-spacing: -1.3616px;
  color: #ffc600;
}
@media screen and (min-width: 48.0625em) {
  .success-stories-legacy .testimonials_headline {
    margin-left: 2.8125rem;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy .testimonials_headline {
    margin-left: 3.4375rem;
  }
}
@media screen and (min-width: 80em) {
  .success-stories-legacy .testimonials_headline {
    margin-left: 120px;
  }
}
@media screen and (min-width: 137.5em) {
  .success-stories-legacy .testimonials_headline {
    margin-left: 9.5%;
  }
}
.success-stories-legacy__lp .stories__wrapper {
  margin-top: 0;
  padding-top: 70px;
}
@media screen and (min-width: 48em) {
  .success-stories-legacy__lp .stories__wrapper {
    padding-left: 60px;
  }
}
.success-stories-legacy__lp .testimonial__block {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  max-width: 270px;
  min-height: 300px;
  max-height: 300px;
  background: #fafafb;
  border-radius: 16px;
  margin-right: 24px;
  margin-left: 0;
  text-align: center;
  position: relative;
  padding: 5.0625rem 1rem 1rem;
}
@media screen and (min-width: 37.5em) {
  .success-stories-legacy__lp .testimonial__block {
    margin-right: 32px;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy__lp .testimonial__block {
    max-width: 15.625rem;
  }
}
.success-stories-legacy__lp .testimonial__image {
  width: 82px;
  height: 82px;
  border-radius: 100%;
  top: -41px;
  left: 50%;
  margin-left: -41px;
  position: absolute;
}
.success-stories-legacy__lp .testimonial__person {
  display: table;
  position: absolute;
  top: 75%;
}
.success-stories-legacy__lp .testimonial__name {
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
  color: #2b334a;
  display: block;
}
.success-stories-legacy__lp .testimonial__position {
  font-style: normal;
  font-weight: 600;
  line-height: 14px;
  text-align: center;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #9da1ae;
  display: block;
}
.success-stories-legacy__lp .testimonial__content {
  font-style: normal;
  font-weight: 400;
  line-height: 19px;
  text-align: center;
  color: #5f677b;
}
@media screen and (min-width: 64.0625em) {
  .success-stories-legacy__lp .testimonials__arrow {
    top: 50%;
    width: 48px;
    height: 48px;
    background: #fff;
    -webkit-box-shadow: 1px 6px 6px rgba(0, 0, 0, 0.04);
    box-shadow: 1px 6px 6px rgba(0, 0, 0, 0.04);
    -webkit-transition: -webkit-box-shadow 0.2s;
    transition: -webkit-box-shadow 0.2s;
    transition: box-shadow 0.2s;
    transition: box-shadow 0.2s, -webkit-box-shadow 0.2s;
  }
  .success-stories-legacy__lp .testimonials__arrow--moved {
    top: 60%;
  }
  .success-stories-legacy__lp .testimonials__arrow img,
  .success-stories-legacy__lp .testimonials__arrow svg {
    opacity: 0.1;
    -webkit-transition: opacity 0.2s;
    transition: opacity 0.2s;
  }
  .success-stories-legacy__lp .testimonials__arrow:hover {
    -webkit-box-shadow: 1px 6px 6px rgba(0, 0, 0, 0.06);
    box-shadow: 1px 6px 6px rgba(0, 0, 0, 0.06);
  }
  .success-stories-legacy__lp .testimonials__arrow:hover img,
  .success-stories-legacy__lp .testimonials__arrow:hover svg {
    opacity: 1;
  }
}
.success-stories-legacy__lp .testimonials__overlay-left {
  background: -webkit-gradient(
    linear,
    left top,
    right top,
    from(#fff),
    to(rgba(255, 255, 255, 0))
  );
  background: linear-gradient(to right, #fff, rgba(255, 255, 255, 0) 100%);
  left: -1px;
}
@media screen and (min-width: 64em) {
  .success-stories-legacy__lp .testimonials__overlay-left {
    width: 130px;
  }
}
.success-stories-legacy__lp .testimonials__overlay-right {
  background: -webkit-gradient(
    linear,
    right top,
    left top,
    from(#fff),
    to(rgba(255, 255, 255, 0))
  );
  background: linear-gradient(to left, #fff, rgba(255, 255, 255, 0) 100%);
  right: -1px;
}
@media screen and (min-width: 64em) {
  .success-stories-legacy__lp .testimonials__overlay-right {
    width: 130px;
  }
}
.success-stories-legacy__customer #testimonial-parent.large-screen {
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.success-stories-legacy__customer .stories__wrapper {
  margin-left: auto;
  margin-right: auto;
}
@media screen and (min-width: 48.0625em) {
  .success-stories-legacy__customer .stories__wrapper {
    width: 95%;
    padding-left: 36px;
  }
}
@media screen and (min-width: 64.0625em) {
  .success-stories-legacy__customer .stories__wrapper {
    width: 95%;
    padding-left: 80px;
  }
}
@media screen and (min-width: 64em) {
  .success-stories-legacy__customer .testimonials__overlay-left,
  .success-stories-legacy__customer .testimonials__overlay-right {
    top: 20%;
    height: 80%;
  }
}
.success-stories-legacy__customer .testimonial__block {
  background: 0 0;
  margin-bottom: 0;
  padding-bottom: 1.875rem;
}
.success-stories-legacy__customer .testimonial__block .card--article {
  height: 100%;
}
.success-stories-legacy__customer .testimonial__block .card--article:hover {
  -webkit-transform: none;
  -ms-transform: none;
  transform: none;
}
.success-stories-legacy__customer .testimonials__arrow svg path {
  fill: #000c2c;
}
.success-stories-legacy__customer #testimonial-dots .dot {
  background: 0 0;
  border: 3px solid #000;
  opacity: 0.2;
}
.success-stories-legacy__customer #testimonial-dots .dot.active {
  background: #ffc600;
  border: 3px solid #ffc600;
  opacity: 1;
}
.success-stories-legacy__customer .testimonials__cta {
  margin-top: 3.875rem;
}
.events__title {
  font-size: 2.25rem;
  margin-bottom: 0.625rem;
}
@media print, screen and (max-width: 80em) {
  .events__title {
    font-size: 2rem;
  }
}
.events__list {
  left: -1.25rem;
  width: calc(100% + 40px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .events__list {
    left: -10px;
    width: calc(100% + 20px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__list {
    left: auto;
    width: 100%;
  }
}
.events__item {
  width: 22rem;
  margin: 2.5rem 1.25rem 0;
  color: #000c2c;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  position: relative;
  overflow: hidden;
}
.events__item.is-hidden {
  display: none;
}
.events__item--not-found {
  font-size: 1.125rem;
  margin: 1.25rem;
}
@media print, screen and (max-width: 48em) {
  .events__item--not-found {
    margin: 1.25rem 0.625rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__item--not-found {
    margin: 1.25rem 0;
  }
}
@media print, screen and (max-width: 80em) {
  .events__item {
    width: 25.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .events__item {
    width: 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .events__item {
    width: calc(50% - 20px);
    margin: 1.25rem 0.625rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .events__item {
    width: 100%;
    margin: 2.5rem 0 0;
  }
}
.events__item-image-wrapper {
  width: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 11.25rem;
  -ms-flex: 0 0 11.25rem;
  flex: 0 0 11.25rem;
  border-top-left-radius: 1.0625rem;
  border-top-right-radius: 1.0625rem;
  background-color: #f8f8f8;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 48em) {
  .events__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
}
.events__item-image {
  width: 100%;
  height: auto;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .events__item-image {
    top: auto;
    left: auto;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    position: relative;
  }
}
.events__item.is-dimmed .events__item-image {
  opacity: 1;
}
.events__item-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  padding: 1.5rem;
  border-bottom-left-radius: 1.0625rem;
  border-bottom-right-radius: 1.0625rem;
  border: 0.0625rem solid #eee;
  border-top: 0;
}
.events__item-label {
  margin-bottom: 0.3125rem;
  font-size: 0.875rem;
  font-weight: 700;
}
.events__item--type-webinar .events__item-label {
  color: #3eaa08;
}
.events__item--type-attend .events__item-label {
  color: #ff7a00;
}
.events__item--type-sponsor .events__item-label {
  color: #7711de;
}
.events__item--type-host .events__item-label {
  color: #005ce6;
}
.events__item-title {
  margin-bottom: 0.9375rem;
  font-size: 1.125rem;
  letter-spacing: 0.01875rem;
}
.events__item-info {
  margin-top: auto;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  color: #879099;
}
.events__item-date {
  padding-right: 0.625rem;
  margin-right: 0.625rem;
  position: relative;
}
.events__item-date:after {
  content: "";
  top: 0.625rem;
  right: -0.125rem;
  width: 0.25rem;
  height: 0.25rem;
  border-radius: 50%;
  background-color: #879099;
  position: absolute;
}
.section-events .container .section {
  padding: 3.75rem 0;
}
.page-careers-open-positions .careers__content {
  max-width: 395px;
  margin: auto;
  font-size: 18px;
  line-height: 25px;
}
.page-careers-open-positions .jobs-wrap {
  padding: 0;
}
@media screen and (min-width: 64em) {
  .page-careers-open-positions .jobs-wrap {
    padding: 0 2rem;
  }
}
.page-careers-open-positions .jobs {
  text-align: left;
  padding: 0 16px;
}
.page-careers-open-positions .jobs__department {
  margin-bottom: 6.25rem;
}
.page-careers-open-positions .jobs__title {
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  letter-spacing: -1.3616px;
  text-transform: capitalize;
  color: #000c2c;
  margin: 1.25rem;
}
.page-careers-open-positions .jobs__title span {
  font-size: 18px;
  line-height: 21px;
  font-weight: 400;
  padding-left: 10px;
  color: #acb6bf;
}
.page-careers-open-positions .jobs__item {
  display: block;
  position: relative;
  border-bottom: 1px solid rgba(0, 12, 44, 0.1);
  margin-bottom: 1.25rem;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.page-careers-open-positions .jobs__item.hidden {
  display: none;
}
.page-careers-open-positions .jobs__item:before {
  content: "";
  width: 0.5rem;
  height: 3.25rem;
  border-radius: 0.25rem;
  position: absolute;
  left: 0;
  top: 50%;
  -webkit-transform: translate(0, -50%);
  -ms-transform: translate(0, -50%);
  transform: translate(0, -50%);
  -webkit-transition: 0.2s;
  transition: 0.2s;
  background-color: #999;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="customer-success"]:before {
  background-color: #60bf00;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="customer-support"]:before {
  background-color: #77e65c;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="engineering"]:before {
  background-color: #4da6ff;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="finance-ops"]:before {
  background-color: #ff9e59;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="marketing"]:before {
  background-color: #5ce6e6;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="people-ops"]:before {
  background-color: #e066ff;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="product-design"]:before {
  background-color: #f66;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="sales"]:before {
  background-color: #ffd659;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="finance-operations"]:before {
  background-color: #d5b94e;
}
.page-careers-open-positions .jobs__item:focus:before,
.page-careers-open-positions .jobs__item:hover:before {
  height: 3.875rem;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="customer-success"]:hover
  .jobs__name {
  color: #60bf00;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="customer-support"]:hover
  .jobs__name {
  color: #77e65c;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="engineering"]:hover
  .jobs__name {
  color: #4da6ff;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="finance-ops"]:hover
  .jobs__name {
  color: #ff9e59;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="marketing"]:hover
  .jobs__name {
  color: #5ce6e6;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="people-ops"]:hover
  .jobs__name {
  color: #e066ff;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="product-design"]:hover
  .jobs__name {
  color: #f66;
}
.page-careers-open-positions
  .jobs__item[data-jobs-item-department="sales"]:hover
  .jobs__name {
  color: #ffd659;
}
.page-careers-open-positions .jobs__list {
  position: relative;
  margin: 0 0 48px;
}
.page-careers-open-positions .jobs__link {
  position: relative;
  z-index: 2;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  padding: 1.5625rem;
  display: flex;
}
.page-careers-open-positions .jobs__name {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  font-weight: 600;
  font-size: 18px;
  line-height: 25px;
  margin-bottom: 0.3125rem;
  color: #000c2c;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.page-careers-open-positions .jobs__location {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 100%;
  -ms-flex: 0 0 100%;
  flex: 0 0 100%;
  font-weight: 400;
  font-size: 14px;
  line-height: 19px;
  color: rgba(0, 12, 44, 0.8);
  margin-bottom: 0;
}
.page-careers-open-positions .jobs__content {
  margin-left: -15px;
  margin-right: -15px;
  margin-top: 80/18em;
  margin-bottom: 40/18em;
  text-align: center;
  max-width: 100%;
  margin: 0 auto;
  padding: 0 30px;
}
.page-careers-open-positions .jobs__content p {
  margin: 0 0 0.5em;
}
.page-careers-open-positions .jobs__content .jobs__cta {
  margin-top: 3em;
  margin-bottom: 3em;
}
.page-careers-open-positions .jobs__cta {
  margin-top: 5em;
  margin-bottom: 5em;
}
.page-careers-open-positions .jobs .job-detail {
  width: 100%;
  font-size: 16px;
  line-height: 32px;
  color: #000;
  word-wrap: break-word;
}
.page-careers-open-positions .jobs .job-detail h1 {
  color: #000 !important;
  font-size: 32px !important;
  line-height: 37px !important;
}
.page-careers-open-positions .jobs .job-detail h2 {
  color: #000 !important;
  font-size: 24px !important;
  line-height: 37px !important;
}
.page-careers-open-positions .jobs .careers .intro__indicator {
  margin-top: 0;
  margin-bottom: -20px;
}
.page-careers-open-positions .jobs #job-list .section--description {
  padding-bottom: 65px;
}
.page-careers-open-positions .jobs #job-list .section--description .row-main {
  padding: 0;
}
.page-careers-open-positions .jobs #job-list .section--description.job-list {
  padding-top: 30px;
  background-image: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(lightgray),
    to(gray)
  );
  background-image: linear-gradient(180deg, #d3d3d3, gray);
}
.page-careers-open-positions .jobs #job-list .no-padding {
  padding: 0;
}
.page-careers-open-positions .jobs .jobsplaces {
  text-align: center;
  width: -webkit-fit-content;
  width: -moz-fit-content;
  width: fit-content;
  padding-bottom: 6px;
  margin: 64px auto;
  white-space: nowrap;
  width: 90%;
}
.page-careers-open-positions .jobs .jobsplaces .dropdown {
  position: relative;
}
.page-careers-open-positions .jobs .jobsplaces .dropdown.open .list {
  display: block;
}
.page-careers-open-positions .jobs .jobsplaces .dropdown .caption {
  font-size: 18px;
  line-height: 32px;
  text-align: center;
  color: #000;
  border-bottom: 2px solid gray;
  min-width: 100%;
  cursor: pointer;
}
.page-careers-open-positions .jobs .jobsplaces .dropdown .caption svg {
  margin-left: 20px;
}
.page-careers-open-positions .jobs .jobsplaces .dropdown .list {
  display: none;
  position: absolute;
  background: #fff;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-box-shadow: 0 10px 32px rgba(71, 80, 89, 0.15);
  box-shadow: 0 10px 32px rgba(71, 80, 89, 0.15);
  border-radius: 8px;
  padding: 24px 0;
  width: 100%;
  top: 40px;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
}
.page-careers-open-positions .jobs .jobsplace {
  color: #000;
  font-size: 18px;
  line-height: 32px;
  padding: 8px 0 8px 24px;
  text-decoration: none;
  cursor: pointer;
  text-align: left;
}
.page-careers-open-positions .jobs .jobsplace:hover {
  background-color: gray;
}
.page-careers-open-positions .jobs .no-jobs {
  font-size: 18px;
  line-height: 36px;
  text-align: center;
  color: gray;
  margin: 0 auto 38px;
}
.page-careers-job-detail .careers__content {
  max-width: 800px;
  margin: auto;
  font-size: 18px;
  line-height: 25px;
}
.page-careers-job-detail .jobs-wrap {
  padding: 0;
}
@media screen and (min-width: 64em) {
  .page-careers-job-detail .jobs-wrap {
    padding: 0 2rem;
  }
}
.page-careers-job-detail .greenhouse-vectors {
  width: 100%;
  margin-top: 3.125rem;
  background-image: url(/wp-content/themes/productboard/public//img/careers/form_elements@2x.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain;
}
.page-careers-job-detail .greenhouse-vectors .greenhouse-form {
  max-width: 600px;
  margin: auto;
}
.page-careers-job-detail .greenhouse-vectors .greenhouse-form #grnhse_app {
  background: #fff;
  -webkit-box-shadow: 0 20px 120px rgba(71, 80, 89, 0.1);
  box-shadow: 0 20px 120px rgba(71, 80, 89, 0.1);
  border-radius: 24px;
}
.roadmap_templates__title {
  font-weight: 600;
  font-size: 3rem;
  line-height: 3.625rem;
  text-align: center;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin: auto;
  margin-bottom: 2rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__title {
    max-width: 560px;
  }
}
.roadmap_templates__subtitle {
  font-size: 1.5rem;
  line-height: 1.9375rem;
  text-align: center;
  letter-spacing: -0.435px;
  color: #7e8494;
  margin: auto;
  margin-bottom: 5.3125rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__subtitle {
    max-width: 550px;
  }
}
.roadmap_templates__items {
  max-width: 940px;
  margin: auto;
}
.roadmap_templates__item {
  padding: 0;
  margin-bottom: 2.5rem;
  position: relative;
  top: 0;
  -webkit-transition: top 0.3s ease 0s;
  transition: top 0.3s ease 0s;
  cursor: pointer;
  border-radius: 16px;
  -webkit-box-shadow: 0 8px 32px rgba(63, 71, 79, 0.08);
  box-shadow: 0 8px 32px rgba(63, 71, 79, 0.08);
  width: auto;
  max-width: 100%;
}
@media print, screen and (max-width: 48.06125em) {
  .roadmap_templates__item {
    margin: 0 auto 2.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item {
    width: 47%;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:hover {
    top: -10px;
    -webkit-box-shadow: 0 20px 32px rgba(63, 71, 79, 0.1);
    box-shadow: 0 20px 32px rgba(63, 71, 79, 0.1);
  }
}
.roadmap_templates__item[data-is-hidden] {
  position: absolute;
  -webkit-transform: scaleY(0);
  -ms-transform: scaleY(0);
  transform: scaleY(0);
  -webkit-transition: -webkit-transform 0.4s ease 0s;
  transition: -webkit-transform 0.4s ease 0s;
  transition: transform 0.4s ease 0s;
  transition: transform 0.4s ease 0s, -webkit-transform 0.4s ease 0s;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:nth-child(odd) {
    margin-right: 0.625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap_templates__item:nth-child(odd) {
    margin-right: 1.25rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item:nth-child(even) {
    margin-left: 0.625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .roadmap_templates__item:nth-child(even) {
    margin-left: 1.25rem;
  }
}
.roadmap_templates__item--image-wrapper {
  overflow: hidden;
}
.roadmap_templates__item--image {
  position: relative;
  display: block;
  overflow: hidden;
  max-width: 450px;
  max-height: 256px;
  margin: auto;
  border: none;
  border-radius: 16px 16px 0 0;
  padding: 24px 24px 0;
  background-color: pink;
  cursor: pointer;
}
.roadmap_templates__item--image img {
  width: 100%;
  height: auto;
  background: #fafafb;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 10px 10px 0 0;
  -webkit-transform-origin: center;
  -ms-transform-origin: center;
  transform-origin: center;
  -webkit-transition: visibility 0.25s ease-in, -webkit-transform 0.25s;
  transition: visibility 0.25s ease-in, -webkit-transform 0.25s;
  transition: transform 0.25s, visibility 0.25s ease-in;
  transition: transform 0.25s, visibility 0.25s ease-in, -webkit-transform 0.25s;
}
.roadmap_templates__item--content {
  position: relative;
  display: block;
  margin: auto;
  max-width: 450px;
  padding: 1.5rem;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__item--content {
    margin: 0;
  }
}
.roadmap_templates__item--title {
  font-weight: 600;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  color: #000c2c;
  font-style: normal;
  font-weight: 600;
  margin-bottom: 0.75rem;
  cursor: pointer;
  -webkit-transition: 0.3s;
  transition: 0.3s;
}
.roadmap_templates__item--text {
  font-size: 1rem;
  line-height: 1.5rem;
  color: #5f677b;
  font-style: normal;
  font-weight: 400;
  margin-bottom: 1.5rem;
}
.roadmap_templates__item--link {
  font-size: 0.875rem;
  line-height: 1.1875rem;
  color: #0079f2;
  font-style: normal;
  font-weight: 400;
  cursor: pointer;
}
.roadmap_templates__cta {
  padding-top: 0;
  display: block;
}
.roadmap_templates__cta[data-is-hidden] {
  display: none;
}
.roadmap_templates__explore {
  color: #000c2c;
  background: #f8f8f8;
  border-radius: 14.8465px;
  font-weight: 600;
  font-size: 1rem;
  line-height: 1.375rem;
  text-align: center;
  padding: 0.875rem 3.40625rem;
  margin: auto;
  max-width: 273px;
  display: block;
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__explore {
    margin-top: 3.5rem;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .roadmap_templates__explore {
    margin-top: 3.5rem;
  }
}
.roadmap_templates__explore:hover {
  color: #000c2c;
  background: #e3e3e3;
}
.section-cards .page-cards__list-intro {
  max-width: 100%;
  margin-bottom: 4rem;
}
.section-cards .page-cards__list-title {
  margin-bottom: 3.5rem;
}
.section-cards .page-cards__list-subtitle {
  margin-bottom: 4rem;
  font-weight: 400;
}
.section-cards .page-cards__list {
  left: -1.25rem;
  width: calc(100% + 40px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__list {
    left: -10px;
    width: calc(100% + 20px);
  }
}
@media print, screen and (max-width: 37.5em) {
  .section-cards .page-cards__list {
    left: auto;
    width: 100%;
  }
}
.section-cards .page-cards__item {
  width: 22rem;
  margin: 2.5rem 1.25rem 0;
  color: #000c2c;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 80em) {
  .section-cards .page-cards__item {
    width: 25.625rem;
  }
}
@media print, screen and (max-width: 64em) {
  .section-cards .page-cards__item {
    width: 18.75rem;
  }
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item {
    width: calc(50% - 20px);
    margin: 1.25rem 0.625rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section-cards .page-cards__item {
    width: 100%;
    margin: 2.5rem 0 0;
  }
}
.section-cards .page-cards__item-image-wrapper {
  width: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 11.25rem;
  -ms-flex: 0 0 11.25rem;
  flex: 0 0 11.25rem;
  border-top-left-radius: 1.0625rem;
  border-top-right-radius: 1.0625rem;
  background-color: #f8f8f8;
  position: relative;
  overflow: hidden;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item-image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
}
.section-cards .page-cards__item-image {
  width: 100%;
  height: auto;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  position: absolute;
}
@media print, screen and (max-width: 48em) {
  .section-cards .page-cards__item-image {
    top: auto;
    left: auto;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    position: relative;
  }
}
.page-cards__item.is-dimmed .section-cards .page-cards__item-image {
  opacity: 1;
}
.section-cards .page-cards__item-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex: 1 1 auto;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  padding: 1.5rem;
  border-bottom-left-radius: 1.0625rem;
  border-bottom-right-radius: 1.0625rem;
  border: 0.0625rem solid #eee;
  border-top: 0;
}
.section-cards .page-cards__item-title {
  margin-bottom: 0.9375rem;
  font-size: 1.125rem;
  letter-spacing: 0.01875rem;
}
.section-cards .page-cards__item-info {
  margin-top: auto;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  color: #879099;
}
.section-connect_boards .connect_boards__title {
  margin-bottom: 1.5rem;
}
.section-connect_boards .connect_boards__items {
  margin-top: 4rem;
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__items {
    margin-top: 5rem;
  }
}
.section-connect_boards .connect_boards__item {
  max-width: 50%;
  border-radius: 20px;
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__item {
    max-width: 100%;
  }
}
.section-connect_boards .connect_boards__item:first-child {
  padding-right: 1.25rem;
}
@media print, screen and (max-width: 64em) {
  .section-connect_boards .connect_boards__item:first-child {
    padding-right: 0.625rem;
  }
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__item:first-child {
    max-width: 75%;
    padding-right: 0;
    margin: auto;
    margin-bottom: 2rem;
  }
}
.section-connect_boards .connect_boards__item:last-child {
  padding-left: 1.25rem;
}
@media print, screen and (max-width: 64em) {
  .section-connect_boards .connect_boards__item:last-child {
    padding-left: 0.625rem;
  }
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__item:last-child {
    max-width: 75%;
    padding-left: 0;
    margin: auto;
  }
}
.section-connect_boards .connect_boards__item-title {
  font-weight: 600;
  font-size: 1.5rem;
  line-height: 2.0625rem;
  color: #000c2c;
  margin-top: 2rem;
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__item-title {
    margin-top: 1.5rem;
    font-size: 1.125rem;
    line-height: 1.5625rem;
  }
}
.section-connect_boards .connect_boards__item-text {
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.5625rem;
  text-align: center;
  color: #2b334a;
  margin-top: 0.75rem;
  max-width: 90%;
  margin: auto;
}
@media print, screen and (max-width: 48em) {
  .section-connect_boards .connect_boards__item-text {
    margin-top: 1rem;
    font-size: 0.875rem;
    line-height: 1.25rem;
  }
}
.section-connect_boards .connect_boards__subtitle {
  font-size: 1.125rem;
  max-width: 31.875rem;
  margin: auto;
}
.loading-spinner-cake {
  z-index: 20;
  position: absolute;
  top: 20px;
  right: 17px;
  border-radius: 50%;
  border-right-color: #ffc600;
  border-top-color: #e81d2e;
  border-bottom-color: #ffc600;
  border-left-color: #0079f2;
  border-width: 12px;
  border-style: solid;
  height: 0;
  width: 0;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
  -webkit-animation: cake-spin 2s linear infinite;
  animation: cake-spin 2s linear infinite;
}
@media print, screen and (max-width: 48em) {
  .loading-spinner-cake {
    right: 27px;
  }
}
.loading-spinner-cake::before {
  display: block;
  content: "";
  position: absolute;
  left: -12px;
  top: -12px;
  border-radius: 50%;
  border-right-color: transparent;
  border-top-color: #e81d2e;
  border-bottom-color: transparent;
  border-left-color: transparent;
  border-width: 12px;
  border-style: solid;
  height: 0;
  width: 0;
  -webkit-transform: rotate(30deg);
  -ms-transform: rotate(30deg);
  transform: rotate(30deg);
  -webkit-box-shadow: 0 0 0 1px #fff inset, 0 0 0 1px #fff;
  box-shadow: 0 0 0 1px #fff inset, 0 0 0 1px #fff;
}
.loading-spinner-cake::after {
  display: block;
  content: "";
  position: absolute;
  left: -12px;
  top: -12px;
  border-radius: 50%;
  border-right-color: transparent;
  border-top-color: transparent;
  border-bottom-color: transparent;
  border-left-color: #0079f2;
  border-width: 12px;
  border-style: solid;
  height: 0;
  width: 0;
  -webkit-transform: rotate(-30deg);
  -ms-transform: rotate(-30deg);
  transform: rotate(-30deg);
  -webkit-box-shadow: 0 0 0 1px #fff inset, 0 0 0 1px #fff;
  box-shadow: 0 0 0 1px #fff inset, 0 0 0 1px #fff;
}
.hero__media-wistia-button .loading-spinner-cake {
  top: 10px;
  left: 30px;
  right: auto;
}
@media screen and (min-width: 48.0625em) {
  .hero__media-wistia-button .loading-spinner-cake {
    left: 40px;
  }
}
.media__wistia-wistia-button .loading-spinner-cake {
  top: 10px;
  left: 20px;
  right: auto;
}
@media screen and (min-width: 48.0625em) {
  .media__wistia-wistia-button .loading-spinner-cake {
    left: 28px;
  }
}
@-webkit-keyframes cake-spin {
  0% {
    -webkit-transform: rotate(0);
    transform: rotate(0);
  }
  100% {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}
@keyframes cake-spin {
  0% {
    -webkit-transform: rotate(0);
    transform: rotate(0);
  }
  100% {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}
.home__section {
  position: relative;
  z-index: 1;
  width: 100%;
  height: 100vh;
}
.home__summary-image {
  margin: 4rem auto 0;
  max-width: 100%;
}
.home__product {
  margin: 4rem auto 0;
  min-height: 40rem;
  width: calc(100% - 40px);
  border-radius: 1.25rem;
  position: relative;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 80em) {
  .home__product {
    min-height: 37.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .home__product {
    width: 100%;
    padding: 0 1.25rem;
    margin-top: 4rem;
    border-radius: 0;
    min-height: auto;
  }
}
.home__product-container {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: static;
}
@media print, screen and (max-width: 64em) {
  .home__product-container {
    padding: 0;
  }
}
.home__product-visual {
  height: 100%;
  width: auto;
  max-width: 50%;
  top: 0;
  right: 0;
  padding: 2.5rem 0;
  position: absolute;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}
@media print, screen and (max-width: 64em) {
  .home__product-visual {
    position: relative;
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    left: 0;
    width: 100%;
    max-width: 100%;
    height: auto;
    padding: 0;
    margin-bottom: 3rem;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.home__product-visual:before {
  content: "";
  left: 60px;
  top: 0;
  width: 200%;
  height: 100%;
  border-radius: 1.25rem;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .home__product-visual:before {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
  }
}
.home__product-visual-image {
  max-height: 100%;
  max-width: 61.875rem;
  border-radius: 1.25rem 0 0 1.25rem;
  -webkit-box-shadow: 0 1rem 2rem rgba(0, 0, 0, 0.1);
  box-shadow: 0 1rem 2rem rgba(0, 0, 0, 0.1);
  width: auto;
  height: auto;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .home__product-visual-image {
    border-radius: 1.25rem;
    max-width: 100%;
  }
}
.home__product-content {
  padding: 0 4.125rem 0 0;
  width: 50%;
}
@media print, screen and (max-width: 64em) {
  .home__product-content {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    padding: 0;
    width: 100%;
    text-align: center;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.home__product-label {
  margin-bottom: 1.25rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
.home__product-label-wrap {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.home__product-label-icon {
  width: 1.25rem;
  height: 1.25rem;
  margin-right: 0.9375rem;
  position: relative;
}
.home__product--insights .home__product-label-icon svg {
  fill: #005ce6;
}
.home__product--prioritization .home__product-label-icon svg {
  fill: #ff2638;
}
.home__product--roadmaps .home__product-label-icon svg {
  fill: #ffc600;
}
.home__product--engagement .home__product-label-icon svg {
  fill: #000c2c;
}
.home__product--portal .home__product-label-icon svg {
  fill: #7711de;
}
.home__product-label-icon-image {
  width: 1.25rem;
  height: 1.25rem;
  vertical-align: top;
}
.home__product-label-text {
  letter-spacing: 0.03125rem;
  line-height: 1rem;
  font-size: 0.875rem;
  font-weight: 700;
  text-transform: uppercase;
}
.home__product--insights .home__product-label-text {
  color: #005ce6;
}
.home__product--prioritization .home__product-label-text {
  color: #ff2638;
}
.home__product--roadmaps .home__product-label-text {
  color: #ffc600;
}
.home__product--engagement .home__product-label-text {
  color: #000c2c;
}
.home__product--portal .home__product-label-text {
  color: #7711de;
}
.home__product-replacement {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-left: 2rem;
}
@media print, screen and (max-width: 64em) {
  .home__product-replacement {
    margin-left: 1rem;
  }
}
.home__product-replacement-text {
  font-size: 0.875rem;
  line-height: 1rem;
  color: #838c96;
}
.home__product-replacement-icon {
  max-height: 1.25rem;
  margin-left: 0.5rem;
}
.home__product-replacement-product {
  margin-left: 0.1875rem;
  font-size: 0.875rem;
  line-height: 1rem;
  color: #838c96;
  font-weight: 600;
  white-space: nowrap;
}
.home__product-title {
  width: 100%;
  margin-bottom: 1.5rem;
  font-size: 2.25rem;
  line-height: 1.2;
  letter-spacing: -0.0851rem;
  color: #202428;
}
@media print, screen and (max-width: 80em) {
  .home__product-title {
    font-size: 2rem;
  }
}
@media print, screen and (max-width: 64em) {
  .home__product-title {
    font-size: 1.625rem;
  }
}
.home__product-text {
  margin-bottom: 1.5rem;
  font-size: 1.125rem;
  line-height: 1.3125rem;
  color: #202428;
}
.home__product-cta {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  color: #666d80;
}
@media print, screen and (max-width: 64em) {
  .home__product-cta {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    text-align: center;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.home__product-cta-text {
  line-height: 1.4;
  font-size: 0.75rem;
  margin-right: 3.125rem;
}
@media print, screen and (max-width: 64em) {
  .home__product-cta-text {
    margin: 0 0 1.25rem;
  }
}
.home__product-cta-button {
  color: #666d80;
  border: 1px solid #e6e7ea;
  white-space: nowrap;
  overflow: hidden;
  border-radius: 0.625rem;
  padding: 0.625rem 2.1875rem;
  font-size: 0.75rem;
  line-height: 1;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
@media print, screen and (max-width: 64em) {
  .home__product-cta-button {
    width: 100%;
    max-width: 12.5rem;
  }
}
.home__product--insights .home__product-cta-button:hover {
  border-color: #005ce6;
  background-color: #005ce6;
  color: #fff;
}
.home__product--prioritization .home__product-cta-button:hover {
  border-color: #ff2638;
  background-color: #ff2638;
  color: #fff;
}
.home__product--roadmaps .home__product-cta-button:hover {
  border-color: #ffc600;
  background-color: #ffc600;
  color: #fff;
}
.home__product--engagement .home__product-cta-button:hover {
  border-color: #000c2c;
  background-color: #000c2c;
  color: #fff;
}
.home__product--portal .home__product-cta-button:hover {
  border-color: #7711de;
  background-color: #7711de;
  color: #fff;
}
.home__product-customer_story {
  margin-top: 2.5rem;
}
.home__product-customer_story--quote {
  font-size: 1rem;
  line-height: 1.5rem;
  color: #838c96;
  font-style: italic;
}
.home__product-customer_story--author {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-top: 1rem;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .home__product-customer_story--author {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.home__product-customer_story--avatar {
  width: 2.5rem;
  height: 2.5rem;
  border-radius: 50%;
}
.home__product-customer_story--authorinfo {
  margin-left: 0.75rem;
  text-align: left;
}
.home__product-customer_story--name {
  font-size: 0.75rem;
  line-height: 1.125rem;
  color: #202428;
  font-weight: 700;
}
.home__product-customer_story--company {
  font-size: 0.625rem;
  line-height: 0.75rem;
  letter-spacing: 0.00625rem;
  text-transform: uppercase;
  color: #838c96;
  opacity: 0.64;
  font-weight: 700;
}
.home__footer-cta {
  position: relative;
}
.home__footer-cta .button {
  margin: 0.625rem;
}
@media screen and (min-width: 27.8125em) {
  .home__footer-cta .button {
    margin: 0 0.625rem;
  }
}
.home-customer-story {
  margin-bottom: 2.5rem;
  min-height: 27.5rem;
  border-radius: 1.25rem;
  color: #000c2c;
  font-weight: 400;
  overflow: hidden;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
}
.home-customer-story:hover {
  color: #000c2c;
  -webkit-box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
  box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
}
.home-customer-story:focus {
  color: #000c2c;
  -webkit-box-shadow: 0 0 0 0.1875rem #cce4fc;
  box-shadow: 0 0 0 0.1875rem #cce4fc;
}
.home-customer-story:focus .home-customer-story__content {
  border-color: #0079f2;
}
.home-customer-story:active {
  color: #000c2c;
  opacity: 0.64;
}
@media print, screen and (max-width: 80em) {
  .home-customer-story {
    min-height: auto;
  }
}
.home-customer-story__image-wrapper {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .home-customer-story__image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding-top: 56.25%;
  }
}
.home-customer-story__image {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}
@media print, screen and (max-width: 64em) {
  .home-customer-story__image {
    left: 0;
    top: 0;
    position: absolute;
  }
}
.home-customer-story__content {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 50%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  padding: 3.625rem 4rem;
  border-top-right-radius: 1.25rem;
  border-bottom-right-radius: 1.25rem;
  border: 0.0625rem solid #e0e2e5;
  border-left: none;
}
@media print, screen and (max-width: 80em) {
  .home-customer-story__content {
    padding: 3rem;
  }
}
@media print, screen and (max-width: 64em) {
  .home-customer-story__content {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    padding: 1.5rem;
    border: 0.0625rem solid #e0e2e5;
    border-top: none;
    border-top-right-radius: 0;
    border-bottom-left-radius: 1.25rem;
  }
}
.home-customer-story__content > :first-child {
  margin-top: 0;
}
.home-customer-story__content > :last-child {
  margin-bottom: 0;
}
.home-customer-story__logo {
  width: auto;
  max-height: 1.5rem;
}
.home-customer-story__title {
  margin: 1rem 0 0;
}
@media print, screen and (max-width: 80em) {
  .home-customer-story__title {
    font-size: 1.5rem;
  }
}
.home-customer-story__text {
  margin: 1.5rem 0 0;
}
.home-customer-story__link {
  margin: 1.5rem 0 0;
}
.summit-intro {
  width: 100%;
  padding: 0 6.25rem;
  max-width: 43rem;
  position: relative;
  text-align: left;
}
@media print, screen and (max-width: 80em) {
  .summit-intro {
    padding: 0;
    max-width: 35rem;
  }
}
@media print, screen and (max-width: 80em) {
  .summit-intro {
    max-width: 100%;
  }
}
.summit-intro__logo {
  margin-bottom: 5rem;
}
.summit-intro__button {
  margin-top: 3rem;
}
.summit-intro__title {
  margin-bottom: 1.875rem;
}
.summit-intro__text {
  font-size: 1rem;
  margin-bottom: 1.875rem;
  font-weight: 700;
}
.summit-intro__datetime {
  font-size: 2rem;
  font-weight: 700;
  text-transform: uppercase;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}
@media print, screen and (max-width: 80em) {
  .summit-intro__datetime {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
}
@media screen and (min-width: 80.0625em) {
  .summit-intro__datetime--multiple {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
}
@media print, screen and (max-width: 64em) {
  .summit-intro__datetime-date {
    width: 100%;
    margin-bottom: 0.625rem;
  }
}
.summit-intro__datetime-date sup {
  font-size: 1.125rem;
}
@media print, screen and (max-width: 64em) {
  .summit-intro__datetime-time {
    width: 100%;
    margin-left: 0;
  }
}
.summit-background {
  left: 1.25rem;
  top: 0;
  width: calc(100% - 40px);
  height: 100%;
  opacity: 1;
  background-position: 117% 50%;
  background-repeat: no-repeat;
  position: absolute;
  overflow: hidden;
}
@media print, screen and (max-width: 64em) {
  .summit-background {
    display: none;
  }
}
.summit-schedule {
  width: 100%;
  margin: 3.75rem auto 0;
}
@media print, screen and (max-width: 48em) {
  .summit-schedule {
    display: block;
  }
}
@media print, screen and (max-width: 48em) {
  .summit-schedule tr {
    display: block;
  }
}
.summit-schedule tr td {
  width: 50%;
  padding: 1.25rem;
  vertical-align: top;
}
@media print, screen and (max-width: 48em) {
  .summit-schedule tr td {
    width: 100%;
    font-size: 0.875rem;
    display: block;
  }
}
.summit-schedule tr td:first-child {
  width: 40%;
  font-size: 1.25rem;
  line-height: 1.3;
  text-align: right;
}
@media print, screen and (max-width: 48em) {
  .summit-schedule tr td:first-child {
    text-align: left;
    font-size: 1.125rem;
    padding-bottom: 0;
    width: 100%;
  }
}
.summit-schedule tr td:last-child {
  width: 60%;
}
@media print, screen and (max-width: 48em) {
  .summit-schedule tr td:last-child {
    width: 100%;
    padding-top: 0.625rem;
  }
}
.summit-schedule tr td h4 {
  font-size: 1.25rem;
  line-height: 1.3;
  margin-bottom: 0.625rem;
}
.card-section.blog-featured .blog-featured__category,
.card-section.blog-featured .blog-featured__excerpt,
.card-section.blog-featured .blog-featured__title {
  width: 100%;
}
.card-section.blog-featured .section__title {
  margin-bottom: 2.3125rem;
}
.card-section.blog-featured .blog-featured__category {
  margin-bottom: 0.75rem;
  font-style: normal;
  font-weight: 600;
  font-size: 10px;
  line-height: 14px;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #11171f;
}
.card-section.blog-featured .blog-featured__title {
  margin-bottom: 1.3125rem;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 33px;
  color: #11171f;
}
.card-section.blog-featured .blog-featured__excerpt {
  margin-bottom: 1.875rem;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  color: #11171f;
}
@media print, screen and (max-width: 64em) {
  .card--mainstory.news {
    display: block;
  }
}
.blog .card--mainstory.news {
  text-align: left;
  margin-top: 5rem;
}
.card--mainstory.news .card-image {
  padding: 0;
}
@media print, screen and (max-width: 64em) {
  .card--mainstory.news .card-image {
    width: 100%;
    border-radius: 1.0625rem 1.0625rem 0 0;
  }
}
@media screen and (min-width: 64em) {
  .card--mainstory.news .card-image {
    width: 45%;
    position: initial;
  }
}
@media print, screen and (max-width: 48.06125em) {
  .card--mainstory.news .card-image .cards__item-image {
    border-radius: 1.0625rem;
  }
}
@media screen and (min-width: 64.0625em) {
  .card--mainstory.news .card-image .cards__item-image {
    position: absolute;
    width: auto;
    height: 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .card--mainstory.news .blog-featured {
    width: 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .card--mainstory.news .blog-featured__image-desktop {
    display: none;
  }
}
@media screen and (min-width: 64.0625em) {
  .card--mainstory.news .blog-featured__image-mobile {
    display: none;
  }
}
.card--mainstory.news .hero__content {
  margin-bottom: 5rem;
}
figcaption {
  margin-bottom: 1.875rem;
}
#customers-list {
  opacity: 1;
  -webkit-transition: opacity 0.1s;
  transition: opacity 0.1s;
}
#customers-list.fade {
  opacity: 0;
}
.section--customer {
  margin-top: 12.5rem;
  padding: 1.875rem 0;
}
@media (max-height: 1000px) and (min-width: 1025px) {
  .section--customer {
    margin-top: 8.75rem;
  }
}
@media print, screen and (max-width: 64em) {
  .section--customer {
    margin-top: 6.25rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .section--customer {
    margin-top: 5rem;
  }
}
.section--customer .customer {
  color: #475059;
}
@media print, screen and (max-width: 37.5em) {
  .section--customer .grid-container {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
.customer .section__content .grid-container {
  padding-left: 2.875rem;
  padding-right: 2.875rem;
}
@media screen and (min-width: 37.5em) {
  .customer .section__content .grid-container {
    padding-left: 4.375rem;
    padding-right: 4.375rem;
  }
}
@media screen and (min-width: 48em) {
  .customer .section__content .grid-container {
    padding-left: 1.25rem;
    padding-right: 1.25rem;
  }
}
@media screen and (min-width: 64em) {
  .customer .section__content .grid-container {
    padding-left: 0;
    padding-right: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .customer.cell {
    width: 100%;
    margin-left: 0;
    margin-right: 0;
  }
}
.customer .section__title {
  margin-bottom: 2.5625rem;
}
@media print, screen and (min-width: 64.0625em) {
  .customer .section__title {
    display: none;
  }
}
.customer__meta {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64.06125em) {
  .customer__meta {
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }
}
.customer__meta li {
  margin-right: 1.25rem;
}
@media print, screen and (max-width: 37.5em) {
  .customer__meta li {
    margin-right: 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .customer__meta li {
    width: 100%;
  }
}
.customer__category,
.customer__date {
  opacity: 0.4;
  margin-right: 0.625rem;
}
@media print, screen and (min-width: 64.0625em) {
  .customer__category,
  .customer__date {
    margin-left: 2.5rem;
  }
}
.customer h1,
.customer h2,
.customer h3,
.customer h4,
.customer h5 {
  margin-bottom: 1.5625rem;
  margin-top: 2.8125rem;
}
.customer h1 {
  color: #000c2c;
  margin-top: 0;
  margin-bottom: 1.875rem;
}
@media print, screen and (max-width: 64em) {
  .customer h1 {
    text-align: center;
  }
}
.customer img,
.customer ol,
.customer p,
.customer ul {
  margin-bottom: 1.25rem;
}
.customer ol,
.customer p,
.customer ul {
  font-size: 1.125rem;
  line-height: 1.5625rem;
}
.customer ol {
  margin-left: 0;
  list-style: none;
  counter-reset: item;
}
.customer ol li {
  padding-bottom: 2.5rem;
  padding-left: 3.125rem;
  position: relative;
}
.customer ol li:before {
  content: counter(item) ". ";
  counter-increment: item;
  opacity: 0.4;
  font-weight: 700;
  position: absolute;
  left: 0;
}
@media print, screen and (max-width: 64em) {
  .customer .hero__image-wrap {
    display: none;
  }
}
@media print, screen and (max-width: 37.5em) {
  .customer .hero__image-wrap {
    padding-left: 0.625rem;
    padding-right: 0.625rem;
  }
}
.customer .hero__image-wrap img {
  width: 100%;
  border-radius: 0.625rem;
}
.aligncenter {
  display: block;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}
.alignright {
  display: block;
  margin-left: auto;
  text-align: right;
}
.customer-sidebar {
  position: -webkit-sticky;
  position: sticky;
  top: 7.5rem;
  left: 0;
  float: none;
  font-size: 0;
  padding: 3.625rem;
  padding: 1.875rem;
}
@media print, screen and (max-width: 64.06125em) {
  .customer-sidebar {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
}
@media print, screen and (min-width: 48.0625em) {
  .customer-sidebar {
    padding: 3.625rem;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .customer-sidebar {
    padding: 3.625rem 0;
  }
}
@media screen and (min-width: 79.375em) {
  .customer-sidebar {
    padding: 3.625rem;
  }
}
.customer-sidebar__item {
  width: 2.25rem;
  height: 2.25rem;
  background: #fff;
  border: 1px solid #d5dde3;
  color: #475059;
  border-radius: 50%;
  display: block;
  position: relative;
  -webkit-transition: background 0.25s ease;
  transition: background 0.25s ease;
}
@media print, screen and (min-width: 64.0625em) {
  .customer-sidebar__item {
    margin-bottom: 1.25rem;
  }
}
@media print, screen and (max-width: 64.06125em) {
  .customer-sidebar__item:not(:last-child) {
    margin-right: 0.625rem;
  }
}
.customer-sidebar__item:hover {
  background: #d5dde3;
}
.customer-sidebar__item svg {
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%) scale(0.75);
  -ms-transform: translate(-50%, -50%) scale(0.75);
  transform: translate(-50%, -50%) scale(0.75);
}
.customer-sidebar__interviewee-block {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__interviewee-block {
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }
}
.customer-sidebar__interviewee-block--text {
  display: grid;
}
.customer-sidebar__info {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 12.25rem;
  -ms-flex: 0 0 12.25rem;
  flex: 0 0 12.25rem;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__info {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.customer-sidebar__info-logo--wrapper {
  width: 100%;
}
.customer-sidebar__info-logo--image {
  display: block;
  margin: 0 auto 36px;
}
.customer-sidebar__info-item {
  margin-bottom: 1.875rem;
  font-size: 1.125rem;
  color: #879099;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__info-item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 50%;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
    font-size: 1rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .customer-sidebar__info-item {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__info-item:nth-child(2n + 1) {
    padding-right: rem-cac(20);
  }
}
@media print, screen and (max-width: 37.5em) {
  .customer-sidebar__info-item:nth-child(2n + 1) {
    padding-right: 0;
  }
}
.customer-sidebar__info-item:last-child {
  margin-bottom: 0;
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__info-item p {
    font-size: 1rem;
  }
}
.customer-sidebar__info-item > :first-child {
  margin-top: 0;
}
.customer-sidebar__info-item > :last-child {
  margin-bottom: 0;
}
.customer-sidebar__info-item__black {
  color: #000c2c;
  font-size: 14px;
  line-height: 16px;
  display: block;
  margin-bottom: 0.3125rem;
}
.customer-sidebar__info-item__quote {
  margin: 4.375rem 0 1.25rem;
}
@media print, screen and (max-width: 64em) {
  .customer-sidebar__info-item__quote {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 0.625rem 0 1.25rem;
  }
}
.customer-sidebar__info-item__quote--position {
  font-size: 10px;
  line-height: 12px;
  font-weight: 600;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}
.customer-sidebar__info-item__quote--text {
  font-size: 14px;
  line-height: 16px;
  color: #000c2c;
  opacity: 0.5;
}
.customer-sidebar__info-item__quote .customer-sidebar__info-item {
  margin-top: 1.25rem;
}
.customer-sidebar__info-title {
  color: #000c2c;
  font-size: 10px;
  line-height: 12px;
  font-weight: 600;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  opacity: 0.3;
  margin-bottom: 0.625rem;
}
.customer-sidebar__info-title__company_title {
  color: #0569ff;
  font-size: 14px;
  line-height: 16px;
}
@media print, screen and (max-width: 37.5em) {
  .customer-sidebar .grid-container {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
.page-template-default.roadmap-templates-home .hero {
  margin-bottom: 0;
}
.page-template-default.roadmap-templates-home section:first-of-type {
  padding-top: 3.9375rem;
}
@media print, screen and (min-width: 48.0625em) {
  .page-template-default.roadmap-templates-home section:first-of-type {
    padding: 4.25rem 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .page-template-default.roadmap-templates-home section:first-of-type {
    padding: 0 0 4.5625rem;
    margin-top: 4.5625rem;
  }
}
.page-template-template-roadmap section:first-of-type {
  padding-top: 0;
}
@media print, screen and (min-width: 48.0625em) {
  .page-template-template-roadmap section:first-of-type {
    padding: 2.75rem 0;
  }
}
@media print, screen and (min-width: 64.0625em) {
  .page-template-template-roadmap section:first-of-type {
    padding: 9rem 0 7rem;
  }
}
.page-template-template-roadmap .roadmap_templates__title {
  font-style: normal;
  font-weight: 600;
  font-size: 2rem;
  line-height: 2.375rem;
  letter-spacing: -1.3616px;
  margin-bottom: 4.6875rem;
}
@media print, screen and (min-width: 48.0625em) {
  .page-template-template-roadmap .roadmap_templates__title {
    margin-bottom: 6rem;
    font-size: 2.25rem;
    line-height: 2.6875rem;
  }
}
.page-template-template-security .page-security-intro {
  margin: auto;
}
@media screen and (min-width: 64em) {
  .page-template-template-security .page-security-intro {
    max-width: 55%;
  }
}
.page-template-template-security
  .page-security-intro
  .page-security-intro-title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  text-align: center;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin-bottom: 29px;
}
.page-template-template-security
  .page-security-intro
  .page-security-intro-text {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  text-align: center;
  color: #475059;
}
.page-template-template-security
  .page-security-intro
  .page-security-intro-text
  p {
  margin-bottom: 29px;
}
.page-template-template-security
  .page-security-intro
  .page-security-intro-learn-more {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  text-align: center;
  color: #2693ff;
}
.page-template-template-security .page-security-intro-image {
  margin-top: 125px;
}
.page-template-template-security .page-security-intro-image img {
  margin: auto;
}
.page-template-template-security .section-buttons {
  margin-left: auto;
  margin-right: auto;
}
@media screen and (min-width: 48em) {
  .page-template-template-security .section-buttons {
    max-width: 70%;
  }
}
.page-template-template-security .section-buttons .grid-container {
  padding: 0 1rem;
}
.page-template-template-security .section-buttons .button {
  min-width: 0;
  background: #fafafb;
  border-radius: 8px;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 19px;
  color: #000c2c;
  -webkit-box-flex: 0;
  -webkit-flex: none;
  -ms-flex: none;
  flex: none;
  -webkit-box-ordinal-group: 1;
  -webkit-order: 0;
  -ms-flex-order: 0;
  order: 0;
  -webkit-align-self: center;
  -ms-flex-item-align: center;
  align-self: center;
  margin: 0.875rem 0;
  padding: 0.875rem 1.875rem;
}
.page-template-template-security .section-buttons .button:hover {
  color: #fafafb;
  background: #000c2c;
}
.page-template-template-security .section-accordions {
  margin-left: auto;
  margin-right: auto;
}
@media screen and (min-width: 64em) {
  .page-template-template-security .section-accordions {
    max-width: 75%;
  }
}
.page-template-template-security .section-accordions--header {
  scroll-margin-top: 7.5rem;
}
.page-template-template-security .section-accordions .accordion:last-child {
  margin-bottom: 0;
}
.page-template-template-security .report-wrap .report-box {
  padding: 2rem;
}
@media print, screen and (max-width: 64em) {
  .page-template-template-security .report-wrap .report-image {
    margin-bottom: 1rem;
  }
}
.page-template-template-security .report-wrap .report-title {
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 25px;
}
@media print, screen and (max-width: 64em) {
  .page-template-template-security .report-wrap .report-title {
    margin-bottom: 1rem;
  }
}
.page-template-template-security .report-wrap .report-text p {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 19px;
  color: #475059;
}
.page-template-template-security .learn .learn-title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  text-align: center;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin-bottom: 48px;
}
.accordion {
  width: 100%;
  color: #475059;
  background: #fff;
}
.accordion + .accordion {
  margin-top: 7rem;
}
@media print, screen and (max-width: 64em) {
  .accordion + .accordion {
    margin-top: 4rem;
  }
}
.accordion .accordion-toggle {
  display: none;
}
.accordion .accordion-option {
  position: relative;
  border-bottom: 2px solid #e3e3e3;
}
.accordion .accordion-content,
.accordion .accordion-title {
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  margin: 0;
  padding-left: 0;
}
.accordion .accordion-title {
  background: #fff;
  padding: 24px 0;
  display: block;
  color: #000c2c;
  width: 100%;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 33px;
}
.accordion .accordion-short-text,
.accordion .accordion-short-text p {
  width: 100%;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  padding-top: 24px;
}
.accordion .accordion-content {
  max-height: 0;
  overflow: hidden;
  background-color: #fff;
}
.accordion .accordion-content p {
  margin: 0;
  padding: 0.5em 1em 1em 0;
  font-size: 0.9em;
  line-height: 1.5;
}
.accordion .accordion-chevron {
  position: absolute;
  background-image: url(/wp-content/themes/productboard/public/img/icons/icon-chevron-down.svg);
  width: 10px;
  height: 6px;
  top: 3rem;
  right: 0;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}
.accordion .accordion-toggle:checked + .accordion-title + .accordion-content {
  max-height: inherit;
  padding-bottom: 40px;
}
.accordion .accordion-toggle:checked ~ label .accordion-chevron {
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.accordion {
  width: 100%;
}
.accordion__item {
  width: 100%;
  border-bottom: 2px solid #e3e3e3;
  position: relative;
}
.accordion__checkbox {
  opacity: 0;
  position: absolute;
}
.accordion__title {
  width: 100%;
  padding: 1.875rem 3.125rem 1.875rem 0;
  font-size: 1.5rem;
  line-height: 1.4;
  font-weight: 700;
  margin: 0 !important;
  position: relative;
  display: block;
}
@media print, screen and (max-width: 64em) {
  .accordion__title {
    font-size: 1.125rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .accordion__title {
    font-size: 1rem;
    padding: 1.25rem 1.25rem 1.25rem 0;
  }
}
.accordion__title:after {
  content: "";
  top: 50%;
  right: 1.25rem;
  width: 0.625rem;
  height: 0.625rem;
  margin-top: -0.3125rem;
  border-left: 2px solid #879099;
  border-bottom: 2px solid #879099;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  -webkit-transition: 0.15s;
  transition: 0.15s;
  position: absolute;
}
@media print, screen and (max-width: 37.5em) {
  .accordion__title:after {
    right: 0;
  }
}
.accordion__item > .accordion__checkbox:checked + .accordion__title:after {
  -webkit-transform: rotate(135deg);
  -ms-transform: rotate(135deg);
  transform: rotate(135deg);
}
.accordion__content {
  font-size: 1.125rem;
  line-height: 1.4;
  margin-bottom: 2.1875rem;
  display: none;
}
@media print, screen and (max-width: 64em) {
  .accordion__content {
    font-size: 1rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .accordion__content {
    margin-bottom: 1.25rem;
  }
}
.accordion__item
  > .accordion__checkbox:checked
  + .accordion__title
  + .accordion__content {
  display: block;
}
.accordion__content > :first-child {
  margin-top: 0;
}
.accordion__content > :last-child {
  margin-bottom: 0;
}
@media print, screen and (max-width: 48em) {
  .page-template-template-integrations .section-integrations .integration {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
}
.page-template-template-integrations .section-integrations .integrations-item {
  margin-bottom: 96px;
}
.page-template-template-integrations .section-integrations .integrations-title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin-bottom: 24px;
}
.page-template-template-integrations
  .section-integrations
  .integrations-description {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  color: #879099;
  margin-bottom: 48px;
}
.page-template-template-integrations .section-integrations .integration-item {
  min-width: 192px;
  padding: 10px;
}
@media print, screen and (max-width: 48em) {
  .page-template-template-integrations .section-integrations .integration-item {
    min-width: 145px;
    padding: 10px;
  }
}
.page-template-template-integrations .section-integrations .integration-image {
  height: 10.75rem;
  background: #fafafb;
  border-radius: 16px;
  padding: 3rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
@media print, screen and (max-width: 48em) {
  .page-template-template-integrations
    .section-integrations
    .integration-image {
    padding: 2.4rem;
    height: 7.8125rem;
  }
}
@media (min-width: 1025px) {
  .page-template-template-integrations
    .section-integrations
    a.integration-image:hover {
    background: #e1e6eb;
  }
}
.page-template-template-integrations .section-integrations .integration-title {
  padding: 16px;
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 25px;
  color: #000c2c;
}
@media print, screen and (max-width: 48em) {
  .page-template-template-integrations
    .section-integrations
    .integration-title {
    font-size: 1rem;
    line-height: 1.4;
    text-align: center;
  }
}
.page-template-template-integrations .section-learn .learn-title {
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  text-align: center;
  letter-spacing: -1.3616px;
  color: #000c2c;
  margin-bottom: 30px;
}
.page-template-template-integrations .section-learn .learn-text {
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 31px;
  text-align: center;
  letter-spacing: -0.435px;
  color: #879099;
  margin-bottom: 48px;
}
.lp {
  text-align: center;
}
.lp .hero__subtitle {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 25px;
  color: #000c2c;
  opacity: 0.8;
  margin: auto;
  width: 100%;
}
.lp .hero__buttons {
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
.lp-v3 {
  text-align: center;
}
.lp-v3.hero {
  padding: 0;
  min-height: 10rem;
}
.lp-v3.hero .hero__subtitle {
  font-size: 1.25rem;
  color: #000c2c;
  opacity: 0.4;
  font-weight: 400;
  width: 100%;
}
.lp-v3.hero .hero__buttons {
  margin-left: auto;
  margin-right: auto;
}
.lp-v3.section-content {
  text-align: left;
}
.lp-v3.section-content h2.section__title {
  text-align: left !important;
}
.lp-v3.section-media {
  text-align: left;
}
.lp-v4.hero .hero__subtitle {
  font-size: 1.25rem;
  color: #000c2c;
  opacity: 0.4;
  font-weight: 400;
}
.iframe-livestorm {
  min-height: 500px;
}
.interactive-demo {
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  width: 90rem;
  height: 56.25rem;
  font-size: 1rem;
  padding: 0.75rem;
  border-radius: 0.9375rem;
  -webkit-box-shadow: 0 1.875rem 5rem rgba(0, 0, 0, 0.1);
  box-shadow: 0 1.875rem 5rem rgba(0, 0, 0, 0.1);
  background-color: #fff;
  position: relative;
  overflow: hidden;
}
@media (max-width: 1600px), (max-height: 1000px) {
  .interactive-demo {
    width: 71rem;
    height: 44.375rem;
    font-size: 0.8rem;
  }
}
@media (max-width: 1200px), (max-height: 800px) {
  .interactive-demo {
    width: 62rem;
    height: 38.75rem;
    font-size: 0.6875rem;
  }
}
@media (max-width: 1000px) {
  .interactive-demo {
    width: 100%;
    height: 0;
    padding-top: 56.25%;
  }
}
.interactive-demo:after,
.interactive-demo:before {
  content: "";
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  border-radius: 0.9375rem;
  position: absolute;
  pointer-events: none;
}
.interactive-demo:before {
  z-index: 10;
  border: 0.75rem solid #fff;
}
.interactive-demo [data-intdem-section] {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  pointer-events: none;
  position: absolute;
  background-size: cover;
}
.interactive-demo [data-intdem-section].is-active {
  z-index: 2;
  pointer-events: all;
  opacity: 1;
}
.interactive-demo [data-intdem-el] {
  position: absolute;
}
.interactive-demo [data-intdem-tooltip] {
  padding: 1.875rem;
  max-width: 28.75rem;
  border-radius: 1.5rem;
  font-size: 94%;
  line-height: 1.6;
  font-weight: 700;
  color: #fff;
  opacity: 0;
  -webkit-transition-duration: 1s;
  transition-duration: 1s;
  background-color: #2b334a;
  position: absolute;
}
@media (max-width: 1200px), (max-height: 1000px) {
  .interactive-demo [data-intdem-tooltip] {
    max-width: 23.125rem;
    padding: 1.5rem;
    border-radius: 1.125rem;
  }
}
@media (max-width: 1200px), (max-height: 800px) {
  .interactive-demo [data-intdem-tooltip] {
    max-width: 19.75rem;
    padding: 1.25rem;
    border-radius: 0.9375rem;
  }
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="top"] {
  -webkit-transform: translateY(10%);
  -ms-transform: translateY(10%);
  transform: translateY(10%);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="bottom"] {
  -webkit-transform: translateY(-10%);
  -ms-transform: translateY(-10%);
  transform: translateY(-10%);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="left"] {
  -webkit-transform: translateX(10%);
  -ms-transform: translateX(10%);
  transform: translateX(10%);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="right"] {
  -webkit-transform: translateX(-10%);
  -ms-transform: translateX(-10%);
  transform: translateX(-10%);
}
.interactive-demo [data-intdem-tooltip]:after {
  content: "";
  width: 1.625rem;
  height: 1.625rem;
  border-radius: 0.125rem;
  background-color: #2b334a;
  position: absolute;
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="top"]:after {
  top: 0;
  left: 50%;
  -webkit-transform: translate(-50%, -35%) rotate(45deg);
  -ms-transform: translate(-50%, -35%) rotate(45deg);
  transform: translate(-50%, -35%) rotate(45deg);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="bottom"]:after {
  bottom: 0;
  left: 50%;
  -webkit-transform: translate(-50%, 35%) rotate(45deg);
  -ms-transform: translate(-50%, 35%) rotate(45deg);
  transform: translate(-50%, 35%) rotate(45deg);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="left"]:after {
  top: 50%;
  left: 0;
  -webkit-transform: translate(-35%, -50%) rotate(45deg);
  -ms-transform: translate(-35%, -50%) rotate(45deg);
  transform: translate(-35%, -50%) rotate(45deg);
}
.interactive-demo [data-intdem-tooltip][data-intdem-tooltip="right"]:after {
  top: 50%;
  right: 0;
  -webkit-transform: translate(35%, -50%) rotate(45deg);
  -ms-transform: translate(35%, -50%) rotate(45deg);
  transform: translate(35%, -50%) rotate(45deg);
}
.interactive-demo [data-intdem-tooltip] > :first-child {
  margin-top: 0;
}
.interactive-demo [data-intdem-tooltip] > :last-child {
  margin-bottom: 0;
}
.interactive-demo
  [data-intdem-section]:not([data-intdem-section="1"]).is-active
  [data-intdem-tooltip] {
  opacity: 1;
  -webkit-transform: translate(0);
  -ms-transform: translate(0);
  transform: translate(0);
}
.interactive-demo [data-intdem-pager] {
  z-index: 50;
  width: 11.875rem;
  right: 2.5rem;
  bottom: 2.5rem;
  position: absolute;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  opacity: 0;
}
@media (max-width: 1600px), (max-height: 1000px) {
  .interactive-demo [data-intdem-pager] {
    right: 1.875rem;
    bottom: 1.875rem;
    width: 8.125rem;
  }
}
.interactive-demo [data-intdem-pager-status] {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 4.375rem;
  -ms-flex: 0 0 4.375rem;
  flex: 0 0 4.375rem;
  line-height: 3.125rem;
  font-weight: 700;
  color: #2b334a;
  text-align: center;
}
@media (max-width: 1600px), (max-height: 1000px) {
  .interactive-demo [data-intdem-pager-status] {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 3.125rem;
    -ms-flex: 0 0 3.125rem;
    flex: 0 0 3.125rem;
    line-height: 2.5rem;
  }
}
.interactive-demo [data-intdem-pager-nav] {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 3.125rem;
  -ms-flex: 0 0 3.125rem;
  flex: 0 0 3.125rem;
  height: 3.125rem;
  border-radius: 0.75rem;
  background-color: #2b334a;
  -webkit-box-shadow: 0 0.25rem 1rem rgba(43, 51, 74, 0.25);
  box-shadow: 0 0.25rem 1rem rgba(43, 51, 74, 0.25);
  -webkit-transition: 0.2s;
  transition: 0.2s;
  position: relative;
  cursor: pointer;
}
@media (max-width: 1600px), (max-height: 1000px) {
  .interactive-demo [data-intdem-pager-nav] {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 2.5rem;
    -ms-flex: 0 0 2.5rem;
    flex: 0 0 2.5rem;
    height: 2.5rem;
  }
}
.interactive-demo [data-intdem-pager-nav]:hover {
  background-color: #0079f2;
}
.interactive-demo [data-intdem-pager-nav]:before {
  content: "";
  width: 10px;
  height: 10px;
  left: 50%;
  top: 50%;
  border-left: 3px solid #fff;
  border-bottom: 3px solid #fff;
  -webkit-transform: translate(-30%, -50%) rotate(45deg);
  -ms-transform: translate(-30%, -50%) rotate(45deg);
  transform: translate(-30%, -50%) rotate(45deg);
  position: absolute;
}
.interactive-demo [data-intdem-pager-nav="next"]:before {
  -webkit-transform: translate(-70%, -50%) rotate(-135deg);
  -ms-transform: translate(-70%, -50%) rotate(-135deg);
  transform: translate(-70%, -50%) rotate(-135deg);
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="1"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s2-bg.png);
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="1"]
  [data-intdem-tooltip] {
  left: 55%;
  top: 13.5%;
  -webkit-transition-delay: 1.5s;
  transition-delay: 1.5s;
  max-width: 360px;
}
.interactive-demo[data-intdem="insights"].started [data-intdem-pager],
.interactive-demo[data-intdem="insights"].started
  [data-intdem-section="1"]
  [data-intdem-tooltip] {
  -webkit-animation: s1-fade-in 1s;
  animation: s1-fade-in 1s;
  -webkit-animation-delay: 1s;
  animation-delay: 1s;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s1-insights"] {
  left: 27.22%;
  top: 100.8%;
  width: 28.3%;
  height: 89.2%;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  opacity: 0;
  -webkit-transform: translateY(10%);
  -ms-transform: translateY(10%);
  transform: translateY(10%);
}
.interactive-demo[data-intdem="insights"].started
  [data-intdem-el="s1-insights"] {
  -webkit-animation: s1-slide-up 1s;
  animation: s1-slide-up 1s;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
@-webkit-keyframes s1-slide-up {
  from {
    top: 100%;
  }
  to {
    top: 10.8%;
  }
}
@keyframes s1-slide-up {
  from {
    top: 100%;
  }
  to {
    top: 10.8%;
  }
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="1"].is-active
  [data-intdem-el="s1-insights"] {
  opacity: 1;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s1-highlight"] {
  left: 27.22%;
  top: 14.77%;
  width: 28.26%;
  height: 12.33%;
  border-radius: 0.3125rem;
  border: 2px solid #2693ff;
  background-color: rgba(38, 147, 255, 0.05);
  opacity: 0;
  -webkit-transition: 1s 1.5s;
  transition: 1s 1.5s;
  pointer-events: none;
  cursor: pointer;
  -webkit-animation: s1-pulse 3s linear infinite;
  animation: s1-pulse 3s linear infinite;
}
.interactive-demo[data-intdem="insights"].started
  [data-intdem-el="s1-highlight"] {
  -webkit-animation: s1-fade-in 1s, s1-pulse 3s linear infinite;
  animation: s1-fade-in 1s, s1-pulse 3s linear infinite;
  -webkit-animation-delay: 1s;
  animation-delay: 1s;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="1"].is-active
  [data-intdem-el="s1-highlight"] {
  pointer-events: all;
}
@-webkit-keyframes s1-fade-in {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes s1-fade-in {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes s1-pulse {
  0% {
    border-color: rgba(38, 147, 255, 0.4);
    background-color: rgba(38, 147, 255, 0.05);
  }
  50% {
    border-color: #2693ff;
    background-color: rgba(38, 147, 255, 0.3);
  }
  100% {
    border-color: rgba(38, 147, 255, 0.4);
    background-color: rgba(38, 147, 255, 0.05);
  }
}
@keyframes s1-pulse {
  0% {
    border-color: rgba(38, 147, 255, 0.4);
    background-color: rgba(38, 147, 255, 0.05);
  }
  50% {
    border-color: #2693ff;
    background-color: rgba(38, 147, 255, 0.3);
  }
  100% {
    border-color: rgba(38, 147, 255, 0.4);
    background-color: rgba(38, 147, 255, 0.05);
  }
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s1-cursor"] {
  width: 5%;
  height: 5%;
  opacity: 0;
  top: 29%;
  left: 54%;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  -webkit-transform: translateY(20%);
  -ms-transform: translateY(20%);
  transform: translateY(20%);
  pointer-events: none;
  cursor: pointer;
  z-index: 1;
}
.interactive-demo[data-intdem="insights"].started [data-intdem-el="s1-cursor"] {
  -webkit-animation: s1-hand-fade 0.6s;
  animation: s1-hand-fade 0.6s;
  -webkit-animation-delay: 1.6s;
  animation-delay: 1.6s;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
@-webkit-keyframes s1-hand-fade {
  0% {
    opacity: 0;
    top: 29%;
    left: 54%;
  }
  50% {
    opacity: 1;
    top: 23%;
    left: 48.5%;
  }
  75% {
    opacity: 1;
    top: 24%;
    left: 48.5%;
  }
  100% {
    opacity: 1;
    top: 23%;
    left: 48.5%;
  }
}
@keyframes s1-hand-fade {
  0% {
    opacity: 0;
    top: 29%;
    left: 54%;
  }
  50% {
    opacity: 1;
    top: 23%;
    left: 48.5%;
  }
  75% {
    opacity: 1;
    top: 24%;
    left: 48.5%;
  }
  100% {
    opacity: 1;
    top: 23%;
    left: 48.5%;
  }
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="2"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s3-bg.png);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el^="s2-highlight"] {
  left: 60.76%;
  height: 3.55%;
  width: 0;
  border-radius: 0.125rem;
  background-color: rgba(38, 147, 255, 0.1);
  -webkit-transition-duration: 1s;
  transition-duration: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s2-highlight-1"] {
  top: 35.33%;
  -webkit-transition-delay: 0.5s;
  transition-delay: 0.5s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="2"].is-active
  [data-intdem-el="s2-highlight-1"] {
  width: 35.76%;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s2-highlight-2"] {
  top: 39.33%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="2"].is-active
  [data-intdem-el="s2-highlight-2"] {
  width: 26.04%;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s2-button"] {
  width: 4.44%;
  height: 8.33%;
  left: 80%;
  top: 45%;
  -webkit-transition: 1s 1.5s;
  transition: 1s 1.5s;
  -webkit-transform: translateY(20%);
  -ms-transform: translateY(20%);
  transform: translateY(20%);
  opacity: 0;
  pointer-events: none;
  cursor: pointer;
  -webkit-animation: 2s ease-in-out 1s infinite forwards running s2-pulse;
  animation: 2s ease-in-out 1s infinite forwards running s2-pulse;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="2"].is-active
  [data-intdem-el="s2-button"] {
  opacity: 1;
  -webkit-transform: translateY(0);
  -ms-transform: translateY(0);
  transform: translateY(0);
  pointer-events: all;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="2"]
  [data-intdem-tooltip] {
  left: 54.3%;
  top: 44.7%;
  -webkit-transition-delay: 2s;
  transition-delay: 2s;
}
@-webkit-keyframes s2-pulse {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(-10px);
    transform: translateY(-10px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}
@keyframes s2-pulse {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(-10px);
    transform: translateY(-10px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="3"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s4-bg.png);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s3-highlight"] {
  left: 5.5%;
  top: 50.8%;
  width: 53.7%;
  height: 5%;
  border: 2px solid #2693ff;
  background-color: rgba(38, 147, 255, 0.05);
  border-radius: 0.3125rem;
  opacity: 0;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  pointer-events: none;
  cursor: pointer;
  -webkit-animation: s1-pulse 3s linear infinite;
  animation: s1-pulse 3s linear infinite;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="3"].is-active
  [data-intdem-el="s3-highlight"] {
  opacity: 1;
  pointer-events: all;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="3"]
  [data-intdem-tooltip] {
  left: 48%;
  top: 48.4%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="4"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s5-bg.png);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s4-highlight"] {
  left: 51.7%;
  top: 42.65%;
  width: 3.33%;
  height: 5.33%;
  opacity: 0;
  -webkit-transition: 1s;
  transition: 1s;
  cursor: pointer;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="4"].is-active
  [data-intdem-el="s4-highlight"] {
  opacity: 1;
  -webkit-animation-delay: 1s;
  animation-delay: 1s;
  -webkit-animation-name: s4-pulse;
  animation-name: s4-pulse;
  -webkit-animation-duration: 2s;
  animation-duration: 2s;
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="4"]
  [data-intdem-tooltip] {
  left: 37.4%;
  top: 50.5%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
@-webkit-keyframes s4-pulse {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}
@keyframes s4-pulse {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="5"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s6-bg.png);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s5-highlight"] {
  left: 5.4%;
  top: 32.5%;
  width: 100%;
  height: 6%;
  border-radius: 0.3125rem;
  border: 2px solid #2693ff;
  background-color: rgba(38, 147, 255, 0.05);
  opacity: 0;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  pointer-events: none;
  cursor: pointer;
  -webkit-animation: s1-pulse 3s linear infinite;
  animation: s1-pulse 3s linear infinite;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="5"].is-active
  [data-intdem-el="s5-highlight"] {
  opacity: 1;
  pointer-events: all;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="5"]
  [data-intdem-tooltip] {
  left: 50%;
  top: 26%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="6"] {
  background-image: url(/wp-content/themes/productboard/public/img/interactive-demo/insights/s7-bg.png);
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s6-highlight"] {
  left: 60.5%;
  top: 37%;
  width: 38%;
  height: 18%;
  border-radius: 0.3125rem;
  border: 2px solid #2693ff;
  background-color: rgba(38, 147, 255, 0.05);
  opacity: 0;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  pointer-events: none;
  cursor: pointer;
  -webkit-animation: s1-pulse 3s linear infinite;
  animation: s1-pulse 3s linear infinite;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="6"].is-active
  [data-intdem-el="s6-highlight"] {
  opacity: 1;
  pointer-events: all;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="6"]
  [data-intdem-tooltip] {
  left: 26.5%;
  top: 34%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-section="7"] {
  background-color: #fafafb;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-title"] {
  left: 25%;
  top: 11.5%;
  width: 50%;
  font-size: 200%;
  font-weight: 700;
  line-height: 1.4;
  text-align: center;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el^="s7-text"] {
  position: relative;
  opacity: 0.1;
  -webkit-transition-duration: 1s;
  transition-duration: 1s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el^="s7-text"] {
  opacity: 1;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el="s7-text-1"] {
  -webkit-transition-delay: 0.5s;
  transition-delay: 0.5s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el="s7-text-2"] {
  -webkit-transition-delay: 1.5s;
  transition-delay: 1.5s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el="s7-text-3"] {
  -webkit-transition-delay: 2.5s;
  transition-delay: 2.5s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-button"] {
  opacity: 0;
  -webkit-transition: 1s 0.5s;
  transition: 1s 0.5s;
  margin: 2.5rem 0 0;
  position: relative;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el="s7-button"] {
  opacity: 1;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el^="s7-box"] {
  top: 47.77%;
  width: 29.16%;
  height: 46.66%;
  border-radius: 1.25rem;
  border: 2px solid #e0e2e5;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-box-1"] {
  left: 3.12%;
  -webkit-transition-delay: 1s;
  transition-delay: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-box-2"] {
  left: 35.42%;
  -webkit-transition-delay: 2s;
  transition-delay: 2s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-box-3"] {
  left: 67.7%;
  -webkit-transition-delay: 3s;
  transition-delay: 3s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el^="s7-image"] {
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  -webkit-transition-duration: 1s;
  transition-duration: 1s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-image-1"] {
  -webkit-transition-delay: 0.5s;
  transition-delay: 0.5s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-image-2"] {
  -webkit-transition-delay: 1.5s;
  transition-delay: 1.5s;
}
.interactive-demo[data-intdem="insights"] [data-intdem-el="s7-image-3"] {
  -webkit-transition-delay: 2.5s;
  transition-delay: 2.5s;
}
.interactive-demo[data-intdem="insights"]
  [data-intdem-section="7"].is-active
  [data-intdem-el^="s7-image"] {
  opacity: 1;
}
.interactive-demo__content {
  display: none;
}
@media (min-width: 1000px) {
  .interactive-demo__content {
    display: block;
  }
}
.interactive-demo__image {
  left: 0;
  top: 0;
  position: absolute;
  display: none;
}
@media (max-width: 1000px) {
  .interactive-demo__image {
    display: block;
  }
}
.pricing-plan {
  width: 100%;
  padding: 0 6.25rem;
  border-radius: 1.25rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .pricing-plan {
    padding: 0;
  }
}
@media print, screen and (max-width: 48em) {
  .pricing-plan {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    background: 0 0;
  }
}
.pricing-plan__content {
  z-index: 2;
  width: 50%;
  max-width: 28.125rem;
  padding-right: 2.5rem;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .pricing-plan__content {
    width: 100%;
    max-width: 100%;
    padding-right: 0;
    margin-bottom: 2.1875rem;
  }
}
.pricing-plan__content > :first-child {
  margin-top: 0;
}
.pricing-plan__content > :last-child {
  margin-bottom: 0;
}
.pricing-plan__content-title {
  margin-bottom: 2.1875rem;
}
.pricing-plan__content-list {
  margin: 0;
  list-style: none;
  font-size: 1.125rem;
  color: #7e8494;
}
.pricing-plan__content-list li {
  line-height: 1.5;
  padding-left: 1.5625rem;
  margin: 0.9375rem 0;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .pricing-plan__content-list li {
    font-size: 1rem;
  }
}
.pricing-plan__content-list li:first-child {
  margin-top: 0;
}
.pricing-plan__content-list li:last-child {
  margin-bottom: 0;
}
.pricing-plan__content-list li:before {
  content: "";
  left: 0;
  top: 0.625rem;
  width: 0.6875rem;
  height: 0.4375rem;
  border-left: 0.125rem solid #000c2c;
  border-bottom: 0.125rem solid #000c2c;
  -webkit-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  transform: rotate(-45deg);
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .pricing-plan__content-list li:before {
    top: 0.5rem;
  }
}
.pricing-plan__card {
  z-index: 1;
  max-width: 17.25rem;
  margin-left: auto;
  position: relative;
}
@media print, screen and (max-width: 48em) {
  .pricing-plan__card {
    margin: 0 auto;
  }
}
.pricing-plan__card-background {
  top: 0;
  right: 100%;
  width: 10rem;
  height: 25.3125rem;
  background-position: 50% 50%;
  background-size: contain;
  position: absolute;
}
@media print, screen and (max-width: 64em) {
  .pricing-plan__card-background {
    display: none;
  }
}
.pricing-plan__card-content {
  padding: 1.875rem;
  background-color: #fafafb;
  border: 0.5rem solid #fff;
  border-radius: 1.25rem;
  -webkit-box-shadow: 0 1.25rem 1.875rem rgba(0, 0, 0, 0.1);
  box-shadow: 0 1.25rem 1.875rem rgba(0, 0, 0, 0.1);
  position: relative;
}
.pricing-plan__card-header {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 0.9375rem;
}
.pricing-plan__card-title {
  font-weight: 700;
}
.pricing-plan__card-icon {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 0.9375rem;
  -ms-flex: 0 0 0.9375rem;
  flex: 0 0 0.9375rem;
  height: 1rem;
  margin-left: auto;
}
.pricing-plan__card-description {
  margin-bottom: 1.875rem;
}
.pricing-plan__card-price {
  margin-bottom: 3.75rem;
}
.pricing-plan__card-price-value {
  font-size: 1.625rem;
  font-weight: 700;
}
.pricing-plan__card-price-note {
  font-size: 0.875rem;
}
.pricing-plan__card-button {
  width: 100%;
  margin-bottom: 0.625rem;
}
.pricing-plan__card-more {
  width: 100%;
  font-size: 0.875rem;
  font-weight: 400;
  color: #7e8494;
  display: block;
  text-align: center;
}
.cta-banner {
  width: 100%;
  min-height: 10rem;
  border-radius: 1.25rem;
  background-color: #e2effd;
  padding: 0 6.25rem 0 1.875rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 80em) {
  .cta-banner {
    min-height: 7.5rem;
    padding: 0 3.125rem 0 1.875rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cta-banner {
    min-height: auto;
    text-align: center;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    padding: 1.875rem 1.25rem;
  }
}
.cta-banner__image-wrapper {
  height: 100%;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 10rem;
  -ms-flex: 0 0 10rem;
  flex: 0 0 10rem;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .cta-banner__image-wrapper {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 7.5rem;
    -ms-flex: 0 0 7.5rem;
    flex: 0 0 7.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cta-banner__image-wrapper {
    display: none;
  }
}
.cta-banner__text {
  padding: 0 4.375rem;
  margin: 0 auto 0 0;
}
@media print, screen and (max-width: 80em) {
  .cta-banner__text {
    font-size: 1.25rem;
    padding: 0 3.125rem;
  }
}
@media print, screen and (max-width: 64em) {
  .cta-banner__text {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    font-size: 1.125rem;
    padding: 0;
  }
}
.cta-banner__button {
  margin: 0 0 0 auto;
}
@media print, screen and (max-width: 64em) {
  .cta-banner__button {
    margin: 1.875rem auto 0;
  }
}
.slideshow-timer-small {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-small {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.slideshow-timer-small--intro {
  padding: 5rem 0 6rem;
}
.slideshow-timer-small--intro:before {
  content: "";
  left: 50%;
  top: 0;
  height: 100%;
  width: calc(100vw - 40px);
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
  background: linear-gradient(112deg, #fef0f0 0, #fef7e1 100%);
  position: absolute;
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-small--intro:before {
    width: calc(100vw - 20px);
  }
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-small--intro {
    padding: 2.75rem 0 3.75rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-small--intro {
    width: calc(100% + 32px);
    left: -16px;
    position: relative;
  }
}
.slideshow-timer-small__images {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 45.5rem;
  -ms-flex: 0 0 45.5rem;
  flex: 0 0 45.5rem;
  border-radius: 1.25rem;
  background-color: #fff;
  overflow: hidden;
  position: relative;
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-small__images {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 35rem;
    -ms-flex: 0 0 35rem;
    flex: 0 0 35rem;
  }
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-small__images {
    display: none;
  }
}
.slideshow-timer-small--intro .slideshow-timer-small__images {
  -webkit-box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.05);
  box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.05);
}
.slideshow-timer-small__images-item {
  left: 0;
  top: 0;
  max-width: 100%;
  opacity: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  height: auto;
  position: absolute;
}
.slideshow-timer-small__images-item.is-active {
  opacity: 1;
  position: relative;
}
.slideshow-timer-small__pager {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 21.875rem;
  -ms-flex: 0 0 21.875rem;
  flex: 0 0 21.875rem;
  margin-left: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-small__pager {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 17.5rem;
    -ms-flex: 0 0 17.5rem;
    flex: 0 0 17.5rem;
  }
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-small__pager {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 0;
  }
}
@-webkit-keyframes progress-bar {
  0% {
    width: 0;
  }
  100% {
    width: calc(100% - 24px);
  }
}
@keyframes progress-bar {
  0% {
    width: 0;
  }
  100% {
    width: calc(100% - 24px);
  }
}
.slideshow-timer-small__pager-item {
  width: 100%;
  margin: 0.3125rem 0;
  outline: 0;
  border: 0;
  text-align: left;
  cursor: pointer;
  position: relative;
}
.slideshow-timer-small__pager-item:after,
.slideshow-timer-small__pager-item:before {
  content: "";
  position: absolute;
  left: 0.75rem;
  bottom: 0;
  height: 0.25rem;
  border-radius: 0.125rem;
  width: calc(100% - 24px);
  background-color: #ebecef;
  opacity: 0;
  -webkit-transition: 0.25s;
  transition: 0.25s;
}
.slideshow-timer-small__pager-item:after {
  background-color: #000c2c;
}
.slideshow-timer-small__pager-item.is-active:after {
  opacity: 1;
  -webkit-animation-name: progress-bar;
  animation-name: progress-bar;
  -webkit-animation-duration: 5s;
  animation-duration: 5s;
  -webkit-animation-iteration-count: 1;
  animation-iteration-count: 1;
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
.slideshow-timer-small.is-stopped .slideshow-timer-small__pager-item:after,
.slideshow-timer-small.is-stopped .slideshow-timer-small__pager-item:before {
  opacity: 0;
}
.slideshow-timer-small__pager-image-wrapper {
  width: 100%;
  max-height: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  -webkit-box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
  box-shadow: 0 0.75rem 1.5rem rgba(0, 0, 0, 0.04);
  border-radius: 0.625rem;
  background-color: #fff;
  overflow: hidden;
  display: none;
  text-align: center;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-small__pager-image-wrapper {
    display: block;
  }
}
.slideshow-timer-small__pager-item.is-active
  .slideshow-timer-small__pager-image-wrapper {
  max-height: 31.25rem;
  margin-bottom: 1rem;
}
.slideshow-timer-small__pager-image {
  display: block;
}
.slideshow-timer-small__pager-content {
  width: 100%;
  border-radius: 0.625rem;
  padding: 1.5rem;
  -webkit-transition: 0.15s;
  transition: 0.15s;
  background-color: #fafafb;
}
@media screen and (min-width: 64em) {
  .slideshow-timer-small__pager-item
    .slideshow-timer-small__pager-content:hover {
    background-color: #ebecef;
  }
}
.slideshow-timer-small--intro .slideshow-timer-small__pager-content {
  background-color: transparent;
}
.slideshow-timer-small--intro
  .slideshow-timer-small__pager-item.is-active
  .slideshow-timer-small__pager-content {
  background-color: #fff;
}
@media screen and (min-width: 64em) {
  .slideshow-timer-small--intro
    .slideshow-timer-small__pager-item
    .slideshow-timer-small__pager-content:hover {
    background-color: #fff;
  }
}
.slideshow-timer-small__pager-title {
  font-size: 1.125rem;
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-small__pager-title {
    font-size: 1rem;
  }
}
.slideshow-timer-small__pager-text {
  margin: 0;
  font-size: 0.875rem;
  line-height: 1.4;
  -webkit-transition: 0.25s;
  transition: 0.25s;
  max-height: 0;
  overflow: hidden;
}
.slideshow-timer-small__pager-text:empty {
  display: none;
}
.slideshow-timer-small__pager-item.is-active
  .slideshow-timer-small__pager-text {
  margin: 0.625rem 0 0;
  max-height: 6.25rem;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}
.slideshow-timer-large {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
}
.slideshow-timer-large__images-wrapper {
  width: 90%;
  margin: auto;
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-large__images-wrapper {
    width: 100%;
  }
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__images-wrapper.scrollable {
    width: 100%;
    max-width: 100%;
    overflow: auto;
  }
}
.slideshow-timer-large__images {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  overflow: hidden;
  position: relative;
  border-radius: 1.5rem;
  padding: 3.5rem 3.5rem 0;
  margin: auto;
  max-width: 100%;
  width: 69.5rem;
  height: 38.5rem;
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-large__images {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 auto;
    -ms-flex: 0 0 auto;
    flex: 0 0 auto;
  }
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__images {
    width: 34.75rem;
    height: 19.25rem;
    min-height: 19.25rem;
    padding: 1rem 1rem 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-large__images {
    border-radius: unset;
    width: 100%;
    height: 18.5rem;
    min-height: 18.5rem;
  }
}
@media print, screen and (max-width: 37.5em) {
  .scrollable .slideshow-timer-large__images {
    max-width: none;
    width: 34.75rem;
    height: 18.5rem;
    padding: 1rem 1rem 0;
  }
}
.slideshow-timer-large__images.orange {
  background-image: -webkit-gradient(
    linear,
    left top,
    right top,
    from(#fbb06f),
    to(#ffd659)
  );
  background-image: linear-gradient(to right, #fbb06f, #ffd659);
}
.slideshow-timer-large__images-item {
  position: absolute;
  top: 3.5rem;
  left: 3.5rem;
  right: 3.5rem;
  bottom: 0;
  margin: auto;
  max-width: 100%;
  opacity: 0;
  -webkit-transition: 1.5s;
  transition: 1.5s;
  height: 35rem;
  border-radius: 0.75rem 0.75rem 0 0;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__images-item {
    height: 17.5rem;
    width: 31.25rem;
    top: auto;
    left: 0;
    right: 0;
    bottom: 0;
  }
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-large__images-item {
    top: 1rem;
    right: 0;
    bottom: 0;
    left: 1rem;
  }
}
.slideshow-timer-large__images-item.is-active {
  opacity: 1;
  position: absolute;
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-large__images-item.is-active {
    position: absolute;
  }
}
.slideshow-timer-large__images-item_image {
  width: 100%;
  height: 100%;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__images-item_image {
    height: 17.5rem;
    width: 31.25rem;
  }
}
@media screen and (max-width: 31.25em) {
  .slideshow-timer-large__images-item_image {
    max-width: none;
  }
}
.slideshow-timer-large__pager {
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin: auto;
  margin-bottom: 2rem;
}
@media print, screen and (max-width: 37.5em) {
  .slideshow-timer-large__pager {
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 100%;
    -ms-flex: 0 0 100%;
    flex: 0 0 100%;
    margin: 0 0 1.5rem;
    max-width: 100%;
    overflow: auto;
  }
}
@keyframes progress-bar {
  0% {
    width: 0;
  }
  100% {
    width: calc(100% - 24px);
  }
}
.slideshow-timer-large__pager-inner {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-left: 1.5rem;
  overflow: auto;
}
.slideshow-timer-large__pager-item {
  width: auto;
  min-width: 10rem;
  margin: 0.3125rem 0;
  outline: 0;
  border: 0;
  text-align: left;
  cursor: pointer;
  position: relative;
  white-space: nowrap;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__pager-item {
    min-width: auto;
  }
}
.slideshow-timer-large__pager-item:after,
.slideshow-timer-large__pager-item:before {
  content: "";
  position: absolute;
  left: 0.75rem;
  bottom: 0;
  height: 0.25rem;
  border-radius: 0.125rem;
  width: calc(100% - 24px);
  background-color: #ebecef;
  opacity: 0;
  -webkit-transition: 0.25s;
  transition: 0.25s;
}
.slideshow-timer-large__pager-item:after {
  background-color: #000c2c;
}
.slideshow-timer-large__pager-item.is-active:after {
  opacity: 1;
  -webkit-animation-name: progress-bar;
  animation-name: progress-bar;
  -webkit-animation-duration: 5s;
  animation-duration: 5s;
  -webkit-animation-iteration-count: 1;
  animation-iteration-count: 1;
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}
.slideshow-timer-large.is-stopped .slideshow-timer-large__pager-item:after,
.slideshow-timer-large.is-stopped .slideshow-timer-large__pager-item:before {
  opacity: 0;
}
.slideshow-timer-large__pager-image-wrapper {
  width: 100%;
  max-height: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  overflow: hidden;
  display: none;
  text-align: center;
  position: relative;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__pager-image-wrapper {
    display: block;
  }
}
.slideshow-timer-large__pager-item.is-active
  .slideshow-timer-large__pager-image-wrapper {
  max-height: 31.25rem;
  margin-bottom: 0.3125rem;
}
.slideshow-timer-large__pager-content {
  width: 100%;
  border-radius: 0.75rem;
  padding: 1.625rem;
  -webkit-transition: 0.15s;
  transition: 0.15s;
  background-color: transparent;
  text-align: center;
}
@media print, screen and (max-width: 64em) {
  .slideshow-timer-large__pager-content {
    padding: 1rem;
  }
}
@media screen and (min-width: 64em) {
  .slideshow-timer-large__pager-item
    .slideshow-timer-large__pager-content:hover {
    background-color: #ebecef;
  }
}
.slideshow-timer-large__pager-title {
  font-size: 1.125rem;
}
@media print, screen and (max-width: 80em) {
  .slideshow-timer-large__pager-title {
    font-size: 1rem;
  }
}
.slideshow-timer-large__pager-text {
  margin: 0;
  font-size: 0.875rem;
  line-height: 1.4;
  -webkit-transition: 0.25s;
  transition: 0.25s;
  max-height: 0;
  overflow: hidden;
}
.slideshow-timer-large__pager-text:empty {
  display: none;
}
.slideshow-timer-large__pager-item.is-active
  .slideshow-timer-large__pager-text {
  margin: 0.625rem 0 0;
  max-height: 6.25rem;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}
.cta {
  text-align: center;
  border-radius: 1.25rem;
}
.cta--has-background {
  padding: 6rem 2rem;
}
@media print, screen and (max-width: 64em) {
  .cta--has-background {
    padding: 4rem 1.5rem;
  }
}
.cta__title {
  font-size: 3rem;
}
@media print, screen and (max-width: 64em) {
  .cta__title {
    font-size: 2.25rem;
  }
}
.cta__text {
  margin-top: 1.5rem;
  font-size: 1.25rem;
}
.cta__microcopy {
  margin-top: 1rem;
  font-size: 0.8125rem;
  color: #5f677b;
}
.cta__actions {
  margin-top: 1.5rem;
}
.cta__actions-item {
  margin: 0.5rem;
}

</style>
