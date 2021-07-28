<template>
  <div class="cotainer">
    <div class="row">
      <b-cole sm="12" md="7">
        <div class="post-bg">
          <div class="title">
            <h2 class="post-title" for="">Total Items</h2>
          </div>

          <div class="posters">
            <div class="poster">
              <b-card
                no-body
                class="overflow-hidden"
                style="max-width: 61vw; max-height: 36vh; border: white"
              >
                <b-row no-gutters>
                  <b-col md="" sm="4" class="imgp">
                    <b-card-img
                      src="https://picsum.photos/400/400/?image=20"
                      alt="Image"
                      class="rounded-0"
                    ></b-card-img>
                  </b-col>
                  <b-col md="" sm="4" >
                    <b-card-body title="Super Dinner">
                      <b-card-text>
                        <p style="color: #848490">KFC Salmiya</p>
                        <p></p>
                        <p style="font-weight: bold">2.350 x 1=2.350KD</p>
                      </b-card-text>
                    </b-card-body>
                  </b-col>
                  <b-col sm="3">
                    <div class="add">
                      <div><button class="btnadd">-</button></div>
                      <div><p style="width: 2rem">1</p></div>
                      <div><button class="btnadd">+</button></div>
                    </div>
                  </b-col>
                  <b-col sm="1">
                    <div class="iclose">
                      <b-icon icon="x-square-fill" font-scale="1.5" class="" />
                    </div>
                  </b-col>
                </b-row>
              </b-card>
            </div>
            <div class="poster">
              <b-card
                no-body
                class="overflow-hidden"
                style="max-width: 61vw; max-height: 36vh; border: white"
              >
                <b-row no-gutters>
                  <b-col md="" sm="4" class="imgp">
                    <b-card-img
                      src="https://picsum.photos/400/400/?image=20"
                      alt="Image"
                      class="rounded-0"
                    ></b-card-img>
                  </b-col>
                  <b-col md="" sm="4" >
                    <b-card-body title="Super Dinner">
                      <b-card-text>
                        <p style="color: #848490">KFC Salmiya</p>
                        <p></p>
                        <p style="font-weight: bold">2.350 x 1=2.350KD</p>
                      </b-card-text>
                    </b-card-body>
                  </b-col>
                  <b-col sm="3">
                    <div class="add">
                      <div><button class="btnadd">-</button></div>
                      <div><p style="width: 2rem">1</p></div>
                      <div><button class="btnadd">+</button></div>
                    </div>
                  </b-col>
                  <b-col sm="1">
                    <div class="iclose">
                      <b-icon icon="x-square-fill" font-scale="1.5" class="" />
                    </div>
                  </b-col>
                </b-row>
              </b-card>
            </div><div class="poster">
              <b-card
                no-body
                class="overflow-hidden"
                style="max-width: 61vw; max-height: 36vh; border: white"
              >
                <b-row no-gutters>
                  <b-col md="" sm="4" class="imgp">
                    <b-card-img
                      src="https://picsum.photos/400/400/?image=20"
                      alt="Image"
                      class="rounded-0"
                    ></b-card-img>
                  </b-col>
                  <b-col md="" sm="4" >
                    <b-card-body title="Super Dinner">
                      <b-card-text>
                        <p style="color: #848490">KFC Salmiya</p>
                        <p></p>
                        <p style="font-weight: bold">2.350 x 1=2.350KD</p>
                      </b-card-text>
                    </b-card-body>
                  </b-col>
                  <b-col sm="3">
                    <div class="add">
                      <div><button class="btnadd">-</button></div>
                      <div><p style="width: 2rem">1</p></div>
                      <div><button class="btnadd">+</button></div>
                    </div>
                  </b-col>
                  <b-col sm="1">
                    <div class="iclose">
                      <b-icon icon="x-square-fill" font-scale="1.5" class="" />
                    </div>
                  </b-col>
                </b-row>
              </b-card>
            </div>





          </div>
        </div>
      </b-cole>

      <b-col>
        <div class="rightdiv">
          <div class="title"></div>
          <div class="tbtn">
            <b-button href="" variant="white" class="btnTo"
              >Back to Shops</b-button
            >
          </div>
          <div class="post2">
            <div class="txt">
              <b-card-text>
                <h5>Sub Total(3 Items):KD 10.35</h5>
                <p>Pomo Discount:KD 2.0</p>
                <h6 style="color: #56d8f8">Total:KD 8.35</h6>
              </b-card-text>
            </div>
            <div class="btncheck">
              <b-button class="btn2" href="" variant="white"
                >CHECKOUT</b-button
              >
            </div>
          </div>
        </div>
      </b-col>
    </div>



    
    
  </div>
