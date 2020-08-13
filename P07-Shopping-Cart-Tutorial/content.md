---
title: "Shopping Cart Tutorial"
slug: shopping-cart-tutorial
---

This chapter along with the remaining chapters will guide you through how to make your ecommerce website functional. We will be adding a shopping cart functionality where users can add and remove items from their cart.

 For simplicity, we will have the shopping cart page on the same page where the moods are displayed. 

# Adding Items to Cart

Our cart 
Our shopping cart will be located in the footer of our ecommerce page.

We will add a footer element in our html. 
>[action]
> Add a footer element after the main element inside your ```index.html``` file
>
```html
<footer>
</footer>
```

Your HTML markup should now look like this:
```html
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Groceries</title>
  <link rel='stylesheet' href='./resources/css/styles.css'>
</head>
<body>
  <header class='page-header'>
    <h4>The Mood Shop</h4>
    <nav> 
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Cart</a></li>
      </ul>
    </nav>
  </header>
  <main class='items' id='items'>
    <!-- 
      Display moods here
     -->
  </main>
  <footer>
 
  </footer>
  <script src='./resources/js/scripts.js' type="module"></script>
</body>
</html>
```

Follow this shopping cart tutorial to add the shopping cart functionality.

The tutorial is slightly different, but we’re essentially using the same functionality of the shopping cart tutorial. 

In the video tutorial, every code is written inside ```index.html```. But since we have a separate ```scripts.js``` file, we’ll write the javascript code in there instead of inside the ```<script>``` tag.

You can write the javascript functions below the code you wrote for displaying moods in ```scripts.js``` file.

# 1st video (start at 5:25 - end)

This first video will walk you through how to add and show items on your console by writing the functions ```addItem()``` and ```showItems()```.

Follow the video starting at 5:25 until the end. 

![ms-video-youtube](https://www.youtube.com/embed/oMTO0LbBGLA)


# 2nd video

In this video, we'll be discussing how to use objects to add items into an array. Follow the full video. 

![ms-video-youtube](https://www.youtube.com/embed/yUfbzeKol04)



# Update progress on Github
> [action]
>
> Now is a good time to update your progress on Github.
>
```bash
git add .
git commit -m ‘add item and show item functions working’
git push
```
