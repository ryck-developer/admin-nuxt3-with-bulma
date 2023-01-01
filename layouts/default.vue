<template>
  <div>
    <div class="homepage">
      <!----><!---->
      <div>
        <div>
          <div>
            <nav role="navigation" aria-label="main navigation" class="navbar">
              <div class="navbar-brand">
                <a href="/" class="navbar-item"
                  ><img
                    src="https://bulma.io/images/bulma-logo.png"
                    width="112"
                    height="28"
                /></a>
                <a
                  role="button"
                  aria-label="menu"
                  aria-expanded="false"
                  data-target="navbarBasicExample"
                  class="navbar-burger"
                  ><span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span
                ></a>
              </div>
              <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                  <a class="navbar-item">
                    Em Alta <v-icon>mdi-fire-circle</v-icon>
                  </a>
                  <a class="navbar-item"> Modal </a>
                  <div class="navbar-item has-dropdown is-hoverable">
                    <a class="navbar-link"> Soluções </a>
                    <div class="navbar-dropdown">
                      <a class="navbar-item"> Estratégias de Vendas </a>
                      <a class="navbar-item"> Monetização de Conteúdo</a>
                      <a class="navbar-item"> Plataforma de Pagamentos</a>
                      <a class="navbar-item"> Otimização de Receitas</a>
                      <a class="navbar-item"> Marketing Digital</a>
                      <a class="navbar-item"> Gestão de Produtos Digitais</a>
                      <a class="navbar-item"> Gestão de Conteúdo</a>
                      <hr class="navbar-divider" />
                      <a class="navbar-item"> Vender Produto Digital </a>
                      <a class="navbar-item"> Produtor Digital </a>
                    </div>
                  </div>
                </div>
                <div class="navbar-end">
                  <div class="navbar-item">
                    <div class="buttons">
                      <a
                        class="btn btn-sm btn-outline-primary ml-4"
                        href="/signup"
                        ><strong>Sign up</strong></a
                      >
                      <a class="btn btn-sm btn-primary ml-4" href="/login">
                        Log in
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
    <Modal />
    <Nuxt />
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          Desenvolvido por<a href="https://www.instagram.com/luiz.henrique.dev/"
            >Luiz Henrique Chaves</a
          >.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700,800&display=swap');
body {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  font-size: 16px;
  line-height: 1.6;
  color: #333;
}

p,
.paragraph {
  font-weight: 400;
  color: #333;
  font-size: 16px;
  line-height: 26px;
  font-family: 'Montserrat', sans-serif;
  margin-bottom: 1rem;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: #222;
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  line-height: 1.2;
}

h1,
.h1 {
  font-size: 50px;
  font-weight: 800;
}
@media (max-width: 575px) {
  h1,
  .h1 {
    font-size: 36px;
    font-weight: 600;
  }
}

h2,
.h2 {
  font-size: 42px;
  font-weight: 800;
}
@media (max-width: 575px) {
  h2,
  .h2 {
    font-size: 32px;
    font-weight: 600;
  }
}

h3,
.h3 {
  font-size: 32px;
}
@media (max-width: 575px) {
  h3,
  .h3 {
    font-size: 28px;
  }
}

h4,
.h4 {
  font-size: 26px;
}

h5,
.h5 {
  font-size: 22px;
}

h6,
.h6 {
  font-size: 18px;
}

dt {
  font-weight: 700;
}

dd {
  margin-bottom: 0.5rem;
  margin-left: 0 !important;
}

/* Button style */
.btn {
  font-size: 16px;
  font-family: 'Montserrat', sans-serif;
  text-transform: capitalize;
  padding: 13px 30px;
  border-radius: 6px;
  border: 1px solid;
  position: relative;
  z-index: 1;
  transition: 0.2s ease;
  font-weight: 600;
  display: inline-block;
}
.btn:hover,
.btn:active,
.btn:focus {
  outline: 0;
  box-shadow: none !important;
}
.btn-sm {
  font-size: 14px;
  padding: 10px 25px;
}

.btn-primary {
  background: #ff0043;
  color: #fff;
  border-color: #ff0043;
}
.btn-primary:active,
.btn-primary:hover,
.btn-primary:focus,
.btn-primary.focus,
.btn-primary.active {
  color: #fff;
  background: #cc0036 !important;
  border-color: #cc0036 !important;
}

.btn-outline-primary {
  background: transparent;
  color: #ff0043;
  border-color: #ff0043;
}
.btn-outline-primary:active,
.btn-outline-primary:hover,
.btn-outline-primary:focus,
.btn-outline-primary.focus,
.btn-outline-primary.active {
  background: #cc0036 !important;
  border-color: #cc0036 !important;
  color: #fff;
}

