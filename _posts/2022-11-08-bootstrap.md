---
layout: post
title: "Bootstrap"
date: 2022-11-08T11:04:44+05:30
categories: tutorial
---
### What is Bootstrap?
Bootstrap is a free and open-source tool collection for creating responsive websites and web applications. It is the most popular HTML, CSS, and JavaScript framework for developing responsive, mobile-first websites. Nowadays, the websites are perfect for all browsers (IE, Firefox, and Chrome) and for all sizes of screens (Desktop, Tablets, Phablets, and Phones). All thanks to Bootstrap developers – Mark Otto and Jacob Thornton of Twitter, though it was later declared to be an open-source project.

### Why we use Bootstrap?
By using this framework we can easily manipulate the styling of any web page, like font style, text color, background color, flex, grid system, etc. Bootstrap Vesrion 4 & Vesrion 5 are the most popular versions. There are lots of other CSS frameworks like Tailwind CSS, Bulma, and Foundation but among them, this framework is the most popular because of below mentioned features:

+ It is Faster and Easier way for Web-Development.
+ It creates Platform-independent web-pages.
+ It creates Responsive Web-pages.
+ It designs responsive web pages for mobile devices too.
+ It is a free and open-source framework available on www.getbootstrap.com
+ How to use Bootstrap on the webpage: There are two ways to include Bootstrap in the website.

#### Include Bootstrap through CDN links:
```html
<!– CSS library –>
<link rel=”stylesheet” href=”https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css” integrity=”sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T” crossorigin=”anonymous”>

<!– jQuery library –>
<script src=”https://code.jquery.com/jquery-3.3.1.slim.min.js” integrity=”sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo” crossorigin=”anonymous”></script>

<!– JavaScript library –>
<script src=”https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js” integrity=”sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1″ crossorigin=”anonymous”></script>

<!– Latest compiled JavaScript library –>
<script src=”https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js” integrity=”sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM” crossorigin=”anonymous”></script>
```
### Example:
```html
<!DOCTYPE html>
<html lang="en">
 
<head>
    <meta charset="utf-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1">
 
    <!-- Bootstrap CSS library -->
    <link rel="stylesheet" href= "https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity= "sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
 
    <!-- jQuery library --> 
    <script src= "https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity= "sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous">
    </script>
 
    <!-- JavaScript library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity= "sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"  crossorigin="anonymous">
    </script>
 
    <!-- Latest compiled JavaScript library -->
    <script src=
"https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
            integrity=
"sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
            crossorigin="anonymous">
    </script>
</head>
 
<body>
    <div class="container text-center">
        <!-- Text color class used -->
        <h1 class="text-success">Hello</h1>
        <p>A computer science portal</p>
    </div>
</body>
```

