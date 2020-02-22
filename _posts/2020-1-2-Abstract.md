---
layout: post
title: abstract
featured-img: abstract
mathjax: true
summary: " "
---


<html>
<head>
<style>
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  background-color: white;
  grid-column-gap: 20px;
  padding: 10px;
}
.grid-image {
  background-color: blue;
  border: 1px solid white;
  padding: 0px;
  font-size: 30px;
  text-align: center;
  align-self: center;
  justify-self: center;
}
.grid-caption {
  background-color: white;
  border: 1px solid white;
  padding: 10px;
  margin-bottom:15px;
  font-size: 15px;
  text-align: center;
}
</style>
</head>
<body>

<!-- 
INSTRUCTIONS: 
To add new rows, insert all these lines: 


To add "sold" tag, insert this text immediately after the name of the painting:

<span style="color:red;"> - sold</span>


 -->

<div class="grid-container">
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/blueandgreen1.jpg">
  </div>
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/blueandgreen2.jpg">
  </div>
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/explosion.jpg">
  </div>  
  <div class="grid-caption">Blue and green 1<span style="color:red;"> - sold</span><br>9x9"</div>
  <div class="grid-caption">Blue and green 2<br>9x9"</div>
  <div class="grid-caption">Explosion<br>9x17"</div>  
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/jardin.jpg">
  </div>
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/redandblue1.jpg">
  </div>
  <div class="grid-image">
    <img src="{{site.url}}{{site.baseurl}}/assets/img/posts/abstract/redandblue2.jpg">
  </div>  
  <div class="grid-caption">Garden of Eden<span style="color:red;"> - sold</span><br>9x17"</div>
  <div class="grid-caption">Red and blue 1<br>9x9"</div>
  <div class="grid-caption">Red and blue 2<br>9x9"</div>  

  <!-- INSERT NEW ROWS HERE AS NECESSARY:  -->



  <!-- DO NOT INSERT ANYTHING AFTER THIS POINT -->

</div>

</body>
</html>
