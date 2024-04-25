# SNAKE layout

## purpose

build a pure CSS layout able to display a list of items in a horizontal snake layout :

* items are displayed from left to right on odd rows
* items are displayed from right to left on even rows
* a "link" is displayed between items (from previous to next items)
* 1st item has no incoming link
* last item has no outgoing link
* the number of items per row is automatically computed (based on *screen* width)

## build & run

### build

1. build the css (as the demo pages use `css`): `npm run build`

### run & develop

1. automatically build `css`: `npm run scss`
1. start demo server: `npm start`
