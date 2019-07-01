
* {
  box-sizing: border-box;
}
main {
  max-width: 900px;
  padding: 10px 80px;
  margin: 0 auto;
}
nav {
text-align: center;
}
.myButton {
text-align: center;
-moz-box-shadow: 0px 18px 22px -7px #276873;
-webkit-box-shadow: 0px 18px 22px -7px #276873;
box-shadow: 0px 18px 22px -7px #276873;
background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #599bb3), color-stop(1, #408c99));
background:-moz-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:-webkit-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:-o-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:-ms-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:linear-gradient(to bottom, #599bb3 5%, #408c99 100%);
filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#599bb3', endColorstr='#408c99',GradientType=0);
background-color:#599bb3;
-moz-border-radius:8px;
-webkit-border-radius:8px;
border-radius:8px;
display:inline-block;
cursor:pointer;
color:#ffffff;
font-family:Arial;
font-size:20px;
font-weight:bold;
padding:13px 30px;
text-decoration:none;
text-shadow:0px 7px 4px #3d768a;

margin: 10px 0px 0px 0px;
}
.myButton:hover {
color: black;
background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #408c99), color-stop(1, #599bb3));
background:-moz-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-webkit-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-o-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-ms-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:linear-gradient(to bottom, #408c99 5%, #599bb3 100%);
filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#408c99', endColorstr='#599bb3',GradientType=0);
background-color:#408c99;
}
.myButton:active {
  position: relative;
  top: 5px;
}
.highlight {
color: rgb(236, 15, 15);
}
.lichtblauw {
  color: #3CF;
}
.hoogte {
  height: 40px;
}
form p{
  color: blue;
}
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 200px;
  border: 3px solid #73AD21;
}
div.top-navigatie {
  text-align: center;
  color: white;
  background-color: black;
  position: relative;
  padding: 10px 12px;
}
div.top-navigatie a {
  color: white;
  padding-right: 40px;
  }
#form1 {
/*margin: 20px 10px 5px 15px;*/
text-align: center;
}
#fieldset1 {
  /*padding: 10px;*/
  max-width: 800px;
  /*border-color: rgb(38, 175, 230);*/
  margin: 0 auto ;
}
legend {
  color: rgb(33, 152, 199);
}
/*.kolommen {
  padding: 0px 10px 0px 10px;
  align: center;
}*/
.kolom1 {
  float: left;
  width: 50%;
  padding-right: 20px;
}
.kolom2 {
  float: left;
  width: 50%;
}
/*.buttons {
  float: bottom;
} */
input[type=text], input[type=email], textarea, select {
  width: 100%
}
div.TD {
  margin: 0;
  padding: 0;
  justify-content: center;
  height: vh;
}

/*h1.TheDutchMannekes {
  position: relative;
  font-family: sans-serif;
  text-transform: uppercase;
  font-size: 27px;
  letter-spacing: 4px;
  overflow: hidden;
  background: linear-gradient(90deg, rgb(0, 0, 255), #06F);
  background-repeat: no-repeat;
  background-size: 80%;
  animation: animate 5s linear 3;
  -webkit-background-clip: text;
  -webkit-text-fill-color: rgba(255, 255, 255, 0);
}*/

