<template>
  <div>
    <header>
      <div>
        <b-navbar toggleable="lg" type="dark" variant="info" class="pdg">
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="mr-auto">
              <b-nav-form class="">
                <b-form-input
                  size="sm "
                  class="mr-sm-2 c-primary input"
                  placeholder="Streel 1,Lane 4,block 12,Salmiya.."
                ></b-form-input>
                <b-icon
                  class="icon-location"
                  font-scale="1.5"
                  icon="geo-alt-fill"
                />
              </b-nav-form>
              <div class="sep"></div>

              <b-nav-form class="">
                <b-form-input
                  size="sm "
                  class="mr-sm-2 input"
                  placeholder="Search"
                ></b-form-input>
                <b-icon class="icon-search" font-scale="1.5" icon="search" />
              </b-nav-form>
              <div class="space"></div>

              <div class="lang-drop">
                <b-dropdown text="EN " variant="white" class="lang-drop">
                  <b-dropdown-item href="#">EN</b-dropdown-item>
                  <b-dropdown-item href="#">ES</b-dropdown-item>
                  <b-dropdown-item href="#">RU</b-dropdown-item>
                  <b-dropdown-item href="#">FA</b-dropdown-item>
                </b-dropdown>
              </div>
              <div class="bell-div">
                <b-icon
                  icon="bell-fill"
                  font-scale="1.3"
                  class=""
                  variant="light"
                ></b-icon>
                <b-icon
                  class="card32"
                  icon="exclamation-circle-fill"
                  animation="throb"
                  font-scale=".6"
                  variant="warning"
                ></b-icon>
              </div>
              <div>
                <div class="btn-p">
                  <div class="kwd">
                    <p>12.5</p>
                    <p style="">KWD</p>
                  </div>
                  <div class="cart3">
                    <b-icon
                      class="card31"
                      icon="exclamation-circle-fill"
                      animation="throb"
                      font-scale=".6"
                      variant="warning"
                    ></b-icon>
                    <b-icon icon="cart3" font-scale="1.3" />
                  </div>
                </div>
              </div>
              <div>
                <div class="btn-user">
                  <div class="cart3">
                    <b-icon icon="person-circle" font-scale="1.3" />
                  </div>
                  <div class="kwd">
                    <p>Name</p>
                  </div>
                </div>
              </div>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "vue-pro",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.pdg {
  width: 100%;
  padding-top: 1rem;
  position: sticky;
   top:0;
    
}
.bg-info {
  z-index: 10;
    position: fixed;
  padding-left: 5rem;
  background-color: #56d8f8 !important;
  padding-top: 1.5rem;
}
article,
aside,
figcaption,
figure,
footer,
header,
hgroup,
main,
nav,
section {
  display: block;
  height: 5rem;
}
.navbar.navbar-dark.bg-dark {
  background-color: #bbd82a !important;
}
.b-nav-form {
  background-color: blueviolet;
}
.mr-auto,
.mx-auto {
  height: 2rem;
  margin-right: auto !important;
}
.form-inline {
  flex-wrap: nowrap;
  vertical-align: middle;
  margin-top: 1px;
  height: 1.7rem;
  width: 22rem;
  background-color: white;
  display: flex;
  flex-flow: row wrap;
  align-items: center;
  border-radius: 4px;
}
.form-inline[data-v-469af010][data-v-469af010] {
  color: #56d8f8;
  vertical-align: middle;
  margin-top: 1px;
  height: -webkit-fit-content;
  height: -moz-fit-content;
  height: fit-content;
  width: 24vw;
  background-color: white;
  display: flex;
  flex-flow: row wrap;
  align-items: stretch;
  border-radius: 4px;
  flex-wrap: nowrap;
}

.form-inline[data-v-1ee389d7] {
  color: #56d8f8;
  vertical-align: middle;
  margin-top: 1px;
  height: fit-content;
  width: 24vw;
  background-color: white;
  display: flex;
  flex-flow: row wrap;
  align-items: center;
  border-radius: 4px;
}

.sep {
  width: 1rem;
}
.icon-location[data-v-469af010] {
  margin: auto;
  cursor: pointer;
  color: #46bdd0;

  position: sticky;
}
.icon-search[data-v-469af010] {
  margin: auto;
  margin-right: 1px;
  position: sticky;
  cursor: pointer;
}

.language[data-v-469af010] {
  border-radius: 4px;
  color: #46bdd0;
  background-color: white;
  height: 2rem;
}

