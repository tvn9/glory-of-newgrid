# THE GLORY of NEW CSS GRID SYSTEM
A simple demonstration of the new grid layout from the CSS advance grid system.

## PURPOSE of THIS PROJECT
The puspose of this work is to demonstrate and test the CSS grid layout system for experimental, and learning.

## Run test
[Click to run](https://tvn9.github.io/glory-of-newgrid/)

## Code snippet
```css
.container { 
  width: 90%;
  margin: 30px auto;
  display: grid;
  grid-template-rows: 100px 250px 150px 250px 70px;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 8px;
}

.container > div {
  padding: 20px;
  background-color: #1e3deb;
  color: white;
  font-size: 16px;
  font-family: sans-serif;
  text-transform: uppercase;
  letter-spacing: 2px;
  text-align: center;
}

.header {
  grid-column: 1 / span 4;
}

.hero {
  grid-column: 1 / -1;
}

.card-1, .container .card-2, .container .card-3 {
  grid-row: 3 / 4;
}

.side-col {
  grid-column: 4 / 5;
  grid-row: 3 / span 2;
}

.main-content {
  grid-column: 1 / span 3;
}

.footer {
  grid-column: 1 / -1;
}

```

## Screenshot
### WireFrame Design
![](img/newgrid.jpg)

