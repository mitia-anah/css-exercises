# CSS exercise 26: Flexbox

Flexbox helps us align and distribute items within a container, along one direction (or main axis) at a time.

We'll need to look at the following properties for containers (that set up a flexbox)…

- `display` values of `flex` and `inline-flex`
- `flex-flow`
  - `flex-wrap`
  - `flex-direction`
- `align-items`
- `justify-content`
- `align-content` (for wrapping flex containers)

…and the flex-item or individual elements within the container can be controlled independently using these properties…

- `flex`
  - `flex-grow`
  - `flex-shrink`
  - `flex-basis`
- `align-self`
- `order`

We're going to need to learn some terms or concepts too:

- Flex container
- Flex item
- Main axis
- Cross axis
- `flex-start` value
- `flex-end` value

With all that in mind, here are some questions you should be able to answer after your research:

1. What is the order of property values in the shorthand `flex` property? i.e. Given… `flex: 2 1 auto`, what does the `2`, `1` and `auto` represent?
1. What `flex-wrap` or `flex-flow` values do we need before we can use `align-content`?
1. How is `align-content` different to `align-items`?
1. Which property overrides the other - the container's `align-items` or the flex item's `align-self`?
1. What other commonly-used box model property is similar to `flex-basis`?
1. There are two ways to change the ordering of flex items within a flex container. One is done on each flex item by using the `order` property. The other can change the whole order of the flex items at the container level. What is that property or value?
1. Let's say we wanted some space between each of our three flex items in a flex column. Name at least two possible ways to achieve this.