.stretched-link::after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  pointer-events: auto;
  content: '';
  background-color: rgba(0, 0, 0, 0);
}

html {
  overflow-x: initial !important;
  overflow-y: initial !important;
}

body {
  background-color: #fff;
  overflow-x: hidden;
}

::-moz-selection {
  background: #ff3369;
  color: #fff;
}

::selection {
  background: #ff3369;
  color: #fff;
}

/* preloader */
.preloader {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #fff;
  z-index: 9999;
  display: flex;
  align-items: center;
  justify-content: center;
}

img {
  vertical-align: middle;
  border: 0;
  max-width: 100%;
  height: auto;
}

ul {
  list-style: none;
}

a {
  color: inherit;
}

a,
a:hover,
a:focus {
  text-decoration: none;
}

a,
button,
select {
  cursor: pointer;
  transition: 0.2s ease;
}
a:focus,
button:focus,
select:focus {
  outline: 0;
}

a:hover {
  color: #ff0043;
}

.slick-slide {
  outline: 0;
}

.section {
  padding-top: 80px;
  padding-bottom: 80px;
  padding-left: 0;
  padding-right: 0;
}
.section-sm {
  padding-top: 50px;
  padding-bottom: 50px;
}
.section-title {
  margin-bottom: 40px;
}

.bg-cover {
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}

.border-default {
  border-color: #e2e2e2 !important;
}

/* overlay */
.overlay {
  position: relative;
}
.overlay::before {
  position: absolute;
  content: '';
  height: 100%;
  width: 100%;
  top: 0;
  left: 0;
  background: #000;
  opacity: 0.5;
}

.outline-0 {
  outline: 0 !important;
}

.rounded,
.card-icon,
.card {
  border-radius: 12px !important;
}

.shadow,
.card,
.search-wrapper .input,
.navigation.nav-bg {
  box-shadow: 0px 15px 60px rgba(62, 62, 62, 0.102) !important;
}

.d-unset {
  display: unset !important;
}

.bg-primary {
  background: #ff0043 !important;
}

.text-primary {
  color: #ff0043 !important;
}

.text-light {
  color: #999 !important;
}

.mb-10 {
  margin-bottom: 10px !important;
}

.mb-20 {
  margin-bottom: 20px !important;
}

.mb-30 {
  margin-bottom: 30px !important;
}

.mb-40 {
  margin-bottom: 40px !important;
}

.mb-50 {
  margin-bottom: 50px !important;
}

.mb-60 {
  margin-bottom: 60px !important;
}

.mb-70 {
  margin-bottom: 70px !important;
}

.mb-80 {
  margin-bottom: 80px !important;
}

.mb-90 {
  margin-bottom: 90px !important;
}

.mb-100 {
  margin-bottom: 100px !important;
}

.zindex-1 {
  z-index: 1;
}

.overflow-hidden {
  overflow: hidden;
}

.has-text-weight-medium {
  font-weight: 500;
}

@media screen and (min-width: 1216px) {
  .container:not(.is-max-desktop) {
    max-width: 1140px;
  }
}
@media (max-width: 1023px) {
  .container {
    max-width: 765px;
  }
}
@media (max-width: 768px) {
  .container {
    max-width: 540px;
  }
}

.container,
.container-fluid {
  padding-left: 15px;
  padding-right: 15px;
}

.column {
  padding: 15px;
}

.columns {
  margin-left: -15px;
  margin-right: -15px;
  margin-top: -15px;
}

.columns:last-child {
  margin-bottom: -15px;
}

.list-inline {
  padding-left: 0;
  list-style: none;
}
.list-inline .list-inline-item {
  display: inline-block;
}
.list-inline .list-inline-item:not(:last-child) {
  margin-right: 0.5rem;
}

.w-100 {
  width: 100%;
}

.ml-auto {
  margin-left: auto;
}

.border-0 {
  border: 0;
}

.bg-white {
  background-color: #fff;
}

.border {
  border: 1px solid #dee2e6 !important;
}

.border-top {
  border-top: 1px solid #dee2e6 !important;
}

.border-right {
  border-right: 1px solid #dee2e6 !important;
}

.border-bottom {
  border-bottom: 1px solid #dee2e6 !important;
}

.border-left {
  border-left: 1px solid #dee2e6 !important;
}

.border-0 {
  border: 0 !important;
}

.border-top-0 {
  border-top: 0 !important;
}