</template>


<script>
export default {
  name: "posters",
};
</script>


<style scoped>

.post-bg {
  display: flex;
  align-content: center;
      height: 139vh;
  float: inherit;
  background-color: rgba(247, 234, 234, 0.425);
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: flex-start;
  align-items: stretch;
}
.title {
  font-size: 1rem;
  width: 100%;
  height: 15vh;
}
.post-title {
  color: #2ac5ea;
  float: left;
  padding-top: 1rem;
  margin-left: 20vh;
  font-weight: 600;
  margin: auto;
  margin-left: 6vw;
  margin-top: 1rem;
}
.posters {
  margin-top: -33px;
  width: 120vh;
  margin-left: 13vh;
  margin-right: 3vw;
}
.poster {
  
  height: 36vh;
  margin-top: 8vh;
}
.rounded-0 {
   overflow: hidden;
    border-radius: 0 !important;
   
   
}

.add {
  text-align: center;
  background-color: #efefef;
  display: flex;
  /* margin: 1rem; */
  height: 2rem;
  width: 6rem;
  float: left;
  margin-bottom: 11vh;
  margin-left: 4vw;
  margin-top: 14vh;
  align-content: stretch;
  flex-wrap: nowrap;
  flex-direction: row;
  justify-content: space-around;
  align-items: stretch;
}
.btnadd {
  border: #dbe3ea;
  border-radius: 4px;
  width: 3vw;
  height: 8vh;
  background-color: #eaeaea;
  width: 3vw;
  height: -webkit-fill-available;
}
.card-body {
  position: absolute;
  flex: 1 1 auto;
  height: -webkit-fill-available;
  padding: 1.25rem;
}
.b-icon.bi {
  color: red;
  display: inline-block;
  overflow: visible;
  vertical-align: -0.15em;
}
.iclose {
  position: absolute;
  margin-top: 0vh;
  margin-left: 2.5vw;
}
.rightdiv {
  padding-left: 2vw;
  margin-left: -17px;
  height: 100%;
  background-color: #fcf6f6;
}
.post2 {
  padding: 1rem;
  margin-top: 3vh;
  background-color: white;
  margin-right: 2vw;
  border-radius: 25px;
}
.card-body[data-v-d20b3834] {
  margin-top: 3vh;
  background-color: white;
  position: absolute;
  flex: 1 1 auto;
  padding: 1.25rem;
}
.btnTo {
    color: white;
  height: 5vh;
  width: 17vw;
  border: #56d8f8;
  background-color: #56d8f8;
  position: sticky;
}
.btnTo:hover {
  background-color: #67ddfa;
}
.tbtn {
  margin-right: 2vw;
  text-align: end;
}
.btncheck {
  margin-left: 10vw;
  height: 5vh;
  width: 17vw;
  position: sticky;
}
.btn2 {
    margin: -9px;
    color: white;
  width: 15vw;
  border-radius: 31px;
  background-color: #56d8f8;
}
.txt {
  margin-left: 13vw;
  height: 20vh;
  text-align: right;
}
.body{
    background-color: #faeded;
}
.imgp{
    vertical-align: middle;
        display: flex;
    align-items: stretch;
}
</style>
