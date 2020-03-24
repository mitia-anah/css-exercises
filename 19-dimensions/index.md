# CSS exercise 19: Dimensions

Let's take a look at the following properties:

- `width`
- `height`

…and their corresponding properties:

- `min-width`
- `max-width`
- `min-height`
- `max-height`

Now let's see if we can answer these questions.

- What are the default values for these properties?
- Do these default values change if the element is a block-like or an inline-like element?
- What happens if a `min-width` value is greater than a `width` value?
- Similarly, what happens if a `max-width` value is less than a `width` value?
- Similarly, what happens if a `min-width` value is greater than a `max-width` value?
- What happens when `width`s are applied to table cells, and the content inside these cells doesn't fit?
- What's the deal with `height` and percentage values? Percent of what!?

Lastly, imagine the following scenario:

```
div {
  min-width: 20rem;
  max-width: 80vw;
}
```

- What are all the significant or interesting characteristics of this ruleset?
- What is the implied `width` of a `div`?
