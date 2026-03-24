# Ex08 Event Registration Web Application
## Date:20-03-2026

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
page 1
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
    <div class="iphone">
      <img
        class="free-flat-color"
        src="img/free-flat-color-physical-background-images-flat-sports-h5-background-photo-background-PNG-and-vectors-1.png"
      />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">REGISTER</div>
      <div class="div"></div>
      <div class="text-wrapper-2">SPORTS DAY EVENTS</div>
      <div class="text-wrapper-3">SIGN IN</div>
    </div>
  </body>
</html>
style.css
.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .free-flat-color {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone .rectangle {
  top: 385px;
  height: 57px;
  position: absolute;
  left: 57px;
  width: 273px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 402px;
  left: 140px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  top: 464px;
  height: 61px;
  background-color: #ff0000;
  position: absolute;
  left: 57px;
  width: 273px;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 129px;
  left: 87px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 480px;
  left: 140px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

page 2
events.html
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
    <div class="iphone">
      <img class="figma" src="img/figma-2-1.png" />
      <div class="text-wrapper">FOOTBALL</div>
      <div class="div">CRICKET</div>
      <div class="text-wrapper-2">LIST OF EVENTS</div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">THROW BALL</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">VOLLEY BALL</div>
      <div class="pagination-next">
        <div class="text-wrapper-5">Next</div>
        <img class="arrow-right" src="img/arrow-right.svg" />
      </div>
    </div>
  </body>
</html>
style.css
.iphone {
  background-color: #ffffff80;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 344px;
  left: 112px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 267px;
  left: 120px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 144px;
  left: 85px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  top: 264px;
  left: 89px;
  width: 155px;
  height: 33px;
  position: absolute;
  background-color: #d9d9d9;
  opacity: 0.5;
}

.iphone .rectangle-2 {
  top: 344px;
  left: 89px;
  width: 155px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
  opacity: 0.5;
}

.iphone .rectangle-3 {
  top: 423px;
  left: 89px;
  width: 155px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
  opacity: 0.5;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 426px;
  left: 97px;
  opacity: 0.5;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-4 {
  top: 503px;
  left: 96px;
  width: 148px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
  opacity: 0.5;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 506px;
  left: 102px;
  width: 136px;
  opacity: 0.5;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .pagination-next {
  display: flex;
  width: 121px;
  height: 51px;
  align-items: center;
  justify-content: center;
  gap: var(--size-space-200);
  padding: var(--size-space-200) var(--size-space-300) var(--size-space-200)
    var(--size-space-300);
  position: absolute;
  top: 582px;
  left: 101px;
  border-radius: var(--size-radius-200);
}

.iphone .text-wrapper-5 {
  position: relative;
  width: fit-content;
  font-family: var(--single-line-body-base-font-family);
  font-weight: var(--single-line-body-base-font-weight);
  color: var(--color-text-default-default);
  font-size: var(--single-line-body-base-font-size);
  letter-spacing: var(--single-line-body-base-letter-spacing);
  line-height: var(--single-line-body-base-line-height);
  white-space: nowrap;
  font-style: var(--single-line-body-base-font-style);
}

.iphone .arrow-right {
  position: relative;
  width: 16px;
  height: 16px;
}

page 3
register.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="figma" src="img/figma-3-1.png" />
      <div class="text-wrapper">REGISTRATION</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">NAME</div>
      <div class="text-wrapper-3">AGE</div>
      <div class="text-wrapper-4">DEPARTMENT</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-5">EVENT</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-6">CONFIRM</div>
    </div>
  </body>
</html>
style.css
.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.56;
}

.iphone .text-wrapper {
  position: absolute;
  top: 128px;
  left: 116px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  top: 233px;
  left: 110px;
  width: 165px;
  height: 41px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .div {
  top: 347px;
  left: 110px;
  width: 165px;
  height: 37px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .rectangle-2 {
  top: 441px;
  left: 184px;
  width: 165px;
  height: 42px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 239px;
  left: 31px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 354px;
  left: 42px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 447px;
  left: 11px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-3 {
  top: 540px;
  left: 110px;
  width: 157px;
  height: 37px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 544px;
  left: 31px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-4 {
  top: 680px;
  left: 117px;
  width: 158px;
  height: 60px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 695px;
  left: 141px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

page 4
thanks.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="messi" src="img/messi-1.png" />
      <div class="text-wrapper">THANK YOU FOR REGISTERING</div>
      <div class="div">HAVE A GOOD DAY</div>
      <div class="frame"><div class="rectangle"></div></div>
      <p class="element-manorajapriyan">
        © 2026 Manorajapriyan <br />
        All Rights Reserved <br />Home | About | Contact | Help <br />Follow us: Instagram | Twitter
      </p>
    </div>
  </body>
</html>
style.css
.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .messi {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 162px;
  left: 38px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 278px;
  left: 97px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .frame {
  display: flex;
  flex-direction: column;
  width: 413px;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 10px;
  position: absolute;
  top: 699px;
  left: -10px;
}

.iphone .rectangle {
  position: relative;
  align-self: stretch;
  width: 100%;
  height: 143px;
  background-color: #d9d9d9;
  border: 1px solid;
  border-color: #0f0707;
  box-shadow: 0px 4px 4px #00000040;
  opacity: 0.6;
}

.iphone .element-manorajapriyan {
  position: absolute;
  top: 723px;
  left: calc(50.00% - 170px);
  width: 339px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

```



## OUTPUT:
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (45).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
