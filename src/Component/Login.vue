<template>
  <div class="container">
      <b-container class="bv-example-row">
            <b-row>
                <b-col md="4" sm="12">
                          <div class="textmain">
                              log in
                          </div>


                          <div>
                              <b-container class="bv-example-row">
                                  <b-row>
                                    <b-col>
                                          User name:
                                          <b-form-input
                                            type="text"></b-form-input>
                                    </b-col>
                                  </b-row>
                                  <b-row>
                                    <b-col>
                                        Password:
                                        <b-form-input
                                          type="password"></b-form-input>
                                    </b-col>
                                  </b-row>

                              </b-container>
                          </div>

                          <div class="btngroup">
                                <b-button class="button1">
                                    Login
                               </b-button>
                               <b-button class="button2">
                                   Register
                              </b-button>
                          </div>

                          <div class="forgotpwd">
                            Forgot Password?
                          </div>

                   </b-col>
                   <b-col md="5" ></b-col>
                <b-col md="3">
                  <div class="mgbottom"><span class="textcolor">display <span class="spanright"></span></span></div>
                  <div><span class="textcolor">statistics <span class="spanright">04/03/2018</span></span></div>
                  <div class="panel">: <span class="spanright2"><b>58862SHOW</b></span></div>
                  <div class="panel">User: <span class="spanright2"><b>177359</b></span></div>
                  Do you like TandemPartners?
                  <b-card title="Be the first of your friends to like this"
                          img-src="https://lorempixel.com/600/300/food/5/"
                          img-alt="Image"
                          img-top
                          tag="article"
                          style="max-width: 20rem;"
                          class="mb-2">

                    </b-card>
                </b-col>
            </b-row>
      </b-container>


  </div>
</template>

<script>
    export default {
      data() {
        return {
          selected: 'Choose..',
            options: [ 'Male', 'Female'
              ]
        }
      }
    }
</script>

<style>
.container {
  margin-top:2%;
  text-align: left;
}
.btngroup{
  margin:5%;

}
.forgotpwd {
  margin:5%;
  color:#435da5;
}
.button1{
  margin-top:2%;
  background-color:#435da5;
  height:40%;
}
.button2{
  margin-top:2%;
  background-color:#008744;
}
.small {
  font-size:9px;
}

.textmain {
  font-size: 45px;
  color:#435da5;
}

.textcolor {
  color: green;
  font-size: 18px;
}
.code {
  border-style: outset;
  border-width: 1px;
  border-color: #000000;
  background-color: #e5e0e0;
  height: 60px;
  weight: 100%;
  text-align: center;
}
.mgbottom {
margin-bottom: 4%;
}
.panel {
  border-style: ridge;
}
.colorgreen {
  color: #84ce94;
}
.spanright {
  text-align: right;
  margin-left:30%;
}

.spanright2 {
  text-align: right;
  color:#435da5;
  font-size: 22px;
  margin-left:25%;
}

.loginpanel1 {
  border-style: outset;
  border-width: 1px;
  border-color: #FFB410;
  background-color: #fbeccb;
  height: 80px;
  margin-bottom:2%;
}
.insidepanel1 {
  margin: 2%;
}
.btn1{
  background-color:#89b846;
  font-size: 18px;
  width:22%;
  height:6%;
  margin-bottom:100px;
  margin-top:30px;
}
.link{
 color: #3e85ba;
}
</style>