.border-right-0 {
  border-right: 0 !important;
}

.border-bottom-0 {
  border-bottom: 0 !important;
}

.border-left-0 {
  border-left: 0 !important;
}

.border-secondary {
  border-color: #6c757d !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.border-white {
  border-color: #fff !important;
}

.border-muted {
  border-color: #404751 !important;
}

.navigation {
  transition: 0.2s ease;
  padding: 15px 0;
}
.navigation.nav-bg {
  background: #fff;
}
@media (max-width: 1023px) {
  .navigation .form-inline {
    width: 100%;
  }
  .navigation .form-inline input {
    width: 100%;
  }
}

.navbar-item {
  color: #222;
}
.navbar-item:focus,
.navbar-item:hover {
  background-color: transparent !important;
  color: #ff0043 !important;
}

@media (max-width: 1023px) {
  .navbar-brand .navbar-item {
    padding-left: 0;
  }
}

.navbar-brand {
  align-items: center;
}
.navbar-brand img {
  max-height: initial;
}

.navbar-start .navbar-item {
  padding-left: 20px;
  padding-right: 20px;
}

.is-sticky-top {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  z-index: 9997;
}

.navbar-burger {
  color: #000;
  height: 2.7rem;
  width: 2.7rem;
  border: 1px solid #ddd;
  background-color: #fff;
  border-radius: 2px;
  top: 5px;
}
.navbar-burger:hover {
  background-color: #fff;
}

