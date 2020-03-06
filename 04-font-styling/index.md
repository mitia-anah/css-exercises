# CSS exercise 4: Styling fonts

## Explanation

There are many different fonts available in the various operating systems.

Some fonts are available in all operating systems, but this is not reliable.

So, the `font-family` property allows us to *chain* fonts together in a font-stack, whichever one is mentioned first, and is supported by the browser, the browser will use that font.

e.g. in `Arial, Helvetica, sans-serif`, a windows user would probably see Arial, since Arial is available in almost all Windows OSs. Mac users would see Helvetica.

Each font-stack should have a fallback font, and that's why we have keywords like:

- `serif`
- `sans-serif`
- `monospace`
- `fantasy`
- `cursive`

In other words, if none of the other fonts specficied are available, then the browser can fall back on rendering `serif`.

## The exercise

In `fonts.html`, you'll notice there are 3 sections, each with the same HTML for `h1`-`h6`, and three different sizes of paragraphs. Each section is concerned with each fallback font.

**Can you describe what each fallback font is?**

Your job is to create font-stacks for each of the sections, falling back on each keyword, placing these styles in `fonts.css`.

Then, within each of those sections, I want you to style up each of the elements according to this structure:

Element | Size | Weight | Margin (block-end) | Ligatures | Letter spacing
--- | --- | --- | --- | --- | ---
H1 | `2.5rem` | `800` | `1em` | - | -
H2 | `2rem` | `700` | `1em`  | - | -
H3 | `1.5rem` | `700` | `1em`  | - | -
H4 | `1.25rem` | `700` | `1em`  | - | -
H5 | `1rem` | `700` | `1em`  | - | -
H6 | `1rem` | `700` | `1em`  | `small-caps` | -
Intro paragraph | `1.125rem` | `400` | `1em`  | - | `0.1em`
Paragraphs | `1rem` | `400` | `1em`  | - | -
Small | `0.75rem` | `400` | `1em`  | - | -

`1rem` is equivalent to ?

## Further reading

- [Stylistic font-stacks](https://css-tricks.com/snippets/css/font-stacks/)
- [Font support](https://www.cssfontstack.com/)
