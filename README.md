# hslider
A simple, clean, beautiful and robust jQuery plugin to create responsive image slider.

# Demo:
http://codeinn.co/demo/hslider

# Use: 

## Html : 
```html
<div class="hsldr-container">
  	<figure>
  		<img src="images/image1.jpg" />
  		<figcaption>Car in the snow</figcaption>
  	</figure>
  	<figure>
  		<img src="images/Image2.jpg" />
  		<figcaption>People surfing</figcaption>
  	</figure>
</div>
```


## Javascript:
```html
<script src="js/jquery-2.2.1.min.js"></script>
<script src="js/imagesloaded.pkgd.min.js"></script>
<script src="js/jquery.hslider.js"></script>

<script type="text/javascript">       
	$( document ).ready(function() { 
		$( ".hsldr-container" ).hslider({
		  navBar: true,
		  auto: true,
		  delay: 4000
		});
	});	
</script>  
```

## Configuration Variables:
```config
  navBar: true/false ( default : false ) => whether to show navigation bar or not
  auto: true/false ( default : false ) => whether to move the slide automatically or not
  delay: time in ms ( default: 1000 ms )  => the time delay between auto move
```  
