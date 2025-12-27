# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
FIRST PAGE

INDEX.HTML
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-2.png" />
      <div class="div">Register</div>
      <div class="text-wrapper-2">Login</div>
      <div class="text-wrapper-3">@ Designed By Sanjai.S.J</div>
      <img class="rectangle-2" src="img/rectangle-3.png" />
      <div class="register">See Details</div>
    </div>
  </body>
</html>
```
GLOBAL.CSS
```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
```
STYLE.CSS
```
.android-medium {
  background: linear-gradient(
    162deg,
    rgba(62, 245, 255, 1) 45%,
    rgba(84, 37, 153, 1) 100%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  position: relative;
}

.android-medium .sec-logo {
  position: absolute;
  top: 91px;
  left: 40px;
  width: 1000px;
  height: 201px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: calc(50.00% - 480px);
  left: calc(50.00% - 473px);
  width: 939px;
  height: 128px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  top: 751px;
  left: calc(50.00% - 160px);
  width: 320px;
  height: 100px;
  border-radius: var(--shape-corner-extra-large);
  box-shadow: 0px 16px 30px 4px #00000040;
  background: linear-gradient(
    135deg,
    rgba(62, 245, 255, 1) 0%,
    rgba(84, 37, 153, 1) 100%
  );
  position: absolute;
}

.android-medium .img {
  top: 970px;
  left: calc(50.00% - 194px);
  width: 388px;
  height: 168px;
  position: absolute;
}

.android-medium .div {
  position: absolute;
  top: 997px;
  left: calc(50.00% - 108px);
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 762px;
  left: calc(50.00% - 77px);
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1756px;
  left: 109px;
  width: 880px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  top: 1208px;
  left: calc(50.00% - 209px);
  width: 418px;
  height: 168px;
  position: absolute;
}

.android-medium .register {
  position: absolute;
  top: 1235px;
  left: calc(50.00% - 146px);
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
STYLEGUIDE.CSS
```
:root {
  --shape-corner-extra-large: 28px;
}
```
SECOND PAGE
INDEX.HTML
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="rectangle" src="img/rectangle-2.png" />
      <div class="text-wrapper">Register</div>
      <div class="div">EVENT DETAILS</div>
      <p class="date">
        Date:01:01:2026(8.00am-6.00pm)<br /><br />Events:<br /><br />1.Cricket<br />2.100 Meters (Running Race)<br />3.200
        Meters&nbsp;&nbsp;(Running Race)<br />4.Volly ball<br />5.Basket ball<br />6.Foot ball<br />7.Badminton<br />8.Chess<br /><br />Entry
        fees ₹200(Per Game)
      </p>
      <p class="chief-guests-VIJAY">
        <span class="span">Chief Guests </span>
        <span class="text-wrapper-2">:<br /><br />VIJAY , AJITH , SIVAKARTHIKEYAN</span>
      </p>
    </div>
  </body>
</html>
```
GLOBAL.CSS
```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
```
STYLE.CSS
```
.android-medium {
  background: linear-gradient(
    162deg,
    rgba(62, 245, 255, 1) 45%,
    rgba(84, 37, 153, 1) 100%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  position: relative;
}

.android-medium .sec-logo {
  position: absolute;
  top: 91px;
  left: 40px;
  width: 1000px;
  height: 201px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 1607px;
  left: calc(50.00% - 194px);
  width: 388px;
  height: 168px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 1634px;
  left: calc(50.00% - 108px);
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 371px;
  left: calc(50.00% - 400px);
  width: 800px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .date {
  position: absolute;
  top: 570px;
  left: calc(50.00% - 500px);
  width: 1000px;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .chief-guests-VIJAY {
  position: absolute;
  top: 1394px;
  left: 113px;
  width: 850px;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #ffef00;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .span {
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #ffef00;
  font-size: 64px;
  letter-spacing: 0;
}

.android-medium .text-wrapper-2 {
  font-size: 48px;
}
```
THIRD PAGE
INDEX.HTML
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper">Enter your name :</div>
      <div class="text-wrapper-2">Enter your Gender :</div>
      <div class="text-wrapper-3">Enter your age :</div>
      <p class="p">Enter the sport to participate :</p>
      <div class="text-wrapper-4">Enter your Height :</div>
      <div class="text-wrapper-5">SPORTS DAY REGISTRATION FORM:</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">Submit</div>
    </div>
  </body>
</html>
```
GLOBAL.CSS
```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
```
STYLE.CSS
```
.android-medium {
  background: linear-gradient(
    162deg,
    rgba(62, 245, 255, 1) 45%,
    rgba(84, 37, 153, 1) 100%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  position: relative;
}

.android-medium .sec-logo {
  position: absolute;
  top: 91px;
  left: 40px;
  width: 1000px;
  height: 201px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .rectangle {
  top: 580px;
  left: 99px;
  width: 900px;
  background-color: #ffffff;
  border-radius: var(--shape-corner-large-increased);
  border: 1px solid;
  border-color: #000000;
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .div {
  top: 760px;
  left: 99px;
  width: 900px;
  background-color: #ffffff;
  border-radius: var(--shape-corner-large-increased);
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .rectangle-2 {
  top: 950px;
  left: 99px;
  width: 900px;
  background-color: #ffffff;
  border-radius: var(--shape-corner-large-increased);
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .rectangle-3 {
  top: 1138px;
  left: 99px;
  width: 900px;
  background-color: #ffffff;
  border-radius: var(--shape-corner-large-increased);
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .rectangle-4 {
  top: 1354px;
  left: 99px;
  width: 900px;
  background-color: #ffffff;
  border-radius: var(--shape-corner-large-increased);
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .text-wrapper {
  top: 603px;
  left: 356px;
  position: absolute;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.3;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  top: 782px;
  left: 335px;
  position: absolute;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.3;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  top: 968px;
  left: 378px;
  position: absolute;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.3;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .p {
  position: absolute;
  top: 1156px;
  left: 230px;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.3;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  top: 1376px;
  left: 343px;
  position: absolute;
  height: 55px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.3;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: calc(50.00% - 568px);
  left: calc(50.00% - 473px);
  width: 939px;
  height: 128px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Times New Roman-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 48px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  top: 1604px;
  left: 389px;
  width: 320px;
  border-radius: var(--shape-corner-extra-large);
  background: linear-gradient(
    135deg,
    rgba(62, 245, 255, 1) 0%,
    rgba(84, 37, 153, 1) 100%
  );
  position: absolute;
  height: 100px;
  box-shadow: 0px 16px 30px 4px #00000040;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 1615px;
  left: 452px;
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
STYLEGUIDE.CSS
```
:root {
  --shape-corner-large-increased: 20px;
  --shape-corner-extra-large: 28px;
}
```
FOURTH PAGE
INDEX.HTML
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <div class="text-wrapper">Thank you for Registering</div>
    </div>
  </body>
</html>
```
GLOBAL.CSS
```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
```
STYLE.CSS
```
.android-medium {
  border: 1px solid;
  border-color: #000000;
  background: linear-gradient(
    162deg,
    rgba(62, 245, 255, 1) 45%,
    rgba(84, 37, 153, 1) 100%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  display: flex;
  flex-direction: column;
  gap: 197px;
}

.android-medium .sec-logo {
  margin-left: 40px;
  width: 1000px;
  height: 201px;
  margin-top: 91px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .text-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-left: 199px;
  width: 700px;
  height: 900px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```

## OUTPUT:
<img width="1919" height="1079" alt="image_2025-12-26_20-49-11" src="https://github.com/user-attachments/assets/44285136-1e03-4d37-8de1-07843f3f8bba" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
