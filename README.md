# Ex09 Event Registration Web Application

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
## home.html
```python
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="HOME">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="img" src="img/20250620065225saveetha-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENT REGISTER</div>
      <div class="frame"></div>
      <div class="rectangle"></div>
      <div class="group"><div class="div">REGISTER</div></div>
      <div class="div-wrapper"><div class="text-wrapper-2">LOGIN</div></div>
      <img class="download" src="img/download-2.png" />
    </div>
  </body>
</html>
```
## style.css
```python
.HOME {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.HOME .sec-logo {
  position: absolute;
  top: 1px;
  left: 0;
  width: 440px;
  height: 89px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.HOME .img {
  position: absolute;
  top: 90px;
  left: 0;
  width: 440px;
  height: 440px;
  aspect-ratio: 1;
  object-fit: cover;
}

.HOME .text-wrapper {
  position: absolute;
  top: 553px;
  left: calc(50.00% - 185px);
  font-family: "Dangrek-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.HOME .frame {
  position: absolute;
  top: 643px;
  left: 32px;
  width: 375px;
  height: 68px;
  background-color: #4ea3cb;
}

.HOME .rectangle {
  position: absolute;
  top: 752px;
  left: calc(50.00% - 188px);
  width: 375px;
  height: 68px;
  background-color: #4ea3cb;
}

.HOME .group {
  top: 752px;
  left: calc(50.00% - 66px);
  width: 134px;
  position: absolute;
  height: 68px;
  display: flex;
  justify-content: center;
}

.HOME .div {
  width: 132px;
  height: 68px;
  margin-left: -2px;
  font-family: "Dangrek-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.HOME .div-wrapper {
  top: 643px;
  left: calc(50.00% - 49px);
  width: 100px;
  position: absolute;
  height: 68px;
  display: flex;
  justify-content: center;
}

.HOME .text-wrapper-2 {
  width: 98px;
  height: 68px;
  margin-left: -2px;
  font-family: "Dangrek-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.HOME .download {
  position: absolute;
  top: 820px;
  left: 149px;
  width: 142px;
  height: 136px;
  aspect-ratio: 1;
  object-fit: cover;
}
```
## events.html
```python
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="EVNTS">
      <img class="sports-transparent" src="img/sports-transparent-1.png" />
      <div class="CRICKET-FOOTBALL">
        CRICKET<br />FOOTBALL<br />KABADDI<br />VOLLEYBALL<br />BADMINTON<br />BASKETBALL<br />ATHLETICS <br />TABLE
        TENNIS<br />CHESS<br />THROWBALL
      </div>
      <div class="text-wrapper">SPORTS EVENTS</div>
      <img class="download" src="img/download-3.png" />
      <div class="rectangle"></div>
    </div>
  </body>
</html>
```
## style.css
```python
.EVNTS {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.EVNTS .sports-transparent {
  position: absolute;
  top: 391px;
  left: 40px;
  width: 330px;
  height: 263px;
  aspect-ratio: 1.26;
  object-fit: cover;
}

.EVNTS .CRICKET-FOOTBALL {
  position: absolute;
  top: calc(50.00% - 358px);
  left: calc(50.00% - 94px);
  width: 188px;
  font-family: "Dangrek-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.EVNTS .text-wrapper {
  position: absolute;
  top: 30px;
  left: calc(50.00% - 162px);
  width: 323px;
  font-family: "David Libre-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.EVNTS .download {
  position: absolute;
  top: 814px;
  left: 148px;
  width: 142px;
  height: 142px;
  aspect-ratio: 1;
  object-fit: cover;
}

.EVNTS .rectangle {
  position: absolute;
  top: 743px;
  left: 126px;
  width: 4px;
  height: 1px;
  background-color: #d9d9d9;
}
```
## register.html
```python
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="REGISTER">
      <div class="text-wrapper">EVENT REGISTERATION FORM</div>
      <div class="div">FILL THE DETAILS</div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="rectangle-9"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="text-wrapper-3">Email ID</div>
      <div class="text-wrapper-4">REGISTER</div>
      <div class="text-wrapper-5">Events To Register</div>
      <div class="text-wrapper-6">Mobile Number</div>
      <div class="text-wrapper-7">Deparment</div>
      <div class="text-wrapper-8">Register Number</div>
      <div class="text-wrapper-9">Gender</div>
      <img class="download" src="img/download-1.png" />
      <div class="text-wrapper-10">Age</div>
      <img class="sports-transparent" src="img/sports-transparent-2.png" />
    </div>
  </body>
</html>
```
## style.css
```python
.REGISTER {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.REGISTER .text-wrapper {
  position: absolute;
  top: 44px;
  left: calc(50.00% - 199px);
  font-family: "David Libre-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.REGISTER .div {
  position: absolute;
  top: 93px;
  left: 22px;
  font-family: "David Libre-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.REGISTER .rectangle {
  top: 125px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-2 {
  top: 692px;
  left: 91px;
  background-color: #000000;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-3 {
  top: 468px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-4 {
  top: 419px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-5 {
  top: 370px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-6 {
  top: 321px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-7 {
  top: 272px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-8 {
  top: 223px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .rectangle-9 {
  top: 174px;
  left: 25px;
  background-color: #d9d9d9;
  position: absolute;
  width: 258px;
  height: 32px;
}

.REGISTER .text-wrapper-2 {
  position: absolute;
  top: 130px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-3 {
  position: absolute;
  top: 421px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-4 {
  position: absolute;
  top: 695px;
  left: 171px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-5 {
  position: absolute;
  top: 470px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-6 {
  position: absolute;
  top: 372px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-7 {
  position: absolute;
  top: 325px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-8 {
  position: absolute;
  top: 275px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .text-wrapper-9 {
  position: absolute;
  top: 179px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .download {
  position: absolute;
  top: 814px;
  left: 149px;
  width: 142px;
  height: 142px;
  aspect-ratio: 1;
  object-fit: cover;
}

.REGISTER .text-wrapper-10 {
  position: absolute;
  top: 225px;
  left: 25px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.REGISTER .sports-transparent {
  position: absolute;
  top: 385px;
  left: 43px;
  width: 330px;
  height: 263px;
  aspect-ratio: 1.26;
  object-fit: cover;
}
```
## thankyou.html
```python
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="THANK-YOU">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="div">we are all eagerly waiting for your participation in the sports events</p>
      <div class="CONTACT-US">CONTACT US : 9782400165<br />EMAIL:saveethaeng@gmaiul.com</div>
      <img class="img" src="img/20250620065225saveetha-1.png" />
    </div>
  </body>
</html>
```
## style.css
```python
.THANK-YOU {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.THANK-YOU .sec-logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 89px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.THANK-YOU .text-wrapper {
  position: absolute;
  top: 191px;
  left: calc(50.00% - 119px);
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.THANK-YOU .div {
  position: absolute;
  top: 315px;
  left: 23px;
  width: 393px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.THANK-YOU .CONTACT-US {
  position: absolute;
  top: 875px;
  left: 0;
  width: 440px;
  font-family: "Copse-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.THANK-YOU .img {
  position: absolute;
  top: 427px;
  left: 0;
  width: 440px;
  height: 440px;
  aspect-ratio: 1;
  object-fit: cover;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-11-23 182028.png>)
![alt text](<Screenshot 2025-11-23 182043.png>)
![alt text](<Screenshot 2025-11-23 182049.png>)
![alt text](<Screenshot 2025-11-23 182056.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
