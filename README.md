<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>PEC1-final-v1</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
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
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
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
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="width: 100%; clear: both;">
<div style="float: left; width: 50%;">
<img src="http://www.uoc.edu/portal/_resources/common/imatges/marca_UOC/UOC_Masterbrand.jpg" align="left">
</div>
<div style="float: right; width: 50%;">
<p style="margin: 0; padding-top: 22px; text-align:right;">M2.855 · Modelos avanzados de minería de datos · PEC1</p>
<p style="margin: 0; text-align:right;">2018-2 · Máster universitario en Ciencia de datos (Data science)</p>
<p style="margin: 0; text-align:right; padding-button: 100px;">Estudios de Informática, Multimedia y Telecomunicación</p>
<p style="margin: 0; text-align:right; padding-button: 100px;"><b>Autor: Joaquín Fernández León</b></p>
</div>
</div>
<div style="width:100%;">&nbsp;</div><h1 id="PEC-1:-Preparaci&#243;n-de-datos">PEC 1: Preparaci&#243;n de datos<a class="anchor-link" href="#PEC-1:-Preparaci&#243;n-de-datos">&#182;</a></h1><p>A lo largo de esta práctica veremos como aplicar distintas técnicas para la carga y preparación de datos:</p>
<ol start="1">
  <li>Carga de conjuntos de datos</li>
  <li>Análisis de los datos
  <br>2.1 Análisis estadístico básico
  <br>2.2 Análisis exploratorio de los datos
  <li>Reducción de dimensionalidad</li>
  <li>Aplicación de CART</li>
