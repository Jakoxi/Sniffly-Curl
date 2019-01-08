# Sniffly-Curl
aha
/*
Theme Name: Button 2
Theme URI: https://wordpress.com/themes/button-2/
Description: A stylish, lighthearted theme for crafters, hobbyists, and creatives.
Version: 2.1.0
Author: Automattic
Author URI: http://automattic.com
License: GNU General Public License v2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Text Domain: button
*/

/*--------------------------------------------------------------
>>> TABLE OF CONTENTS:
----------------------------------------------------------------
# Normalize
# Typography
# Elements
# Forms
# Navigation
	## Links
	## Menus
# Accessibility
# Alignments
# Clearings
# Widgets
# Content
	## Posts and pages
	## Asides
	## Comments
# Infinite scroll
# Media
	## Captions
	## Galleries
--------------------------------------------------------------*/
/*--------------------------------------------------------------
# Normalize
--------------------------------------------------------------*/
html {
	font-family: Georgia, serif;

	-webkit-text-size-adjust: 100%;
		-ms-text-size-adjust: 100%;
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
	border-bottom: 0px dotted;
}

b,	
strong {
	font-weight: bold;
}

dfn {
	font-style: normal;
}

h1 {
	margin: .67em 0;
	font-size: 2em;
}

mark {
	color: #000;
	background: #ff0;
}

small {
	font-size: 80%;
}

sub,
sup {
	position: relative;
	font-size: 75%;
	line-height: 0;
	vertical-align: baseline;
}

sup {
	top: -.5em;
}

sub {
	bottom: -.25em;
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
	margin: 0;
	font: inherit;
	color: #ffdf00;
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
	cursor: pointer;

	-webkit-appearance: button;
}

button[disabled],
html input[disabled] {
	cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
	padding: 0;
	border: 0;
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
	box-sizing: content-box;
	-webkit-appearance: none;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
	-webkit-appearance: none;
}

fieldset {
	margin: 0 2px;
	padding: .35em .625em .75em;
	border: 1px solid #ffdf00;
}

legend {
	padding: 0;
	border: 0;
}

textarea {
	overflow: auto;
}

optgroup {
	font-weight: bold;
}

table {
	border-spacing: 0;
	border-collapse: collapse;
}

td,
th {
	padding: 0;
}

/*--------------------------------------------------------------
# Typography
--------------------------------------------------------------*/
body,
button,
input,
select,
textarea {
	font-family: Lato, Helvetica, sans-serif;
	font-size: 16px;
	font-size: 1rem;
	line-height: 1.6;
	color: black;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	clear: both;
	font-family: Lora, Garamond, serif;
	font-weight: normal;
	font-style: normal;
	line-height: 1.2;
}

h1 {
	font-size: 3.052em;
}

h2 {
	font-size: 2.441em;
}

h3 {
	font-size: 1.953em;
}

h4 {
	font-size: 1.563em;
}

h5 {
	font-size: 1.25em;
}

h6 {
	font-size: 1em;
}

p {
	margin-bottom: 1.5em;
}

dfn,
cite,
em,
i {
	font-style: normal;
}

blockquote {
	margin: 0 1.5em;
}

address {
	margin: 0 0 1.5em;
}

pre {
	overflow: auto;
	max-width: 100%;
	margin-bottom: 1.6em;
	padding: 1.6em;
	font-family: "Georgia, serif";
	font-size: 15px;
	font-size: .9375rem;
	line-height: 1.6;
	background: black;
}

code,
kbd,
tt,
var {
	font-family: Monaco, Consolas, "Andale Mono", "DejaVu Sans Mono", monospace;
	font-size: 15px;
	font-size: .9375rem;
}

abbr,
acronym {
	cursor: help;
	border-bottom: 1px dotted #ffdf00;
}

mark,
ins {
	text-decoration: none;
	background: black;
}

big {
	font-size: 125%;
}

/*--------------------------------------------------------------
# Elements
--------------------------------------------------------------*/
html {
	box-sizing: border-box;
}

*,
*:before,
*:after {
	/* Inherit box-sizing to make it easier to change the property for components that leverage other behavior; see http://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/ */
	box-sizing: inherit;
}

body {
	background: black;
	/* Fallback for when there is no custom background color defined. */
	background-size: 50px auto;
}

body.user-background {
	background-size: auto auto;
}

blockquote,
q {
	quotes: "" "";
	font-family: Lora, Garamond, serif;
	font-size: 1.25em;
	font-style: normal;
	color: black;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
	content: "";
}
blockquote blockquote,
q blockquote {
	font-size: inherit;
}

hr {
	height: 1px;
	margin-bottom: 1.5em;
	border: 0;
	background-color: black;
}

ul,
ol {
	margin: 0 0 1.5em 3em;
	padding-left: 0;
}

ul {
	list-style: disc;
}

ol {
	list-style: decimal;
}

li > ul,
li > ol {
	margin-bottom: 0;
	margin-left: .75em;
	padding-left: 0;
}

dt {
	font-weight: bold;
}

dd {
	margin: 0 1.5em 1.5em;
}

img {
	/* Make sure images are scaled correctly. */
	max-width: 100%;
	height: auto;
	/* Adhere to container width. */
}

table {
	width: 100%;
	margin: 0 0 1.5em;
}

td,
th {
	padding: 5px 3px;
	border-bottom: 1px solid #ffdf00;
}

