# ajSlider
Image and Content Slider jQuery Plugin
Developed by Arun Thomas
www.ajarunthomas.com
<br>
<br>
<a href="http://www.ajarunthomas.com/jquery/ajSlider/demo/" target="_blank" style="text-decoration:none">Demo</a>
<a download href="http://www.ajarunthomas.com/files/ajSlider.js" style="text-decoration:none">Download</a>
##USAGE
###Step 1 : Include js
```
<script type="text/javascript" src="js/jquery-1.12.0.min.js"></script>
<script type="text/javascript" src="js/ajSlider.js"></script>
```
###Step 2 : HTML
```
<div id="ajSlider">
  <img src="images/1.jpg" />
  <img src="images/2.jpg" />
  <img src="images/3.jpg" />
  <img src="images/4.jpg" />
  <img src="images/5.jpg" />
  
  <a>Text 1</a>
  <a>Text 2</a>
  <a>Text 3</a>
  <a>Text 4</a>
  <a>Text 5</a>
</div>
```
###Step 3 : Initialize jQuery
```
$( document ).ready(function() {
    $('#ajSlider').ajSlider(3000);
});
```
where 3000 is the interval between each slide
### more options
```
$( document ).ready(function() {
    $('#ajSlider').ajSlider(3000,{
		"slideshow":"disable", //disable or enable the slideshow
		"width":"100%", //width of slider
		"height":"100%", //height of slider
		"activeBullet":"red", //color of the active bullet
		"inactiveBullet":"orange", //color of inactive bullet
		"textPosition":"30%", //position of text from top
		"textSize":"60px" //font size of the text
		});
});
```
