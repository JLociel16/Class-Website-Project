Session #1
==========

It's been a fast paced introduction to the three main pieces for web page development: html, css, javascript.
Jquery is a Javascript library that allows easy web page manipulation.

```
HTML is within the <html> tags.
CSS is within the <style> tag.
Javascript is within the <script> tags.
```

The full example is posted in the following jsbin:
[jsbin](http://jsbin.com/kuzavalava/1/edit?html,output)


Some other reference links:
[thimble](https://thimble.webmaker.org/)

jquery:
[download](http://jquery.com/download/)
[effects api](https://api.jquery.com/category/effects/)

Reference for web: Mozilla Developer Network
[MDN] (https://developer.mozilla.org/en-US/)

[HTML reference] (https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
[CSS reference] (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
[Javascript] (https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[Google Fonts] (https://www.google.com/fonts)

[Web colors] (http://en.wikipedia.org/wiki/Web_colors)

For the next session, you should download and install Sublime Text 3, which will be our professional web editor.
[download] (http://www.sublimetext.com/3)

You should also signup for a Github.com account. Github will allow you to keep track of your projects and ease future collaboration.
[join github] (https://github.com/join)

3) You should complete a greeting card for mother's day (or different web page project)

4) We'll build a mini-site of 3 pages. The theme will be amazing vacation spots (either that you visited or would like to visit).

Each page should contain a selection of 3 images with some titles and description of the places. Bring your own photos or google around.


```html
<!doctype html>
<html>
  
  <head>
    <meta charset="utf-8">
    <title>Your Awesome Webpage created on Mon, May 4 2015 10:45 PM</title>
    
<link href='https://fonts.googleapis.com/css?family=Lobster' rel='stylesheet' type='text/css'>
    
    <style>
      body {
        background-image: url(https://thumbs.dreamstime.com/x/funny-tiger-cartoon-24674849.jpg);
      }
      h2 {
        font-family: 'Lobster', cursive;
        color: orange;
        background-color: lime;
        text-align: center;
        border: 4px solid red;
        border-radius: 10px;
      }
    </style>
  </head>
  
  <body>
    
    <h2>Little Tiger</h2>
    <p>Hello  Bronx</p>
    
    <img src="http://thumbs.dreamstime.com/x/funny-tiger-cartoon-24674849.jpg" width="100" border="10" id="tiger">
    
    <iframe width="360" height="215" src="https://www.youtube.com/embed/kJ2pQ_Vhh58" frameborder="0" allowfullscreen></iframe>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
    
    <script>
  
      var showing = true;
    
      $('h2').on('click', function() {
        if (showing) {
          $('#tiger').fadeOut();
        }
        else {
          $('#tiger').fadeIn();
        }
  
        showing = !showing;
      });
 
    </script>
    
  </body>
</html>

```