th {
	border-bottom: 3px solid #ffdf00;
}

/*--------------------------------------------------------------
# Forms
--------------------------------------------------------------*/
.button,
.button:visited,
button,
input[type="button"],
input[type="reset"],
input[type="submit"],
#infinite-handle span button {
	margin-top: 5px;
	margin-left: 5px;
	padding: .75em 1em;
	transition: .3s;
	font-size: 14px;
	font-weight: bold;
	line-height: 1;
	text-decoration: none;
	text-transform: capitalize;
	color: #ffdf00;
	border: 1px solid;
	border-color: #ffdf00;
	outline: 5px solid black;
	background: black;
	box-shadow: none;
	text-shadow: none;
}
.button:hover,
button:hover,
input[type="button"]:hover,
input[type="reset"]:hover,
input[type="submit"]:hover,
#infinite-handle span button:hover {
	color: #ffdf00;
	outline: 5px solid #ffdf00;
	background: white0;
	box-shadow: none;
}
.button:active,
.button:focus,
button:active,
button:focus,
input[type="button"]:active,
input[type="button"]:focus,
input[type="reset"]:active,
input[type="reset"]:focus,
input[type="submit"]:active,
input[type="submit"]:focus,
#infinite-handle span button:active,
#infinite-handle span button:focus {
	color: #ffdf00;
	outline: 5px solid #ffdf00;
	background: #ffdf00;
	box-shadow: none;
}
button + button,
button + input[type="button"],
button + input[type="reset"],
button + input[type="submit"],
input[type="button"] + button,
input[type="button"] + input[type="button"],
input[type="button"] + input[type="reset"],
input[type="button"] + input[type="submit"],
input[type="reset"] + button,
input[type="reset"] + input[type="button"],
input[type="reset"] + input[type="reset"],
input[type="reset"] + input[type="submit"],
input[type="submit"] + button,
input[type="submit"] + input[type="button"],
input[type="submit"] + input[type="reset"],
input[type="submit"] + input[type="submit"],
#infinite-handle span button + button,
#infinite-handle span button + input[type="button"],
#infinite-handle span button + input[type="reset"],
#infinite-handle span button + input[type="submit"] {
	margin-left: .75em;
}

#infinite-handle span:hover button,
#infinite-handle span button:hover {
	margin-top: 5px;
	margin-left: 5px;
	padding: .75em 1em;
	transition: .3s;
	font-size: 14px;
	font-weight: bold;
	line-height: 1;
	text-transform: capitalize;
	color: #ffdf00;
	border: 1px solid;
	border-color: #ffdf00;
	outline: 5px solid #ffdf00;
	background: #ffdf00;
	box-shadow: none;
	box-shadow: none;
	text-shadow: none;
}

input[type="text"],
input[type="email"],
input[type="url"],
input[type="password"],
input[type="search"],
input[type="tel"],
input[type="number"],
textarea {
	display: inline-block;
	color: black;
	border: 1px solid black;
	border-radius: 3px;
	background: black;
}
input[type="text"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="password"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="number"]:focus,
textarea:focus {
	color: black;
	border-color: #ffdf00;
	outline: none;
}

input[type="text"],
input[type="email"],
input[type="url"],
input[type="password"],
input[type="search"],
input[type="tel"],
input[type="number"] {
	padding: .65em .75em;
}

textarea {
	width: 100%;
	padding-left: 3px;
}

/*--------------------------------------------------------------
# Navigation
--------------------------------------------------------------*/
/*--------------------------------------------------------------
## Links
--------------------------------------------------------------*/
a {
	color: 	#ffdf00;
}
a:visited {
	color: 	#ffdf00;
}
a:hover,
a:focus,
a:active {
	color: black;
}
a:focus {
	outline: thin dotted;
}
a:hover,
a:active {
	outline: 0;
}

/*--------------------------------------------------------------
## Menus
--------------------------------------------------------------*/
.main-navigation {
	display: block;
	clear: both;
	width: 100%;
	margin: 2.25em auto 4.5em;
	padding: .75em 0;
	font-size: 13px;
	font-weight: bold;
	letter-spacing: 1px;
	text-transform: capitalize;
}
.main-navigation ul {
	margin: 0;
	padding: 0;
	list-style: none;
}
.main-navigation li {
	list-style: none;
}
.main-navigation li li {
	padding-left: 1.5em;
}
.main-navigation li li li {
	padding-left: 2.25em;
}
.main-navigation li li li li {
	padding-left: 3em;
}
.main-navigation li li li li li {
	padding-left: 3.75em;
}
.main-navigation a {
	display: block;
	width: 100%;
	margin: .75em 0 0;
	padding: .75em 0 0;
	text-decoration: none;
	border-top: 1px solid black;
}
.main-navigation a:hover,
.main-navigation a:visited:hover {
	color: #ffdf00;
}
.main-navigation a:visited {
	color: black;
}

/* Small menu. */
.menu-toggle,
.main-navigation.toggled ul {
	display: block;
}

.menu-toggle {
	margin: 0 auto;
	font-size: 16px;
}

.menu-toggle svg {
	position: relative;
	top: -2px;
	width: 16px;
	height: 16px;
	margin-right: 3px;
	vertical-align: middle;
}

#menu-icon {
	fill: black;
}
.main-navigation ul {
	display: none;
}

