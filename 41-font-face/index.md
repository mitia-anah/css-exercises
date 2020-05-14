# CSS exercise 41: Font-face

Webfonts are strongly tied to a site's design and its visual identity.

But before we can use them, there are a few things we need to know:

1. There are several types of font formats, e.g. `WOFF`, `TTF`, etc.? Name at least 2 other font file formats.
2. Which of these font file formats is a good candidate to use in all browsers?
3. The font-face syntax is also different to other @-blocks. What are the differences between a `@font-face` block and `@keyframes` / `@media` queries / `@supports` blocks, etc.
4. Some fonts come with licencing restrictions. What does this mean?
5. A designer has assigned you a mockup to turn into HTML/CSS. You've tabled the list of fonts used in the document as follows:

font-family | font-weights | italic?
--- | --- | ---
'Roboto' | 400, 700 | Both
'Proxima Nova' | 100, 300, 600, 800 | No

How many font-face blocks do we need to provide if we want to support all the chosen fonts?

6. At roughly 20KB per font file, how many kilobytes of fonts would each of our users have to download in the example above?
7. If we chose to offer WOFF2 as well as WOFF, what syntax would we use? How many files would we have, according to question 5?
8. Most of our users would probably have the exact font we want to serve already installed on their devices. How can we make sure the user's browser doesn't download the fonts they might already have?
9. Sometimes we have to assign fallback fonts for our custom webfonts we add via `@font-face`. What are some things to keep in mind when it comes to selecting these fallback fonts?
10. The browser can use one of several strategies for loading the fonts, e.g. showing nothing until the font is downloaded, or using a fallback font first. What property can we use to help the browser decide on which strategy to use?