.space {
  width: 4rem;
}
@media (min-width: 576px) {
  .form-inline .form-control[data-v-1ee389d7] {
    font-weight: bold;
    color: #46bdd0;
    height: inherit;
    border-color: white;
    display: flex;
    width: 20vw;
    vertical-align: middle;
    justify-content: center;
    align-items: center;
    align-content: stretch;
    flex-wrap: wrap;
    border: white;
    flex-direction: column;
  }
}

.bell-div[data-v-469af010] {
  vertical-align: middle;
  margin: 0;
  padding: 0;
  text-align: center;
  width: 5rem;
  height: 2rem;
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: #04dce6;
  width: 4rem;
  text-align: center;
  font-weight: bold;
}
.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.25rem 1.5rem;
  clear: both;
  font-weight: 400;
  color: #07b7d4;
  text-align: inherit;
  white-space: nowrap;
  background-color: transparent;
  border: 0;
}
.navbar-dark .navbar-nav .nav-link {
  font-weight: bold;
  color: rgb(26 204 222);
  width: 4rem;
  align-content: center;
  text-align: center;
}
.navbar-dark .navbar-nav .nav-link {
  height: 2rem;
  border-radius: 4px;
  text-align: center;
  background-color: white;
  color: rgb(38 179 232 / 90%);
  width: 4rem;
}
.input::placeholder {
  color: #04dce6;
}
.lang-drop {
  color: #04dce6;
  height: inherit;
  border-radius: 4px;
  text-align: center;
  background-color: white;
  color: rgb(38 179 232 / 90%);
  width: 5rem;
}
.btn-secondary {
  color: #14b4e4;
  background-color: #fdfdfd;
  border-color: #ffffff;
}
.bell-div {
  padding-top: 0.5rem;
  vertical-align: middle;
  margin: 0;

  text-align: center;
  width: 5rem;
  height: 2rem;
}
.bell-div[data-v-469af010][data-v-469af010] {
  vertical-align: middle;
  margin: 0;
  padding: 0.5rem;
  text-align: center;
  width: 5rem;
  height: 2rem;
}
.btn:not(:disabled):not(.disabled) {
  color: #0dd4d4;
  cursor: pointer;
}
.btn {
  display: inline-block;
  font-weight: 400;
  color: #94a0a1;
  text-align: center;
  vertical-align: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  background-color: transparent;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}
.btn-p[data-v-1ee389d7] {
  color: #45d2f5;
  background-color: white;
  display: flex;
  height: -moz-fit-content;
  height: 2rem;
  border-radius: 4px;
  width: 6rem;
  cursor: pointer;
  flex-direction: row;
  flex-wrap: nowrap;
  align-content: stretch;
  justify-content: space-between;
  align-items: flex-end;
}

.kwd[data-v-1ee389d7] {
  padding-left: 0.3rem;
  height: inherit;
  padding-top: 1rem;
  color: #04dce6;
  display: flex;
  align-content: flex-end;
  /* text-align: center; */
  vertical-align: middle;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
  align-items: center;
  font-weight: 500;
  font-size: smaller;
}
.cart3[data-v-1ee389d7] {
  padding-left: 0.3rem;
  font-weight: 900;
  padding-right: 0.4rem;
  padding-bottom: 0.2rem;
}
.btn-user {
  margin-left: 2rem;
  color: #45d2f5;
  background-color: white;
  display: flex;
  height: -moz-fit-content;
  height: 2rem;
  border-radius: 4px;
  width: 6rem;
  cursor: pointer;
  flex-direction: row;
  flex-wrap: nowrap;
  align-content: stretch;
  justify-content: flex-start;
  align-items: flex-end;
}
.btn:not(:disabled):not(.disabled) {
  cursor: pointer;
  color: #56d8f8;
}

.dropdown-toggle::placeholder {
  color: #56d8f8;
}

.cart3[data-v-1ee389d7][data-v-1ee389d7] {
  padding-left: 0.3rem;
  font-weight: 900;
  padding-right: 0.4rem;
  padding-bottom: 0.2rem;
  display: flex;
}
.cart32 {
  margin-left: -0.5rem;
  padding-bottom: 2em;
  text-align: center;
  padding-left: 1rem;
  font-weight: 900;
  padding-right: 0.4rem;
  padding-bottom: 0.2rem;
  display: flex;
}
.navbar-dark .navbar-toggler {
  margin-left: -3rem;
  color: rgba(255, 255, 255, 0.5);
  border-color: rgb(255 255 255 / 78%);
}
</style>