@media screen and (min-width: 40.063em) {
	.menu-toggle {
	display: none;
	}

	.main-navigation {
	border-top: 1px solid #ffdf00;
	border-bottom: 1px solid #ffdf00;
	}

	.main-navigation ul {
	display: block;
	}
}
.comment-navigation,
.posts-navigation,
.post-navigation {
	padding: .75em 0;
	font-family: Lora, Garamond, serif;
	font-style: normal;
	border-top: 1px solid #ffdf00;
	border-bottom: 1px solid #ffdf00;
}
.site-main .comment-navigation,
.site-main
	.posts-navigation,
.site-main
	.post-navigation {
	overflow: hidden;
	margin: 0 0 3em;
}
.comment-navigation .nav-previous,
.posts-navigation .nav-previous,
.post-navigation .nav-previous {
	width: 100%;
	margin-bottom: .75em;
	padding-bottom: .75em;
	font-size: 1.25em;
	line-height: 1.3;
	border-bottom: 2px solid #ffdf00;
}
.comment-navigation .nav-next,
.posts-navigation .nav-next,
.post-navigation .nav-next {
	width: 100%;
	font-size: 1.25em;
	line-height: 1.3;
	text-align: right;
}
.comment-navigation .meta-nav,
.posts-navigation .meta-nav,
.post-navigation .meta-nav {
	display: block;
	clear: both;
	width: 100%;
	font-family: Lato, Helvetica, sans-serif;
	font-size: 13px;
	font-weight: bold;
	font-style: normal;
	letter-spacing: 1px;
	text-transform: capitalize;
	color: black;
}
.comment-navigation a,
.posts-navigation a,
.post-navigation a {
	transition: .3s;
	text-decoration: none;
}

.jetpack-social-navigation-svg .icon {
	width: .5em !important;
	height: .5em !important;
}

.jetpack-social-navigation {
	margin: 0 auto;
	padding: 0;
	text-align: center;
}

.jetpack-social-navigation ul {
	margin: 0 0 1.5em 0;
	padding: 0;
	list-style: none;
}

.jetpack-social-navigation ul li {
	display: inline-block;
	margin: 0 .03em;
	padding: 0;
	list-style: none;
	font-size: 48px;
}

.jetpack-social-navigation ul a {
	color: #ffdf00;
	font-size: 48px;
	line-height: .75;
	position: relative;
	display: inline-block;
	margin-bottom: .1875em;
	transition: .3s;
	text-decoration: none;
	border-radius: 50%;
	background: black;
}

.jetpack-social-navigation ul a:before {
	display: block;
	padding: .5em;
	transition: .3s;
	font-size: 24px;
	text-align: center;
	color: black;
}

.jetpack-social-navigation ul a:after {
	position: absolute;
	z-index: 1;
	top: 3px;
	left: 3px;
	display: block;
	width: 42px;
	height: 42px;
	content: "";
	border: 1px solid #ffdf00;
	border-radius: 50%;
}

.jetpack-social-navigation ul a:hover {
	transition: .3s;
	text-decoration: none;
	color: #ffdf00;
	background: #ffdf00;
}

.jetpack-social-navigation ul a:hover:before {
	color: #ffdf00;
}

/*--------------------------------------------------------------
# Accessibility
--------------------------------------------------------------*/
/* Text meant only for screen readers. */
.screen-reader-text {
	position: absolute !important;
	overflow: hidden;
	clip: rect(1px, 1px, 1px, 1px);
	width: 1px;
	height: 1px;
}
.screen-reader-text:hover,
.screen-reader-text:active,
.screen-reader-text:focus {
	z-index: 100000;
	top: 5px;
	left: 5px;
	display: block;
	clip: auto !important;
	width: auto;
	height: auto;
	padding: 15px 23px 14px;
	font-size: 14px;
	font-size: .875rem;
	font-weight: bold;
	line-height: normal;
	text-decoration: none;
	color: black;
	border-radius: 3px;
	background-color: black;
	box-shadow: 0 0 2px 2px rgba(0, 0, 0, .6);
	/* Above WP toolbar. */
}

/*--------------------------------------------------------------
# Alignments
--------------------------------------------------------------*/
.alignleft {
	display: inline;
	float: left;
	margin-top: .75em;
	margin-right: 1.5em;
	margin-bottom: .75em;
}

.alignright {
	display: inline;
	float: right;
	margin-top: .75em;
	margin-bottom: .75em;
	margin-left: 1.5em;
}

.aligncenter {
	display: block;
	margin-top: .75em;
	margin-right: auto;
	margin-bottom: .75em;
	margin-left: auto;
}

/*--------------------------------------------------------------
# Clearings
--------------------------------------------------------------*/
.clear:before,
.clear:after,
.entry-content:before,
.entry-content:after,
.comment-content:before,
.comment-content:after,
.site-header:before,
.site-header:after,
.site-content:before,
.site-content:after,
.site-footer:before,
.site-footer:after {
	display: table;
	content: "";
}

.clear:after,
.entry-content:after,
.comment-content:after,
.site-header:after,
.site-content:after,
.site-footer:after {
	clear: both;
}

