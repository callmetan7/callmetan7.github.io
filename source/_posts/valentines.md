---
title: A Nerds Valentines Day
date: 2024-02-14 2:23:11
author: Tanuj Padaliya
keywords: [valentines, math, desmos, tanuj, padaliya]
cover: [
https://wallpapercave.com/wp/wp8535521.jpg
]
sticky: 10
banner:
    bgurl:   [
        https://wallpapercave.com/wp/wp8535521.jpg   
  ]
---

<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML' async></script>

# How to Impress Your Date When Both of you are a Nerd?

Make a graph that shows your love obviously!

{% asset_img valentinesDayBanner.png https://www.desmos.com/calculator/advpkabrkj %}

## Step 1

- Lets start off with how to make a heart with a graph first

1. Break down the shape of the heart
   a. We can observe that the heart is a curved v-shaped line and 2 straight <br> lines. We can achieve this shape by using the function
   $$ f(x) = x^{\frac{2}{3}} $$
   {% asset_img x2over3.png %}
2. Now we can mirror the half of a circle using the function
   $$ f(x) = \sqrt{10-x^2} $$
   {% asset_img semicircle.png %}
3. When we add these two functions together we get the top part of the heart
   $$ f(x) = x^{\frac{2}{3}} + \sqrt{10-x^2} $$
   {% asset_img buttocks.png %}
   a. If you notice the \\(10\\) is setting the limit to the size of your heart because \\(x^2\\) cannot excede \\(10\\)
4. We now make this function oscilate to create the shape of a heart by multiplying it by a \\sin\\ function
   Our final result should look like this
   $$ f(x) = x^{\frac{2}{3}} + \sqrt{10-x^2} \sin(10x) $$
   We multiply the x value inside by 10 increase the amount waves that the sin function goes through to ensure that we capture the shape of the heart
   {% asset_img heart.png %}
