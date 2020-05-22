---
title: Partners
permalink: /community/partners/
---
<style>
.mySlides {display:none;}
</style>
<h2 class="w3-center">Manual Slideshow</h2>

<div class="w3-content w3-display-container">
  <img class="mySlides" src="/images/facilities/facilities-and-equipment/DS1.jpg" style="width:100%">
  <img class="mySlides" src="/images/facilities/facilities-and-equipment/DSC03115Draft-electronic.jpg" style="width:100%">
  <img class="mySlides" src="/images/facilities/facilities-and-equipment/DSC03178Draft-bench-tools.jpg" style="width:100%">
  <img class="mySlides" src="/images/facilities/facilities-and-equipment/DT2.jpg" style="width:100%">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
