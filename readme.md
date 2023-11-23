# LEARN

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />
    <title>Learn-Flex</title>
  </head>
  <body>
    <!-- <h1>Learn-Flex</h1> -->
    <div class="flex-parent">
      <!-- display:block -->
      <div class="flex-children child-1">child-1</div>
      <div class="flex-children child-2">child-2</div>
      <!-- <div class="flex-children">child-3</div>
      <div class="flex-children">child-4</div> -->
      <!-- <div class="flex-children">child-5</div>
      <div class="flex-children">child-6</div>
      <div class="flex-children">child-7</div>
      <div class="flex-children">child-8</div> -->
    </div>
  </body>
</html>
```
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.flex-parent {
  height: 10vh;
  width: 300px;
  background: wheat;
  display: flex;
  /* flex-direction: row; */
  /* justify-content: space-around; */
  /* align-items: flex-start; */
  /* flex-wrap: nowrap; */
  /* flex-flow: row wrap; */
  /* align-content: space-evenly; */
  gap: 20px;
}
.flex-children {
  background-color: orangered;
  width: 150px; // nowrap => max-width | wrap => width
  /* height: 100px; */
  /* aspect-ratio: 2; */
}
.child-1 {
  /* flex-grow: 11; */
  /* flex-grow: 1;
  flex-shrink: 5;
  flex-basis: 200px; // min-width */
  /* flex: 1 5 200px; */
  flex: 1;
}
.child-2 {
  /* flex-grow: 1; */
  flex-grow: 1;
  flex-shrink: 1;
}
.child-3 {
  height: 200px;
  aspect-ratio: 1;
}
.order-1 {
  order: -1;
  background: blue;
}
.self {
  align-self: flex-end;
}
```
# WORKSHOP