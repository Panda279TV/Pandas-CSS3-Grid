# Pandas CSS3 Grid System
### I have tried many grid systems or grid frameworks. Many were too big or too confusing. That's exactly why I wrote my own CSS Grid. It is minimalistic, super simple and has only the most important functions. 

---
## Demo

[Link](https://github.com/Panda279TV/Panda-CSS3-Grid/blob/master/pandas-grid-demo.gif)

![](pandas-grid-demo.gif)

The demo shows the HTML file. You can download this and the CSS and have a look at it again.

---

## Statistics
- Minimalistic
- Small
- Simple
- Normal or Responsive Grid
- Very good and practical padding distances
- No CSS `!Important`
- Only about 2200 bytes

---

## Introduction
My grid has 12 columns. No matter the size of the browser, each of these columns will always have an equal width.

Each column is width: 8.3333333333333333333%, that result then times 12 gives the width: 100%.

#### In order to use the grid correctly, a row must be around a column.

    <div class="row">
      <div class="col s-1">1</div>
      <div class="col s-1">2</div>
      <div class="col s-1">3</div>
      <div class="col s-1">4</div>
      <div class="col s-1">5</div>
      <div class="col s-1">6</div>
      <div class="col s-1">7</div>
      <div class="col s-1">8</div>
      <div class="col s-1">9</div>
      <div class="col s-1">10</div>
      <div class="col s-1">11</div>
      <div class="col s-1">12</div>
    </div> 

---

## Container
The container class is not strictly part of the grid but is important in laying out content. It allows you to center your page content. The container class is set to 70% of the window width (responsive 70% to 90%). It helps you center and contain your page content. I use the container to contain my body content.

To add a container just put your content inside a <div> tag with a container class. Here's an example of how your page might be set up.
  
    <div class="container">
      <!-- Page Content goes here -->
    </div> 

---

## Responsive Layouts
Above i showed you how to layout elements using my grid system. Now i show you how to design your layouts so that they look great on all screen sizes.

Screen Sizes

| Table | Mobile Devices <= 600px | Tablet Devices > 601px | Desktop Devices > 992px | Large Desktop Devices > 1281px |
|:-----|:----:|:-----:|:-----:|:-----:|
| Class Prefix | .s- | .m- | .l- | .xl- |
| Number of Columns | 12 | 12 | 12 | 12 |
| Container Width | 90% | 83% | 76% | 70% |

Adding Responsiveness
In the previous examples, i only defined the size for small screens using "col s-12". This is fine if i want a fixed layout since the rules propagate upwards.

By just saying s-12, we are essentially saying "col s-12 m-12 l-12 xl-12". But by explicitly defining the size we can make our website more responsive.

---
