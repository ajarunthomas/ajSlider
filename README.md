# ajSlider
Image and Content Slider jQuery Plugin
Developed by Arun Thomas
www.ajarunthomas.com
##USAGE
###Step 1 : HTML
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
###Step 2 : Initialize jQuery
```
jQuery(window).load(function() {
    $('#ajSlider').ajSlider(3000);
});
```
where 3000 is the interval between each slide
### more options
```
jQuery(window).load(function() {
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
