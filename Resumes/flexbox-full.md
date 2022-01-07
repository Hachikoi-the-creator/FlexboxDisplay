# Flexbox 

Whit the following html

```html
<nav class="container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
  <div>4</div>
</nav>
```

# Flex direction

- **(Default)** row
- column

```css
.container {
  flex-direction: row | column;
}
```

# Justify content

- **(Default)** Flex Start
  - All -> left
- Flex End
  - All -> right
- Center
  - All -> center
- Space Around
  - uneven, 1fr: wall-item, 2fr: item-item
- Space Between
  - items stuck in the walls, even space in between
- Space Evenly
  - even espace, 1fr: wall-item, 1fr: item-item


```css
.container {
  justify-content: flex-end | space-between;
}
```

# Positioning items

*Send the first child to the right*
```css
.container > div:nth-child(1) {
  margin-left: auto;
}
```

# Flex shorthand

*Makes the 4th child grow 4 times faster & min-width of 200px*
```css
.container > div:nth-child(4) {
  flex: 4 4 200px;
}
```

# Align & Justify

both have same options

- **(Default)** Flex Start
  - All -> left
- Flex End
  - All -> right
- Center
  - All -> center
- Stretch
  - gets bigger or larger depending on axis



**Align**
Move tru X axis

**Justify**
Move tru Y axis

*Moves the last child to top*
```css
.container > div:nth-child(4) {
  align-items: flex-end;
  justify-content: flex-end;
}
```

## Center a div

```css
.container > div:nth-child(4) {
  align-items: center;
  justify: center;
}
```

# Make the container of the divs, fit outer container

*Container big and content in the middle*
```css
.container {
  height: 100%;
  width: 100%;
  align-items: center;
  justify-items: center;
}
```

# Wrap

*Make the items got to another row if they are too big*

*Using flex to set min-width*
```css
.container {
  display: flex;
  height: 100%;
  width: 100%;
  flex-wrap: wrap;
}
.container > div {
  flex: 1 1 200px
}
```

# Flex shorthand

- flex-grow
  - Rate of incresing size, depending on **flex direction**
- flex-shrink
  - Rate of decresing size, depending on **flex direction**
- flex-basis
  - same as min-width

**Defaults**: flex: 1 **==** flex: 1 1 0

*The second child grows twice as bigger and has min-width of 100px*
```css
.container > div:nth-child(2) {
  flex: 2 2 100px;
}
```

# Change the order whit CSS

*Inverse the order of the items*
```css
.container > div:nth-child(1) {
  order: 4;
}
.container > div:nth-child(2) {
  order: 3;
}
.container > div:nth-child(3) {
  order: 2;
}
.container > div:nth-child(4) {
  order: 1;
}
```

<br><br>

## Have fun & Practice ! ! 


