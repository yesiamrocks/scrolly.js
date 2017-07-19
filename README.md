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
 

    <script type="text/javascript" src="scrolly/scrolly.js">
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