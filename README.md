![css flexbox logo](./assets/images/css-flexbox-01.jpg)

# PRACTICE: CSS FLEXBOX BASIC 01

## Project description

The objective of this project is to have a guide for using CSS FLEXBOX, with all the properties that are available to us to date and with some practical examples of how we can implement them in our projects.

## Main and Cross axis

Taking into account the default values:

- display: flex;
- flex-direction: row;

In this case "justify-content" applies to the main axis, and "align-items" to the cross axis.

![css flexbox main and cross axis](./assets/images/css-flexbox-02.png 'Flexbox Architecture')

## Container (flex container). Properties for the Parent

- display: flex | inline-flex;
- flex-direction: row | row-reverse | column | column-reverse;
- flex-wrap: nowrap | wrap | wrap-reverse;
- flex-flow: row nowrap; (shorthand of flex-direction and flex-wrap)
- justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
- align-items: stretch | flex-start | flex-end | center | baseline;
- align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | baseline;
- place-content: center flex-start; (shorthand for align-content and justify-content)
- place-items: center flex-start; (shorthand for align-items and justify-items)
- row-gap: 5px;
- column-gap: 10px;
- gap: 5px 10px; (shorthand of row-gap and column-gap)
- gap: 5px; (apply the same values "5px" for row-gap and column-gap)

## Items (flex items). Properties for the Children

- order: 0; (Default is zero, accepts negatives and positives, the lowest value will be placed first)
- flex-grow: 0; (Default is zero, ability to grow or not. Only positives)
- flex-shrink: 1; (Default 1, ability to shrink or not. Only positives)
- flex-basis: auto; (Default auto. This defines the default size of an element %, px, rem, etc.)
- flex: 0 1 auto; (shorthand for flex-grow, flex-shrink and flex-basis)
- align-self: auto | flex-start | flex-end | center | baseline | stretch; (One specified and individual flex item)

## Used technology

- Html 5
- CSS

## Resources and documentation used

- CSS-TRICKS: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## Developers: Requirements

- Web Browser
- Code editor

## Developers: Installtion

1. Clone the repository: https://github.com/newmanferrer/practice-091022-css-flexbox-01.git
2. Another option is to download the repository using ZIP format.

---

## Author: Newman Ferrer

newmanferrer@gmail.com

:sun_with_face: Maracaibo - Venezuela :venezuela:

Practice date: 09/10/2022
