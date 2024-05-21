```css
@font-face {
    font-family: source-sans-pro;
    font-style: normal;
    font-weight: 400;
    src: url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n4.woff2) format("woff2"),url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n4.woff) format("woff")
}

@font-face {
    font-family: source-sans-pro;
    font-style: italic;
    font-weight: 400;
    src: url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-i4.woff2) format("woff2"),url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-i4.woff) format("woff")
}

@font-face {
    font-family: source-sans-pro;
    font-style: normal;
    font-weight: 600;
    src: url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n6.woff2) format("woff2"),url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n6.woff) format("woff")
}

@font-face {
    font-family: source-sans-pro;
    font-style: normal;
    font-weight: 700;
    src: url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n7.woff2) format("woff2"),url(//cdn.public.lu/fonts/source-sans-pro/source-sans-pro-n7.woff) format("woff")
}

/*! normalize.css v3.0.1 | MIT License | git.io/normalize */
html {
    -webkit-text-size-adjust: 100%;
    -moz-text-size-adjust: 100%;
    text-size-adjust: 100%;
    font-family: sans-serif
}

body {
    margin: 0
}

article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary {
    display: block
}

audio,canvas,progress,video {
    display: inline-block;
    vertical-align: baseline
}

audio:not([controls]) {
    display: none;
    height: 0
}

[hidden],template {
    display: none
}

a {
    background: transparent
}

a:active,a:hover {
    outline: 0
}

abbr[title] {
    border-bottom: 1px dotted
}

b,strong {
    font-weight: 700
}

dfn {
    font-style: italic
}

h1 {
    font-size: 2em;
    margin: .67em 0
}

mark {
    background: #FF0;
    color: #000
}

small {
    font-size: 80%
}

sub,sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline
}

sup {
    top: -.5em
}

sub {
    bottom: -.25em
}

img {
    border: 0
}

svg:not(:root) {
    overflow: hidden
}

figure {
    margin: 1em 40px
}

hr {
    box-sizing: content-box;
    height: 0
}

pre {
    overflow: auto
}

code,kbd,pre,samp {
    font-family: monospace;
    font-size: 1em
}

button,input,optgroup,select,textarea {
    color: inherit;
    font: inherit;
    margin: 0
}

button {
    overflow: visible
}

button,select {
    text-transform: none
}

button,html input[type=button],input[type=reset],input[type=submit] {
    -webkit-appearance: button;
    -moz-appearance: button;
    appearance: button;
    cursor: pointer
}

button[disabled],html input[disabled] {
    cursor: default
}

button::-moz-focus-inner,input::-moz-focus-inner {
    border: 0;
    padding: 0
}

input {
    line-height: normal
}

input[type=number]::-webkit-inner-spin-button,input[type=number]::-webkit-outer-spin-button {
    height: auto
}

input[type=search] {
    -webkit-appearance: textfield;
    -moz-appearance: textfield;
    appearance: textfield;
    box-sizing: content-box
}

input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration {
    -webkit-appearance: none;
    appearance: none
}

fieldset {
    border: 1px solid #c0c0c0;
    margin: 0 2px;
    padding: .35em .625em .75em
}

legend {
    border: 0
}

textarea {
    overflow: auto
}

optgroup {
    font-weight: 700
}

table {
    border-spacing: 0
}

td,th {
    padding: 0
}

.root-container {
    overflow-x: hidden
}

.block {
    display: block
}

.semi-bold {
    font-weight: 600
}

.bold {
    font-weight: 700
}

.at {
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px,1px,1px,1px);
    height: 1px;
    overflow: hidden;
    position: absolute!important;
    width: 1px
}

.is-hidden {
    display: none
}

a {
    color: #1065cb;
    text-decoration: none
}

a:active,a:visited {
    color: #1A0DAB;
    text-decoration: underline
}

a:focus,a:hover {
    color: #0f275b;
    text-decoration: underline
}

a:focus {
    outline: 1px dotted currentColor
}

.btn,button,input[type=submit] {
    background: #274891;
    border: 1px solid #274891;
    border-radius: 5px;
    box-sizing: border-box;
    color: #FFFFFF;
    display: inline-block;
    font-size: 1rem;
    font-weight: 600;
    line-height: 1.437;
    padding: .625rem 2.5rem;
    position: relative;
    text-align: center;
    text-decoration: none;
    width: auto
}

.btn:visited,button:visited,input[type=submit]:visited {
    background: #274891;
    border-color: #274891;
    color: #FFFFFF;
    text-decoration: none
}

.btn:hover,button:hover,input[type=submit]:hover {
    background: #0f275b;
    border-color: #0f275b;
    color: #FFFFFF;
    text-decoration: none
}

.btn:focus,button:focus,input[type=submit]:focus {
    background: #0f275b;
    border-color: #0f275b;
    color: #FFFFFF;
    outline: 1px dotted #0f275b
}

.btn:active,button:active,input[type=submit]:active {
    background: #0f275b;
    border-color: #0f275b;
    color: #FFFFFF;
    text-decoration: none
}

.btn[disabled],.btn[disabled]:focus,.btn[disabled]:hover,button[disabled],button[disabled]:focus,button[disabled]:hover,input[type=submit][disabled],input[type=submit][disabled]:focus,input[type=submit][disabled]:hover {
    background: #d1d1d1;
    border-color: #d1d1d1;
    color: #686868;
    outline: none
}

.btn .cmp-button__text,button .cmp-button__text,input[type=submit] .cmp-button__text {
    vertical-align: middle
}

.btn .cmp-button__icon,button .cmp-button__icon,input[type=submit] .cmp-button__icon {
    line-height: 1;
    margin-right: .625rem
}

.btn .cmp-button__icon img,.btn .cmp-button__icon svg,button .cmp-button__icon img,button .cmp-button__icon svg,input[type=submit] .cmp-button__icon img,input[type=submit] .cmp-button__icon svg {
    vertical-align: middle
}

.btn .cmp-button__text+.cmp-button__icon,button .cmp-button__text+.cmp-button__icon,input[type=submit] .cmp-button__text+.cmp-button__icon {
    margin: 0 0 0 .625rem
}

.btn-bright,.btn-bright:visited {
    background: #f9f9f9;
    border-color: #274891;
    color: #274891
}

.btn-bright:visited {
    text-decoration: none
}

.btn-bright:active,.btn-bright:focus,.btn-bright:hover {
    background: #274891;
    border-color: #274891;
    color: #FFFFFF;
    text-decoration: none
}

.btn-bright[disabled],.btn-bright[disabled]:focus,.btn-bright[disabled]:hover {
    background: #d1d1d1;
    border-color: #686868;
    color: #686868;
    outline: none
}

.btn-link {
    font-weight: 400
}

.btn-link,.btn-link:visited {
    background: transparent;
    border-color: transparent;
    color: #1065cb;
    text-decoration: none
}

.btn-link:focus,.btn-link:hover {
    background: transparent;
    border-color: transparent;
    color: #0f275b;
    text-decoration: underline
}

.btn-link:focus {
    text-decoration: none
}

.btn-link:active {
    background: transparent;
    border-color: transparent;
    color: #1A0DAB;
    text-decoration: none
}

.btn-link[disabled],.btn-link[disabled]:focus,.btn-link[disabled]:hover {
    background: transparent;
    border-color: transparent;
    color: #7F7F7F;
    outline: none
}

.btn-secondary {
    background: #274891;
    border: 1px solid #274891;
    border-radius: 3.125rem;
    box-shadow: 0 5px 6px 0 rgba(0,0,0,.16);
    color: #FFFFFF;
    padding: .46875rem 1.25rem
}

.btn-secondary:visited {
    background: #274891;
    border-color: #274891;
    color: #FFFFFF;
    text-decoration: none
}

.btn-secondary:hover {
    background: #0f275b;
    border-color: #0f275b;
    color: #FFFFFF;
    text-decoration: none
}

.btn-secondary:focus {
    outline: 1px dotted #274891
}

.btn-secondary:active,.btn-secondary:focus {
    background: #FFFFFF;
    border-color: #274891;
    color: #274891
}

.btn-secondary[disabled],.btn-secondary[disabled]:focus,.btn-secondary[disabled]:hover {
    background: #f9f9f9;
    border-color: #f9f9f9;
    color: #7C7C7C;
    outline: none
}

.btn-bright-secondary {
    background: #EFEFEF;
    border: 1px solid #efefef;
    border-radius: 3.125rem;
    color: #274891;
    font-size: .875rem;
    padding: .1875rem 1.25rem
}

.btn-bright-secondary:visited {
    background: #EFEFEF;
    border-color: #EFEFEF;
    color: #274891;
    text-decoration: none
}

.btn-bright-secondary:hover {
    background: #dbdbdb;
    border-color: #274891;
    color: #0f275b;
    text-decoration: none
}

.btn-bright-secondary:focus {
    background: #dbdbdb;
    border-color: #dbdbdb;
    color: #0f275b;
    text-decoration: none
}

.btn-bright-secondary:active {
    background: #FFFFFF;
    border-color: #274891;
    color: #0f275b
}

.btn-bright-secondary[disabled],.btn-bright-secondary[disabled]:focus,.btn-bright-secondary[disabled]:hover {
    background: #f9f9f9;
    border-color: #f9f9f9;
    color: #7C7C7C;
    outline: none
}

.btn-insert-row {
    background: #BED6F6;
    border-color: #BED6F6;
    border-radius: 2.8125rem;
    color: #0f275b;
    font-size: .875rem;
    font-weight: 600;
    padding: .3125rem .625rem .3125rem 2.1875rem;
    position: relative
}

.btn-insert-row:focus,.btn-insert-row:hover {
    background: #dbdbdb;
    border-color: #274891;
    color: #274891
}

.btn-insert-row:before {
    background: url(fb069fc1ad2d0f2ad065.svg) no-repeat 50% transparent;
    content: "";
    display: inline-block;
    height: 1rem;
    left: .625rem;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 1rem
}

fieldset {
    border: none;
    margin: .9375rem 0 3.75rem;
    padding: 0
}

fieldset .form-group:last-child .form-field {
    margin-bottom: 0
}

legend {
    color: #000;
    font-size: 1.25rem;
    line-height: 1.3333;
    margin: 0 0 .9375rem;
    padding: 0;
    width: 100%
}

label,legend {
    display: block;
    font-weight: 600
}

label {
    font-size: 1rem;
    max-width: 600px
}

textarea {
    min-height: 9.375rem;
    resize: vertical
}

input,select,textarea {
    background: #FFF;
    border: 1px solid #8b8b8b;
    border-radius: .3125rem;
    box-sizing: border-box;
    line-height: 1.5625;
    max-width: 600px;
    min-width: 3.125rem;
    padding: .5625rem .5rem;
    width: 100%
}

input::-moz-placeholder,select::-moz-placeholder,textarea::-moz-placeholder {
    color: #000000;
    opacity: 1
}

input:-ms-input-placeholder,select:-ms-input-placeholder,textarea:-ms-input-placeholder {
    color: #000000;
    opacity: 1
}

input::placeholder,select::placeholder,textarea::placeholder {
    color: #000000;
    opacity: 1
}

input:hover,select:hover,textarea:hover {
    background: #e5f4fe;
    border-color: #6e9caa
}

input:focus,select:focus,textarea:focus {
    background: #e5f4fe;
    border-color: #274891;
    outline: 1px dotted #274891
}

input[disabled=disabled],input[disabled=disabled]:focus,input[disabled=disabled]:hover,select[disabled=disabled],select[disabled=disabled]:focus,select[disabled=disabled]:hover,textarea[disabled=disabled],textarea[disabled=disabled]:focus,textarea[disabled=disabled]:hover {
    background: #f9f9f9;
    border-color: #8b8b8b
}

input[disabled=disabled]::-moz-placeholder,input[disabled=disabled]:focus::-moz-placeholder,input[disabled=disabled]:hover::-moz-placeholder,select[disabled=disabled]::-moz-placeholder,select[disabled=disabled]:focus::-moz-placeholder,select[disabled=disabled]:hover::-moz-placeholder,textarea[disabled=disabled]::-moz-placeholder,textarea[disabled=disabled]:focus::-moz-placeholder,textarea[disabled=disabled]:hover::-moz-placeholder {
    opacity: .5
}

input[disabled=disabled]:-ms-input-placeholder,input[disabled=disabled]:focus:-ms-input-placeholder,input[disabled=disabled]:hover:-ms-input-placeholder,select[disabled=disabled]:-ms-input-placeholder,select[disabled=disabled]:focus:-ms-input-placeholder,select[disabled=disabled]:hover:-ms-input-placeholder,textarea[disabled=disabled]:-ms-input-placeholder,textarea[disabled=disabled]:focus:-ms-input-placeholder,textarea[disabled=disabled]:hover:-ms-input-placeholder {
    opacity: .5
}

input[disabled=disabled]::placeholder,input[disabled=disabled]:focus::placeholder,input[disabled=disabled]:hover::placeholder,select[disabled=disabled]::placeholder,select[disabled=disabled]:focus::placeholder,select[disabled=disabled]:hover::placeholder,textarea[disabled=disabled]::placeholder,textarea[disabled=disabled]:focus::placeholder,textarea[disabled=disabled]:hover::placeholder {
    opacity: .5
}

input[type=date] {
    background-image: url(6d7a7f002751cf456852.svg),linear-gradient(90deg,transparent 0,transparent 50px,#8b8b8b 0,transparent 51px,transparent);
    padding-left: 3.75rem
}

input[type=date],input[type=date]:hover {
    background-position: .9375rem,0 0;
    background-repeat: no-repeat
}

input[type=date]:hover {
    background-image: url(6d7a7f002751cf456852.svg),linear-gradient(90deg,transparent 0,transparent 50px,#6e9caa 0,transparent 51px,transparent)
}

input[type=date]:focus {
    background-image: url(6d7a7f002751cf456852.svg),linear-gradient(90deg,transparent 0,transparent 50px,#274891 0,transparent 51px,transparent);
    background-position: .9375rem,0 0;
    background-repeat: no-repeat
}

input[type=date][disabled=disabled],input[type=date][disabled=disabled]:focus,input[type=date][disabled=disabled]:hover {
    background-image: url(6d7a7f002751cf456852.svg),linear-gradient(90deg,transparent 0,transparent 50px,#8b8b8b 0,transparent 51px,transparent);
    background-position: .9375rem,0 0;
    background-repeat: no-repeat
}

select {
    padding: .78125rem .5rem
}

select[disabled] {
    background: #F9F9F9;
    border-color: #8B8B8B;
    color: #7C7C7C
}

select option {
    background: #FFF
}

select[size] {
    padding: 0
}

select[size]:focus,select[size]:hover {
    background: #FFF
}

select[size]:focus option:checked {
    color: #000!important
}

select[size] option {
    color: #000;
    padding: .78125rem .5rem
}

select[size] option:hover {
    background: url(a2ce3cd5ba073d884547.svg) no-repeat 100% #e5f4fe;
    border-color: #6e9caa
}

select[size] option:focus {
    background: #e5f4fe;
    border-color: #274891;
    color: #000;
    outline: 1px dotted #274891
}

select[size] option:checked {
    background: url(6d87d7038ea2a547c082.svg) no-repeat 100% #e5f4fe;
    border-color: #274891;
    color: #000
}

select[size] option:checked+option {
    border-top-color: #274891
}

select[size] option+option {
    border-top: 1px solid #8b8b8b;
    margin-top: -1px
}

.form-field--pills {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background: url(01f62ecb38bbdad5ab0e.svg) no-repeat 100% #E5F4FE;
    border-radius: .9375rem;
    color: #274891;
    font-size: 1rem;
    font-weight: 600;
    padding: 0 1.25rem 0 .9375rem;
    width: auto
}

.form-field--pills:focus,.form-field--pills:hover {
    background: url(01f62ecb38bbdad5ab0e.svg) no-repeat 100% #FFF
}

.form-field--pills[disabled],.form-field--pills[disabled]:focus,.form-field--pills[disabled]:hover {
    background: url(01f62ecb38bbdad5ab0e.svg) no-repeat 100% #F9F9F9;
    border-color: #8B8B8B;
    color: #7C7C7C
}

.form-field--pills option {
    background: #FFF;
    color: #212529;
    font-size: .875rem;
    font-weight: 400
}

.cmp-form-options {
    margin: 0 0 .9375rem
}

.cmp-form-options legend {
    display: block;
    font-size: 1rem;
    font-weight: 600;
    margin: 0;
    max-width: 600px
}

.cmp-form-options .cmp-form-options__field-label {
    font-weight: 400
}

.cmp-form-options .cmp-form-options__field-label span {
    margin-left: .625rem
}

.cmp-form-date {
    display: flex;
    flex-flow: row wrap;
    margin: 0 -.625rem;
    max-width: 620px
}

.cmp-form-date legend {
    display: block;
    flex: 0 0 100%;
    font-size: 1rem;
    font-weight: 600;
    margin: 0 .625rem;
    max-width: 600px
}

.cmp-form-date label {
    font-size: .875rem;
    font-weight: 400
}

.cmp-form-date input {
    -webkit-appearance: textfield;
    -moz-appearance: textfield;
    appearance: textfield
}

.cmp-form-date .form-group {
    flex: 1 1 0;
    padding: 0 .625rem
}

.cmp-form-group-number .cpfgn-row {
    display: flex;
    flex-flow: row nowrap
}

.cmp-form-group-number input {
    -webkit-appearance: textfield;
    -moz-appearance: textfield;
    appearance: textfield;
    border-radius: 0;
    margin: 0 -1px;
    max-width: 6rem;
    position: relative;
    text-align: center;
    width: auto;
    z-index: 1
}

.cmp-form-group-number .form-group-number-step-down,.cmp-form-group-number .form-group-number-step-up {
    border-color: #8b8b8b;
    line-height: 1;
    padding: .6875rem .75rem
}

.cmp-form-group-number .form-group-number-step-down svg,.cmp-form-group-number .form-group-number-step-up svg {
    height: 1.1875rem;
    width: 1.1875rem
}

.cmp-form-group-number .form-group-number-step-down:focus,.cmp-form-group-number .form-group-number-step-down:hover,.cmp-form-group-number .form-group-number-step-up:focus,.cmp-form-group-number .form-group-number-step-up:hover {
    background: #E5F4FE;
    border-color: #6E9CAA;
    color: #274891;
    position: relative;
    z-index: 2
}

.cmp-form-group-number .form-group-number-step-down {
    border-bottom-right-radius: 0;
    border-top-right-radius: 0
}

.cmp-form-group-number .form-group-number-step-up {
    border-bottom-left-radius: 0;
    border-top-left-radius: 0
}

input[type=checkbox],input[type=radio] {
    border: none;
    box-sizing: border-box;
    cursor: pointer;
    line-height: normal;
    min-width: auto;
    padding: 0;
    vertical-align: middle;
    width: auto
}

input[type=checkbox] {
    height: 1.25rem;
    width: 1.25rem
}

input[type=radio] {
    height: 1rem;
    width: 1rem
}

.field-error input,.field-error select,.field-error textarea {
    background-color: #ffe9e5;
    border-color: #b22d36;
    color: #460000
}

.field-error input::-moz-placeholder,.field-error select::-moz-placeholder,.field-error textarea::-moz-placeholder {
    color: #460000;
    opacity: 1
}

.field-error input:-ms-input-placeholder,.field-error select:-ms-input-placeholder,.field-error textarea:-ms-input-placeholder {
    color: #460000;
    opacity: 1
}

.field-error input::placeholder,.field-error select::placeholder,.field-error textarea::placeholder {
    color: #460000;
    opacity: 1
}

.field-error input[type=date] {
    background-image: url(6d7a7f002751cf456852.svg),linear-gradient(90deg,transparent 0,transparent 50px,#b22d36 0,transparent 51px,transparent);
    background-position: .9375rem,0 0;
    background-repeat: no-repeat
}

.form-field {
    margin-bottom: .9375rem
}

@namespace xlink "http://www.w3.org/1999/xlink";.iconset g,.iconset path {
    fill: inherit;
    stroke: inherit
}

.icon {
    fill: currentColor;
    height: 24px;
    width: 24px
}

.icon>use {
    stroke: none;
    fill: inherit
}

.btn .icon>use,a .icon>use,button .icon>use {
    fill: currentColor
}

.icon--small {
    height: 14px;
    width: 14px
}

.icon--large {
    height: 36px;
    width: 36px
}

img {
    max-width: 100%
}

ol,ul {
    line-height: 1.4;
    list-style-position: inside;
    list-style-type: disc;
    margin: .9375rem 0;
    padding-left: 0
}

ol li,ul li {
    padding-left: .9375rem;
    position: relative
}

ol ol,ol ul,ul ol,ul ul {
    margin: .46875rem
}

ol ol li:before,ol ul li:before,ul ol li:before,ul ul li:before {
    color: #274891
}

ul li {
    padding-left: 0
}

ul>li::marker {
    color: #274891
}

ol {
    counter-reset: section
}

ol li {
    list-style-type: none
}

ol>li:before {
    color: #274891;
    content: counter(section) ".";
    counter-increment: section;
    margin-right: -.625rem;
    position: absolute;
    right: 100%
}

dl {
    margin: .9375rem 0
}

dt {
    color: #000;
    display: block;
    font-weight: 600;
    text-transform: uppercase
}

dd+dt {
    margin-top: .9375rem
}

dd {
    margin-left: 0
}

.nude {
    list-style: none;
    margin: 0;
    padding: 0
}

.nude li {
    padding-left: 0
}

.nude>li:before {
    content: none;
    display: none
}

.table--container:focus-visible {
    outline: 1px dotted #000
}

.table-container {
    overflow-x: auto
}

table {
    border-collapse: collapse;
    box-sizing: border-box;
    font-size: .875rem;
    white-space: nowrap;
    width: 100%
}

table caption {
    color: #000;
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 300;
    margin: .9375rem 0;
    text-align: left
}

table td,table th {
    background: #f9f9f9;
    color: #000;
    -webkit-hyphens: none;
    -ms-hyphens: none;
    hyphens: none;
    padding: .46875rem .625rem;
    text-align: left;
    vertical-align: top
}

table tr+tr {
    border-top: 1px solid #efefef
}

table thead th {
    background-color: #d1d1d1;
    color: #000;
    font-size: 1.125rem;
    font-weight: 600
}

table thead th:first-child {
    border-top-left-radius: .625rem
}

table thead th:last-child {
    border-top-right-radius: .625rem
}

table thead th>.icon--small {
    height: 10px;
    margin-left: .3125rem;
    vertical-align: baseline;
    width: 10px
}

table tbody {
    background-color: #f3ffde
}

.table--striped tbody tr:nth-child(2n) td,.table--striped tbody tr:nth-child(2n) th {
    background-color: #FFFFFF
}

.table--hover tbody tr:hover td,.table--hover tbody tr:hover th {
    background: #f3ffde
}

.table--tufte tbody tr:nth-child(3n+1) {
    border-top: 1px dotted #d1d1d1
}

.table-insert-row td,.table-insert-row th {
    background: #F1F7FF
}

.table-footer-actions {
    align-items: center;
    background: #F9F9F9;
    border-top: 1px solid #dbdbdb;
    display: flex;
    flex-flow: row wrap;
    gap: 1.25rem;
    justify-content: flex-end;
    padding: .3125rem 1.25rem
}

.table-footer-actions.table-footer-actions--center {
    justify-content: center
}

.table-row-per-page {
    align-items: center;
    display: flex;
    flex-flow: row wrap;
    gap: 1.25rem
}

.table-row-per-page select {
    min-width: 0;
    padding: .46875rem .625rem;
    width: auto
}

.table-pagination {
    align-items: center;
    display: flex;
    flex-flow: row wrap
}

.table-pagination p {
    margin: 0 1.25rem
}

.table-pagination button {
    background: transparent;
    border-color: transparent;
    color: #000;
    padding: .46875rem .625rem
}

.table-pagination button svg {
    height: 16px;
    width: 16px
}

.table-pagination button:focus,.table-pagination button:hover {
    background: #dbdbdb;
    border-color: #dbdbdb
}

html {
    background: #EFEFEF;
    color: #000;
    -webkit-hyphens: auto;
    -ms-hyphens: auto;
    hyphens: auto;
    line-height: 1.5625
}

body,html {
    font-family: source-sans-pro,Calibri,Candara,Segoe,Segoe UI,Optima,Arial,sans-serif
}

body {
    font-size: 1rem;
    overflow-x: hidden
}

h1,h2,h3,h4,h5,h6 {
    font-family: source-sans-pro,Calibri,Candara,Segoe,Segoe UI,Optima,Arial,sans-serif;
    -webkit-hyphens: none;
    -ms-hyphens: none;
    hyphens: none
}

h1 {
    color: #000;
    font-size: 1.875rem;
    line-height: 1.3333;
    margin: 2em 0 1em
}

h1.green {
    color: #608100
}

h1.blue {
    color: #3670ab
}

h2 {
    color: #000;
    font-size: 1.625rem;
    line-height: 1.3846;
    margin: 1.875rem 0 .9375rem
}

h3 {
    line-height: 1.4761;
    margin: 1.875rem 0 .46875rem;
    text-transform: uppercase
}

h3,h4 {
    color: #000;
    font-size: 1.3125rem
}

h4 {
    line-height: 1.3809;
    margin: 1.25rem 0 .46875rem
}

h5 {
    font-size: 1.1875rem;
    line-height: 1.421
}

h5,h6 {
    color: #000;
    margin: 1.25rem 0 .46875rem
}

h6 {
    font-size: 1.125rem;
    line-height: 1.3888
}

p {
    margin: 0 0 .9375rem
}

pre {
    margin: .9375rem 0
}

address {
    color: #dbdbdb
}

.cmp-blockquote {
    margin: 1.875rem 0
}

.cmp-blockquote blockquote {
    display: inline-block;
    font-size: 1rem;
    font-style: italic;
    margin: 0;
    padding: 0 2.5rem;
    position: relative
}

.cmp-blockquote blockquote:after,.cmp-blockquote blockquote:before {
    color: #274891;
    display: block;
    font-family: pt-sans,serif;
    font-size: 3em;
    line-height: .2em;
    position: absolute
}

.cmp-blockquote blockquote:before {
    content: "“";
    left: 0;
    top: 0
}

.cmp-blockquote blockquote:after {
    bottom: 2rem;
    content: "„";
    right: 0
}

.cmp-blockquote>p {
    display: block;
    font-size: .9375rem;
    font-style: normal;
    margin-top: .9375rem;
    text-align: right
}

.cmp-blockquote cite {
    color: #000;
    font-size: 1rem;
    font-style: italic
}

sub {
    font-feature-settings: "subs";
    font-variant-position: sub
}

sup {
    font-feature-settings: "sups";
    font-variant-position: super
}

code,pre,samp {
    font-family: Consolas,Monaco,Andale Mono,monospace
}

hr {
    border: 1px solid #d1d1d1
}

.page-header {
    background: #FFF;
    margin: 0 -.625rem 1.875rem;
    padding-top: 3.75rem;
    position: relative
}

.page-header .page-logo {
    padding: 0 1.25rem .3125rem
}

.page-header .page-logo .image {
    margin: 0 auto;
    max-width: 1280px
}

.page-header .page-logo .image img {
    display: block
}

.page-header .page-title {
    background: #FAFAFA;
    border-top: 5px solid #608100;
    color: #060606;
    display: block;
    min-height: 1.5rem;
    padding: .9375rem 1.25rem
}

.page-header .page-title h1 {
    font-size: 1.125rem;
    font-weight: 600;
    margin: 0 auto;
    max-width: 1280px
}

.page-header .page-user {
    position: absolute;
    right: 1.25rem;
    text-align: right;
    top: 3.43125rem;
    z-index: 1
}

.page-header .page-user .dropdown {
    position: relative
}

.page-header .page-user .dropdown-toggle {
    background: transparent;
    border: none;
    border-radius: 1.875rem;
    font-weight: 400;
    line-height: 0;
    margin: 0;
    padding: 0;
    min-height: 30px
}

.page-header .page-user .dropdown-toggle:before {
    content: "";
    display: inline-block
}

.page-header .page-user .dropdown-toggle:before {
    border: solid #608100;
    border-width: 0 1px 1px 0;
    content: "";
    display: inline-block;
    margin-bottom: .3rem;
    margin-left: 1rem;
    padding: 3px;
    position: relative;
    transform: rotate(45deg);
    transition: .3s ease-in;
}

.page-header .page-user .dropdown-toggle span {
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px,1px,1px,1px);
    height: 1px;
    overflow: hidden;
    position: absolute!important;
    width: 1px
}

.page-header .page-user .dropdown-toggle:focus,.page-header .page-user .dropdown-toggle:hover {
    background: #608100
}

.page-header .page-user .dropdown-toggle:focus:after,.page-header .page-user .dropdown-toggle:hover:after {
    border-color: #ffffff;
    transform: rotate(225deg)
}

.page-header .page-user .dropdown-toggle[aria-expanded=true] {
    background: #608100
}

.page-header .page-user .dropdown-toggle[aria-expanded=true]:after {
    filter: invert(100%);
    transform: rotate(180deg)
}

.page-header .page-user .dropdown-toggle[aria-expanded=true] span {
    color: #FFFFFF
}

.page-header .page-user .dropdown-toggle[aria-expanded=true]+.dropdown-menu {
    display: block
}

.page-header .page-user .dropdown-toggle[aria-expanded=false]+.dropdown-menu {
    display: none
}

.page-header .page-user .dropdown-menu {
    background: #E4E4E4;
    border-radius: .625rem;
    font-size: .875rem;
    list-style-type: none;
    margin: .625rem 0 0;
    max-width: calc(100vw - 2.5rem);
    padding: .3125rem .625rem;
    position: absolute;
    right: 0;
    text-align: right;
    top: 100%;
    width: 18.75rem
}

.page-header .page-user .dropdown-menu li {
    padding: .3125rem 0
}

.page-header .page-user .dropdown-menu li:before {
    content: none
}

.page-header .page-user .dropdown-menu li+li {
    border-top: 1px solid #c9c9c9
}

.page-header .page-user .dropdown-menu .dropdown-header-item {
    margin: 0 -.625rem;
    padding: 0
}

.page-header .page-user .dropdown-menu .dropdown-header-item:first-child {
    margin-top: -.3125rem
}

.page-header .page-user .dropdown-menu .dropdown-header-item:first-child .dropdown-header {
    border-radius: .625rem .625rem 0 0
}

.page-header .page-user .dropdown-menu .dropdown-header {
    background: #707070;
    color: #FFF;
    font-size: .75rem;
    font-weight: 700;
    padding: .625rem .9375rem;
    text-transform: uppercase
}

.page-header .page-user .dropdown-menu .page-user-dropdown-name {
    display: block;
    font-weight: 700
}

.page-header .page-user .dropdown-menu .page-user-sign-out {
    background: #EFEFEF;
    border-radius: 1.25rem;
    color: #274891;
    display: inline-block;
    font-size: .875rem;
    font-weight: 600;
    margin: .3125rem 0;
    padding: .3125rem .625rem;
    text-decoration: none
}

.page-header .page-user .dropdown-menu .page-user-sign-out:after {
    background: url(https://mengstudien.public.lu/content/dam/cdn/ctie/icons/arrow-down.svg);
    content: "";
    display: inline-block;
    height: .875rem;
    margin-left: .625rem;
    vertical-align: middle;
    width: .75rem
}

.page-header .page-user .dropdown-menu .page-user-sign-out:focus,.page-header .page-user .dropdown-menu .page-user-sign-out:hover {
    background: #DBDBDB;
    text-decoration: none
}

.page-footer {
    background: #E4E4E4
}

.page-copyright {
    background: #FFF;
    box-sizing: border-box;
    display: block;
    margin: 0 auto;
    padding: .625rem 1.25rem;
    position: relative
}

.page-copyright .page-copyright img,.page-copyright a {
    position: relative;
    z-index: 1
}

.page-copyright a {
    display: inline-block
}

.page-copyright img {
    display: block
}

.page-copyright .page-copyright:before {
    background: #FFF;
    bottom: 0;
    content: "";
    display: block;
    left: -300rem;
    position: absolute;
    right: -300rem;
    top: 0;
    z-index: 0
}

.page-footer-content {
    box-sizing: border-box;
    margin: 0 auto;
    max-width: 1280px;
    padding: .9375rem 1.25rem
}

.page-footer-content .nav {
    list-style-type: none;
    margin: 0;
    padding: 0
}

.page-footer-content .nav li {
    padding: 0
}

.page-footer-content .nav li:before {
    display: none
}

.page-footer-content .nav--support {
    display: flex;
    flex-flow: column wrap
}

.page-footer-content .nav--support li {
    display: block
}

.page-footer-content .nav--support li+li {
    border-top: 1px solid #8b8b8b
}

.page-footer-content .nav--support li a {
    color: #555555;
    display: block;
    font-size: 1rem;
    font-weight: 400;
    padding: .9375rem 1.25rem;
    text-decoration: none
}

.page-footer-content .nav--support li a:focus,.page-footer-content .nav--support li a:hover {
    text-decoration: underline
}

@media (min-width: 45em) {
    .page-footer-content .nav--support {
        flex-flow:row wrap
    }

    .page-footer-content .nav--support li+li {
        border: none;
        padding-left: 1px;
        position: relative
    }

    .page-footer-content .nav--support li+li:before {
        background: #555555;
        border: none;
        bottom: .3125rem;
        content: "";
        display: block;
        height: auto;
        left: 0;
        position: absolute;
        top: .3125rem;
        transform: none;
        width: 1px
    }

    .page-footer-content .nav--support li a {
        padding: .3125rem 1.25rem
    }
}

@media (min-width: 61.5em) {
    .page-header .page-user .dropdown-toggle {
        color:#000
    }

    .page-header .page-user .dropdown-toggle:before {
        border: solid #608100;
        border-width: 0 1px 1px 0;
        content: "";
        display: inline-block;
        margin-bottom: .1rem;
        margin-left: 1rem;
        padding: 3px;
        position: relative;
        transform: rotate(45deg);
        transition: .3s ease-in;
    }

    .page-header .page-user .dropdown-toggle span {
        clip: auto;
        height: auto;
        margin-left: .625rem;
        overflow: visible;
        position: static!important;
        vertical-align: middle;
        width: auto
    }

    .page-header .page-user .dropdown-toggle:focus,.page-header .page-user .dropdown-toggle:hover {
        background: #608100;
        color: #FFFFFF
    }

    .page-header .page-user .dropdown-toggle:focus:before,.page-header .page-user .dropdown-toggle:hover:before {
        border-color: #ffffff;
        transform: rotate(225deg);
        margin-bottom: -0.1rem
    }

    .page-header .page-user .dropdown-toggle:focus:after,.page-header .page-user .dropdown-toggle:hover:after {
        filter: none;
        transform: none
    }

    .page-header .page-user .dropdown-toggle[aria-expanded=true] {
        background: #608100
    }

    .page-header .page-user .dropdown-toggle[aria-expanded=true]:before {
        filter: invert(100%);
        transform: rotate(180deg)
    }

    .page-header .page-user .dropdown-toggle[aria-expanded=true]:after {
        filter: none;
        transform: none
    }

    .page-header .page-user .dropdown-menu {
        margin-top: 1.25rem
    }

    .page-header .page-user .dropdown-menu li {
        padding: .46875rem 0
    }
}

@media (min-width: 61.5em) and (min-width:80em) {
    .page-header .page-header-content {
        display:flex;
        flex-flow: row wrap
    }

    .page-header .page-logo {
        margin-left: calc(50% - 640px)
    }

    .page-header .page-title {
        flex: 1 0 100%
    }

    .page-header .page-user {
        margin: -.3125rem calc(50% - 640px) 0 auto;
        position: static
    }
}

.cmp-breadcrumb {
    margin: .9375rem auto;
    max-width: 1280px
}

.cmp-breadcrumb__list {
    display: flex;
    flex-wrap: wrap;
    margin: 0;
    padding: 0 1rem
}

.cmp-breadcrumb__item {
    color: #1065cb;
    display: flex;
    flex-wrap: wrap;
    font-size: 1.4rem;
    line-height: 1.5;
    padding: 0;
    position: relative
}

.cmp-breadcrumb__item:before {
    background-image: url(https://cdn.public.lu/dam-assets/ctie/icons/chevron.svg);
    background-position: 50%;
    background-repeat: no-repeat;
    background-size: contain;
    content: "";
    height: 10px;
    left: 0;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 20px
}

.cmp-breadcrumb__item>a,.cmp-breadcrumb__item>span {
    color: inherit;
    padding-left: 2rem
}

.cmp-breadcrumb__item>a:visited,.cmp-breadcrumb__item>span:visited {
    color: inherit
}

.cmp-breadcrumb__item:first-child:before {
    display: none
}

.cmp-breadcrumb__item:first-child a {
    padding-left: 0
}

.cmp-breadcrumb__item:first-child a:focus use,.cmp-breadcrumb__item:first-child a:hover use {
    fill: #608100
}

.cmp-breadcrumb__item:first-child svg {
    display: block;
    height: 1.25em;
    width: 1.25em
}

.cmp-breadcrumb__item:first-child span {
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px,1px,1px,1px);
    height: 1px;
    overflow: hidden;
    position: absolute!important;
    width: 1px
}

#error-page {
    box-sizing: border-box;
    padding: 2.8125rem 1.25rem 7.5rem;
    position: relative
}

#error-page .error-page-app-mobile {
    background: #EFEFEF;
    margin: -.9375rem -1.25rem
}

#error-page .error-wrapper {
    margin: 0 auto;
    max-width: 380px
}

#error-page .title-wrapper {
    display: block
}

#error-page .title-wrapper h1 {
    font-size: 2.8125rem;
    margin: 0
}

#error-page .title-wrapper p {
    font-size: 1.5rem;
    font-weight: 600;
    margin: 0
}

#error-page img {
    margin: 3.75rem 0;
    max-width: 100%
}

#error-page button {
    bottom: 1.875rem;
    left: 50%;
    padding-left: 5rem;
    padding-right: 5rem;
    position: absolute;
    transform: translateX(-50%)
}

@media (min-width: 61.5em) {
    #error-page .error-wrapper {
        max-width:52.5rem
    }

    #error-page .title-wrapper {
        display: block
    }

    #error-page .title-wrapper h1 {
        font-size: 7.125rem
    }

    #error-page .title-wrapper p {
        font-size: 1.5rem
    }

    #error-page .content-wrapper {
        align-items: center;
        display: flex;
        flex-flow: row-reverse;
        justify-content: space-between
    }

    #error-page img {
        margin: .9375rem 0 .9375rem 3.125rem
    }

    #error-page button {
        bottom: 6.25rem
    }
}

.govbar {
    background: #FFF;
    border-bottom: 1px solid #cccaca;
    font-family: Helvetica,Arial,sans-serif;
    font-size: 12px;
    height: 46px;
    overflow: hidden;
    position: relative;
    width: 100%;
    z-index: 30000
}

.govbar:after {
    clear: both;
    content: "";
    display: table
}

.govbar img {
    border: 0;
    display: block;
    height: 40px;
    padding: 3px 8px
}

@media (min-width: 45em) {
    .govbar img {
        float:right
    }
}

.page-content {
    display: block;
    padding: .9375rem 0
}

.page-sidebar {
    margin-bottom: 1.875rem
}

.page-text+.page-secondary {
    margin-top: 1.875rem
}

@media (min-width: 61.5em) {
    .page-content {
        display:flex;
        flex-flow: row nowrap;
        max-width: 100%;
        min-width: 0
    }

    .page-sidebar {
        flex: 2;
        margin-bottom: 0;
        min-width: 0
    }

    .page-text {
        flex: 8;
        max-width: 100%;
        min-width: 0;
        padding-left: 0
    }

    .page-sidebar+.page-text {
        padding-left: 2.5rem
    }

    .page-secondary {
        flex: 2;
        min-width: 0
    }

    .page-text+.page-secondary {
        margin-top: 0;
        padding-left: 2.5rem
    }
}

details {
    margin-bottom: 1.875rem
}

details summary::-webkit-details-marker {
    display: none
}

details>* {
    display: none
}

details>summary,details[open]>* {
    display: block
}

details>summary {
    background: #FFF;
    border-radius: 3px;
    cursor: pointer;
    font-size: 1rem;
    font-weight: 600;
    padding: .9375rem 3.75rem .9375rem .9375rem;
    position: relative
}

details>summary:focus-visible,details>summary:hover {
    background: #D9D9D9
}

details>summary:focus {
    outline: 1px dotted
}

details>summary:after {
    background: url(535d9482cf3a45ded58c.svg) no-repeat 50% transparent;
    background-size: contain;
    content: "";
    display: block;
    height: 1rem;
    position: absolute;
    right: .9375rem;
    top: 50%;
    transform: translateY(-50%);
    width: 1rem
}

details>summary .h1,details>summary .h2,details>summary .h3,details>summary .h4,details>summary .h5,details>summary .h6,details>summary h1,details>summary h2,details>summary h3,details>summary h4,details>summary h5,details>summary h6 {
    margin-bottom: 0
}

details[open]>summary {
    background: #EFEFEF
}

details[open]>summary:after {
    background: url(131a538f14f6a2d79ce0.svg) no-repeat 50% transparent;
    background-size: contain
}

.cmp-accordion__panel {
    background: #FFF;
    border-radius: 3px;
    padding: .9375rem 1.25rem
}

.cmp-accordion--secondary>summary {
    background: transparent;
    border-bottom: 1px solid #c5c5c5;
    border-radius: 0;
    font-size: 1.125rem;
    font-weight: 600;
    margin-bottom: 1.875rem;
    padding: .9375rem 3.75rem .9375rem 0;
    position: relative
}

.cmp-accordion--secondary>summary:focus-visible,.cmp-accordion--secondary>summary:hover {
    background: transparent
}

.cmp-accordion--secondary>summary:after {
    height: 1rem;
    width: 1rem
}

.cmp-accordion--secondary .cmp-accordion__panel {
    background: transparent;
    border-radius: 0;
    padding: 0
}

.action-toolbar {
    background: #FAFAFA;
    margin: 1.875rem -1.25rem 0
}

.action-toolbar-content {
    margin: 0 auto;
    max-width: 1280px;
    padding: .9375rem 1.25rem
}

.action-toolbar-content>div {
    display: inline
}

.action-toolbar-content>div button {
    align-items: center;
    display: inline-flex;
    flex-flow: row nowrap;
    font-size: 1.125rem;
    margin: .625rem 1.25rem .625rem 0;
    padding: .3125rem 1.25rem
}

@media (min-width: 45em) {
    .tab-content .action-toolbar {
        margin:1.875rem -2.5rem -.9375rem
    }

    .tab-content .action-toolbar-content {
        padding: .625rem 2.5rem
    }
}

@media (min-width: 61.5em) {
    .action-toolbar {
        bottom:0;
        left: 0;
        margin: 0;
        position: fixed;
        right: 0;
        z-index: 10
    }

    .action-toolbar-content {
        display: flex;
        flex-flow: row wrap;
        justify-content: space-between;
        padding: .625rem 1.25rem
    }

    .action-toolbar-content>div {
        display: flex;
        flex-flow: row wrap;
        justify-content: flex-start
    }

    .action-toolbar-content .action-toolbar-right button {
        margin-right: 0
    }

    .action-toolbar-content .action-toolbar-right button+button {
        margin-left: 1.25rem
    }
}

.alert {
    background: #F5F5F5;
    border: 1px solid #dbdbdb;
    border-radius: .625rem;
    box-shadow: 0 3px 6px 0 rgba(0,0,0,.16);
    color: #000000;
    margin: .9375rem 0;
    padding: .9375rem 1.25rem
}

.alert :last-child {
    margin-bottom: 0
}

.alert--info {
    background: #F1F9FF;
    border-color: #BCD4E6;
    font-style: italic
}

.alert--success {
    background: #DFE9E0;
    border-color: #00A811;
    color: #0B3700
}

.alert--warning {
    background: #FEFCE7;
    border-color: #C97A00;
    color: #5A3804
}

.alert--error {
    background: #FFE9E5;
    border-color: #CB7076;
    color: #460000
}

.alert--definition {
    background: none;
    border: none;
    border-radius: 0;
    box-shadow: none;
    margin: 0;
    padding: 0
}

.alert--definition-item {
    align-items: stretch;
    background: #F5F5F5;
    border: 1px solid #bcd4e6;
    border-radius: .625rem;
    box-shadow: 0 3px 6px 0 rgba(0,0,0,.16);
    color: #000000;
    display: flex;
    flex-flow: row nowrap;
    margin: .9375rem 0;
    min-width: 0
}

.alert--definition-item:last-child {
    margin-bottom: .9375rem
}

.alert--definition-item dt {
    background: #F1F9FF;
    border-radius: 1rem 0 0 1rem;
    border-right: 1px solid #bcd4e6;
    max-width: 20%;
    text-transform: none
}

.alert--definition-item dd,.alert--definition-item dt {
    color: #000;
    flex: 1 1 auto;
    padding: .9375rem 1.25rem
}

.cff-field-length {
    float: right;
    font-size: .875rem;
    font-weight: 400;
    text-align: right
}

.progress {
    background: #8B8B8B;
    margin: 1.875rem 0;
    position: relative;
    width: 100%
}

.progress,.progress-bar {
    display: block;
    height: .25rem
}

.progress-bar {
    background: #0E2059;
    color: #0E2059;
    left: 0;
    position: absolute;
    top: 0;
    transition: width .2s linear
}

.progress-bar span {
    font-size: .875rem;
    position: absolute;
    right: 0;
    text-align: right;
    top: 100%
}

.progress-bar--start span {
    left: 0;
    right: auto
}

.progress-bar--complete {
    background: #608100;
    color: #4F6B00
}

.progress-bar--warning {
    background: #C97A00;
    color: #5A3804
}

.progress-bar--error {
    background: #B22D36;
    color: #460000
}

.switch-item {
    display: block
}

.switch-item .label,.switch-item label {
    display: inline-block;
    font-weight: 400;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    vertical-align: middle
}

.switch-item .label {
    margin-right: .625rem
}

.switch-item input[role=switch] {
    margin-right: -1.5rem;
    opacity: 0
}

.switch-item input[role=switch]~.state {
    display: inline-block;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    vertical-align: middle
}

.switch-item input[role=switch]~.state>.container {
    background: #E7E7E7;
    border: 1px solid #7d7d7d;
    border-radius: 1.25rem;
    cursor: pointer;
    display: inline-block;
    height: 1.9375rem;
    position: relative;
    top: .125rem;
    transition: background .2s ease-in-out;
    width: 3.18rem
}

.switch-item input[role=switch]~.state>.container>.position {
    background: #FFF;
    border: 1px solid #939393;
    border-radius: 2rem;
    box-shadow: 0 0 1px 0 rgba(0,0,0,.78);
    display: inline-block;
    height: 1.6875rem;
    left: .125rem;
    position: relative;
    top: .0625rem;
    transition: left .2s ease-in-out;
    width: 1.6875rem
}

.switch-item input[role=switch]:checked~.state>.container {
    background: #274891;
    border-color: #274891
}

.switch-item input[role=switch]:checked~.state>.container>.position {
    left: 1.25rem
}

.switch-item input[role=switch]:focus~.state>.container {
    outline: 1px dotted currentColor;
    outline-offset: 2px
}

.switch-item label:hover input[role=switch]:not(:checked)~.state>.container {
    background: #707070
}

.switch-item input[role=switch][disabled]~.state>.container,.switch-item label:hover input[role=switch][disabled]~.state>.container {
    background: #E8E8E8;
    border-color: #B8B8B8;
    cursor: not-allowed
}

.switch-item .state+.label {
    margin-left: .625rem;
    margin-right: 0
}

.switch-item--mini input[role=switch]~.state>.container {
    height: 1.5rem;
    width: 2.375rem
}

.switch-item--mini input[role=switch]~.state>.container>.position {
    height: 1.25rem;
    width: 1.25rem
}

.switch-item--mini input[role=switch]:checked~.state>.container>.position {
    left: .875rem
}

.switch-item--background {
    background: #F9F9F9;
    border-radius: 1.25rem;
    display: inline-block;
    margin: .9375rem 0;
    padding: .3125rem 1.25rem
}

@media print {
    .anchor,.back,.breadcrumbs,.button,.govbar,.page-footer,.page-headernav,.page-localnav,.pagination,.search-meta,.skiplinks,nav {
        display: none!important
    }

    body {
        background: #FFF;
        color: #000;
        line-height: 14pt;
        margin: 0;
        padding: 0 28pt
    }

    h1,h2,h3,h4,h5,h6 {
        page-break-after: avoid
    }
}

/*# sourceMappingURL=myguichet.css.map*/

.cmp-progress-indicator {
    background: #FFF;
    border: 1px solid #8b8b8b;
    border-radius: .625rem;
    padding-bottom: .625rem
}

.cpi-title {
    display: block;
    font-size: 1.125rem;
    font-weight: 700;
    margin: 0;
    padding: .9375rem .625rem
}

.cpi-list,.cpi-list ul {
    list-style-type: none;
    margin: 0
}

.cpi-item {
    align-items: stretch;
    border-top: 1px solid #d1d1d1;
    display: flex;
    flex-flow: row wrap
}

.cpi-item button {
    align-items: flex-start;
    background: transparent;
    border: none;
    border-radius: 0;
    color: #000;
    display: flex;
    padding: .46875rem .625rem
}

.cpi-item button:focus svg,.cpi-item button:hover svg {
    transform: scale(1.1667)
}

.cpi-item button[aria-expanded=false]+ul {
    display: none
}

.cpi-item button[aria-expanded=true]+ul {
    display: block
}

.cpi-item button svg {
    height: 12px;
    margin-top: 4px;
    width: 12px
}

.cpi-item .cpi-item>.cpi-item-text {
    padding-left: 1.25rem
}

.cpi-item .cpi-item>.cpi-item-text:before {
    background: #707070;
    border-radius: 5px;
    box-sizing: border-box;
    content: "";
    display: block;
    flex: 0 0 5px;
    height: 5px;
    margin-right: .625rem;
    margin-top: .46875rem;
    width: 5px
}

.cpi-item .cpi-item .cpi-item>.cpi-item-text {
    padding-left: 1.875rem
}

.cpi-item .cpi-item .cpi-item>.cpi-item-text:before {
    background: transparent;
    border: 1px solid #707070
}

.cpi-item .cpi-item .cpi-item .cpi-item>.cpi-item-text {
    font-size: .875rem;
    padding-left: 2.5rem
}

.cpi-item .cpi-item .cpi-item .cpi-item>.cpi-item-text:before {
    background: #707070;
    border: none;
    border-radius: 0;
    transform: rotate(-45deg)
}

.cpi-item .cpi-item .cpi-item .cpi-item .cpi-item>.cpi-item-text {
    font-size: .8125rem;
    padding-left: 3.125rem
}

.cpi-item .cpi-item .cpi-item .cpi-item .cpi-item>.cpi-item-text:before {
    flex: 0 0 4px;
    height: 4px;
    transform: rotate(0);
    width: 5px
}

.cpi-item ul {
    flex: 1 0 100%
}

.cpi-item-text {
    border-left: .25rem solid transparent;
    color: #000;
    display: flex;
    flex: 1 0 0;
    flex-flow: row nowrap;
    font-size: .9375rem;
    -webkit-hyphens: none;
    -ms-hyphens: none;
    hyphens: none;
    justify-content: flex-start;
    padding: .46875rem .625rem
}

.cpi-item-text[href]:visited {
    color: #000
}

.cpi-item-text[href]:focus,.cpi-item-text[href]:hover {
    text-decoration: underline
}

.cpi-list ul .cpi-item-text,.cpi-list ul .cpi-item-text>button {
    background: #fafafa
}

.cpi-item.cpi-item--completed>.cpi-item-text,.cpi-item.cpi-item--completed>button {
    background: #fbfff9
}

.cpi-item.cpi-item--error>.cpi-item-text,.cpi-item.cpi-item--error>button {
    background: #FFF6F6
}

.cpi-item--current>.cpi-item-text {
    font-weight: 700
}

.cpi-item--current>span.cpi-item-text {
    border-left-color: #707070
}

.cpi-status {
    margin-left: auto
}

.cpi-status.cpi-status--completed {
    color: #00A811
}

.cpi-status.cpi-status--error {
    color: #FE0000
}

.cpi-status .icon {
    height: 10px;
    margin-left: .625rem;
    width: 10px
}

/*# sourceMappingURL=progress-indicator.css.map*/

.mandatory-text{
  text-align:right;
  margin-right: 10px;
}

.page-text{
    max-width: 700px;
}

.page-logo img{
    max-width: 150px;
}

.page-logo .logo-title{
    display:none;
}

.user-icon{
    background-color: #608100;
    padding: 5px 6px;
    border-radius: 50%;
}

.user-icon svg{
    width: 16px;
    height: 16px;
    color: #FFFFFF;
    margin-bottom: -3px;
}

.dropdown-menu ul{
    list-style-type: none;
}

.skiplinks>a {
    border: 0;
    clip: rect(1px, 1px, 1px, 1px);
    background: #849891;
    color: #fff;
    font-size: 1em;
    font-weight: 700;
    height: 1px;
    line-height: 1.6;
    overflow: hidden;
    padding: 2rem 0;
    position: absolute;
    text-align: center;
    top: 0;
    width: 100%;
    z-index: 32768;
}

.skiplinks>a:focus {
    clip: auto;
    height: auto;
    left: 0;
    outline: 0;
    overflow: visible;
    position: absolute;
    width: 100%;
}
```