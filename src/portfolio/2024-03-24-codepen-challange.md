---
title: CodePen Gnarly Grid Challenge
author: Nathaniel Downey
date: 2024-03-24
tags: ["post", "featured"]
image: /assets/portfolio/article-3.png
imageAlt: A screenshot of the website showing a collection of cards in a grid with images, a head, and a paragraph.
description: My attempt at a CodePen challenge that involved fixing a Grid while only being able to change the CSS.
---

CodePen hosts monthly challenge that, well... challenge the user to complete a challenge. The one I took a go at was the [Gnarly Grid Challenge.](https://codepen.io/challenges/2022/september/1) This challenge involved fixing a CSS grid without changing the HTML. Before I did anything, the CodePen was quite broken with all the content just layed on top of each other. Before I could start writing CSS to fix that, I added [Normalize.css](https://necolas.github.io/normalize.css/) to my CodePen. I added it because it "makes browsers render all elements more consistently and in line with modern standards." After doing that, I started to work on the CSS.

The first thing I needed to do was to make it actually be a grid. I achieved this by writing.
```css
body {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  grid-gap: 20px;
  margin-block: 20px;
  margin-inline: 25px;
}
```
This code makes all the content form into a gird. After I got the content into a grid, I started to style it to make it look nice. I made all the content into boxes with shadows and rounded them. I also added a hover effect to make it stand out. The end result can be seen in the image above.

Overall, I found this project to be quite fun. Limiting myself to making the project look nice with just CSS proved to be an interesting challenge. I'm quite happy with how this project turned out and you can check out for yourself [here!](https://codepen.io/Nate7611/pen/xxeRyNr)