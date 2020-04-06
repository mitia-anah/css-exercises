# CSS exercise 28: CSS Grid

Grid is the most powerful and freshest layout technique in our tool-belt.

Some grid-like layouts are easily achieveable, but more complex layouts can be really tricky to implement.

You're going to need to learn more about these properties:

- `display` values of `grid` and `inline-grid`
- `grid`
  - `grid-template-columns`
  - `grid-template-rows`
  - `grid-gap` and `gap`
    - `grid-row-gap`
    - `grid-column-gap`
  - `grid-auto-columns`
  - `grid-auto-rows`

As our grids become more complex, we might need to use other properties.

Some of these properties apply to the grid items, and tell a grid item where to start and end in terms of columns and rows:

- `grid-column`
  - `grid-column-start`
  - `grid-column-end`
- `grid-row`
  - `grid-row-start`
  - `grid-row-end`

We could also start naming certain areas in the whole grid:

- `grid-template-areas`

…and then assign a grid-item to a named area:

- `grid-area`

Lastly, we can change the algorithm CSS grid uses to fill the available spaces using…

- `grid-auto-flow`

Phew!

Along with the CSS Grid properties, there are a number of new keywords and functions to use:

- `repeat()`
- `minmax()`
- `max-content`
- `min-content`

and the fraction unit:

- `fr`

OK, now try answer these questions:

- How many columns does a grid have by default?
- What are the differences between Flexbox and Grid?
- Why would you use flexbox rather than grid?
- Why would you use grid rather than flexbox?
- What's a more concise way to write out the following: `grid-template-columns: 10rem 10rem 10rem 10rem;`
- How can we specify a minimum height for a grid row, but still allow the row to increase in height if its content is too tall?
