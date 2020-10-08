<br />
<p align="center">
 <a href="https://github.com/Usagib/stylofw">
   <img src="img/logo-01.png" alt="Logo" style="width: 50%;">

 </a>

 <h3 align="center">Grid-based framework (similar to bootstrap) that includes some basic functionality necessary to build a website.</h3>

 <p align="center">
  Stylofw allows us to create complex responsive layouts using just a few classes on our HTML with 3 predefined breakpoints for mobile, tablet, and desktop   
   <br />
 </p>
</p>

## Table of Contents

* [About the Project](#about-the-project)
* [How to install](#how-to-install)
* [How to have Stylo](#how-to-have-stylo)
* [Stylo Working](#stylo-working)
* [Screenshots](#screenshots)
* [Contact](#contact)

## About The Project

RESTful API developed using Ruby on Rails, Json Web Token and bcrypt to ensure log security and deployed to heroku, Frontend built with React / Redux and bootstrap.

## How to install
- copy css/stylo.css to your project
- import stylo to your html file
- start using any of stylo's pre-defined classes

## How to have Stylo
Basic Stylofw structure:

> <div class="stylorow">
    <div class="stylo-1">
      <div class="st1-1-1">
        <span>100% width in all viewport sizes</span>
     </div>
   </div>
> </div> 

- .stylorow {Creates a row with auto height}
- .stylo-1 {Creates an entire width (100%) wrapper}
- .stylo-2 {Creates a half width (50%) wrapper}
- .stylo-3 {Creates a third width (33%) wrapper}
- .stylo-4 {Creates a quarter width (25%) wrapper}**

**stylo-1 to stylo-4 help us divide the row in as many wrappers as we like with auto height**

### stLG-MD-SM responsive classes

st classes had the following sintax:
- **.st[number of divisions in large viewports]-[number of divisions in medium viewports]--[number of divisions in small viewports]**

ej:
- **.st4-2-1**
1. the following class will be 25% (/4) width in 1024px screens
2. the following class will be 50% (/2) width in 740px screens
3. the following class will be 100% (/1) width in 420px screens
4. containers following the same class will auto-wrap in each breakpoint

## Stylo Working
ej:
> <div class="stylorow">
        <div class="stylo-1 stylo-gutter">
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/bg2-01.png" alt="">
          </div>
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/b2-01.png" alt="">
          </div>
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/b2-01.png" alt="">
          </div>
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/bg2-01.png" alt="">
          </div>
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/b2-01.png" alt="">
          </div>
          <div class="st3-2-1 st-bgblack">
            <h1 class="title">st3-2-1</h1>
            <img class="showcaseimg" src="img/b2-01.png" alt="">
          </div>
        </div>
>  </div>

## Screenshots

### large screens
![screenshot1](img/screen1.png)

### medium screens
![screendhot2](img/screen2.png)

### small screens
![screenshot3](img/screen3.png)

### Use st classes to make your own responsive layout!

## Additional classes
- .align {align text to the center}
- .st-bgblack {adds black background to container}
- .fixed {fix container position}
- .title {Mansalva font with 1.5rem size}
- .st-bg {adds stylo background 1 to container}
- .st-bg1 {adds stylo background 2 to container}
- .st-bg2 {adds stylo background 3 to container}
- .mg-[sm md lg]-[left right top bottom]-[0 1 2 3] {adds margin with a direct size on a selected viewport} **ej .mg-lg-left-3**
- .mg-[sm md lg]-[size 0-3] {adds all margins on a selected viewport} **ej .mg-sm-3**
- .pd-[sm md lg]-[left right top bottom]-[0 1 2 3] {adds padding with a direct size on a selected viewport} **ej .pd-lg-left-3**
- .pd-[sm md lg]-[size 0-3] {adds all paddings on a selected viewport} **ej .pd-sm-3**
- .float[left right center] {applies float property} **ej. .floatright**
- .clear[left right both] {applies clear to float} **ej. clearleft**
- .flex {applies flex property to the container}
- .hidden {hides display}
- .[lg md sm]-none { sets display property to none for selected viewport} **ej md-none**
- .align-[h v]-[left right top bottom center] {sets the vertical or horizontal alignment} **ej. align-v-bottom**
- .st-stbg-[1-10] {sets stylo custom color scheme background and font from 1-10}
- .aligntext-[left right center] {aligns text}
- .fontsize-[1-5] {sets the font size} **ej .fontsize-4**
- .fontbold {sets font-weight to bold}
- .fontnormal {sets font-weight to normal}
- .fontlight {sets font-weight to light}
- .border[top bottom left right] {sets border to a specific position}
- .border {sets all borders to normal solid}
- .border[top bottom left right]-[light bold] {sets border to a specific position lighter or bolder}
- .border-[light bold] {sets all borders to light or bold solid}
- .borderround {sets round border corner}
- .bordercircle {defines the border as a circle}
- .stylo-gutter {adds gutters to all divs on the container}
- .he1 to .he5 {defines fixed height 50px to 500px}
- .nowrap {avoids row wrapping}

## Contact

* Eduardo Bonilla Cáceres - eduardobonillac@gmail.com
* [My Portfolio](https://usagib.surge.sh)
* [My Twitter](https://twitter.com/UsagiBonilla)


## Show your support

Give a ⭐️ if you like this project!