@media (max-width: 1023px) {
  .navbar-menu {
    padding: 1.5rem 0;
    text-align: center;
  }
  .navbar-end {
    margin: 12px 0 2px;
  }
  .navbar-end .btn {
    margin-left: 5px !important;
    margin-right: 5px !important;
    margin-top: 5px;
  }
  .hide-on-desktop {
    display: none;
  }
  .show-on-desktop {
    display: block !important;
    margin-top: 20px;
  }
}
.search-wrapper {
  position: relative;
}
.search-wrapper .input {
  height: 46px;
  border: 0;
  outline: 0;
  padding-left: 17px;
}
.search-wrapper .input::-moz-placeholder {
  color: #999;
  font-size: 15px;
}
.search-wrapper .input::placeholder {
  color: #999;
  font-size: 15px;
}
.search-wrapper .input-lg {
  height: 70px;
}
.search-wrapper .input.active.focus-visible {
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.search-wrapper button {
  position: absolute;
  right: 5px;
  top: 50%;
  transform: translateY(-50%);
}
.search-wrapper button i {
  color: #ff0043;
}

body,
button,
input,
optgroup,
select,
textarea {
  font-family: 'Montserrat', sans-serif;
}

.card {
  transition: 0.2s ease;
  border: 0;
}
.card-lg .card-body {
  padding: 35px;
}
.card-icon {
  background: #ff0043;
  color: #fff;
  height: 55px;
  width: 60px;
  line-height: 55px;
  text-align: center;
  font-size: 27px;
  display: block;
  margin-top: 40px;
}
.card-text {
  margin-bottom: 0;
}
.card-title {
  font-weight: 700;
  margin-bottom: 0.75rem;
}
.card-body {
  padding: 25px;
}
.card:hover {
  box-shadow: 0px 15px 60px rgba(62, 62, 62, 0.2) !important;
}

.social-icons {
  margin-bottom: 0;
}
.social-icons a {
  display: block;
  height: 42px;
  width: 42px;
  line-height: 42px;
  text-align: center;
  color: #fff;
  background: #ff0043;
  border-radius: 6px;
}

.footer-menu {
  margin-bottom: 0;
}
.footer-menu a {
  display: block;
  padding: 10px;
  color: #333;
  transition: 0.2s ease;
}
.footer-menu a:hover {
  color: #ff0043;
}

/* sidenav */
.sidenav {
  border-right: 1px solid #e2e2e2;
  padding-right: 20px;
  padding-left: 30px;
}
.sidenav ul {
  padding-left: 10px;
}
.sidenav > li a {
  padding: 20px 0;
  color: #222;
  display: block;
  font-size: 18px;
  font-weight: 500;
}
.sidenav > li:not(:last-child) {
  border-bottom: 1px solid #e2e2e2;
}
.sidenav .sidelist ul {
  display: none;
}
.sidenav .parent > a {
  color: #ff0043 !important;
  position: relative;
  margin-left: 10px;
}
.sidenav .parent > a::before {
  position: absolute;
  content: '';
  left: -10px;
  top: 25%;
  height: 50%;
  width: 1px;
  background: #ff0043;
}
.sidenav .parent ul {
  display: block;
  margin-bottom: 10px;
}
.sidenav .parent ul a {
  padding: 5px 0;
  font-size: 14px;
  font-weight: 400;
  color: #222;
}
.sidenav .parent ul li.active > a {
  margin-left: 10px;
}
.sidenav .parent ul li.active > a::before {
  height: 5px;
  width: 5px;
  border-radius: 50%;
  display: block;
  top: 13px;
}

/* /sidenav */
.page-list {
  list-style-type: none;
}
.page-list a {
  display: none;
}
.page-list ul {
  padding: 0;
}
.page-list ul a {
  display: inline-block;
  padding: 7px 0;
  font-size: 20px;
  color: #222;
}

.pagination {
  margin-top: 50px;
  justify-content: space-between;
}
.pagination a {
  color: #ff0043;
  font-size: 18px;
  font-weight: 500;
}
.pagination i {
  line-height: 1.6;
}

.code-tabs {
  border: 1px solid #e2e2e2;
  overflow: hidden;
  margin-bottom: 20px;
}
.code-tabs .nav-tabs {
  margin-bottom: 0;
}
.code-tabs .nav-tabs .nav-item {
  padding-left: 0;
  border-right: 1px solid #e2e2e2;
}
.code-tabs .nav-tabs .nav-item .nav-link {
  text-decoration: none;
  font-weight: 500;
  border: 0;
}
.code-tabs .nav-tabs .nav-item::before {
  display: none;
}
.code-tabs .nav-tabs .nav-item.active {
  background: #ff0043;
}
.code-tabs .nav-tabs .nav-item.active .nav-link {
  color: #fff;
}
.code-tabs .tab-content {
  padding: 20px 15px;
}

pre {
  position: relative;
}
pre .copy-to-clipboard {
  background: #ff0043;
  color: #fff;
  cursor: pointer;
  padding: 4px 5px;
  line-height: 1;
  font-size: 12px;
  font-weight: 500;
  border-radius: 4px;
  position: absolute;
  right: 10px;
  top: 10px;
}

:not(pre) > code + span.copy-to-clipboard {
  display: none;
}

.autocomplete-suggestions {
  border: 0;
  border-radius: 0 0 6px 6px;
  box-shadow: 0px 50px 60px rgba(62, 62, 62, 0.102) !important;
  background: #fff;
}
.autocomplete-suggestions .autocomplete-suggestion {
  transition: 0.2s ease;
  padding: 10px;
  font-weight: 500;
}
.autocomplete-suggestions .autocomplete-suggestion.selected {
  background: #ff0043;
}

.search-item a {
  color: #222;
  display: block;
}
.search-item a:hover {
  color: #ff0043;
}
.search-item:not(:last-child) {
  border-bottom: 1px solid #e2e2e2;
}

.form-group label {
  font-size: 15px;
  font-weight: 500;
}
.form-group .input {
  height: 40px;
  background: transparent;
  border: 0;
  border-bottom: 1px solid #e2e2e2;
  border-radius: 0;
  padding: 10px 0;
  box-shadow: none;
}
.form-group .input::-moz-placeholder {
  font-size: 13px;
  color: #999;
}
.form-group .input::placeholder {
  font-size: 13px;
  color: #999;
}
.form-group .input:focus {
  outline: 0;
  border-color: #ff0043;
  box-shadow: none;
}
.form-group .custom-select {
  font-size: 13px;
  color: #999;
}
.form-group textarea.input {
  height: 100px;
}

.badge {
  margin-bottom: 20px;
  font-weight: 500;
  font-size: 15px;
  padding: 5px 10px;
}
.badge.added {
  background: #3778ff;
  color: #fff;
}
.badge.fixed {
  background: #f54773;
  color: #fff;
}
.badge.changed {
  background: #3aaa55;
  color: #fff;
}
.badge.depricated {
  background: #343434;
  color: #fff;
}
.badge.removed {
  background: #3bbfe4;
  color: #fff;
}
.badge.security {
  background: #f53535;
  color: #fff;
}
.badge.unreleased {
  background: #a037ff;
  color: #fff;
}

.collapse-wrapper {
  padding: 5px 15px;
}
.collapse-wrapper .collapse-head {
  text-decoration: none;
  color: #333;
  font-size: 18px;
  font-weight: 500;
  align-items: center;
}

:not(.highlight) pre {
  background: #fbfbfb;
}

.content h1,
.content h2,
.content h3,
.content h4,
.content h5,
.content h6 {
  font-weight: 500;
}
.content strong {
  font-weight: 600;
}
.content a {
  text-decoration: underline;
  color: #ff0043;
}
.content ol,
.content ul {
  padding-left: 20px;
  margin-left: 0;
}
.content ol li,
.content ul li {
  margin-bottom: 10px;
}
.content ul {
  list-style: none;
  padding-left: 0;
  margin-bottom: 20px;
}
.content ul li {
  padding-left: 20px;
  position: relative;
}
.content ul li::before {
  position: absolute;
  content: '';
  height: 8px;
  width: 8px;
  border-radius: 50%;
  background: #ff0043;
  left: 3px;
  top: 8px;
}
.content table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 1rem;
  border: 1px solid #eeeeee;
}
.content table td,
.content table th {
  padding: 0.75rem;
  vertical-align: top;
  margin-bottom: 0;
}
.content tr:not(:last-child) {
  border-bottom: 1px solid #eeeeee;
}
.content th {
  font-weight: 500;
}
.content thead {
  background: #fbfbfb;
  margin-bottom: 0;
}
.content thead tr {
  border-bottom: 1px solid #eeeeee;
}
.content tbody {
  background: #fff;
  margin-bottom: 0;
}
.content .notices {
  margin: 2rem 0;
  position: relative;
  overflow: hidden;
}
.content .notices p {
  padding: 10px;
  margin-bottom: 0;
}
.content .notices p::before {
  position: absolute;
  top: 2px;
  color: #fff;
  font-family: 'themify';
  font-weight: 900;
  content: '\e717';
  left: 10px;
}
.content .notices.note p {
  border-top: 30px solid #6ab0de;
  background: #e7f2fa;
}
.content .notices.note p::after {
  content: 'Note';
  position: absolute;
  top: 2px;
  color: #fff;
  left: 2rem;
}
.content .notices.tip p {
  border-top: 30px solid #78c578;
  background: #e6f9e6;
}
.content .notices.tip p::after {
  content: 'Tip';
  position: absolute;
  top: 2px;
  color: #fff;
  left: 2rem;
}
.content .notices.info p {
  border-top: 30px solid #f0b37e;
  background: #fff2db;
}
.content .notices.info p::after {
  content: 'Info';
  position: absolute;
  top: 2px;
  color: #fff;
  left: 2rem;
}
.content .notices.warning p {
  border-top: 30px solid #e06f6c;
  background: #fae2e2;
}
.content .notices.warning p::after {
  content: 'Warning';
  position: absolute;
  top: 2px;
  color: #fff;
  left: 2rem;
}
.content blockquote {
  font-size: 20px !important;
  color: #222;
  padding: 20px 40px;
  border-left: 2px solid #ff0043;
  margin: 40px 0;
  font-weight: bold;
  background: #fbfbfb;
}
.content blockquote p {
  margin-bottom: 0 !important;
}
.content pre {
  display: block;
  padding: 9.5px;
  margin: 10px 0px 10px;
}
.content code {
  margin-bottom: 0 !important;
  font-size: 100%;
}