/*--------------------------------------------------------------
# Widgets
--------------------------------------------------------------*/
.widget {
	margin: 0 0 3em;
	font-size: 14px;
	/* Make sure select elements fit in widgets. */
}
.widget select {
	max-width: 100%;
	margin-left: 1px;
}
.widget a {
	transition: .3s;
	text-decoration: none;
}
.widget ul {
	margin: 0;
	padding: 0;
	list-style: none;
}
.widget ul li {
	margin-top: .75em;
	padding-top: .75em;
	list-style: none;
	border-top: 1px solid black;
}
.widget ul li li {
	padding-left: 1.5em;
}
.widget ul li li li {
	padding-left: 3em;
}
.widget ul li li li li {
	padding-left: 4.5em;
}

.widget-title {
	width: 100%;
	font-size: 1.25em;
	font-style: normal;
}
.widget-title a {
	text-decoration: none;
	color: black;
}
.widget-title:before {
	position: relative;
	top: -2px;
	display: inline-block;
	float: left;
	width: 22px;
	height: 32px;
	margin-right: .45em;
	content: "";
	background: url(img/button.svg) no-repeat;
	background-position: 0 0;
	background-size: 84px 22px;
}

/* Search widget */
.widget_search .search-field {
	box-sizing: border-box;
	width: 100%;
	max-width: 100%;
}

.widget_search .search-submit {
	display: none;
}

td#next {
	text-align: right;
}

/* RSS */
.widget_rss cite {
	font-family: Lora, Garamond, serif;
}
.widget_rss .rss-date {
	display: block;
	clear: both;
	width: 100%;
	margin-bottom: .375em;
	color: black;
}
.widget_rss .rssSummary {
	margin-bottom: .375em;
}

/* Recent comments */
.widget_recent_comments td,
.widget_recent_comments td.recentcommentsavatarend,
.widget_recent_comments td.recentcommentsavatartop,
.widget_recent_comments td.recentcommentstexttop,
.widget_recent_comments td.recentcommentstextend {
	padding-top: .5em;
	padding-bottom: .5em;
	line-height: 1.5;
	vertical-align: top;
	border-top: 1px solid black !important;
}
.widget_recent_comments td.recentcommentsavatarend,
.widget_recent_comments td.recentcommentsavatartop {
	vertical-align: middle;
}

/* =Footer Widgets */
.footer-widgets {
	margin: 27px 0 0;
	padding: 27px 0 0;
	border-top: 1px solid black;
}
.footer-widgets .widget-area {
	width: 100%;
	margin: 0 auto;
}

/*--------------------------- -----------------------------------
# Structure
--------------------------------------------------------------*/
.site {
	position: relative;
	margin: 0 auto;
	padding: 1.75em;
	background-color: white;
}

.content-area {
	float: none;
	width: 100%;
	margin: 0;
}

.site-main {
	margin: 0;
}

.site-content .widget-area {
	float: none;
	overflow: hidden;
	width: 100%;
	margin-top: 3em;
	padding-top: 1.5em;
	border-top: 1px solid black;
}

.site-footer {
	clear: both;
	width: 100%;
	margin: 4.5em 0 0;
}

.site-header {
	text-align: center;
}

.custom-logo {
	width: auto;
	max-width: 100%;
	height: auto;
	max-height: 150px;
	margin: 0 0 .75em;
}

.header-image {
	display: block;
	margin: -1.5em auto 1.5em;
}

.site-title {
	margin: 0;
	font-family: Lora, Garamond, serif;
	font-size: 2.441em;
	font-weight: bold;
	font-style: normal;
	line-height: 1.2;
}
.site-title a,
.site-title a:visited {
	text-decoration: none;
	color: white;
}

.site-description {
	margin: .5em 0 .25em;
	font-family: Lora, Garamond, serif;
	font-size: 18px;
	font-style: normal;
	line-height: 1.2;
	color: black;
}

.hentry {
	position: relative;
	margin: 0 0 4.5em;
	padding: 0 0 3em;
	border-bottom: 1px solid #ffdf00;
}
.sticky {
	/* Required for WP.org */
}

.error404 .page-content .search-field {
	position: relative;
	top: 1px;
	margin-right: 5px;
}

.page-links {
	clear: both;
	margin: .75em 0;
}

.page-links span.active-link {
	display: inline-block;
	width: 35px;
	height: 35px;
	margin: 0 0 3px;
	padding: 3px;
	transition: .3s;
	font-weight: bold;
	line-height: 29px;
	text-align: center;
	color: white;
	border-radius: 35px;
	background-color: white;
}

.page-links a span.active-link {
	display: inline-block;
	width: 35px;
	height: 35px;
	margin: 0 0 3px;
	padding: 3px;
	line-height: 29px;
	text-align: center;
	color: white;
	border-radius: 35px;
	background-color: black;
}

.page-links a:hover span.active-link {
	transition: .3s;
	color: white;
	background-color: white;
}

