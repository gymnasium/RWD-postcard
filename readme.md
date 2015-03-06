![Gymnasium Logo](https://cdn.rawgit.com/gymnasium/gymnasium.github.io/master/assets/GYM-logo.svg)

##  Postcard: Media Queries for Popular Devices

Last year we made a postcard to give to attendees at Internet Week NY. We really didn't want to make just-another-piece-of-marketing-collateral that would end up in the trash, so instead of just being all blah blah marketing-y, we figured we'd put something useful on one side!

Of course we weren't *quite* as smart as we'd thought, so we've redesigned the postcard — and this time it includes a link to this repository so you can **copy and paste** the code. Better, right?

### How To Use This Repository

Use these media queries as a starting point for your responsive design breakpoints. You could simply copy the code snippets below, but if you clone or download the entire repo you'll get a PDF of the postcard, as well as [this sample web page](http://gymnasium.github.io/rwd-postcard/) that demonstrates the breakpoints as well. 

Seriously, [check it out](http://gymnasium.github.io/rwd-postcard/)... it is very cool.

Remember, these are just four out of **many**. Good responsive designers will modify these breakpoints as needed! 

If you're completely new to responsive design, you might want to check out some of our [free online courses](http://gymnasium.aquent.com/catalog/).

### The Media Queries

#### Smartphones

**Portrait**

```css
/* Smartphones (portrait) ---- */
@media only screen and (max-device-width : 320px) {
   
}
```

**Landscape**

```css
/* Smartphones (landscape) ---- */
@media only screen and (min-width : 321px) {
   
}
```

**Portrait and Landscape**

```css
/* Smartphones (portrait and landscape) ---- */
@media only screen and (min-device-width : 320px) and (max-device-width : 480px) {
   
}
```

#### Tablets

**Portrait**

```css
/* iPads (portrait) ---- */
@media only screen and (min-device-width : 768px) and (max-device-width : 1024px) and (orientation : portrait) {
    
}
```

**Landscape**

```css
/* iPads (landscape) ---- */
@media only screen and (min-device-width : 768px) and (max-device-width : 1024px) and (orientation : landscape) {
   
}
```

**Portrait and Landscape**

```css
/* iPads (portrait and landscape) ---- */
@media only screen and (min-device-width : 768px) and (max-device-width : 1024px) {
   
}
```

#### Desktop and Laptops
```css
/* Desktop and laptops ---- */
@media only screen and (min-width : 1224px) {
   
}
```

#### Large Screens
```css
/* Large screens ---- */
@media only screen and (min-width : 1824px) {
   
}
```

