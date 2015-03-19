Spectrum
========

A dynamic &amp; colourful jQuery plugin perfect for adding subtle colour transitions to your web applications. View Spectrum live at www.andreacrofts.codes/spectrum.

### First Things First
Download jquery.spectrum.js and place the file into the JavaScript folder in your directory. The root path should look something like this:

```
mainFolder > js > jquery.spectrum.js
```

### Getting Started
Include jQuery and the jquery.spectrum.js script in your HTML document, before the closing body tag, as demonstrated below. Note that the plugin script must be placed after the jQuery script, and must be properly linked from your directory (example, js/jquery.spectrum.js).
  
  
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script> 
<script src="js/jquery.spectrum.js"></script> 
</body>
```

### Initialization
Paste the following code into your primary JavaScript file (for example, main.js) to initialize jquery.spectrum.js and to call the function:

```
$(document).ready(function(){
	$('.header').spectrum();
});
```

### Customization
To change the colours in the spectrum, substitute the existing RGB values in the jquery.spectrum.js file to your RGB values of choice.

```
var colourArray = [{
	src: 'colour1',
	colour: 'rgb(252,115,49)'
}];
```

### CSS Time
Insert the following code into your CSS file (for example, style.css).

```
.spectrumHeader {
	transition: background-color 4s ease;
}
```

### The Final Touch
Ensure that the corresponding HTML element (in this case, the header) has an id of spectrumPlugin and a class of spectrumHeader.

```
<header id="spectrumPlugin" class="spectrumHeader">
```

========

That's it! Enjoy your spectrum, and go wrap the interwebz in chroma. 
If you'd like to improve this plugin, please feel free to fork it ;)