.featured-image {
	position: relative;
	margin: 0 0 1.5em;
	line-height: 0;
	text-align: center;
}
.fancy-image {
	display: inline-block;
	position: relative;
	line-height: 1;
}
.fancy-image .alignright,
.fancy-image .alignleft,
.fancy-image .aligncenter {
	margin: 0;
}
.fancy-image img,
.featured-image img {
	max-width: 99.9%;
}
.fancy-image img {
	display: inline-block;
}
.fancy-image .shadow,
.featured-image .shadow {
	position: absolute;
	z-index: 0;
	top: 0;
	left: 0;
	display: inline-block;
	width: 100%;
	height: 100%;
	box-shadow: inset 0 0 85px 1px rgba(0, 0, 0, .1);
}
.fancy-image:before,
.fancy-image:after,
.featured-image:before,
.featured-image:after {
	position: absolute;
	z-index: 1;
	top: -1px;
	left: -1px;
	display: block;
	width: 45px;
	height: 45px;
	content: "";
	background-image: url(img/corner.svg);
	background-repeat: no-repeat;
	background-size: 45px;
}
.fancy-image:after,
.featured-image:after {
	right: -1px;
	left: auto;
	-webkit-transform: rotate(90deg);
		-ms-transform: rotate(90deg);
			transform: rotate(90deg);
}
.fancy-image > .corners:before,
.fancy-image > .corners:after,
.featured-image > .corners:before,
.featured-image > .corners:after {
	position: absolute;
	z-index: 1;
	bottom: -1px;
	left: -1px;
	display: block;
	width: 45px;
	height: 45px;
	content: "";
	-webkit-transform: rotate(-90deg);
		-ms-transform: rotate(-90deg);
			transform: rotate(-90deg);
	background-image: url(img/corner.svg);
	background-repeat: no-repeat;
	background-size: 45px;
}
.fancy-image > .corners:after,
.featured-image > .corners:after {
	right: -1px;
	left: auto;
	-webkit-transform: rotate(-180deg);
		-ms-transform: rotate(-180deg);
			transform: rotate(-180deg);
}

.entry-meta,
.entry-footer {
	margin-bottom: 0;
	font-size: 14px;
	text-align: center;
	color: black;
}
.entry-meta a,
.entry-meta a:visited,
.entry-footer a,
.entry-footer a:visited {
	transition: .3s;
	text-decoration: none;
	color: black;
}
.entry-meta a:hover,
.entry-meta a:visited:hover,
.entry-footer a:hover,
.entry-footer a:visited:hover {
	color: #ffdf00;
}

.entry-meta {
	margin-bottom: 1.5em;
}

.entry-meta > span {
	display: inline-block;
	margin: 0 .375em;
}
.entry-meta > span:after {
	margin-left: .75em;
	content: "\00B7";
}
.entry-meta > span:last-of-type:after {
	display: none;
}

.cat-links {
	display: block;
	margin: 0 0 .5em;
	font-size: 13px;
	font-weight: bold;
	text-align: center;
	letter-spacing: 1px;
	text-transform: capitalize;
	color: black;
}
.cat-links a,
.cat-links a:visited {
	margin: 0 .375em;
	transition: .3s;
	text-decoration: none;
}

.tags-links,
.widget_tag_cloud {
	display: block;
	clear: both;
	width: 100%;
	margin: 0;
}
.tags-links a,
.tags-links a:visited,
.widget_tag_cloud a,
.widget_tag_cloud a:visited {
	position: relative;
	display: inline-block;
	height: 24px;
	margin-right: 1.5em;
	margin-bottom: .75em;
	padding: 2px 1px 2px 5px;
	transition: .3s;
	font-size: 13px;
	font-weight: bold;
	text-decoration: none;
	letter-spacing: 1px;
	text-transform: capitalize;
	color: white;
	background-color: black;
}
.tags-links a:last-of-type,
.tags-links a:visited:last-of-type,
.widget_tag_cloud a:last-of-type,
.widget_tag_cloud a:visited:last-of-type {
	margin-right: 0;
}
.tags-links a:hover,
.tags-links a:visited:hover,
.widget_tag_cloud a:hover,
.widget_tag_cloud a:visited:hover {
	color: #ffdf00;
	background-color: white;
}
.tags-links a:hover:after,
.tags-links a:visited:hover:after,
.widget_tag_cloud a:hover:after,
.widget_tag_cloud a:visited:hover:after {
	border-left-color: white;
}
.tags-links a:hover:before,
.tags-links a:visited:hover:before,
.widget_tag_cloud a:hover:before,
.widget_tag_cloud a:visited:hover:before {
	border-top-color: white;
	border-bottom-color: white;
}
.tags-links a:before,
.tags-links a:visited:before,
.widget_tag_cloud a:before,
.widget_tag_cloud a:visited:before {
	position: absolute;
	top: 0;
	left: -8px;
	display: inline-block;
	margin: 0;
	content: "";
	transition: .3s;
	border-width: 12px;
	border-style: solid;
	border-top-color: black;
	border-right-width: 0;
	border-right-color: white;
	border-bottom-color: black;
	border-left-width: 8px;
	border-left-color: white;
}
.tags-links a:after,
.tags-links a:visited:after,
.widget_tag_cloud a:after,
.widget_tag_cloud a:visited:after {
	position: absolute;
	top: 0;
	right: -12px;
	display: inline-block;
	margin: 0;
	content: "";
	transition: .3s;
	border-width: 12px;
	border-style: solid;
	border-top-color: white;
	border-right-width: 0;
	border-right-color: white;
	border-bottom-color: white;
	border-left-color: black;
}

.widget_tag_cloud {
	margin-bottom: 3em;
}
.widget_tag_cloud a {
	font-size: 14px !important;
}

.entry-summary {
	position: relative;
}

a.more-link {
	position: absolute;
	z-index: 1;
	bottom: -32px;
	display: block;
	width: 100%;
	height: 124px;
	padding-top: 100px;
	transition: .3s;
	font-family: Lora, Garamond, serif;
	font-weight: bold;
	font-style: normal;
	text-align: center;
	text-decoration: none;
	color: white;
	box-shadow: inset 0 -80px 80px -5px rgba(255, 255, 255, .75);
}
a.more-link:hover {
	color: #ffdf00;
	box-shadow: inset 0 -80px 80px -50px rgba(255, 255, 255, .75);
}

