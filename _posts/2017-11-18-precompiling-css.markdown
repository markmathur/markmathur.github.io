---
layout: post
title:  "Precompiling CSS"
date:   2017-11-18 12:44:39 +0100
comments: true
categories: CSS
---
# Sass-disambiguation

There are several ways to precompile CSS for a site. The tool I used is called [Sass](http://sass-lang.com/). Sass is the 
name of the precompiler, but it is also the name of one of two syntaxes that work with the Sass *precompiler*, the other 
one being "SCSS": 

- SCSS is a syntax that reminds a lot of ordinary CSS, using curly brackets and semicolons  (SCSS stands for "Sassy CSS"). 
- Sass does away with the brackets and uses linebreaks and tab stops instead. SassScript, as it is also called, is the older form of the two.

# The point with Sass

## Pros

There are two main reasons to use Sass. 

1. Just like the Markdown language, it avoids characters that require you doing finger gymnastics, pressing the "alt gr" key
while at the same time aiming at the 7-key to get those curly braces on to the screen. It might not seem like a big win, but
when you write hours of code, you notice the difference. 
2. There are options for scripting your within your style sheet. Using variables, loops and  much more. So a little Sass code can
generate alot och CSS lines, which is very helpful when you work with bigger projects.

I used the Sass syntax and really liked the fluency of writing. I also used variables. I tried to work with a limited set of 
colors, and set variables to their RGB-codes. That way I could easily change the color of several elements using the same. Quite nifty!

## Cons

However, everyone won't like Sass. There are some cons. It can be quite cumbersome when you find errors in the CSS file, and then have to 
find what caused them in the Sass file. Also, you are dependent on having the Sass compiler available. It might not be a problem now, but 
who knows how the land lies in ten years time, when you need to update a site. 
