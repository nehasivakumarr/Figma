# Ex09 Event Registration Web Application
## Date:18/10/2025

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
Page 1
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="ecommerce">
      <div class="frame"></div>
      <div class="text-wrapper">CULINARY CARNIVAL</div>
      <div class="div-wrapper"><div class="div">REGISTER NOW</div></div>
      <p class="p">Feast,Fun and Flavours-All in One Bite!</p>
    </div>
  </body>
</html>

style.css

.ecommerce {
  overflow: hidden;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  display: flex;
  flex-direction: column;
}

.ecommerce .frame {
  margin-left: 41px;
  width: 292px;
  height: 79px;
  margin-top: 35px;
  background-image: url(./img/frame-1.png);
  background-size: cover;
  background-position: 50% 50%;
}

.ecommerce .text-wrapper {
  margin-left: 10px;
  width: 451px;
  height: 58px;
  margin-top: 29px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #a52a2a;
  font-size: 34px;
  letter-spacing: 0;
  line-height: 45.9px;
}

.ecommerce .div-wrapper {
  margin-left: 80px;
  width: 202px;
  height: 46px;
  margin-top: 30px;
  display: flex;
  background-color: #36aec6;
}

.ecommerce .div {
  margin-top: 12px;
  width: 152px;
  height: 27px;
  margin-left: 25px;
  font-family: "Linden Hill-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 27.0px;
  white-space: nowrap;
}

.ecommerce .p {
  margin-left: 35px;
  width: 305px;
  height: 19px;
  margin-top: 64px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: 18.9px;
  white-space: nowrap;
}

page2
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="checkout">
      <div class="frame"><div class="text-wrapper">EVENTS</div></div>
      <div class="div">
        <p class="STREET-TACON">
          STREET TACON SHOWDOWN<br /><br />CHILLI COOK-OFF<br /><br />BAKE-OFF<br /><br />BARBECUE BATTLE<br /><br />SPICY
          FOOD CHALLENGE<br /><br />COOKIE DECORATING CONTEST<br /><br />FOOD ART COMPETITION<br /><br />IRON CHEF-STYLE
          CHALLENGE<br /><br />DESSERT CARNIVAL<br /><br />DIY FOOD STATIONS
        </p>
        <div class="text"></div>
      </div>
    </div>
  </body>
</html>

style.css

.checkout {
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  display: flex;
  flex-direction: column;
  gap: 34px;
}

.checkout .frame {
  margin-left: 34px;
  width: 131px;
  height: 34px;
  margin-top: 34px;
  display: flex;
  background-color: #808080;
}

.checkout .text-wrapper {
  margin-top: 3px;
  width: 79px;
  height: 27px;
  margin-left: 26px;
  font-family: "Instrument Sans-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 27.0px;
  white-space: nowrap;
}

.checkout .div {
  margin-left: 89px;
  width: 270px;
  height: 408px;
  display: flex;
  flex-direction: column;
  gap: 126px;
  overflow: hidden;
}

.checkout .STREET-TACON {
  width: 265px;
  height: 448px;
  margin-top: 5px;
  font-family: "HeadlandOne-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 17.6px;
}

.checkout .text {
  margin-left: 213px;
  width: 1px;
  height: 36px;
  font-family: "HeadlandOne-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 17.6px;
}

page 3
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="booking">
      <div class="text-wrapper">FILL THE DETAILS</div>
      <div class="frame"><div class="div">NAME</div></div>
      <div class="div-wrapper"><div class="text-wrapper-2">REGISTER NO</div></div>
      <div class="div-wrapper"><div class="text-wrapper-3">DEPARTMENT</div></div>
      <div class="div-wrapper"><div class="text-wrapper-4">YEAR OF STUDYING</div></div>
      <div class="frame-2">
        <div class="text-wrapper-5">EVENT</div>
        <div class="frame-3"></div>
      </div>
      <div class="frame-4"><div class="text-wrapper-6">REGISTER</div></div>
    </div>
  </body>
</html>

style.css

.booking {
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  display: flex;
  flex-direction: column;
}

.booking .text-wrapper {
  margin-left: 20px;
  width: 155px;
  height: 27px;
  margin-top: 38px;
  font-family: "Gupter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 27.0px;
  white-space: nowrap;
}

.booking .frame {
  margin-left: 35px;
  width: 256px;
  height: 51px;
  margin-top: 82px;
  display: flex;
  background-color: #fffffff5;
}

.booking .div {
  margin-top: 12px;
  width: 61px;
  margin-left: 19px;
  color: #000000;
  height: 32px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}

.booking .div-wrapper {
  margin-left: 35px;
  width: 256px;
  height: 51px;
  margin-top: 31px;
  display: flex;
  background-color: #fffffff5;
}

.booking .text-wrapper-2 {
  margin-top: 10px;
  width: 140px;
  height: 32px;
  margin-left: 14px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}

.booking .text-wrapper-3 {
  margin-top: 10px;
  width: 142px;
  height: 32px;
  margin-left: 13px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}

.booking .text-wrapper-4 {
  margin-top: 10px;
  width: 203px;
  height: 32px;
  margin-left: 11px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}

.booking .frame-2 {
  margin-left: 35px;
  width: 256px;
  height: 51px;
  margin-top: 31px;
  display: flex;
  gap: 117px;
  background-color: #fffffff5;
  overflow: hidden;
}

.booking .text-wrapper-5 {
  margin-top: 10px;
  width: 68px;
  height: 32px;
  margin-left: 21px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}

.booking .frame-3 {
  margin-top: 44px;
  width: 256px;
  height: 47px;
  background-color: #fffffff5;
}

.booking .frame-4 {
  margin-left: 163px;
  width: 183px;
  height: 52px;
  margin-top: 81px;
  display: flex;
  background-color: #347da4;
}

.booking .text-wrapper-6 {
  margin-top: 10px;
  width: 102px;
  margin-left: 40px;
  color: #ffffff;
  height: 32px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 32.4px;
  white-space: nowrap;
}


## OUTPUT:
![alt text](<Screenshot (41).png>)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