.updated {
	display: none;
}

.published.updated {
	display: inline;
}

.entry-title {
	margin: 0 0 .5em;
	font-size: 1.563em;
	font-style: normal;
	text-align: center;
}
.entry-title a,
.entry-title a:visited {
	text-decoration: none;
	color: black;
}
.entry-title:after {
	display: block;
	width: 20%;
	height: 2px;
	margin: .5em auto;
	content: "";
	background-color: black;
}

.entry-content {
	margin: 0 0 1.5em;
}
.entry-content p:last-of-type {
	position: relative;
}
.entry-content a {
	word-wrap: break-word;
	word-break: break-word;
}

.entry-content .sharedaddy:not(#jp-post-flair),
.entry-summary .sharedaddy:not(#jp-post-flair) {
	display: none;
}

.entry-author {
	margin: 27px 0 0;
	padding: 27px 0;
	border-top: 1px solid #ffdf00;
}
.entry-author p:last-of-type {
	margin-bottom: 0;
}
.author-title {
	margin: 0 0 7px;
	font-size: 1.2em;
}
.author-link {
	display: inline-block;
	clear: both;
	font-style: normal;
}
.author-avatar {
	float: left;
	width: 80px;
	margin-right: 1.75em;
	border-radius: 50%;
}
.author-avatar img {
	position: relative;
	display: block;
	float: left;
	width: 80px;
	height: 80px;
	padding: 0px;
	border: 2px solid #ffdf00;
	border-radius: 50%;
}
.author-title {
	clear: none;
}
.author-heading,
.author-bio {
	margin-left: 108px;
}

.page-title {
	font-size: 1.563em;
}


.site-info {
	font-size: 13px;
	font-weight: bold;
	text-align: center;
	letter-spacing: 1px;
	text-transform: capitalize;
	color: black;
}
.site-info .sep {
	display: block;
	visibility: hidden;
	clear: both;
	width: 100%;
	height: 1px;
}
.site-info a,
.site-info a:visited {
	transition: .3s;
	text-decoration: none;
	color: black;
}
.site-info a:hover,
.site-info a:visited:hover {
	color: #ffdf00;
}

/* =Comments */
.comments-title small,
.comment-reply-title small {
	float: right;
}

.comment-list,
.comment-list .children {
	list-style: none;
}

.comment-list {
	margin: 0;
	padding: 0;
}
.comment-list .children {
	margin-left: 2.25em;
}

.comment-list > .comment:first-of-type {
	padding-top: 0;
	border-top: 0;
}

.comment {
	margin-top: 1.5em;
	padding-top: 1.5em;
	border-top: 1px solid black;
}
.comment .comment-content {
	margin-top: 1.5em;
}

.comment-meta {
	display: block;
	color: black
}
.comment-meta .comment-metadata {
	margin-left: 80px;
	font-size: 13px;
	font-weight: bold;
	letter-spacing: 1px;
	text-transform: uppercase;
}
.comment-meta .comment-metadata a,
.comment-meta .comment-metadata a:visited {
	transition: .3s;
}
.comment-meta .comment-metadata a:hover,
.comment-meta .comment-metadata a:visited:hover {
	color: white;
}
.comment-meta a,
.comment-meta a:visited {
	text-decoration: none;
	color: black
	
}
.comment-meta .comment-author .avatar {
	position: relative;
	display: block;
	float: left;
	width: 60px;
	height: 60px;
	padding: 3px;
	border: 1px solid black;
	border-radius: 50%;
}
.comment-meta .comment-author .fn {
	display: block;
	margin-left: 80px;
	font-family: Lora, Garamond, serif;
	font-size: 1.25em;
	font-weight: normal;
	font-style: normal;
	text-transform: none;
	color: black
}
.comment-meta .comment-author .fn a,
.comment-meta .comment-author .fn a:visited {
	color: black
}

.bypostauthor > .comment-body:first-of-type .comment-author .avatar {
	border-color: white;
}

.comments-area .edit-link:before {
	display: inline;
	margin: 0 .875em 0 .75em;
	content: "\00B7";
	color: black
}

.comments-title,
h3#reply-title {
	font-size: 1.563em;
}

div#respond {
	margin: 1.5em 0 0;
	padding: 1.5em 0 0;
	border-top: 1px solid black !important;
}

.comment div#respond {
	padding-top: 0;
	border-top: 0 none !important;
}

.comment-form label {
	display: inline-block;
	width: 109px;
}

.comment-form-author,
.comment-form-email,
.comment-form-url,
.comment-form-comment {
	position: relative;
	margin: 0 0 1.5em;
}
.comment-form-author label,
.comment-form-email label,
.comment-form-url label,
.comment-form-comment label {
	position: absolute;
	top: 4px;
	left: 0;
	padding: .65em .75em;
	font-size: 13px;
	font-weight: bold;
	letter-spacing: 1px;
	text-transform: uppercase;
}
.comment-form-author input,
.comment-form-author textarea,
.comment-form-email input,
.comment-form-email textarea,
.comment-form-url input,
.comment-form-url textarea,
.comment-form-comment input,
.comment-form-comment textarea {
	clear: both;
	width: 100%;
	padding-left: 6em;
}
.comment-form-author textarea,
.comment-form-email textarea,
.comment-form-url textarea,
.comment-form-comment textarea {
	padding: 2em .75em .375em;
}

