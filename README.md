# Ex08 Event Registration Web Application
## Date:21.03.2026

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
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">w</div>
      <img class="img" src="img/rectangle-2.svg" />
      <p class="div">Welcome to the Sports Event</p>
      <div class="text-wrapper-2">compete,perform,win.</div>
      <div class="rectangle-2"></div>
      <img class="rectangle-3" src="img/rectangle-4.svg" />
      <img class="rectangle-4" src="img/rectangle-5.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper-3">Register Now</div>
      <div class="text-wrapper-4">cricket</div>
      <div class="text-wrapper-5">basketball</div>
      <img class="text-on-a-path-2" src="img/text-on-a-path-2.svg" />
      <img class="text-on-a-path-3" src="img/image.svg" />
      <img class="text-on-a-path-4" src="img/text-on-a-path-5.svg" />
      <img class="text-on-a-path-5" src="img/text-on-a-path-3.svg" />
      <img class="text-on-a-path-6" src="img/text-on-a-path-4.svg" />
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">Football</div>
    </div>
  </body>
</html>


.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 2728px;
  min-height: 5129px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 69px;
  left: 115px;
  width: 2509px;
  height: 791px;
  aspect-ratio: 3.17;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 1171px;
  left: calc(50.00% - 1274px);
  width: 2504px;
  height: 1833px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 1634px;
  left: 500px;
  width: 45px;
  aspect-ratio: 0.67;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 5143px;
  left: 6148px;
  width: 1484px;
  height: 552px;
}

.android-medium .div {
  position: absolute;
  top: 1443px;
  left: 185px;
  width: 2357px;
  height: 1116px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-shadow: 0px 4px 7px #00000040;
  font-family: "Island Moments-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 300px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 2858px;
  left: 436px;
  width: 1813px;
  height: 69px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Jersey 10-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 3274px;
  left: 603px;
  width: 1450px;
  height: 338px;
  background-color: #da2427;
  border-radius: 100px;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 3778px;
  left: 792px;
  width: 1072px;
  height: 329px;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 4227px;
  left: 792px;
  width: 1072px;
  height: 283px;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 6705px;
  left: 6313px;
  width: 1072px;
  height: 338px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 3339px;
  left: 761px;
  width: 1153px;
  height: 214px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 150px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 3841px;
  left: 919px;
  width: 837px;
  height: 195px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 4287px;
  left: 975px;
  width: 725px;
  height: 176px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path-2 {
  position: absolute;
  top: 6705px;
  left: 6313px;
  width: 1072px;
  height: 288px;
}

.android-medium .text-on-a-path-3 {
  position: absolute;
  top: 6696px;
  left: 6320px;
  width: 1065px;
  height: 247px;
}

.android-medium .text-on-a-path-4 {
  position: absolute;
  top: 6715px;
  left: 6348px;
  width: 1022px;
  height: 288px;
}

.android-medium .text-on-a-path-5 {
  position: absolute;
  top: 6696px;
  left: 6313px;
  width: 1075px;
  height: 261px;
}

.android-medium .text-on-a-path-6 {
  position: absolute;
  top: 6696px;
  left: 6359px;
  width: 1050px;
  height: 288px;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 4659px;
  left: 799px;
  width: 1050px;
  height: 250px;
  background-color: #d9d9d9;
  border-radius: 200px;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 4743px;
  left: 975px;
  width: 725px;
  height: 116px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


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
      <img class="image" src="img/image-1.png" />
      <img class="rectangle" src="img/rectangle-6.svg" />
      <p class="text-wrapper">Register for the sports event</p>
      <div class="div"></div>
      <div class="text-wrapper-2">Name:</div>
      <img class="img" src="img/rectangle-9.svg" />
      <div class="text-wrapper-3">Email:</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-4">College Name:</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-5">Submit</div>
    </div>
  </body>
</html>


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 2673px;
  min-height: 5129px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 60px;
  left: 82px;
  width: 2509px;
  height: 791px;
  aspect-ratio: 3.17;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 1006px;
  left: 52px;
  width: 2574px;
  height: 483px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 736px;
  left: 471px;
  width: 1731px;
  height: 1022px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 200px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 2310px;
  left: 339px;
  width: 2002px;
  height: 255px;
  background-color: #d9d9d9;
  border-radius: 100px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 2112px;
  left: 212px;
  width: 710px;
  height: 121px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 150px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .img {
  position: absolute;
  top: 3041px;
  left: 360px;
  width: 1981px;
  height: 270px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 2865px;
  left: 346px;
  height: 95px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 150px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 3787px;
  left: 360px;
  width: 1981px;
  height: 267px;
  background-color: #d9d9d9;
  border-radius: 100px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 3627px;
  left: 414px;
  height: 95px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 150px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 4454px;
  left: 805px;
  width: 1106px;
  height: 270px;
  background-color: #d51c1c;
  border-radius: 100px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 4547px;
  left: 973px;
  width: 762px;
  height: 102px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}



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
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">Thank you for Registering</div>
      <div class="div">Event starts on 19/03/2026</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper-2">Sri vijay varshan.G(25008956)</div>
      <div class="rectangle-2"></div>
      <div class="support-contact-us">
        Support&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Contact
        us&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;About&nbsp;&nbsp;us
      </div>
    </div>
  </body>
</html>


.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 2673px;
  min-height: 5129px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 78px;
  left: 82px;
  width: 2509px;
  height: 791px;
  aspect-ratio: 3.17;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 923px;
  left: 249px;
  width: 2171px;
  height: 1709px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Just Me Again Down Here-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 2632px;
  left: 413px;
  height: 107px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 150px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 6836px;
  left: -592px;
  width: 2708px;
  height: 377px;
}

.android-medium .rectangle {
  position: absolute;
  top: 4844px;
  left: 0;
  width: 2673px;
  height: 214px;
  background-color: #2037cb;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 4844px;
  left: 328px;
  width: 2092px;
  height: 214px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 3497px;
  left: 152px;
  width: 2379px;
  height: 437px;
  background-color: #f01a1a;
  border-radius: 100px;
}

.android-medium .support-contact-us {
  position: absolute;
  top: 3622px;
  left: 308px;
  width: 2057px;
  height: 153px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Itim-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}





```

## OUTPUT:
![alt text](<Screenshot (38).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