@keyframes animate {
  0% {
    background-position: -500%;
  }
  100% {
    background-position: 500%;
  }
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/*@media only screen
and (min-device-width : 320px)
and (max-device-width : 480px) {
}

@media only screen
and (min-width : 321px) {
  h1.TheDutchMannekes {
  position: relative;
  font-family: sans-serif;
  text-transform: uppercase;
  font-size: 27px;
  letter-spacing: 4px;
  overflow: hidden;
  background: linear-gradient(90deg, rgb(0, 0, 255), #06F);
  background-repeat: no-repeat;
  background-size: 80%;
  animation: animate 5s linear 3;
  -webkit-background-clip: text;
  -webkit-text-fill-color: rgba(255, 255, 255, 0);
}
}

@media only screen
and (max-width : 320px) {
}*/

/* Mobile Styles */
@media only screen and (max-width: 400px) {
h1.TD {
  font-size: 30px;
}
main {
  padding: 0px 10px ;
  }
.fixed {
  font-size: 1px;
}
.myButton {
  font-size: 100%;
    }
.hoogte {
  height: 90px;
    }
p {
  font-size: 14px;
}
.staffteam {
  padding: 0px;
  margin: 0px;

}
}

/* Tablet Styles */
@media only screen and (min-width: 401px) and (max-width: 960px) {
  h1.TD {
  font-size: 30px;
}
}

/* Desktop Styles */
@media only screen and (min-width: 961px) {
h1.TD {
    position: relative;
    font-family: sans-serif;
    text-transform: uppercase;
    font-size: 27px;
    letter-spacing: 4px;
    overflow: hidden;
    background: linear-gradient(90deg, rgb(0, 0, 255), #06F);
    background-repeat: no-repeat;
    background-size: 80%;
    background-position: center;
    animation: animate 5s linear 3;
    -webkit-background-clip: text;
    -webkit-text-fill-color: rgba(255, 255, 255, 0);
    text-align: center;

}
}
.groottextarea {
  height: 180px;
  }
.hoogte {
  /*height: 100px */
}
h1 {
text-align: center;
text-transform: uppercase;
background: linear-gradient(to right, rgb(14, 215, 241) 0%, blue 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}
/*.highlight {
color: rgb(236, 15, 15);
}*/
.kleinerebutton {
text-align: center;
-moz-box-shadow: 0px 18px 22px -7px #276873;
-webkit-box-shadow: 0px 18px 22px -7px #276873;
box-shadow: 0px 18px 22px -7px #276873;
background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #599bb3), color-stop(1, #408c99));
background:-moz-linear-gradient(top, #599bb3 5%, #408c99 100%);
nackground:-webkit-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:-o-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:-ms-linear-gradient(top, #599bb3 5%, #408c99 100%);
background:linear-gradient(to bottom, #599bb3 5%, #408c99 100%);
filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#599bb3', endColorstr='#408c99',GradientType=0);
background-color:#599bb3;
-moz-border-radius:8px;
-webkit-border-radius:8px;
border-radius:8px;
display:inline-block;
cursor:pointer;
color:#ffffff;
font-family:Arial;
font-size:17px;
font-weight:bold;
padding:13px 30px;
text-decoration:none;
text-shadow:0px 7px 4px #3d768a;
}
.kleinerebutton:hover {
background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #408c99), color-stop(1, #599bb3));
background:-moz-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-webkit-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-o-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:-ms-linear-gradient(top, #408c99 5%, #599bb3 100%);
background:linear-gradient(to bottom, #408c99 5%, #599bb3 100%);
filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#408c99', endColorstr='#599bb3',GradientType=0);
background-color:#408c99;
}
.kleinerebutton:active {
position:relative;
top:1px;
}

.hidden {
  display:none;
}
/*.clearfix:after {
    font-size: 0;
}
.clearfix:after {
    content: ".";
    display: block;
    height: 0;
    clear: both;
    visibility: hidden;
}*/
h3 {
  /*margin-top: 22px;*/
}
.blauw-border {
  margin: 0% 20%;
  border: 3px solid #09C;
  text-align: center;
  /*padding: 10px;*/
}
.center {
  text-align: center
}
table {
  border-color: #09F;
  }
/*div.fixed {
  position: fixed;
  top: 0;
  left: 0;
  width: 300px;
  max-width: 20%
}
img {
  border: 1px solid blue;
  padding: 1px;
  max-width: 5%;
} */

.fixed {
  position: absolute;
  left: 0px;
  top: 0px;
  z-index: -1;
  max-width: 10%;
  padding-top: 50px;
  padding-left: 10px;
}
body {
 background-image: url("https://media.discordapp.net/attachments/566248279453728798/586852006455672845/BACKGROUND_website_TD.png");
 background-repeat: no-repeat;
 text-align: center;
 background-size: 50%;
 background-position: center;
 }
.portfolio {
  text-align: center;
    border: 3px solid #09C;
    margin: 20px;
  padding: 25px;
  }
















  *,
*::before,
*::after { box-sizing: border-box; }
body.animatie {
  display: flex;
  align-items: center;
  justify-content: center;
  align-items: center;

  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;

  background-color: #3c3c3c;
}


.card {
  position: relative;

  width: 700px;
  height: 400px;
  overflow: hidden;

  border-radius: 5px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
}

/*Light blue cover above the slide show*/
.card::after {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  z-index: 900;

  display: block;
  width: 100%;
  height: 100%;

  background-color: rgba(140, 22, 115, 0.2);
}

.card_part {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 7;

  display: flex;
  align-items: center;
  width: 100%;
  height: 100%;

  transform: translateX( 700px );
  background-image: url( https://github.com/Flat-Pixels/assets_hosting/blob/master/picture_slides/1.jpg?raw=true );

  animation: opaqTransition 28s cubic-bezier(0, 0, 0, 0.97) infinite;
}


.card_part.card_part-two {
  z-index: 6;
  background-image: url(   https://cdn.discordapp.com/attachments/556040976817324033/567117097293840385/PicsArt_04-15-12.40.31.jpg
 );
  animation-delay: 7s;
  max-width: 50%;
  max-height: 10%
}

.card_part.card_part-three {
  z-index: 5;
  background-image: url( https://github.com/Flat-Pixels/assets_hosting/blob/master/picture_slides/3.jpg?raw=true );
  animation-delay: 14s;
}

.card_part.card_part-four {
  z-index: 4;
  background-image: url( https://github.com/Flat-Pixels/assets_hosting/blob/master/picture_slides/4.jpg?raw=true );
  animation-delay: 21s;
}


@keyframes opaqTransition {
  3% { transform: translateX( 0 ); }
  25% { transform: translateX( 0 ); }
  28% { transform: translateX( -700px ); }
  100% { transform: translateX( -700px ); }
}
body {
  background-image: url("https://cdn.discordapp.com/attachments/566248279453728798/586852006455672845/BACKGROUND_website_TD.png");
    background-size: cover;
  background-attachment: fixed;
}
img {
  max-width: 50%;
}
td {
  font-size: 15px;
}
h3.blauw {
  color: #03F;
  }
