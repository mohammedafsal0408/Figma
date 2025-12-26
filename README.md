# Ex08 Event Registration Web Application
## Date:26/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
PAGE 1

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
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper">SAVEETHA FIGHTING CHAMPIONSHIP</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle-3"></div>
      <div class="LOGIN">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LOGIN</div>
      <div class="rectangle-4"></div>
      <div class="REGISTER">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;REGISTER
      </div>
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #c7adad;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 18px;
  left: 0;
  width: 1px;
  height: 20px;
  background-color: #d9d9d9;
}

.android-medium .div {
  position: absolute;
  top: 176px;
  left: 31px;
  width: 2px;
  height: 8px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 161px;
  left: 23px;
  width: 524px;
  height: 64px;
  background-color: #dc1616;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 176px;
  left: 43px;
  width: 504px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 572px;
  left: 207px;
  width: 276px;
  height: 60px;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 593px;
  left: 203px;
  width: 278px;
  height: 43px;
  background-color: #1a1919;
}

.android-medium .LOGIN {
  position: absolute;
  top: 597px;
  left: 233px;
  width: 223px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #ffffff;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 674px;
  left: 205px;
  width: 276px;
  height: 59px;
  background-color: #0a0000;
}

.android-medium .REGISTER {
  position: absolute;
  top: 691px;
  left: 164px;
  width: 388px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #ffffff;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

PAGE 2

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
      <div class="rectangle"></div>
      <div class="EVENT-DAY-BOUTS">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EVENT&nbsp;&nbsp;&nbsp;&nbsp;
        DAY&nbsp;&nbsp;&nbsp;&nbsp; BOUTS
      </div>
      <div class="div"></div>
      <div class="MAIN-EVENT">MAIN&nbsp;&nbsp;EVENT</div>
      <div class="text-wrapper">LIGHTWEIGHT BOUT</div>
      <img class="star" src="img/star-1.svg" />
      <img class="star" src="img/star-3.svg" />
      <img class="star" src="img/star-2.svg" />
      <div class="text-wrapper-2">WELTERWEIGHT BOUT</div>
      <img class="img" src="img/star-4.svg" />
      <div class="text-wrapper-3">HEIGHTWEIGHT BOUT</div>
      <img class="star-2" src="img/star-5.svg" />
      <div class="rectangle-2"></div>
      <div class="CO-MAIN-EVENT">CO - MAIN&nbsp;&nbsp;EVENT</div>
      <img class="star-3" src="img/star-6.svg" />
      <div class="text-wrapper-4">JIU JITSU BOUT</div>
      <img class="star-4" src="img/star-7.svg" />
      <div class="text-wrapper-5">SPARRING 5 ROUNDS</div>
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #cbaeae;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .rectangle {
  top: 41px;
  width: 583px;
  height: 103px;
  background-color: #e02626;
  position: absolute;
  left: 56px;
}

.android-medium .EVENT-DAY-BOUTS {
  position: absolute;
  top: 78px;
  left: 114px;
  width: 518px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  top: 189px;
  width: 233px;
  height: 60px;
  background-color: #ffe227;
  position: absolute;
  left: 56px;
}

.android-medium .MAIN-EVENT {
  position: absolute;
  top: 206px;
  left: 89px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 272px;
  left: 131px;
  width: 284px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star {
  position: absolute;
  top: 275px;
  left: 90px;
  width: 24px;
  height: 23px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 331px;
  left: 131px;
  width: 314px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 333px;
  left: 90px;
  width: 24px;
  height: 23px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 386px;
  left: 130px;
  width: 314px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-2 {
  position: absolute;
  top: 390px;
  left: 90px;
  width: 24px;
  height: 21px;
}

.android-medium .rectangle-2 {
  top: 461px;
  width: 294px;
  height: 69px;
  background-color: #ffe629;
  position: absolute;
  left: 56px;
}

.android-medium .CO-MAIN-EVENT {
  position: absolute;
  top: 480px;
  left: 85px;
  width: 314px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .star-3 {
  position: absolute;
  top: 574px;
  left: 91px;
  width: 23px;
  height: 18px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 569px;
  left: 131px;
  width: 321px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .star-4 {
  position: absolute;
  top: 634px;
  left: 90px;
  width: 23px;
  height: 20px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 629px;
  left: 131px;
  width: 303px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

PAGE 3

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
      <img class="line" src="img/line-1.svg" />
      <div class="REGISTRATION-FORM">REGISTRATION&nbsp;&nbsp;FORM</div>
      <div class="rectangle"></div>
      <div class="text-wrapper">NAME</div>
      <div class="div"></div>
      <div class="text-wrapper-2">AGE</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">REFERENCE NO</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">MOBILE NO</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">EMAIL ID</div>
      <div class="ellipse"></div>
      <div class="text-wrapper-7">SUBMIT</div>
    </div>
  </body>
</html>


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


.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .line {
  position: absolute;
  top: 83px;
  left: 55px;
  width: 589px;
  height: 2px;
  object-fit: cover;
}

.android-medium .REGISTRATION-FORM {
  position: absolute;
  top: 45px;
  left: 187px;
  width: 553px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 112px;
  left: 55px;
  width: 175px;
  height: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 123px;
  left: 85px;
  width: 238px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  top: 199px;
  width: 175px;
  height: 55px;
  position: absolute;
  left: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 212px;
  left: 85px;
  width: 259px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  top: 282px;
  width: 175px;
  height: 66px;
  position: absolute;
  left: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 301px;
  left: 85px;
  width: 238px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-3 {
  top: 378px;
  width: 285px;
  height: 54px;
  position: absolute;
  left: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 393px;
  left: 85px;
  width: 343px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  top: 457px;
  width: 285px;
  height: 65px;
  position: absolute;
  left: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 471px;
  left: 85px;
  width: 299px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  top: 538px;
  width: 289px;
  height: 74px;
  position: absolute;
  left: 55px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 558px;
  left: 85px;
  width: 386px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse {
  position: absolute;
  top: 682px;
  left: 145px;
  width: 380px;
  height: 78px;
  background-color: #8d8bf0;
  border-radius: 190px / 39px;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 707px;
  left: 275px;
  width: 182px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


```

## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
