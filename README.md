# Scrolly.js
You can create a rich and **storytelling animated web pages** with up and down scrolling 👋
Visitors can feel the page with scrolling and it has a really minimal learning curve.

Scrolly.js plugin is proudly created and maintained by [cssanimation.io](http://cssanimation.io/) team, that a web based open source animation library by a team of **passionate web animation lover**.

We developed the most easier way to work with scroll animation, Just use `data-scrolly-top` and `data-scrolly-down` attribute to quickly build powerful templates of your own.

# How To Use It?
**Include Library:** To get started, just download `scrolly.js` and `cssanimation.css` [download](http://cssanimation.io/). Now include the `cssanimation.css` stylesheet into the head and add `scrolly.js` scripts before the `body` tag
``` html
<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" href="scrolly/cssanimation.css"> 
</head>
<body> 
 

    <script type="text/javascript" src="scrolly/scrolly.js"></script>
</body>
</html>
```

**Activate Now:** when done with including stuff, time to activate scrolly.js
``` html
<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" href="scrolly/cssanimation.css"> 
</head>
<body> 
 

    <script type="text/javascript" src="scrolly/scrolly.js"></script>
    <script>
       window.onload = function() {
          scrolly();
       }; 
    </script>
</body>
</html>
```


**Define DOWN Animation:** Once you've done that, define animation class name in `data-scrolly-down` attribute like the example below to the element **that you want to animate when the page scroll to DOWN**. here we are using `blurInTop`.

``` html
<div data-scrolly-down="blurInTop"> 
     it's easy to do 
</div>
</html>
```

# Why Scrolly.js
Scrolly JS is efficient and flexible JavaScript library for building an interactive and attractive animation with scrolling. Fully responsive, lightweight, powerful and flexible pure JavaScript scroll animation library.

### Animated by CSS
Your imagination can be real. Just imagine and implement your own animation effect with this platform.

### Flexibility and extendibility
Easy-going installation and flexible scroll animation library that have insignificant production time. The platform is developer friendly and extendable.

### Support for responsive
This is 100% responsive and ready for all devices with any screen resolutions.

### Lightweight
Just a 12KB file which is really lightweight to use any of your projects.

### Easy to use
A Very easiest scroll animation library which has extensive features to build any scroll animation as you want.

### No dependency
Plug and play and ready to implement. No dependency with any third party JavaScript plugin, framework or library.
