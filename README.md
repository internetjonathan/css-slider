
# Carousel Demo Without JS

This is a demo to showcase use of Sass as well as the ability to create an image carousel without using any JavaScript or JavaScript libraries.

## Deployment

This simple demo is deployed on github pages @ https://internetjonathan.github.io/css-slider/



## Features

- No JavaScript used
- Utilizes Sass
- Responsive


## Thought Process

This was very challenging since I have never thought to make a slider without JavaScript, really had to think outside the box.  I found it simpler to not use the keyframes css property instead using the subsequent-sibling combinator to change the opacity of each div containing an image. Since I used the subsequent-sibling combinator span tags being added above the carousel was necesarry in order to create that subsequent-sibling relationship.


## Optimizations

In the future the addition of videos will be added. When using HTML5's video tag video sizing becomes an issue, since the current code has the images as background to each div rather than using the img tag.  Also tried to figure out a hacky way to utitlize The subsequent-sibling combinator without the spans but ran into an issue where the first image opacity couldnt be changed since it is a the first image of the sibilings.
