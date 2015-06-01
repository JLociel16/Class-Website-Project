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

Session #2
==========

We used CSS media queries to make Session #2 web page responsive.

Responsive Web Design
---------------------

Some examples of responsive web sites:
http://mediaqueri.es/

Guide on Media Queries
https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Media_queries

1) Create content
https://developers.google.com/web/fundamentals/getting-started/your-first-multi-screen-site/content?hl=en

Sample Content
http://googlesamples.github.io/web-fundamentals/samples/getting-started/your-first-multi-screen-site/addcontent.html

2) Make it Responsive
https://developers.google.com/web/fundamentals/getting-started/your-first-multi-screen-site/responsive?hl=en

Sample Responsive Web
http://googlesamples.github.io/web-fundamentals/samples/getting-started/your-first-multi-screen-site/fixingfirstbreakpoint.html

Principles of Site Design
https://developers.google.com/web/fundamentals/principles/index?hl=en

Animations
https://developers.google.com/web/fundamentals/look-and-feel/index?hl=en


Web Reference
=============

Fantastic slides for an intro to: HTML, CSS, Javascript and Git/Github
https://www.girldevelopit.com/materials

Slides on HTML5
http://slides.html5rocks.com/


Git and Github

1) Install Git command line
https://www.git-scm.com/download/

2) Create an account with Github
https://github.com/join

3) Setup git
https://help.github.com/articles/set-up-git/

4) Create a repository
https://help.github.com/articles/create-a-repo/

5) Short tutorials on using git
https://try.github.io/ (free)
http://gitreal.codeschool.com/ (Try Level 1, which is free)

Basic Web Page
--------------
You should also try out Front-End Foundations Level 1 on HTML (only level 1 is free)
https://www.codeschool.com/courses/front-end-foundations

If you need to go through basic Javascript, try out the following free class:
https://www.codeschool.com/courses/javascript-road-trip-part-1

Basic Mini Site
---------------
(This is for the more advanced participants who also understands Javascript and jquery)

You should also complete the free jquery class:
https://www.codeschool.com/courses/try-jquery


Google has a nice, comprehensive guide on building web sites:
https://developers.google.com/web/fundamentals/?hl=en
https://developers.google.com/web/fundamentals/principles/index?hl=en

The animation guide is awesome!
https://developers.google.com/web/fundamentals/look-and-feel/animations/