</ol><p>Para ello vamos a necesitar las siguientes librerías:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">datasets</span>
<span class="kn">from</span> <span class="nn">sklearn.decomposition</span> <span class="k">import</span> <span class="n">PCA</span>
<span class="kn">from</span> <span class="nn">sklearn.manifold</span> <span class="k">import</span> <span class="n">TSNE</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">train_test_split</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">tree</span>
<span class="kn">from</span> <span class="nn">sklearn.tree</span> <span class="k">import</span> <span class="n">DecisionTreeClassifier</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="k">import</span> <span class="n">accuracy_score</span><span class="p">,</span> <span class="n">confusion_matrix</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="o">%</span><span class="k">matplotlib</span> inline
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="n">pd</span><span class="o">.</span><span class="n">set_option</span><span class="p">(</span><span class="s1">&#39;display.max_columns&#39;</span><span class="p">,</span> <span class="kc">None</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="1.-Carga-del-conjunto-de-datos-(1-punto)">1. Carga del conjunto de datos (1 punto)<a class="anchor-link" href="#1.-Carga-del-conjunto-de-datos-(1-punto)">&#182;</a></h1><p>En primer lugar, deberéis cargar el conjunto de datos Breast Cancer Wisconsin (más información en <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic">https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic</a>)). Éste se puede descargar de Internet o puede ser cargado directamente de la librería "scikit-learn", que incorpora un conjunto de datasets muy conocidos y empleados para minería de datos y machine learning (<a href="http://scikit-learn.org/stable/datasets/index.html">http://scikit-learn.org/stable/datasets/index.html</a>).</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Cargad el conjunto de datos "Breast Cancer Wisconsin" y mostrad el número y nombre de los atributos (variables que podrían ser usadas para predecir la respuesta "Diagnosis"), así como el número de filas obtenidas.
    <div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
        <p>Hemos descargado el dataset desde la web de Kaggle: <a href="https://www.kaggle.com/uciml/breast-cancer-wisconsin-data">https://www.kaggle.com/uciml/breast-cancer-wisconsin-data</a></p>

</div>
<hr>
Sugerencia: si usáis sklearn (sklearn.datasets.load_breast_cancer), explorad las diferentes keys del objeto obtenido.
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[2]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;input/data.csv&#39;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Analizamos el tipo de dato para cada variable:&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">data</span><span class="o">.</span><span class="n">dtypes</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;El tamaño del csv es:&quot;</span><span class="p">)</span>
<span class="n">n_samples</span><span class="p">,</span> <span class="n">n_features</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">shape</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Numero de filas: &quot;</span><span class="p">,</span> <span class="n">n_samples</span><span class="p">,</span> <span class="s2">&quot;y el numero de columnas&quot;</span><span class="p">,</span> <span class="n">n_features</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Analizamos el tipo de dato para cada variable:
id                           int64
diagnosis                   object
radius_mean                float64
texture_mean               float64
perimeter_mean             float64
area_mean                  float64
smoothness_mean            float64
compactness_mean           float64
concavity_mean             float64
concave points_mean        float64
symmetry_mean              float64
fractal_dimension_mean     float64
radius_se                  float64
texture_se                 float64
perimeter_se               float64
area_se                    float64
smoothness_se              float64
compactness_se             float64
concavity_se               float64
concave points_se          float64
symmetry_se                float64
fractal_dimension_se       float64
radius_worst               float64
texture_worst              float64
perimeter_worst            float64
area_worst                 float64
smoothness_worst           float64
compactness_worst          float64
concavity_worst            float64
concave points_worst       float64
symmetry_worst             float64
fractal_dimension_worst    float64
Unnamed: 32                float64
dtype: object
El tamaño del csv es:
Numero de filas:  569 y el numero de columnas 33
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Eliminamos la columna id y otra que es basura (unnamed)</span>
<span class="n">data_diagnosis</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">diagnosis</span>                     
<span class="n">delete</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Unnamed: 32&#39;</span><span class="p">,</span><span class="s1">&#39;id&#39;</span><span class="p">]</span>

<span class="c1"># Guardamos nuestra variable data_train que utilizaremos en el ejercicio 4 para entrenar</span>
<span class="n">data_train</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">delete</span><span class="p">,</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>

<span class="c1"># Creamos otra variable all_data donde guardaremos todo y además un mapeo de la variable categórica M y B por 0 y 1</span>
<span class="n">all_data</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">delete</span><span class="p">,</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>

<span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;binary&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">map</span><span class="p">({</span><span class="s1">&#39;M&#39;</span><span class="p">:</span> <span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;B&#39;</span><span class="p">:</span> <span class="mi">1</span><span class="p">})</span>

<span class="c1"># Guardamos el subconjunto de datos de tumores malignos y benignos</span>
<span class="n">malignant</span><span class="o">=</span><span class="n">all_data</span><span class="p">[</span><span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;binary&#39;</span><span class="p">]</span><span class="o">==</span><span class="mi">0</span><span class="p">]</span> <span class="c1"># define malignant</span>
<span class="n">benign</span><span class="o">=</span><span class="n">all_data</span><span class="p">[</span><span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;binary&#39;</span><span class="p">]</span><span class="o">==</span><span class="mi">1</span><span class="p">]</span> <span class="c1"># define benign</span>

<span class="c1"># Creamos las variables x para todos los atributos e y para la etiqueta de clase</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">diagnosis</span> 
<span class="n">x</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;Unnamed: 32&#39;</span><span class="p">,</span><span class="s1">&#39;id&#39;</span><span class="p">,</span> <span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span> <span class="p">)</span>

<span class="c1"># Mostramos la variable x</span>
<span class="n">x</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[3]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>radius_mean</th>
      <th>texture_mean</th>
      <th>perimeter_mean</th>
      <th>area_mean</th>
      <th>smoothness_mean</th>
      <th>compactness_mean</th>
      <th>concavity_mean</th>
      <th>concave points_mean</th>
      <th>symmetry_mean</th>
      <th>fractal_dimension_mean</th>
      <th>radius_se</th>
      <th>texture_se</th>
      <th>perimeter_se</th>
      <th>area_se</th>
      <th>smoothness_se</th>
      <th>compactness_se</th>
      <th>concavity_se</th>
      <th>concave points_se</th>
      <th>symmetry_se</th>
      <th>fractal_dimension_se</th>
      <th>radius_worst</th>
      <th>texture_worst</th>
      <th>perimeter_worst</th>
      <th>area_worst</th>
      <th>smoothness_worst</th>
      <th>compactness_worst</th>
      <th>concavity_worst</th>
      <th>concave points_worst</th>
      <th>symmetry_worst</th>
      <th>fractal_dimension_worst</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>17.99</td>
      <td>10.38</td>
      <td>122.80</td>
      <td>1001.0</td>
      <td>0.11840</td>
      <td>0.27760</td>
      <td>0.3001</td>
      <td>0.14710</td>
      <td>0.2419</td>
      <td>0.07871</td>
      <td>1.0950</td>
      <td>0.9053</td>
      <td>8.589</td>
      <td>153.40</td>
      <td>0.006399</td>
      <td>0.04904</td>
      <td>0.05373</td>
      <td>0.01587</td>
      <td>0.03003</td>
      <td>0.006193</td>
      <td>25.38</td>
      <td>17.33</td>
      <td>184.60</td>
      <td>2019.0</td>
      <td>0.1622</td>
      <td>0.6656</td>
      <td>0.7119</td>
      <td>0.2654</td>
      <td>0.4601</td>
      <td>0.11890</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20.57</td>
      <td>17.77</td>
      <td>132.90</td>
      <td>1326.0</td>
      <td>0.08474</td>
      <td>0.07864</td>
      <td>0.0869</td>
      <td>0.07017</td>
      <td>0.1812</td>
      <td>0.05667</td>
      <td>0.5435</td>
      <td>0.7339</td>
      <td>3.398</td>
      <td>74.08</td>
      <td>0.005225</td>
      <td>0.01308</td>
      <td>0.01860</td>
      <td>0.01340</td>
      <td>0.01389</td>
      <td>0.003532</td>
      <td>24.99</td>
      <td>23.41</td>
      <td>158.80</td>
      <td>1956.0</td>
      <td>0.1238</td>
      <td>0.1866</td>
      <td>0.2416</td>
      <td>0.1860</td>
      <td>0.2750</td>
      <td>0.08902</td>
    </tr>
    <tr>
      <th>2</th>
      <td>19.69</td>
      <td>21.25</td>
      <td>130.00</td>
      <td>1203.0</td>
      <td>0.10960</td>
      <td>0.15990</td>
      <td>0.1974</td>
      <td>0.12790</td>
      <td>0.2069</td>
      <td>0.05999</td>
      <td>0.7456</td>
      <td>0.7869</td>
      <td>4.585</td>
      <td>94.03</td>
      <td>0.006150</td>
      <td>0.04006</td>
      <td>0.03832</td>
      <td>0.02058</td>
      <td>0.02250</td>
      <td>0.004571</td>
      <td>23.57</td>
      <td>25.53</td>
      <td>152.50</td>
      <td>1709.0</td>
      <td>0.1444</td>
      <td>0.4245</td>
      <td>0.4504</td>
      <td>0.2430</td>
      <td>0.3613</td>
      <td>0.08758</td>
    </tr>
    <tr>
      <th>3</th>
      <td>11.42</td>
      <td>20.38</td>
      <td>77.58</td>
      <td>386.1</td>
      <td>0.14250</td>
      <td>0.28390</td>
      <td>0.2414</td>
      <td>0.10520</td>
      <td>0.2597</td>
      <td>0.09744</td>
      <td>0.4956</td>
      <td>1.1560</td>
      <td>3.445</td>
      <td>27.23</td>
      <td>0.009110</td>
      <td>0.07458</td>
      <td>0.05661</td>
      <td>0.01867</td>
      <td>0.05963</td>
      <td>0.009208</td>
      <td>14.91</td>
      <td>26.50</td>
      <td>98.87</td>
      <td>567.7</td>
      <td>0.2098</td>
      <td>0.8663</td>
      <td>0.6869</td>
      <td>0.2575</td>
      <td>0.6638</td>
      <td>0.17300</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20.29</td>
      <td>14.34</td>
      <td>135.10</td>
      <td>1297.0</td>
      <td>0.10030</td>
      <td>0.13280</td>
      <td>0.1980</td>
      <td>0.10430</td>
      <td>0.1809</td>
      <td>0.05883</td>
      <td>0.7572</td>
      <td>0.7813</td>
      <td>5.438</td>
      <td>94.44</td>
      <td>0.011490</td>
      <td>0.02461</td>
      <td>0.05688</td>
      <td>0.01885</td>
      <td>0.01756</td>
      <td>0.005115</td>
      <td>22.54</td>
      <td>16.67</td>
      <td>152.20</td>
      <td>1575.0</td>
      <td>0.1374</td>
      <td>0.2050</td>
      <td>0.4000</td>
      <td>0.1625</td>
      <td>0.2364</td>
      <td>0.07678</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="2.-An&#225;lisis-de-los-datos">2. An&#225;lisis de los datos<a class="anchor-link" href="#2.-An&#225;lisis-de-los-datos">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="2.1-An&#225;lisis-estad&#237;stico-b&#225;sico-(1-punto)">2.1 An&#225;lisis estad&#237;stico b&#225;sico (1 punto)<a class="anchor-link" href="#2.1-An&#225;lisis-estad&#237;stico-b&#225;sico-(1-punto)">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Realizad un análisis estadístico básico indicando, para cada atributo numérico del conjunto de datos, su valor medio y desviación estándard. Para las variables categóricas (en los atributos o la respuesta, si las hay), mostrad la frecuencia con la que aparecen las diferentes clases.
<hr>
Sugerencia: podeis usar la librería 'pandas' y sus funciones 'describe' y 'value_counts'
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">data_train</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[4]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>radius_mean</th>
      <th>texture_mean</th>
      <th>perimeter_mean</th>
      <th>area_mean</th>
      <th>smoothness_mean</th>
      <th>compactness_mean</th>
      <th>concavity_mean</th>
      <th>concave points_mean</th>
      <th>symmetry_mean</th>
      <th>fractal_dimension_mean</th>
      <th>radius_se</th>
      <th>texture_se</th>
      <th>perimeter_se</th>
      <th>area_se</th>
      <th>smoothness_se</th>
      <th>compactness_se</th>
      <th>concavity_se</th>
      <th>concave points_se</th>
      <th>symmetry_se</th>
      <th>fractal_dimension_se</th>
      <th>radius_worst</th>
      <th>texture_worst</th>
      <th>perimeter_worst</th>
      <th>area_worst</th>
      <th>smoothness_worst</th>
      <th>compactness_worst</th>
      <th>concavity_worst</th>
      <th>concave points_worst</th>
      <th>symmetry_worst</th>
      <th>fractal_dimension_worst</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
      <td>569.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>14.127292</td>
      <td>19.289649</td>
      <td>91.969033</td>
      <td>654.889104</td>
      <td>0.096360</td>
      <td>0.104341</td>
      <td>0.088799</td>
      <td>0.048919</td>
      <td>0.181162</td>
      <td>0.062798</td>
      <td>0.405172</td>
      <td>1.216853</td>
      <td>2.866059</td>
      <td>40.337079</td>
      <td>0.007041</td>
      <td>0.025478</td>
      <td>0.031894</td>
      <td>0.011796</td>
      <td>0.020542</td>
      <td>0.003795</td>
      <td>16.269190</td>
      <td>25.677223</td>
      <td>107.261213</td>
      <td>880.583128</td>
      <td>0.132369</td>
      <td>0.254265</td>
      <td>0.272188</td>
      <td>0.114606</td>
      <td>0.290076</td>
      <td>0.083946</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3.524049</td>
      <td>4.301036</td>
      <td>24.298981</td>
      <td>351.914129</td>
      <td>0.014064</td>
      <td>0.052813</td>
      <td>0.079720</td>
      <td>0.038803</td>
      <td>0.027414</td>
      <td>0.007060</td>
      <td>0.277313</td>
      <td>0.551648</td>
      <td>2.021855</td>
      <td>45.491006</td>
      <td>0.003003</td>
      <td>0.017908</td>
      <td>0.030186</td>
      <td>0.006170</td>
      <td>0.008266</td>
      <td>0.002646</td>
      <td>4.833242</td>
      <td>6.146258</td>
      <td>33.602542</td>
      <td>569.356993</td>
      <td>0.022832</td>
      <td>0.157336</td>
      <td>0.208624</td>
      <td>0.065732</td>
      <td>0.061867</td>
      <td>0.018061</td>
    </tr>
    <tr>
      <th>min</th>
      <td>6.981000</td>
      <td>9.710000</td>
      <td>43.790000</td>
      <td>143.500000</td>
      <td>0.052630</td>
      <td>0.019380</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.106000</td>
      <td>0.049960</td>
      <td>0.111500</td>
      <td>0.360200</td>
      <td>0.757000</td>
      <td>6.802000</td>
      <td>0.001713</td>
      <td>0.002252</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.007882</td>
      <td>0.000895</td>
      <td>7.930000</td>
      <td>12.020000</td>
      <td>50.410000</td>
      <td>185.200000</td>
      <td>0.071170</td>
      <td>0.027290</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.156500</td>
      <td>0.055040</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>11.700000</td>
      <td>16.170000</td>
      <td>75.170000</td>
      <td>420.300000</td>
      <td>0.086370</td>
      <td>0.064920</td>
      <td>0.029560</td>
      <td>0.020310</td>
      <td>0.161900</td>
      <td>0.057700</td>
      <td>0.232400</td>
      <td>0.833900</td>
      <td>1.606000</td>
      <td>17.850000</td>
      <td>0.005169</td>
      <td>0.013080</td>
      <td>0.015090</td>
      <td>0.007638</td>
      <td>0.015160</td>
      <td>0.002248</td>
      <td>13.010000</td>
      <td>21.080000</td>
      <td>84.110000</td>
      <td>515.300000</td>
      <td>0.116600</td>
      <td>0.147200</td>
      <td>0.114500</td>
      <td>0.064930</td>
      <td>0.250400</td>
      <td>0.071460</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>13.370000</td>
      <td>18.840000</td>
      <td>86.240000</td>
      <td>551.100000</td>
      <td>0.095870</td>
      <td>0.092630</td>
      <td>0.061540</td>
      <td>0.033500</td>
      <td>0.179200</td>
      <td>0.061540</td>
      <td>0.324200</td>
      <td>1.108000</td>
      <td>2.287000</td>
      <td>24.530000</td>
      <td>0.006380</td>
      <td>0.020450</td>
      <td>0.025890</td>
      <td>0.010930</td>
      <td>0.018730</td>
      <td>0.003187</td>
      <td>14.970000</td>
      <td>25.410000</td>
      <td>97.660000</td>
      <td>686.500000</td>
      <td>0.131300</td>
      <td>0.211900</td>
      <td>0.226700</td>
      <td>0.099930</td>
      <td>0.282200</td>
      <td>0.080040</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>15.780000</td>
      <td>21.800000</td>
      <td>104.100000</td>
      <td>782.700000</td>
      <td>0.105300</td>
      <td>0.130400</td>
      <td>0.130700</td>
      <td>0.074000</td>
      <td>0.195700</td>
      <td>0.066120</td>
      <td>0.478900</td>
      <td>1.474000</td>
      <td>3.357000</td>
      <td>45.190000</td>
      <td>0.008146</td>
      <td>0.032450</td>
      <td>0.042050</td>
      <td>0.014710</td>
      <td>0.023480</td>
      <td>0.004558</td>
      <td>18.790000</td>
      <td>29.720000</td>
      <td>125.400000</td>
      <td>1084.000000</td>
      <td>0.146000</td>
      <td>0.339100</td>
      <td>0.382900</td>
      <td>0.161400</td>
      <td>0.317900</td>
      <td>0.092080</td>
    </tr>
    <tr>
      <th>max</th>
      <td>28.110000</td>
      <td>39.280000</td>
      <td>188.500000</td>
      <td>2501.000000</td>
      <td>0.163400</td>
      <td>0.345400</td>
      <td>0.426800</td>
      <td>0.201200</td>
      <td>0.304000</td>
      <td>0.097440</td>
      <td>2.873000</td>
      <td>4.885000</td>
      <td>21.980000</td>
      <td>542.200000</td>
      <td>0.031130</td>
      <td>0.135400</td>
      <td>0.396000</td>
      <td>0.052790</td>
      <td>0.078950</td>
      <td>0.029840</td>
      <td>36.040000</td>
      <td>49.540000</td>
      <td>251.200000</td>
      <td>4254.000000</td>
      <td>0.222600</td>
      <td>1.058000</td>
      <td>1.252000</td>
      <td>0.291000</td>
      <td>0.663800</td>
      <td>0.207500</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">data_train</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[5]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>count     569
unique      2
top         B
freq      357
Name: diagnosis, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <strong>Análisis:</strong>
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
     <p>Aquí podemos observar para cada una de sus <b>30 variables</b> totales,su valor medio y desviación estándard.</p>
    <p> Por lo general si comparamos a simple vista, los valores de media y mediana de los diferentes atributos se observa que toman un rango de valores bastante heterogéneo por lo que puede ser interesante aplicar una <b>normalización</b> para poder realizar mejores comparaciones</p>
    <p>Por último, en la <b>variable de clase (el atributo diagnosis)</b> se puede ver que existe un ligero <b>desbalanceo</b>, lo que implica que haya más atributos de la clase de <b>tumores benignos</b> que de la de <b>tumores malignos.</b></p>
</div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span> 
<span class="n">my_pal</span> <span class="o">=</span> <span class="p">{</span><span class="s2">&quot;M&quot;</span><span class="p">:</span> <span class="s2">&quot;r&quot;</span><span class="p">,</span> <span class="s2">&quot;B&quot;</span><span class="p">:</span> <span class="s2">&quot;g&quot;</span><span class="p">}</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">y</span><span class="p">,</span><span class="n">label</span><span class="o">=</span><span class="s2">&quot;Count&quot;</span><span class="p">,</span> <span class="n">palette</span><span class="o">=</span><span class="n">my_pal</span><span class="p">)</span>      
<span class="n">B</span><span class="p">,</span> <span class="n">M</span> <span class="o">=</span> <span class="n">y</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Number of Benign: &#39;</span><span class="p">,</span><span class="n">B</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Number of Malignant : &#39;</span><span class="p">,</span><span class="n">M</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Number of Benign:  357
Number of Malignant :  212
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="2.2-An&#225;lisis-exploratorio-de-los-datos-(3-puntos)">2.2 An&#225;lisis exploratorio de los datos (3 puntos)<a class="anchor-link" href="#2.2-An&#225;lisis-exploratorio-de-los-datos-(3-puntos)">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>En este ejercicio vamos a explorar la relación de algunos de los atributos numéricos con la variable respuesta ("Diagnosis"), tanto gráficamente como cuantitativamente. Para empezar, seleccionad los 4 atributos que queréis explorar. Si habéis usado los nombres de columnas proporcionados por sklearn, una lista de posibles nombres de atributos serían:</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">feats_to_explore</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;mean radius&#39;</span><span class="p">,</span> <span class="s1">&#39;mean texture&#39;</span><span class="p">,</span> <span class="s1">&#39;mean smoothness&#39;</span><span class="p">,</span> <span class="s1">&#39;mean symmetry&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Utilizando una librería gráfica, como por ejemplo "matplotlib", realizad un gráfico del histograma de valores para cada uno de los atributos seleccionados, separados por los valores de clase de la respuesta ("Diagnosis"). La finalidad es observar como se distribuye cada uno de los atributos en función del valor de clase que toman, para poder identificar de forma visual y rápida si algunos atributos permiten diferenciar de forma clara los diferentes diagnósticos de los tumores.
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x_y</span> <span class="o">=</span> <span class="n">all_data</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;radius_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;texture_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;smoothness_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;symmetry_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;diagnosis&#39;</span><span class="p">]]</span>
<span class="n">x_y</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[8]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>radius_mean</th>
      <th>texture_mean</th>
      <th>smoothness_mean</th>
      <th>symmetry_mean</th>
      <th>diagnosis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>17.99</td>
      <td>10.38</td>
      <td>0.11840</td>
      <td>0.2419</td>
      <td>M</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20.57</td>
      <td>17.77</td>
      <td>0.08474</td>
      <td>0.1812</td>
      <td>M</td>
    </tr>
    <tr>
      <th>2</th>
      <td>19.69</td>
      <td>21.25</td>
      <td>0.10960</td>
      <td>0.2069</td>
      <td>M</td>
    </tr>
    <tr>
      <th>3</th>
      <td>11.42</td>
      <td>20.38</td>
      <td>0.14250</td>
      <td>0.2597</td>
      <td>M</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20.29</td>
      <td>14.34</td>
      <td>0.10030</td>
      <td>0.1809</td>
      <td>M</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
     <p>A continuación mostraremos para cada <b>histograma</b> la distribución de los datos de los <i>tumores malignos</i> en rojo y los <i>tumores benignos</i> en verde para poder <b>comparar entre sí las posibles diferencias que pueden ayudar a detectar si un tumor es benigno o maligno</b>. </p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">lista</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;radius_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;texture_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;smoothness_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;symmetry_mean&#39;</span><span class="p">,</span> <span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span>

<span class="n">malignant</span><span class="o">=</span><span class="n">x_y</span><span class="p">[</span><span class="n">x_y</span><span class="o">.</span><span class="n">diagnosis</span><span class="o">==</span><span class="s1">&#39;M&#39;</span><span class="p">]</span> <span class="c1"># definimos los malignos</span>
<span class="n">benign</span><span class="o">=</span><span class="n">x_y</span><span class="p">[</span><span class="n">x_y</span><span class="o">.</span><span class="n">diagnosis</span><span class="o">==</span><span class="s1">&#39;B&#39;</span><span class="p">]</span> <span class="c1"># definimos los benignos</span>
<span class="n">bins</span> <span class="o">=</span> <span class="mi">10</span>

<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">4</span><span class="p">):</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">malignant</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,</span><span class="n">lista</span><span class="p">[</span><span class="n">i</span><span class="p">]],</span> <span class="n">bins</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.5</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;r&#39;</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">&#39;Malignant&#39;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">benign</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,</span><span class="n">lista</span><span class="p">[</span><span class="n">i</span><span class="p">]],</span> <span class="n">bins</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.5</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;g&#39;</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">&#39;Benign&#39;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="n">feats_to_explore</span><span class="p">[</span><span class="n">i</span><span class="p">])</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;upper right&#39;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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ZfzsZz/r1Ge8Dz744J2v6+rq2L59O1u3buWrX/0q8+fP58UXX+TKK6/cZR87ttmxflcz0CX1epdffjkzZ85k5MiRu8zftGnTzoukd911V7vtnHzyydx7770AzJs3r931d4T34MGD2bx5M/Pnz293m0MPPZR33nmn3fU6wk+5SKqNWn9scR/U19czbdq0PeZ//etfZ/Lkydx222185jOfabed2bNnc+mll/Ktb32Lc889l8MOO6zN9QcOHMiVV17JyJEjGTZsGGPGjGl3H6eddhq33HILDQ0NzJgxo6bj6LHjiuz+MHr06PQLLvadH1tUT7RixQqOPfbY7i6jpt5991369+9PRDBv3jzmzp3Lfffdt19raO24RsTizBzd3rb20CWpYvHixUydOpXMZODAgdx5553dXdI+MdAlqeJTn/oUzz//fHeX0WFeFJWkQhjoklQIA12SCmGgS1IhvCgqqSY68/HaVtur4iO3dXV1jBw5ksykrq6O7373u4wfP75D+5s5cyaf/vSnOf300zu0fU9goEvqtfr378/SpUsBeOSRR5gxYwZPPPFEh9qaNWtWLUvrFg65SCrC22+/zeGHH75z+pvf/CZjxozhxBNP5KabbgJgzZo1HHvssVx55ZUcf/zxnHHGGWzZsgWAyy67bOet+w899BAjRozg1FNP5ZprruG8884DoLGxkcsvv5wJEyZw9NFH853vfGc/v8u2GeiSeq0tW7bQ0NDAiBEj+MpXvsKNN94IwIIFC1i1ahULFy5k6dKlLF68mCeffBKAVatWcfXVV7N8+XIGDhy489ktO2zdupWrrrqKhx9+mKeffpoNGzbssnzlypU88sgjLFy4kJtvvplt27btnzdbBQNdUq+1Y8hl5cqV/PznP+dLX/oSmcmCBQtYsGABo0aN4qSTTmLlypWsWrUKgOHDh9PQ0AC0/ljblStXcvTRRzN8+HCAPZ7geO6553LwwQczePBgjjjiCNatW9f1b7RKjqFLKsIpp5zCm2++yYYNG8hMZsyYwVVXXbXLOmvWrNnjMbg7hlx2aO/5Vq09RrenqKqHHhHTI2J5RCyLiLkR0S8ihkfEMxGxKiLujoiDurpYSdqblStX8v777zNo0CDOPPNM7rzzTjZv3gzAa6+9xvr166tqZ8SIEaxevXpnz73WXxPXldrtoUfEUOAa4LjM3BIR9wAXAecA387MeRHxT8AVwPe7tFpJPVZ3PNlzxxg6NPes58yZQ11dHWeccQYrVqzglFNOAWDAgAH86Ec/oq6urt02+/fvz/e+9z3OOussBg8ezNixY7v0PdRSu4/PrQT6vwN/DrwN/BT4B+DHwEcyc3tEnAI0ZuaZbbXl43M7xsfnqicq8fG5O2zevJkBAwaQmVx99dUcc8wxTJ8+fb/suzOPz213yCUzXwNuBV4F3gA2AYuBtzJzx+DRWmBoa9tHxJSIWBQRi3a/WixJPdEPfvADGhoaOP7449m0adMeY/E9VTVDLocD5wPDgbeA/wGc3cqqrXb1M/N24HZo7qF3uFJJ2k+mT5++33rktVTNRdHTgf+TmRsycxvwE2A8MDAidvxCqAde76IaJfVQ+/Mbz/qCzh7PagL9VeDkiPhgRATwWeAl4HHggso6k4H9+z1NkrpVv3792Lhxo6FeI5nJxo0b6devX4fbaHfIJTOfiYj5wHPAdmAJzUMoDwLzIuIblXl3dLgKdZnOPjDJi6ram/r6etauXbvHnZTquH79+lFfX9/h7au6sSgzbwJu2m32aqD3fJ5HUk0deOCBO++mVM/grf+SVAgDXZIKYaBLUiEMdEkqhIEuSYUw0CWpEAa6JBXCQJekQhjoklQIA12SCmGgS1IhDHRJKoSBLkmFMNAlqRAGuiQVwkCXpEIY6JJUCANdkgphoEtSIQx0SSqEgS5JhTDQJakQBrokFcJAl6RCGOiSVAgDXZIKYaBLUiEMdEkqhIEuSYUw0CWpEAa6JBXCQJekQhjoklQIA12SCmGgS1IhDHRJKoSBLkmFqCrQI2JgRMyPiJURsSIiTomID0fEoxGxqvLz8K4uVpK0d9X20P878PPMHAH8ObACuB74RWYeA/yiMi1J6ibtBnpEfAj4NHAHQGa+l5lvAecDcyqrzQE+11VFSpLaV00P/WhgA/AvEbEkIv45Ig4BjszMNwAqP49obeOImBIRiyJi0YYNG2pWuCRpV9UE+geAk4DvZ+Yo4A/sw/BKZt6emaMzc/SQIUM6WKYkqT3VBPpaYG1mPlOZnk9zwK+LiKMAKj/Xd02JkqRqtBvomfl/gd9GxCcqsz4LvATcD0yuzJsM3NclFUqSqvKBKtf7z8CPI+IgYDXwZZp/GdwTEVcArwKTuqZESVI1qgr0zFwKjG5l0WdrW44kqaO8U1SSCmGgS1IhDHRJKoSBLkmFMNAlqRAGuiQVwkCXpEIY6JJUiGrvFFUnNDY1dncJkvoAe+iSVAgDXZIKYaBLUiEMdEkqhIEuSYUw0CWpEAa6JBXCQJekQnhjkdrU2ZuiGid0bntJ1bOHLkmFMNAlqRAGuiQVwkCXpEIY6JJUCANdkgphoEtSIQx0SSqEgS5JhTDQJakQBrokFcJAl6RCGOiSVAgDXZIKYaBLUiF8Hrpqr6mpxevG2rff2AVtSgWwhy5JhTDQJakQBrokFaLqQI+IuohYEhEPVKaHR8QzEbEqIu6OiIO6rkxJUnv2pYc+DVjRYvq/At/OzGOA3wNX1LIwSdK+qSrQI6IeOBf458p0AJ8B5ldWmQN8risKlCRVp9oe+mzg68AfK9ODgLcyc3tlei0wtLUNI2JKRCyKiEUbNmzoVLGSpL1rN9Aj4jxgfWYubjm7lVWzte0z8/bMHJ2Zo4cMGdLBMiVJ7anmxqK/ACZGxDlAP+BDNPfYB0bEByq99Hrg9a4rU9rPSrl5qZT3oaq020PPzBmZWZ+Zw4CLgMcy8xLgceCCymqTgfu6rEpJUrs68zn064D/EhGv0DymfkdtSpIkdcQ+PcslM5uApsrr1cDY2pckSeoI7xSVpEIY6JJUCANdkgphoEtSIQx0SSqE31hUhcau+NYddZw3y0itsocuSYUw0CWpEAa6JBXCQJekQhjoklQIA12SCmGgS1IhDHRJKoSBLkmFMNAlqRAGuiQVwkCXpEIY6JJUCANdkgphoEtSIXweel/T1NTdFUjqIvbQJakQBrokFcJAl6RCGOiSVAgDXZIKYaBLUiEMdEkqhIEuSYUw0CWpEAa6JBXCQJekQvgsF3WpRpo6se2EmtUh9QX20CWpEAa6JBXCQJekQrQb6BHxsYh4PCJWRMTyiJhWmf/hiHg0IlZVfh7e9eVKkvammh76duDvMvNY4GTg6og4Drge+EVmHgP8ojItSeom7QZ6Zr6Rmc9VXr8DrACGAucDcyqrzQE+11VFSpLat09j6BExDBgFPAMcmZlvQHPoA0fsZZspEbEoIhZt2LChc9VKkvaq6kCPiAHAvcDfZubb1W6Xmbdn5ujMHD1kyJCO1ChJqkJVgR4RB9Ic5j/OzJ9UZq+LiKMqy48C1ndNiZKkalTzKZcA7gBWZOZtLRbdD0yuvJ4M3Ff78iRJ1arm1v+/AL4IvBgRSyvzbgBuAe6JiCuAV4FJXVOiJKka7QZ6Zj4NxF4Wf7a25UiSOso7RSWpEAa6JBXCQJekQhjoklQIA12SCtFnvrGosamxu0uQpC5lD12SCmGgS1IhDHRJKoSBLkmFMNAlqRAGuiQVwkCXpEIY6JJUCANdkgphoEtSIQx0SSqEgS5JhTDQJakQfeZpi71CU1N3VyCpF7OHLkmFMNAlqRAGuiQVwkCXpEJ4UVQqWWNjd1fQeSW8h/3EHrokFcIeunqsRpo6uf2EmtQh9Rb20CWpEAa6JBXCQJekQhjoklSIXnNRtLGpsbtLkKQezR66JBWi1/TQJanLdPXNS/vp5ih76JJUCHvoKpY3JhXCW/+rZg9dkgrRqUCPiLMi4uWIeCUirq9VUZKkfdfhQI+IOuAfgbOB44CLI+K4WhUmSdo3nemhjwVeyczVmfkeMA84vzZlSZL2VWRmxzaMuAA4KzO/Upn+IjAuM6futt4UYEpl8hPAyx0vt1cZDLzZ3UX0YB6ftnl82tbXjs+fZuaQ9lbqzKdcopV5e/x2yMzbgds7sZ9eKSIWZebo7q6jp/L4tM3j0zaPT+s6M+SyFvhYi+l64PXOlSNJ6qjOBPqzwDERMTwiDgIuAu6vTVmSpH3V4SGXzNweEVOBR4A64M7MXF6zynq/PjfMtI88Pm3z+LTN49OKDl8UlST1LN4pKkmFMNAlqRAGeidFxJ0RsT4ilrWY9+GIeDQiVlV+Ht6dNXanvRyfxoh4LSKWVv6d0501dqeI+FhEPB4RKyJieURMq8z3HKLN4+M51ArH0DspIj4NbAb+NTNPqMz7b8DvMvOWyjNuDs/M67qzzu6yl+PTCGzOzFu7s7aeICKOAo7KzOci4lBgMfA54DI8h9o6Pn+D59Ae7KF3UmY+Cfxut9nnA3Mqr+fQfAL2SXs5PqrIzDcy87nK63eAFcBQPIeANo+PWmGgd40jM/MNaD4hgSO6uZ6eaGpEvFAZkumTwwm7i4hhwCjgGTyH9rDb8QHPoT0Y6OoO3wf+A9AAvAF8q3vL6X4RMQC4F/jbzHy7u+vpaVo5Pp5DrTDQu8a6ytjfjjHA9d1cT4+Smesy8/3M/CPwA5qf3NlnRcSBNIfVjzPzJ5XZnkMVrR0fz6HWGehd435gcuX1ZOC+bqylx9kRVBX/EVi2t3VLFxEB3AGsyMzbWizyHGLvx8dzqHV+yqWTImIuMIHmx3muA24CfgrcA/wJ8CowKTP75IXBvRyfCTT/qZzAGuCqHePFfU1EnAo8BbwI/LEy+waax4n7/DnUxvG5GM+hPRjoklQIh1wkqRAGuiQVwkCXpEIY6JJUCANdkgphoEtSIQx0SSrE/wf1oURZQPfSFQAAAABJRU5ErkJggg==
"
>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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vHnccsst7ZY1a9YsZs2axQsvvMDnP//5Ty1bs2YN8+fP59VXX2XTpk387ne/A2DmzJm88MIL+/6yaDlktHfvXlauXMn8+fO5/fbbOeKII5g3bx5Tp06loaGBqVOnlvAnUXzQLwOmZZ+nAUtbzL8yu/pmPLDD4/Nm1h1OPvlkNm/ezKJFiw4YDtmxYwdTpkzhpJNOYvbs2axbt67dsn7/+98zZcoUAL75zW9+atnYsWOpqqrisMMOo6amhs2bNwPw1FNPMW7cOEaOHMmTTz75qX184xvfAOArX/nKvvW7Umcur1wE/B74sqRGSVcDdwBnS9oInJ1NAzwKbAJeB+4DvtMltTYz64RJkyZxww03fGrYBuDWW2/l9NNPZ+3atfzqV7/KdY167969932uqKhg79697N69m+985zssWbKEV155henTp39qH83bNK/f1Tpz1c2lbSw6s5V1A7gub6XMzErhqquu4uijj2bkyJHU19fvm79jx459J2cXLFjQYTnjx4/nkUceYerUqSxevLjD9ZtDfdCgQezcuZMlS5YwefLkdrc56qij+PDDDzssuxi+BYKZda1SX155EKqqqpg1a9YB82+88UamTZvGnXfeyRlnnNFhOfPnz+fyyy/nRz/6ERdccAFHH310u+v379+f6dOnM3LkSKqrqxkzZkyH+zj99NO54447qKmpYc6cOSUdp1fzmeDuNHr06PCDR7qeL6+0Q2H9+vWMGDGiu6tRUh999BF9+/ZFEosXL2bRokUsXbq04w1LqLWfq6TVETG6o23dozcz68Dq1auZOXMmEUH//v154IEHurtKB8VBb2bWga997Wu89NJL3V2NovnulWZmiXPQm5klzkM3PcShOFFqZp9N7tGbmSXOPXoz61Kl/mu1M5fwVlRUMHLkSCKCiooK7rnnHiZMmFDU/ubOncvXv/51zjrrrKK27wkc9GaWnL59+9LQ0ADAY489xpw5c3j66aeLKmvevHmlrFq38NCNmSXtgw8+YMCAAfumf/CDHzBmzBhOPvlkbrvtNgA2b97MiBEjmD59OieeeCLnnHMOu3btAuBb3/oWS5YsAeDRRx9l+PDhnHbaaVx//fVceOGFANTV1XHVVVdRW1vLCSecwN13332IW9k+B72ZJWfXrl3U1NQwfPhwrrnmGm699VYAVqxYwcaNG1m5ciUNDQ2sXr2a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
"
>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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BqCxsZELLriAiRMncuCBB/L973+/yr/lrpXaR79/RKwDyH7ul00fCrxYtFxLNm0HkqZJWippaWtra4llmJntaPPmzTQ0NDBy5Ei+9KUvcdVVVwFw7733snr1apYsWUJzczPLli3joYceAmD16tVccsklLF++nP79+2+7t02bLVu2cNFFF3H33Xfz8MMP0z63Vq1axT333MOSJUu45ppreOedd6rzy3ZBuS/GdvQNth3eYyEiro+I0RExevDgwWUuw8zey9q6blatWsUvf/lLzj33XCKCe++9l3vvvZcjjjiCj370o6xatYrVq1cDMHz4cBoaGoCObx+8atUqDjzwQIYPHw6wwx0xTzrpJHr37s2gQYPYb7/9eOWVVyr/i3ZRqZ+MfUXSkIhYl3XNrM+mtwAfLFquHng5T4FmZnkceeSRvPrqq7S2thIRzJo1i4suumi7ZdauXbvD7Ybbum7adHZfsI5uV1wrSj2jvwOYkg1PAW4vmn6uCsYDG9u6eMzMesKqVat49913GThwIMcffzw33ngjmzZtAuCll15i/fr1nbRQMHLkSNasWbPtTL/cX/dXSV15e+UCYCIwSFILcDVwLXCrpAuB3wOnZ4v/gsJbK5+j8PbK8ytQs5ntRnriDqZtffRQOBOfP38+dXV1HHfccaxcuZIjjzwSgH79+nHLLbdQV1fXaZt9+/blhz/8ISeccAKDBg1i7NixFf0dysm3KX6P8m2KrVJSvE1xm02bNtGvXz8igksuuYQRI0Ywc+bMqmw7z22K/clYM7Mu+vGPf0xDQwOHHnooGzdu3KGvv1b5NsVmZl00c+bMqp3Bl5PP6M2s7GqhSzglefeng97MyqpPnz5s2LDBYV8mEcGGDRvo06dPyW2468bMyqq+vp6WlpYdPjlqpevTpw/19fUlr++gN7Oy2muvvbZ9etRqg7tuzMwS56A3M0ucg97MLHEOejOzxDnozcwS56A3M0ucg97MLHEOejOzxDnozcwS56A3M0ucg97MLHEOejOzxDnozcwS56A3M0ucg97MLHEOejOzxDnozcwS56A3M0ucg97MLHEOejOzxDnozcwS56A3M0ucg97MLHG5gl7STEnLJT0jaYGkPpKGS3pM0mpJiyT1KlexZmbWfXuWuqKkocClwCERsVnSrcCZwInAdyNioaQfARcC15WlWtvtNDY1Vmc7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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <strong>Análisis:</strong>
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
     <p>Después de representar las variables de <i>'radius_mean', 'texture_mean', 'smoothness_mean' y 'symmetry_mean'</i> en diferentes histogramas, podemos afirmar que <b>los picos de los histogramas siempre obtienen un valor más alto para los tumores malignos que para los benignos</b>. Por tanto podemos decir que para estos datos, <b>los tumores malignos tienen mayor radio medio, mayor textura media, mayor suavidad media y mayor simetría media</b>.</p>
</div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <strong>Diagramas de violín:</strong>
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
     <p>Los diagramas de violín nos pueden ser útiles para visualizar la distribución de los datos tal y como hemos generado en la tabla del ejercicio 2.1. </p>
    <p>Aquí también se puede observar que los valores de la mediana siempre son superiores en los tumores malignos que en los tumores benignos.</p>
</div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">pintaDiagramaViolin</span><span class="p">(</span><span class="n">data</span><span class="p">,</span> <span class="n">data_dia</span><span class="p">):</span>
    <span class="n">data_n_2</span> <span class="o">=</span> <span class="p">(</span><span class="n">data</span> <span class="o">-</span> <span class="n">data</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span> <span class="o">/</span> <span class="p">(</span><span class="n">data</span><span class="o">.</span><span class="n">std</span><span class="p">())</span>              <span class="c1"># estandarización</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">y</span><span class="p">,</span><span class="n">data_n_2</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">8</span><span class="p">]]],</span><span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">melt</span><span class="p">(</span><span class="n">data</span><span class="p">,</span><span class="n">id_vars</span><span class="o">=</span><span class="s2">&quot;diagnosis&quot;</span><span class="p">,</span>
                        <span class="n">var_name</span><span class="o">=</span><span class="s2">&quot;features&quot;</span><span class="p">,</span>
                        <span class="n">value_name</span><span class="o">=</span><span class="s1">&#39;value&#39;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
    <span class="n">my_pal</span> <span class="o">=</span> <span class="p">{</span><span class="s2">&quot;M&quot;</span><span class="p">:</span> <span class="s2">&quot;r&quot;</span><span class="p">,</span> <span class="s2">&quot;B&quot;</span><span class="p">:</span> <span class="s2">&quot;g&quot;</span><span class="p">}</span>
    <span class="n">sns</span><span class="o">.</span><span class="n">violinplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s2">&quot;features&quot;</span><span class="p">,</span> <span class="n">y</span><span class="o">=</span><span class="s2">&quot;value&quot;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s2">&quot;diagnosis&quot;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">data</span><span class="p">,</span><span class="n">split</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">inner</span><span class="o">=</span><span class="s2">&quot;quart&quot;</span><span class="p">,</span> <span class="n">palette</span><span class="o">=</span><span class="n">my_pal</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">90</span><span class="p">)</span>
    
<span class="n">pintaDiagramaViolin</span><span class="p">(</span><span class="n">x</span><span class="p">,</span><span class="n">y</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAmMAAAKjCAYAAABRIAjJAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADl0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uIDMuMC4yLCBodHRwOi8vbWF0cGxvdGxpYi5vcmcvOIA7rQAAIABJREFUeJzs3XmcFNW9NvDn9OzDwICAoALiihogxiUYzaLG16veG301MS6J3iRXk2sSY3yjcYkhuW6YuESUa1ARUSIggrLLLosKyCAwDOvAsMy+z/TeXct5/+ipcRhmqerp7urqfr6fDx91lq6fQ03V079z6hwhpQQRERER2cNldwFERERE6YxhjIiIiMhGDGNERERENmIYIyIiIrIRwxgRERGRjRjGiIiIiGzEMEZERERkI4YxIiIiIhsxjBERERHZKNPuAqwYMmSIHD16tN1lEBEREfVq27ZtDVLKob19naPC2OjRo1FUVGR3GURERES9EkIcNfN1HKYkIiIishHDGBEREZGNGMaIiIiIbOSoOWNERETkTIqioKKiAsFg0O5SYi43NxcjRoxAVlZWVN/PMEZERERxV1FRgf79+2P06NEQQthdTsxIKdHY2IiKigqcccYZUb0GhymJiIgo7oLBIAYPHpxSQQwAhBAYPHhwnzp+DGNERESUEKkWxAx9/f9iGCMiIiKyEeeMERERUVL461//ioKCArjdbnz3u9/FNddcY1stEydOTFgNDGNERESUVJ588km7S0hoDRymJCIiIts888wzGDNmDK655hrs378fAPCzn/0M8+bNAxAJRZdeeinGjh2LX/7yl5BSAgC2bt2K8ePH41vf+hYefvhhjB07FgAwY8YM3HLLLbjuuutwzjnn4I9//GP7sWbPno1x48Zh7NixeOSRRwAAmqbhZz/7GcaOHYtx48bhH//4xwk1PProo7jgggswfvx4PPTQQzH/GbAzRkRERLbYtm0b5syZg+3bt0NVVVx00UW4+OKLj/ua3/72t5g4cSIA4K677sKSJUvwgx/8AD//+c/xxhtv4PLLL8ejjz563Pfs2LED27dvR05ODsaMGYP7778fGRkZeOSRR7Bt2zYMGjQI1157LRYsWICRI0eisrISJSUlAICWlpbjXqupqQkfffQR9u3bByHECZ+PBXbGiIiIyBYbN27EzTffjPz8fAwYMAA33njjCV/zySefYMKECRg3bhzWrl2L3bt3o6WlBR6PB5dffjkA4M477zzue77//e+jsLAQubm5uOCCC3D06FFs3boVV155JYYOHYrMzEz85Cc/wYYNG3DmmWeirKwM999/P5YvX44BAwYc91oDBgxAbm4u7rnnHnz44YfIz8+P+c+BYYyIiIhs09OyEMFgEL/+9a8xb9487Nq1C/feey+CwWD7UGV3cnJy2v89IyMDqqp2+z2DBg3Czp07ceWVV+J///d/cc899xz3+czMTHzxxRf44Q9/iAULFuC6666z8H9nDsMYERER2eK73/0uPvroIwQCAXg8HixevPi4zxsLqQ4ZMgRer7d9DtegQYPQv39/bN68GQAwZ86cXo81YcIErF+/Hg0NDdA0DbNnz8b3vvc9NDQ0QNd1/PCHP8RTTz2FL7/88rjv83q9aG1txQ033ICXX34ZO3bsiMX/+nE4Z4yIiIhscdFFF+G2227DhRdeiNNPPx3f+c53jvv8wIEDce+992LcuHEYPXo0Lr300vbPvfXWW7j33nvRr18/XHnllSgsLOzxWKeccgomTZqEq666ClJK3HDDDbjpppuwc+dO/PznP4eu6wCASZMmHfd9Ho8HN910U3tHzpjgH0uit1ZfMrnkkktkUVGR3WUQERGRRXv37sX5558fs9fzer0oKCgAADz33HOorq7G5MmTY/b6VnX1/yeE2CalvKS372VnjIiIiBxn6dKlmDRpElRVxemnn44ZM2bYXVLUGMaIiIjIcW677TbcdtttdpcRE5zAT0RERGQjhjEiIiIiGzGMEREREdmIYYyIiE6wdetWPPvss70urklEfccJ/EREdIIHH3wQ9fX1ePjhh5GVlWV3OZRG7rvzTjRXV8fs9Qadcgr+OWtWj18jhMBPf/pTzJw5EwCgqipOOeUUTJgwAUuWLIlZLd1hGCMiohPU19cDQPtCmESJ0lxdjeeOHInZ6z3a+5egX79+KCkpQSAQQF5eHlatWoXTTjstZjX0hsOURETULU3T7C6BKCGuv/56LF26FAAwe/Zs3HHHHQk7NsMYERF1i50xShe333475syZg2AwiOLiYkyYMCFhx2YYIyKiE7hckdsDwxili/Hjx+PIkSOYPXs2brjhhoQem2GMKE14vV78+NZbsWnTJrtLIQfIyMgAEJnI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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Para cada uno de los atributos representados en el ejercicio anterior, mostrad la media y la desviación estándard para cada valor de clase de la respuesta ("Diagnosis"). La finalidad es verificar numéricamente las diferencias identificadas anteriormente de forma visual.
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Obtenemos conjunto de datos para tumores malignos</span>

<span class="c1">#El eje &#39;X&#39; será los diferentes atributos mientras que el eje &#39;Y&#39; serán los valores del propios de la media </span>
<span class="c1"># y la desviación típica</span>

<span class="n">aux</span> <span class="o">=</span> <span class="n">all_data</span><span class="p">[</span><span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span><span class="o">==</span><span class="s1">&#39;M&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
<span class="n">mean_all_data_m</span> <span class="o">=</span> <span class="n">aux</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="s1">&#39;mean&#39;</span><span class="p">,:]</span>
<span class="n">std_all_data_m</span> <span class="o">=</span> <span class="n">aux</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="s1">&#39;std&#39;</span><span class="p">,:]</span>
<span class="n">mean_all_data_m</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[11]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>radius_mean         17.462830
texture_mean        21.604906
perimeter_mean     115.365377
area_mean          978.376415
smoothness_mean      0.102898
Name: mean, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[12]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Obtenemos conjunto de datos para tumores benignos</span>

<span class="c1">#El eje &#39;X&#39; será los diferentes atributos mientras que el eje &#39;Y&#39; serán los valores del propios de la media </span>
<span class="c1"># y la desviación típica</span>

<span class="n">aux</span> <span class="o">=</span> <span class="n">all_data</span><span class="p">[</span><span class="n">all_data</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span><span class="o">==</span><span class="s1">&#39;B&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
<span class="n">mean_all_data_b</span> <span class="o">=</span> <span class="n">aux</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="s1">&#39;mean&#39;</span><span class="p">,:]</span>
<span class="n">std_all_data_b</span> <span class="o">=</span> <span class="n">aux</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="s1">&#39;std&#39;</span><span class="p">,:]</span>
<span class="n">mean_all_data_b</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[12]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>radius_mean         12.146524
texture_mean        17.914762
perimeter_mean      78.075406
area_mean          462.790196
smoothness_mean      0.092478
Name: mean, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <strong>Diagramas de medias y desviaciones estándares:</strong>
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
     <p>Una vez calculados los valores medios y desviaciones estándares para cada atributo procedemos a visualizar.</p>
</div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Dibujamos nuestro gráfico</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">mean_all_data_b</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;#04B404&quot;</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;media tumor benigno&quot;</span><span class="p">)</span> 
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">std_all_data_b</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;#A9F5A9&quot;</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;std tumor benigno&quot;</span><span class="p">)</span> 
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">mean_all_data_m</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;#FF0040&quot;</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;media tumor maligno&quot;</span><span class="p">)</span> 
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">std_all_data_m</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;#F5A9BC&quot;</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="s2">&quot;std tumor maligno&quot;</span><span class="p">)</span> 
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Media y desviación típica para tumores&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">90</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s2">&quot;upper left&quot;</span><span class="p">)</span> 
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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vvSlLzF//nwuuOACtmzZwoQJE7jpppv4xje+wc9+9jOuueaava550UUXcffdd3PCCSfwzW9+c69jr7zyCi+//DK9e/dm+PDhfOUrXyE3N5dZs2axYsUKCgsLmTx5MgsXLuTMM8/cz6clSZIkdVIxQmU1HNQ72yORpP2ycdRKpaWlLFq0iFmzZvHUU09RUFCwzznPP/88EydOZNCgQfTq1Yuzzz77gO87duxYiouL6d27N0cffTSTJ0+uG8+qVasAePbZZ/nCF74AwPnnn8+yZcvqnv/Zz3620dAI4JOf/CQDBgzgoIMOYvr06SxbtownnniCFStWMHbsWEaPHs0TTzzBX//6VwB69erFGWecAcDxxx9fd/9aGzduZNOmTXVT8GrHVGvSpEkUFBTQp08fPvKRj/DOO+/w4osv1r1nPXr04Nxzz2Xp0qUH9qZJkiRJHVX1Fti9BzZvg527sj0aSWpSs42jEMJc4AxgXYyxpMGxq4EfAINijBUhhADcAZwGbAVmxBhfSp17IVBbS/lujPEXBzr4/TWDMmXYsGGsWLGCxx57jG9961tMnjyZ6667bp/zkreidXr06MGePXsAiDGyY8eOumO9e//9/4nIycmp+zknJ4dduxr/F039MfTr16/J+zYcawiBGCMXXnghN9988z7n9+zZs+45ubm5+9w/xtjkvRq+ltrnN/ccSZIkqUuprP774w2b4JDC7I1FkvajJY2jecCUhjtDCEcAnwTerbf7VGBo6s+lwE9S5xYB1wPjgXHA9SGETvm/jGvXrqVv376cd955XH311bz00ksA5Ofns2nTJgDGjx/PkiVLqKysZOfOnTzwwAONXqv+cyCZvrZixQoAHn74YXbu3NmqsZ1wwgn85je/AWD+/PmceOKJLXre448/TlVVFdu2bWPhwoV87GMfY9KkSTz44IOsW7cOgKqqKt55550WXa+wsJD8/Hyee+45gLox7c/48eN58sknqaioYPfu3SxYsICTTz65RfeTJEmSOp2KBsGRJHVQzTaOYoxLQwiDGzl0O/AN4OF6+6YBv4xJfeS5EMLBIYRiYCLweIyxCiCE8DhJGLXggEafBa+99hpf//rXycnJoWfPnvzkJz8B4NJLL+XUU0+luLiYxYsXc8MNN/DRj36U4uJijjvuuLqFpeubOnUqn/nMZ3j44Ye58847ueSSS5g2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/7HHHuOYY47hxBNP5Morr+SMM84AkobSzJkzmThxIkcddRRz5sype/5tt91GSUkJJSUlzJ49u20fkCRJktSRVVQnWxtHkjqJHtkewIHY8fKb7Nm4Ka3XzDk4n17HDmvy+O9//3sOO+wwHn30UQCqq6spKCjgtttuY/HixQwcOJD33nuP66+/nhUrVlBQUEB5eTnHHnvsXtcZPHgwl112GXl5eVx99dUA3HPPPU3e909/+hMrV66kqKiIo446iosvvpgXXniBO+64gzvvvJPZs2dzxRVXcMEFF3DhhRcyd+5crrzyShYuXAjAm2++yaJFi8jNzd3n2q+//jovv/wy27dv58Mf/jDf//73efnll7nqqqv45S9/yVe/+lWmT5/OJZdcAsA111zDPffcw1e+8pVGx7p9+3a++MUvsnTpUoYMGcI555yz1/E33niDxYsXs2nTJoYPH87ll1/Oq6++yr333svzzz9PjJHx48dz8skn7/O+SZIkSZ1aU42j6i2wezc08t/rkpRNNo5aqbS0lEWLFjFr1iyeeuopCgoK9jnn+eefZ+LEiQwaNIhevXpx9tlnH/B9x44dS3FxMb179+boo49m8uTJdeNZtWoVAM8++yxf+MIXADj//PNZtmxZ3fM/+9nPNhoaAZSXl5Ofn8+gQYMoKChg6tSp+1z79ddf5+Mf/zilpaXMnz+fP//5z02O9Y033uCoo45iyJAhAPsER6effjq9e/dm4MCBHHLIIbz//vssW7aMf/iHf6Bfv37k5eUxffp0nnrqqda/UZIkSVJHVts4qh8cFeVDjEl4JEkdTKduHO2vGZQpw4YNY8WKFTz22GN861vfYvLkyVx33XX7nBdCaPW1e/TowZ49ewCIMbJjx466Y7179657nJOTU/dzTk5Ok+sW1R9Dv379mrxvS649Y8YMFi5cyKhRo5g3bx5Llixp8noxxiaPNbxfbm4uu3btavY5kiRJUpdQ2chUtcL8ZLthExT13/c5kpRFNo5aae3atfTt25fzzjuPq6++mpdeegmA/Px8Nm1Kps2NHz+eJUuWUFlZyc6dO3nggQcavVb950AyfW3FihUAPPzww+zcubNVYzvhhBP4zW9+A8D8+fM58cQTW/36mrJp0yaKi4vZuXMn8+fP3++5xxxzDH/961/r2kr3339/s9c/6aSTWLhwIVu3bmXLli38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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Análisis:</strong>
<br> - Mirando los gráficos, qué atributos te parece que tienen valores claramente diferentes para diagnósticos benignos y malignos? Qué atributos no?
    <div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <p>A simple vista vemos que <b>los valores de media, desviación de tumores malignos (líneas roja fuerte y roja clara) coinciden entre ellas para la mayoría de atributos y coinciden también con los valores de media y desviación para los tumores benignos (líneas verde fuerte y clara). </b></p>
    <p>Sin embargo, hay 6 atributos en los que no ocurre lo mismo. Estos atributos son: <b>'perimeter_mean', 'area_mean', 'area_se', 'radius_worst', 'perimeter_worst' y 'area_worst'</b>. En ellos <b>se aprecia una gran diferencia entre valores de la media para tumores benignos y malignos</b>.</p>
    </div>
<br> - Mirando a los valores medios y desviaciones estándard calculadas, te parecen significativas las diferencias para diagnósticos benignos y malignos?
    <div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p>En estos atributos se observa que hay una gran diferencia (aproximadamente de casi el doble en comparación de uno con otro) en la desviación típica por lo que <b>podemos deducir que por lo general para los tumores malignos existe un rango de valores muchísmo más amplio y grande que para los tumores benignos</b>. Ocurre también una <b>gran diferencia en los valores de media de estos atributos</b> y se puede entender que <b>la tendencia central para los tumores malignos es por lo general muchísimo más alta en estos atributos en comparación a los tumores benignos</b>.</p>
                              </div>
<br> - BONUS: qué test estadístico podrías usar para comparar las distribuciones de los valores de los atributos cuando los diagnósticos son benignos o malignos? Úsalo para evaluar qué atributos (de entre todos los del conjunto de datos) tienen valores más parecidos en tumores benignos y malignos. Interpreta el resultado.
    <div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p>En este caso utilizaríamos un test estadístico entre dos muestras basado en la distribución normal. Por ello nuestra hiótesis nula sería que ambas distribuciones tienen valores parecidos (&mu;_1 == &mu;_2) en otro caso rechazaríamos la hipótesis nula y podríamos decir que no tienen valores parecidos en ambas muestras.</p>
                              </div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[14]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">scipy</span> <span class="k">import</span> <span class="n">stats</span>
<span class="n">stats</span><span class="o">.</span><span class="n">ttest_ind</span><span class="p">(</span><span class="n">malignant</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">),</span> <span class="n">benign</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[14]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Ttest_indResult(statistic=array([25.43582161, 10.86720108,  9.14609881,  8.33831179]), pvalue=array([8.46594057e-96, 4.05863605e-25, 1.05185036e-18, 5.73338403e-16]))</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p>Para un 95% de confianza (nivel significativo de &alpha;=0.05) tenemos que el p-value para las variables de <i>'radius_mean', 'texture_mean', 'smoothness_mean' y 'symmetry_mean'</i> son inferiores a &alpha; y rechazamos la hipótisis nula. </div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="3.-Reducci&#243;n-de-dimensionalidad-(2-puntos)">3. Reducci&#243;n de dimensionalidad (2 puntos)<a class="anchor-link" href="#3.-Reducci&#243;n-de-dimensionalidad-(2-puntos)">&#182;</a></h1><p>En este ejercicio deberéis aplicar métodos de reducción de dimensionalidad al conjunto original de datos. El objetivo es reducir el conjunto de atributos a un nuevo conjunto con menos dimensiones.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Aplicad los métodos de reducción de dimensionalidad:
<br>- Principal Component Analysis (PCA)
<br>- t-distributed Stochastic Neighbor Embedding (t-SNE)
<br>para reducir el conjunto de datos a 2 dimensiones.

<hr>
Sugerencia: No es necesario que programéis los algoritmos, podéis hacer uso de las implementaciones disponibles en la librería "scikit-learn".
</div><div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Principal Component Analysis (PCA) :</strong> 
Para aplicar correctamente esta técnica <b>debemos aplicar una normalización en los datos</b>. 
De esta manera utilizando la librería de <b>StandardScaler normalizaremos y a cada dato se le restará la media de la variable y se dividirá por la desviación típica</b>. De esta manera conseguiremos la normalización de media = 0 y desviación estandar = 1. 

<p>A continuación, hacemos uso de la función PCA de la librería scikit-learn y reducimos la dimensionalidad
de nuestro dataset a <b>2 dimensiones</b>. Después lo guardamos en un dataframe que tendrá los dos atributos seleccionados
por el PCA y le añadimos la etiqueta de clase diagnosis.</p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Principal Component Analysis (PCA)</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="k">import</span> <span class="n">StandardScaler</span>
<span class="n">x_scaled</span> <span class="o">=</span> <span class="n">StandardScaler</span><span class="p">()</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>

<span class="kn">from</span> <span class="nn">sklearn.decomposition</span> <span class="k">import</span> <span class="n">PCA</span>

<span class="n">pca</span> <span class="o">=</span> <span class="n">PCA</span><span class="p">(</span><span class="n">n_components</span><span class="o">=</span><span class="mi">2</span><span class="p">)</span>
<span class="n">principalComponents</span> <span class="o">=</span> <span class="n">pca</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">x_scaled</span><span class="p">)</span>

<span class="n">principalDf</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">principalComponents</span>
             <span class="p">,</span> <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;principal component 1&#39;</span><span class="p">,</span> <span class="s1">&#39;principal component 2&#39;</span><span class="p">])</span>

<span class="n">finalDf</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">principalDf</span><span class="p">,</span> <span class="n">all_data</span><span class="p">[[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]]],</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>t-distributed Stochastic Neighbor Embedding (t-SNE):</strong> Para aplicar t-SNE debemos aplicar una 
    normalización de datos al igual que hemos hecho sobre PCA y a continuación el algoritmo procederá a realizar
    una exploración de los datos y atributos con una técnica no lineal.
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># t-distributed Stochastic Neighbor Embedding (t-SNE)</span>
<span class="kn">from</span> <span class="nn">sklearn.manifold</span> <span class="k">import</span> <span class="n">TSNE</span>

<span class="n">tsne</span> <span class="o">=</span> <span class="n">TSNE</span><span class="p">(</span><span class="n">n_components</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">verbose</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">perplexity</span><span class="o">=</span><span class="mi">40</span><span class="p">,</span> <span class="n">n_iter</span><span class="o">=</span><span class="mi">300</span><span class="p">)</span>

<span class="n">tsne_results</span> <span class="o">=</span> <span class="n">tsne</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">x_scaled</span><span class="p">)</span>

<span class="n">df_tsne</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">tsne_results</span><span class="p">,</span>
                           <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;t-sne1&#39;</span><span class="p">,</span> <span class="s1">&#39;t-sne2&#39;</span><span class="p">])</span>


<span class="n">df_tsne_with_target</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">df_tsne</span><span class="p">,</span> <span class="n">all_data</span><span class="p">[[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]]],</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>[t-SNE] Computing 121 nearest neighbors...
[t-SNE] Indexed 569 samples in 0.001s...
[t-SNE] Computed neighbors for 569 samples in 0.039s...
[t-SNE] Computed conditional probabilities for sample 569 / 569
[t-SNE] Mean sigma: 1.522404
[t-SNE] KL divergence after 250 iterations with early exaggeration: 64.981239
[t-SNE] KL divergence after 300 iterations: 0.908597
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Generad un gráfico (en 2D) con el resultado de cada uno de los métodos de reducción de la dimensión, usando colores diferentes para cada clase de la respuesta, con el objetivo de visualizar si es posible separar eficientemente las clases empleando estos métodos.</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Principal Component Analysis (PCA) :</strong> Visualizamos los datos en función de los dos atributos 
    seleccionados por nuestro algoritmo.
    <p>Se puede observar una separación lineal clara entre las clases benigna y maligna. Esto indica que ambos atributos no son linealmente dependientes y que pueden ser muy útiles para entrenar y realizar predicciones para nuevos conjuntos de datos.</p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Visualización para el método PCA</span>
<span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">8</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span> 
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 1&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 2&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;Scatterplot of Points plotted in first 2 component PCA&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">20</span><span class="p">)</span>
<span class="n">targets</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;M&#39;</span><span class="p">,</span> <span class="s1">&#39;B&#39;</span><span class="p">]</span>
<span class="n">colors</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;r&#39;</span><span class="p">,</span> <span class="s1">&#39;g&#39;</span><span class="p">]</span>
<span class="k">for</span> <span class="n">target</span><span class="p">,</span> <span class="n">color</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">targets</span><span class="p">,</span><span class="n">colors</span><span class="p">):</span>
    <span class="n">indicesToKeep</span> <span class="o">=</span> <span class="n">finalDf</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="n">target</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">finalDf</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">indicesToKeep</span><span class="p">,</span> <span class="s1">&#39;principal component 1&#39;</span><span class="p">]</span>
               <span class="p">,</span> <span class="n">finalDf</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">indicesToKeep</span><span class="p">,</span> <span class="s1">&#39;principal component 2&#39;</span><span class="p">]</span>
               <span class="p">,</span> <span class="n">c</span> <span class="o">=</span> <span class="n">color</span>
               <span class="p">,</span> <span class="n">s</span> <span class="o">=</span> <span class="mi">50</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">targets</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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qXgdz3bQsqqFhE3Q1ddFtCbKsnXLaF/UTvOM5lIXT0TypD4nIlLR4j1xWla1EO+N09XnRlJ09XUR73XTd/aGS44lImNPwYmIVLS2TW0krH9yrIRN0LYxXHIsERl7Ck5EpKJ1bu8crDFJ19XXxeYd4ZNjicjYUnAiIhWtaVoT0Zqo77xoTZRZU8MnxxIZTVVVVRx66KHMmTOHww47jAceeKDURSo5BSciUtFis2NEjP+pLGIixA4JnxxLJCneE6d1QyvL71hO64ZW4j3x0OucPHkyjz76KI899hgXXXQR5557bhFKWtk0WkdEKlpDXQPti9pHjNaJmAjti9qpr1UOCimOsRgV9tprr7HnnnsWZV2VTMGJiFS85hnNbDt7G20b29i8YzOzps4idkhMgYkUTeqosKRkX6eWVS1sO3tbwcfb7t27OfTQQ+nu7ub555/n7rvvLkqZK5mCExEZF+pr61l8mJJjyegIMiqs0OMv2awD8OCDD3LaaaexceNGjDEFl7fSqc+JiIhIDmM1KuzII4/klVde4eWXXy7K+iqVghMREZEcxmpU2BNPPMHAwADTpk0ryvoqlZp1REREcojNjrFs3TLfeWFHhSX7nABYa1m5ciVVVVUFr288UHAiIiKSw2iOChsYGChiSccHBSciIiIBaFTY2FFwIiIiEpBGhY0NdYgVERGRsqLgREREJjRrbamLEFgllTUMBSciIjJhTZo0ie3bt1fERd9ay/bt25k0aVKpizLq1OdEREQmrOnTp7N169ZhSc+6u7vLNgCYNGkS06dPL3UxRp2CExERmbBqamqYOXPmsGnr16/nHe94R4lKJKBmHRERESkzCk5ERESkrCg4ERERkbKi4ERERETKioITERERKSsKTkRERKSsKDgRERGRsqLgRERERMqKghMREREpKwpOREREpKwoOBEREZGyouBEREREyoqCExERESkrCk5ERESkrCg4ERERkbKi4ERERETKioITERERKSsKTkRERKSsKDgRERGRsqLgRERERMqKghMREREpKwpOREREpKwoOBEREZGyUl3qAoiIFEU8Dm1t0NkJTU0Qi0FDQ6lLJSIFUHAiIpWvowNaWiCRgK4uiEZh2TJob4fm5lKXTkTypGYdEals8bgLTOJxF5iAe01O37mztOUTkbwpOBGRytbW5mpM/CQSbr6IVBQFJyJS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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>t-distributed Stochastic Neighbor Embedding (t-SNE):</strong> Visualizamos los datos en función de los dos atributos seleccionados por nuestro algoritmo.
    <p>En este caso se puede ver tambiénuna separación lineal clara entre las clases benigna y maligna aunque esta vez es la partición sería diferente. Esto indica que con este algoritmo también hemos conseguido dos atributos que  no son linealmente dependientes y que pueden ser muy útiles para entrenar y realizar predicciones para nuevos conjuntos de datos.</p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[18]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Visualización para el método t-SNE</span>
<span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">8</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span> 
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">&#39;t-sne1&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;t-sne2&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;Scatterplot of Points plotted in first 2 component t-SNE&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">20</span><span class="p">)</span>
<span class="n">targets</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;M&#39;</span><span class="p">,</span> <span class="s1">&#39;B&#39;</span><span class="p">]</span>
<span class="n">colors</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;r&#39;</span><span class="p">,</span> <span class="s1">&#39;g&#39;</span><span class="p">]</span>
<span class="k">for</span> <span class="n">target</span><span class="p">,</span> <span class="n">color</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">targets</span><span class="p">,</span><span class="n">colors</span><span class="p">):</span>
    <span class="n">indicesToKeep</span> <span class="o">=</span> <span class="n">df_tsne_with_target</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="n">target</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">df_tsne_with_target</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">indicesToKeep</span><span class="p">,</span> <span class="s1">&#39;t-sne1&#39;</span><span class="p">]</span>
               <span class="p">,</span> <span class="n">df_tsne_with_target</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">indicesToKeep</span><span class="p">,</span> <span class="s1">&#39;t-sne2&#39;</span><span class="p">]</span>
               <span class="p">,</span> <span class="n">c</span> <span class="o">=</span> <span class="n">color</span>
               <span class="p">,</span> <span class="n">s</span> <span class="o">=</span> <span class="mi">50</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">targets</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Análisis:</strong>
<br> - Qué método de reducción de dimensionalidad ha resultado más efectivo para visualizar las dos clases de diagnóstico de forma separada?
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<p> A mi parecer, para este caso en particular de dos atributos y estos datos parece que el algoritmo de PCA separa los diferentes datos de manera más clara que el t-SNE. No obstante, puede ser que para otro tipo de problemas u otro número de atributos funcione mejor el t-SNE.</p>
</div>
<br> - BONUS: cuándo es más apropriado usar PCA o t-SNE?
    <div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<p>El <b>PCA</b> es <b>una técinca de reducción de la dimensión de manera lineal que se centra en maximizar la varianza y conservar grandes distancia entre pares</b>. El problema de esta visualización es que puede presentar problemas para estrcturas de datos que no siguen una estructura lineal. Sin embargo, el <b>t-SNE</b> es <b>una técnica no lineal de manera que se amolda a la figura que dibujan los datos</b>. Además,<b>se centra en conservar únicamente las pequeñas distancias entre pares o similaridades locales</b>. Otra diferencia es PCA es un algoritmo determinístico mientras que el t-SNE no lo es.</p>

<p>Depende de la tipología del problema puede ser más apropiado utilizar uno u otro. Mientras que el <b>PCA está enfocado a problemas lineales, el t-SNE está enfocado a problemas no lineales</b>. Además, t-SNE es un algoritmo probabilístico que utiliza dos distribuciones distintas para encontrar las similaridades mientras que el PCA es un algoritmo determinístico.
</p>

<p>
Para nuestro problema en concreto, tras ver la representación de los datos con ambos algoritmos, <b>se puede observar que para estos datos en particular interesa aplicar el algoritmo del PCA para que aplique un algoritmo determinístico lineal para la separación de variables.</b>
</p>

</div>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="4.-Aplicaci&#243;n-de-CART-(3-puntos)">4. Aplicaci&#243;n de CART (3 puntos)<a class="anchor-link" href="#4.-Aplicaci&#243;n-de-CART-(3-puntos)">&#182;</a></h1><p>En este último ejercicio se trata de aplicar un método de aprendizaje supervisado, concretamente los árboles de decisión, para predecir el diagnóstico de cáncer de mama (tumor benigno o maligno) y evaluar la precisión obtenida con el modelo, usando:</p>
<ul>
<li>El conjunto de datos original con todos los atributos</li>
<li>El conjunto de datos reducido a sólo 2 atributos con el método PCA</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Implementación:</strong> Entrenad dos modelos usando árboles de decisión (con una profundidad máxima limitada a 3 niveles para mantener el modelo simple): uno usando el conjunto de datos original y el otro usando el conjunto de datos reducido con PCA.
<br>Calculad la precisión de las predicciones obtenidas por cada uno de los modelos (accuracy) así como la matriz de confusión asociada.
<hr>
Sugerencia: es necesario que generéis un conjunto de datos de entrenamiento para calibrar el modelo, y otro conjunto de test para evaluar la bondad de cada uno de los modelos creados. Podéis usar los módulos 'train_test_split', 'DecisionTreeClassifier' y las funciones dentro del módulo 'metrics' de sckit-learn.
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">KFold</span>

<span class="k">def</span> <span class="nf">CART_decisionTreeClassifier_Train</span><span class="p">(</span><span class="n">x_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">x_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">):</span>

    <span class="c1"># Juntamos el train dentro de una matriz para poder realizar el split del </span>
    <span class="c1"># k-fold cross validation de una manera más sencilla</span>
    <span class="n">_data</span> <span class="o">=</span> <span class="n">x_train</span>
    <span class="n">_data</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">y_train</span>
    <span class="n">n_samples</span><span class="p">,</span> <span class="n">n_features</span> <span class="o">=</span> <span class="n">_data</span><span class="o">.</span><span class="n">shape</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Numero de filas: &quot;</span><span class="p">,</span> <span class="n">n_samples</span><span class="p">,</span> <span class="s2">&quot;y el numero de columnas&quot;</span><span class="p">,</span> <span class="n">n_features</span><span class="p">)</span>
    
    <span class="c1">#**********************************************************************************</span>
    <span class="c1">#************************************TRAIN*****************************************</span>
    <span class="c1">#**********************************************************************************</span>
    <span class="n">n_samples</span><span class="p">,</span> <span class="n">n_features</span> <span class="o">=</span> <span class="n">_data</span><span class="o">.</span><span class="n">shape</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Numero de filas: &quot;</span><span class="p">,</span> <span class="n">n_samples</span><span class="p">,</span> <span class="s2">&quot;y el numero de columnas&quot;</span><span class="p">,</span> <span class="n">n_features</span><span class="p">)</span>
    <span class="n">cv</span> <span class="o">=</span> <span class="n">KFold</span><span class="p">(</span><span class="n">n_splits</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span> <span class="c1"># Asignamos el numero de las k-fold que queremos realizar</span>
    <span class="n">accuracies</span> <span class="o">=</span> <span class="nb">list</span><span class="p">()</span>
    <span class="n">depth</span> <span class="o">=</span> <span class="mi">3</span> <span class="c1"># Profundidad 3 en nuestro algoritmo de árboles de decisión</span>

    <span class="n">fold_accuracy</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="n">clf_cart</span> <span class="o">=</span> <span class="n">DecisionTreeClassifier</span><span class="p">(</span><span class="n">class_weight</span><span class="o">=</span><span class="kc">None</span><span class="p">,</span> <span class="n">criterion</span><span class="o">=</span><span class="s1">&#39;entropy&#39;</span><span class="p">,</span> <span class="n">max_depth</span><span class="o">=</span><span class="n">depth</span><span class="p">,</span>
            <span class="n">max_features</span><span class="o">=</span><span class="kc">None</span><span class="p">,</span> <span class="n">max_leaf_nodes</span><span class="o">=</span><span class="kc">None</span><span class="p">,</span> <span class="n">min_samples_leaf</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
            <span class="n">min_samples_split</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">min_weight_fraction_leaf</span><span class="o">=</span><span class="mf">0.0</span><span class="p">,</span>
            <span class="n">presort</span><span class="o">=</span><span class="kc">False</span><span class="p">,</span> <span class="n">random_state</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span> <span class="n">splitter</span><span class="o">=</span><span class="s1">&#39;best&#39;</span><span class="p">)</span>

    <span class="c1"># Dentro de la división que ha realizado KFold, dividimos en conjunto de entrenamiento </span>
    <span class="c1"># y conjunto de validación</span>
    <span class="k">for</span> <span class="n">train_fold</span><span class="p">,</span> <span class="n">valid_fold</span> <span class="ow">in</span> <span class="n">cv</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="n">_data</span><span class="p">):</span>
        <span class="n">f_train</span> <span class="o">=</span> <span class="n">_data</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="n">train_fold</span><span class="p">]</span>
        <span class="n">f_valid</span> <span class="o">=</span> <span class="n">_data</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="n">valid_fold</span><span class="p">]</span>

        <span class="n">model</span> <span class="o">=</span> <span class="n">clf_cart</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X</span> <span class="o">=</span> <span class="n">f_train</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">),</span> <span class="n">y</span><span class="o">=</span><span class="n">f_train</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">])</span>
        <span class="n">valid_acc</span> <span class="o">=</span> <span class="n">model</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">X</span> <span class="o">=</span> <span class="n">f_valid</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">),</span> <span class="n">y</span><span class="o">=</span><span class="n">f_valid</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">])</span> <span class="c1"># calculamos la precision con el segmento de validacion</span>
        <span class="n">fold_accuracy</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">valid_acc</span><span class="p">)</span>

    <span class="n">avg</span> <span class="o">=</span> <span class="nb">sum</span><span class="p">(</span><span class="n">fold_accuracy</span><span class="p">)</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">fold_accuracy</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;El accuracy en train es de:&quot;</span><span class="p">,</span> <span class="n">avg</span><span class="p">)</span>

    <span class="k">return</span> <span class="n">model</span><span class="p">;</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
        <p>
        Para este ejercicio se ha optado por dividir el conjunto de datos en dos subconjuntos:
            <ul>
                <li><b>Conjunto de entrenamiento (<i>train</i>)</b>, que contendrá el 70% de los datos proporcionados.</li>
                <li><b>Conjunto de validación (<i>test</i>)</b>, que contendrá el 30% restante.</li>
            <ul>
        </p>
        <p>
            A continuación, para el conjunto de entrenamiento aplicaremos una metodología de aprendizaje basada en <b>árboles de decisión con el algoritmo CART</b> y aplicaremos un <b>k-fold cross validation</b> para poder garantizar que son independientes de la partición que se realiza inicialmente entre datos de entrenamiento y prueba. Para este problema en particular hemos parametrizado con un <i>k=5</k>.
        </p>

</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p><b>Empezaremos con el conjunto de datos original con todos los atributos.</b></p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[20]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x_1</span> <span class="o">=</span> <span class="n">x</span>
<span class="n">y_1</span> <span class="o">=</span> <span class="n">y</span><span class="o">.</span><span class="n">map</span><span class="p">({</span><span class="s2">&quot;M&quot;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s2">&quot;B&quot;</span><span class="p">:</span><span class="mi">1</span><span class="p">})</span>

<span class="c1"># dividimos en dos: 70% para train y 30% para test</span>
<span class="n">x_train</span><span class="p">,</span> <span class="n">x_test</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">y_test</span> <span class="o">=</span> <span class="n">train_test_split</span><span class="p">(</span><span class="n">x_1</span><span class="p">,</span> <span class="n">y_1</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.3</span><span class="p">,</span> <span class="n">random_state</span><span class="o">=</span><span class="mi">42</span><span class="p">)</span>

<span class="c1">#_Llamamos a la función de clasificación que aplicará k-fold cross validation con k=5</span>
<span class="c1"># y nos devolverá un modelo de entrenamiento</span>
<span class="n">clf_cart</span> <span class="o">=</span> <span class="n">CART_decisionTreeClassifier_Train</span><span class="p">(</span><span class="n">x_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">x_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Numero de filas:  398 y el numero de columnas 31
Numero de filas:  398 y el numero de columnas 31
El accuracy en train es de: 0.9396835443037975
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>/home/joaquin/anaconda3/lib/python3.7/site-packages/ipykernel_launcher.py:8: SettingWithCopyWarning: 
A value is trying to be set on a copy of a slice from a DataFrame.
Try using .loc[row_indexer,col_indexer] = value instead

See the caveats in the documentation: http://pandas.pydata.org/pandas-docs/stable/indexing.html#indexing-view-versus-copy
  
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <p>Ahora bien, una vez entrenado tenemos un modelo que nos permitirá predecir para nuevos valores su etiqueta de clase. Una vez predicho compararemos la clase predicha con la clase real para obtener su <b>precisión (accuracy)</b> y mostrar la <b>matríz de confusión</b> que nos permitirá conocer los <b>Verdaderos Positivos, Verdaderos Negativos, Falsos Positivos y Falsos Negativos</b>.</p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[21]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#**********************************************************************************</span>
<span class="c1">#************************************Test******************************************</span>
<span class="c1">#**********************************************************************************</span>

<span class="c1"># Probamos la predicción del modelo de entrenamiento previamente creado</span>
<span class="n">y_pred</span> <span class="o">=</span> <span class="n">clf_cart</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x_test</span><span class="p">)</span>

<span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;El accuracy en test es:&quot;</span><span class="p">,</span> <span class="n">accuracy_score</span><span class="p">(</span><span class="n">y_test</span><span class="p">,</span><span class="n">y_pred</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">)</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">y_test</span><span class="p">,</span><span class="n">y_pred</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">cm</span><span class="p">,</span><span class="n">annot</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span><span class="n">fmt</span><span class="o">=</span><span class="s2">&quot;d&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>El accuracy en test es: 94.15204678362574
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p><b>Continuaremos con el conjunto de datos reducido a sólo 2 atributos con el método PCA.</b></p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">y_2</span> <span class="o">=</span> <span class="n">finalDf</span><span class="p">[</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">map</span><span class="p">({</span><span class="s2">&quot;M&quot;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s2">&quot;B&quot;</span><span class="p">:</span><span class="mi">1</span><span class="p">})</span>
<span class="n">x_2</span> <span class="o">=</span> <span class="n">finalDf</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;diagnosis&#39;</span><span class="p">],</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>

<span class="n">x_train_pca</span><span class="p">,</span> <span class="n">x_test_pca</span><span class="p">,</span> <span class="n">y_train_pca</span><span class="p">,</span> <span class="n">y_test_pca</span> <span class="o">=</span> <span class="n">train_test_split</span><span class="p">(</span><span class="n">x_2</span><span class="p">,</span> <span class="n">y_2</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.3</span><span class="p">,</span> <span class="n">random_state</span><span class="o">=</span><span class="mi">42</span><span class="p">)</span>


<span class="n">clf_cart_PCA</span> <span class="o">=</span> <span class="n">CART_decisionTreeClassifier_Train</span><span class="p">(</span><span class="n">x_train_pca</span><span class="p">,</span><span class="n">y_train_pca</span><span class="p">,</span> <span class="n">x_test_pca</span><span class="p">,</span> <span class="n">y_test_pca</span><span class="p">)</span>

<span class="n">y_pred_pca</span> <span class="o">=</span> <span class="n">clf_cart_PCA</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x_test_pca</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">y_pred_pca</span><span class="o">.</span><span class="n">shape</span><span class="p">)</span>

<span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;El accuracy en test es:&quot;</span><span class="p">,</span> <span class="n">accuracy_score</span><span class="p">(</span><span class="n">y_test_pca</span><span class="p">,</span><span class="n">y_pred_pca</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">)</span>

<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">y_test_pca</span><span class="p">,</span><span class="n">y_pred_pca</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">cm</span><span class="p">,</span><span class="n">annot</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span><span class="n">fmt</span><span class="o">=</span><span class="s2">&quot;d&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Numero de filas:  398 y el numero de columnas 3
Numero de filas:  398 y el numero de columnas 3
El accuracy en train es de: 0.9296518987341772
(171,)
El accuracy en test es: 95.90643274853801
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>/home/joaquin/anaconda3/lib/python3.7/site-packages/ipykernel_launcher.py:8: SettingWithCopyWarning: 
A value is trying to be set on a copy of a slice from a DataFrame.
Try using .loc[row_indexer,col_indexer] = value instead

See the caveats in the documentation: http://pandas.pydata.org/pandas-docs/stable/indexing.html#indexing-view-versus-copy
  
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
 <p><b>Visualizamos matríz de confusión.</b></p>
</div>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<div style="background-color: #EDF7FF; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
<strong>Análisis:</strong>
<br> - Con qué tipo de datos (originales o reducidos) has obtenido una precisión (accuracy) mayor?
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <p> El modelo que ha aprendido a partir de <b>los dos atributos proporcionados por el PCA</b> ha obtenido un accuracy de <b>95,9</b>, algo mayor que el modelo que aprendió a partir de <b>todos los atributos</b> ha obtenido un accuracy de <b>94,1</b>. </p>
</div>    
<br> - Si el usuario del modelo de predicción, un hospital por ejemplo, quisese usar el modelo con el menor número de tumores malignos erroneamente clasificados como benignos, cuál de los dos modelos tendría que usar? Porqué?

<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <p>Para este caso debería escoger <b>el modelo que entrenó con los atributos proporcionados por PCA</b> ya que el número de <b>falsos negativos</b> es 3 frente a los 7 que obtuvo el otro modelo.  </p>
    <p>Este modelo tiene pinta de ser un model conservador que intenta minimizar los <b>falsos positivos</b> (solo 3) frente a los <b>falsos positivos</b> (son 4) o lo que es lo mismo prefiere catalogar un tumor benigno como maligno que clasificar un tumor maligno como benigno.</p>
</div><p><br> - Y si el hospital quisese usar el modelo con el menor número de tumores benignos erroneamente clasificados como malignos, cuál de los dos modelos usaría? Porqué?</p>
<div style="background-color: #F5ECCE; border-color: #7C9DBF; border-left: 5px solid #7C9DBF; padding: 0.5em;">
    <p>En este caso le interesaría coger el modelo que aprendió a partir de todos los atributos ya que tiene 3 <b>falsos positivos</b> frente a los 4 <b>falsos positivos</b> que tiene el modelo del PCA.</p>

</div>  
</div>
</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>