@media (max-width: 1023px) {
  .hidden-on-tablet {
    display: none;
  }
}
.code-tabs {
  overflow: hidden;
  margin-bottom: 20px;
  background-color: #fff;
}
.code-tabs .tab-pane {
  display: none;
}
.code-tabs .tab-pane.active {
  display: block;
}
.code-tabs .nav-tabs {
  list-style: none;
  margin: 0 !important;
}
.code-tabs .nav-tabs li {
  padding: 0 !important;
  margin: 0 !important;
}
.code-tabs .nav-tabs li::before {
  display: none;
}
.code-tabs .nav-tabs li a {
  border-radius: 0 !important;
  box-shadow: none !important;
  text-decoration: none;
}
.code-tabs .nav-tabs li a:focus {
  border-color: #ff0043;
}
.code-tabs .nav-tabs li.active a {
  color: #fff;
  background-color: #ff0043;
  border-color: #ff0043;
}
.code-tabs .tab-content {
  padding: 20px 15px;
  border: 1px solid #e2e2e2;
}

.no-pointer {
  pointer-events: none;
}
body {
  background-color: #fafafa;
  height: 100% !important;
}

div[class='card match-height'] {
  height: auto !important;
}

footer {
  bottom: 0;
  left: 0;
  right: 0;
  position: inherit;
}

/*

Icones: 
        https://pictogrammers.github.io/@mdi/font/6.9.96/
        https://materialdesignicons.com/

*/
</style>
