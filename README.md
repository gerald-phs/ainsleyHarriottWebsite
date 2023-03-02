# Ainsley Harriott Tribute Website
Tribute webpage for Ainsley Harriott. This was done because I love the guy, and also as a study project for freeCodeCamp.  

I was struggling to center the `<img>` element. It got mixed up with its `<figure>` parent element and everything became so confusing. Eventually, I accidentally added `display: flex;` property to my `<img>` element. Hah! That gave it some **right margin**. From then on, it was just a matter of setting all margins (top, right, bottom and left) to `auto` using the shorthand property `margin: auto;` which successfully centered the `<img>` element in relation to its parent element (and the whole page). Furthermore, because of flexbox, it shrinks and grows as needed.

## freeCodeCamp’s CSS
```css
.ainsley {
  display: block;
  max-width: 100%;
  height: auto;
  margin: 0 auto; /* I'd omit the `0`. Some top and bottom margin would look good in this particular case. Or would `auto` demolish top and bottom margin as well? */
}
```  

## My CSS
```css
.ainsley {
  display: flex;
  margin: auto;
}
```