.comment-respond {
	margin-top: 1.5em;
	padding-top: 1.5em;
	border-top: 1px solid black;
}

.comment-reply-link {
	transition: .3s;
}

.says {
	display: none;
}

.form-allowed-tags {
	color: black
}

.no-comments {
	font-style: normal;
	text-align: center;
}

.required {
	color: white;
}

/*--------------------------------------------------------------
# Infinite scroll
--------------------------------------------------------------*/
/* Globally hidden elements when Infinite Scroll is supported and in use. */
.infinite-scroll .posts-navigation,
.infinite-scroll.neverending .site-footer {
	/* Theme Footer (when set to scrolling) */
	display: none;
}

/* When Infinite Scroll has reached its end we need to re-display elements that were hidden (via .neverending) before. */
.infinity-end.neverending .site-footer {
	display: block;
}

#infinite-footer {
	z-index: 999;
}

#infinite-footer .container {
	position: relative;
	font-style: normal;
	color: black;
	border-top: 1px solid black;
}

#infinite-footer .container a {
	color: black
}

#infinite-footer .container a:hover {
	color: white;
}

#infinite-footer .blog-info a,
#infinite-footer .blog-credits {
	font-weight: bold;
	font-style: normal;
	text-transform: uppercase;
	color: black
}

.infinite-loader {
	clear: both;
	width: 28px;
	height: 43px;
	margin: 0 auto 14px;
	padding-top: 27px;
}

#infinite-handle {
	clear: both;
	width: 100%;
	margin: 0 auto;
	text-align: center;
}
#infinite-handle span {
	color: white;
	border: 0;
	border-radius: 0;
	background: white;
}

.jetpack-video-wrapper {
	margin-bottom: 1.5em;
}

.jetpack-slideshow.slideshow-black {
	border-color: black;
	background-color: black;
}

/*--------------------------------------------------------------
# Media
--------------------------------------------------------------*/
.page-content .wp-smiley,
.entry-content .wp-smiley,
.comment-content .wp-smiley {
	margin-top: 0;
	margin-bottom: 0;
	padding: 0;
	border: none;
}

/* Make sure embeds and iframes fit their containers. */
embed,
iframe,
object {
	max-width: 100%;
}

figure {
	margin: 0;
}

/*--------------------------------------------------------------
## Captions
--------------------------------------------------------------*/
.wp-caption {
	max-width: 100%;
	margin-bottom: 1.5em;
}
.wp-caption img[class*="wp-image-"] {
	display: block;
	margin-right: auto;
	margin-left: auto;
}
.wp-caption .wp-caption-text {
	margin: .8075em 0;
}

.wp-caption-text {
	font-family: Lora, Garamond, serif;
	font-style: normal;
	text-align: center;
}

/*--------------------------------------------------------------
## Galleries
--------------------------------------------------------------*/
.gallery {
	margin: 0 -2% 1.5em;
}

.gallery-item {
	display: inline-block;
	padding: 0 1% 0;
	width: 100%;
	text-align: center;
	vertical-align: top;
}
.gallery-columns-2 .gallery-item {
	max-width: 50%;
}
.gallery-columns-3 .gallery-item {
	max-width: 33.33%;
}
.gallery-columns-4 .gallery-item {
	max-width: 25%;
}
.gallery-columns-5 .gallery-item {
	max-width: 20%;
}
.gallery-columns-6 .gallery-item {
	max-width: 16.66%;
}
.gallery-columns-7 .gallery-item {
	max-width: 14.28%;
}
.gallery-columns-8 .gallery-item {
	max-width: 12.5%;
}
.gallery-columns-9 .gallery-item {
	max-width: 11.11%;
}

.gallery-caption {
	display: block;
}

