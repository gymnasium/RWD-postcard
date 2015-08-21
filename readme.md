[![Gymnasium Logo](https://cdn.rawgit.com/gymnasium/gymnasium.github.io/master/assets/GYM-logo.svg)](http://www.thegymnasium.com)

# Postcard: Media Queries for Popular Devices

Last year we made a postcard to give to attendees at Internet Week NY. We really didn't want to make just-another-piece-of-marketing-collateral that would end up in the trash, so instead of just being all blah blah marketing-y, we figured we'd put something useful on one side!

Of course we weren't *quite* as smart as we'd thought, so we've redesigned the postcard — and this time it includes a link to this repository so you can **use** the code. Better, right?

## How To Use This Repository

Use these media queries as a starting point for your responsive design breakpoints. You could simply copy the code snippets below, but if you clone or download the entire repo you'll get a PDF of the postcard, as well as [this sample web page](http://gymnasium.github.io/RWD-postcard/) that demonstrates the breakpoints as well. 

Seriously, [check it out](http://gymnasium.github.io/RWD-postcard/)... it is very cool.

Remember, these are just four out of **many**. Good responsive designers will modify these breakpoints as needed! 

If you're completely new to responsive design, you might want to check out some of our [free online courses](http://gymnasium.aquent.com/catalog/).

## The Media Queries

### Smartphone

**Portrait**

```css
/* Smartphone (portrait) --- */

@media only screen
and (max-device-width: 20em) {
    
}
```

**Landscape**

```css
/* Smartphone (landscape) --- */

@media only screen
and (min-width: 20.1em)
and (orientation: landscape) {
    
}
```

**Portrait & Landscape**

```css
/* Smartphone (portrait & landscape) --- */

@media only screen
and (min-device-width: 20em)
and (max-device-width: 30em) {

}
```

### Tablet

**Portrait**

```css
/* Tablet (portrait) --- */

@media only screen
and (min-device-width: 48em)
and (max-device-width: 64em)
and (orientation: portrait) {
    
}
```

**Landscape**

```css
/* Tablet (landscape) --- */

@media only screen
and (min-device-width: 48em)
and (max-device-width: 64em)
and (orientation: landscape) {

}

```

**Portrait & Landscape**

```css
/* Tablet (portrait & landscape) --- */

@media only screen
and (min-device-width: 48em)
and (max-device-width: 64em) {

}
```

### Laptop & Desktop

```css
/* Laptop & Desktop --- */

@media only screen
and (min-width: 76.5em) {
    
}
```

### Desktop & Beyond

```css
/* Desktop & Beyond --- */

@media only screen
and (min-width: 114em) {
    
}
```