/*--------------------------------------------------------------
# Media queries
--------------------------------------------------------------*/
@media only screen and (min-width: 40.063em) {
	.site {
		width: 80%;
		margin: 3em auto;
		padding: 3em 2em;
	}

	.site-title {
		font-size: 3.052em;
	}

	.custom-logo {
		max-width: 600px;
	}

	.entry-title {
		font-size: 1.953em;
	}

	.featured-image {
		overflow: hidden;
	}
	.featured-image .post-thumbnail {
		transition: .5s;
		transform: scale(1.025, 1.025);
	}
	.fancy-image:before,
	.fancy-image:after,
	.featured-image:before,
	.featured-image:after {
		width: 75px;
		height: 75px;
		background-size: 75px;
	}
	.fancy-image > .corners,
	.featured-image > .corners {
		overflow: hidden;
	}
	.fancy-image > .corners:before,
	.fancy-image > .corners:after,
	.featured-image > .corners:before,
	.featured-image > .corners:after {
		width: 75px;
		height: 75px;
		background-size: 75px;
	}
	.featured-image:hover .post-thumbnail {
		transform: scale(1, 1);
	}

	.comment-navigation .nav-previous,
	.posts-navigation .nav-previous,
	.post-navigation .nav-previous {
		float: left;
		width: 50%;
		margin: 0;
		padding: 0;
		border: 0;
	}
	.comment-navigation .nav-next,
	.posts-navigation .nav-next,
	.post-navigation .nav-next {
		float: right;
		width: 50%;
	}

	.main-navigation {
		padding: 0;
		text-align: center;
	}
	.main-navigation ul {
		list-style: none;
	}
	.main-navigation ul ul {
		position: absolute;
		z-index: 99999;
		top: 3em;
		left: -999em;
		float: left;
		text-align: left;
		background: white;
		box-shadow: 0 1px 3px rgba(0, 0, 0, .2);
	}
	.main-navigation ul ul ul {
		top: 0;
		left: -999em;
	}
	.main-navigation ul ul li {
		margin: 0;
		padding: 0;
		border-top: 0;
		border-bottom: 1px solid black;
	}
	.main-navigation ul ul li:hover > ul,
	.main-navigation ul ul li.focus > ul {
		left: 100%;
	}
	.main-navigation ul ul li:last-of-type {
		border: 0;
	}
	.main-navigation ul ul li a:after {
		display: none;
	}
	.main-navigation ul ul li.menu-item-has-children > a:before,
	.main-navigation ul ul li.page_item_has_children > a:before {
		top: .45em;
		right: .75em;
		-webkit-transform: rotate(0deg);
				transform: rotate(0deg);
	}
	.main-navigation ul ul a {
		width: 200px;
		padding: .75em 1em;
	}
	.main-navigation ul li:hover > ul,
	.main-navigation ul li.focus > ul {
		left: auto;
	}
	.main-navigation li {
		position: relative;
		display: inline-block;
		margin-top: 0;
		padding: 0 .5em;
		border-top: 0;
	}
	.main-navigation li a:after {
		display: inline;
		margin-left: 1em;
		content: "\00B7";
		color: black;
	}
	.main-navigation li:last-of-type a:after {
		display: none;
	}
	.main-navigation li.menu-item-has-children a:after,
	.main-navigation li.page_item_has_children a:after {
		padding-left: 1.3em;
	}
	.main-navigation li.menu-item-has-children:last-of-type a:after,
	.main-navigation li.page_item_has_children:last-of-type a:after {
		display: inline-block;
		padding-left: 1.6em;
		content: "";
	}
	.main-navigation li.menu-item-has-children > a:before,
	.main-navigation li.page_item_has_children > a:before {
		position: absolute;
		top: .65em;
		right: 1.3em;
		display: inline-block;
		content: "\203A";
		-webkit-transform: rotate(90deg);
				transform: rotate(90deg);
		font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
		font-family: inherit;
		font-size: 20px;
		font-weight: bold;
		font-style: normal;
		font-variant: normal;
		line-height: 16px;
		text-align: center;
		vertical-align: baseline;
		text-decoration: inherit;
		text-transform: none;

		-webkit-font-smoothing: antialiased;
		speak: none;
	}
	.main-navigation a {
		display: block;
		margin: 0;
		padding-top: .75em;
		padding-bottom: .75em;
		transition: .3s;
		text-decoration: none;
		color: black;
		border: 0;
	}
	.main-navigation a:hover,
	.main-navigation a:visited:hover {
		color: #ffdf00;
	}
	.main-navigation a:visited {
		color: black;
	}
	.main-navigation .current_page_item > a,
	.main-navigation .current-menu-item > a,
	.main-navigation .current_page_ancestor > a {
		color: #ffdf00;
	}
}
/* min-width 641px, medium screens */
@media only screen and (min-width: 64.063em) {
	.site {
		max-width: 1142px;
		padding: 3em;
	}

	.content-area {
		float: left;
		width: 90%;
		margin: 0 -25% 0 0;
	}

	.site-main {
		margin: 0 25% 0 0;
	}

	.site-content .widget-area {
		float: right;
		width: 25%;
		margin-top: 0;
		padding-top: 0;
		border-top: 0;
	}

	.no-sidebar .site-main,
	.page-template-full-width-page .site-main {
		margin: 0;
	}

	.no-sidebar .content-area,
	.page-template-full-width-page .content-area {
		float: none;
		width: 100%;
		margin: 0;
	}

	.site-info .sep {
		display: inline;
		visibility: visible;
		clear: none;
		width: auto;
		height: auto;
		margin: 0 .75em;
	}
	.footer-widgets .widget-area {
		float: left;
	}
	.footer-widgets .widget-area:nth-child(1):nth-last-child(2),
	.footer-widgets .widget-area:nth-child(2):nth-last-child(1) {
		width: 48%;
		margin-right: 4%;
	}
	.footer-widgets .widget-area:nth-child(1):nth-last-child(2):last-of-type,
	.footer-widgets .widget-area:nth-child(2):nth-last-child(1):last-of-type {
		margin-right: 0;
	}
	.footer-widgets .widget-area:nth-child(1):nth-last-child(3),
	.footer-widgets .widget-area:nth-child(2):nth-last-child(2),
	.footer-widgets .widget-area:nth-child(3):nth-last-child(1) {
		width: 30%;
		margin-right: 5%;
	}
	.footer-widgets .widget-area:nth-child(1):nth-last-child(3):last-of-type,
	.footer-widgets .widget-area:nth-child(2):nth-last-child(2):last-of-type,
	.footer-widgets .widget-area:nth-child(3):nth-last-child(1):last-of-type {
		margin-right: 0;
	}
}
/* min-width 1025px, large screens */
@media only screen and (min-width: 75em) {
	.site {
		padding: 3em 5em;
	}

	.no-sidebar .site {
		width: 58.35%;
	}
}
