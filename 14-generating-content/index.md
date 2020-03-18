# CSS Exercise 14: Generating content with CSS

## Numbering & legal documents

You'll find `terms.html` in this folder, it is a reformatted legal document from [Flick Electric’s Terms & Conditions page](https://www.flickelectric.co.nz/terms-and-conditions/)

The document has been alternated significantly, because we want to practice CSS counters and numbering of documents.

All the details for the numbering scheme are in `terms.css`, but your other responsibility is to make the document readable. i.e.:

- indent lists,
- allocate enough space for the numbers on the left,
- set a line-length of roughly 80 characters
- set the font-sizes correctly

## Printer-friendly attributes

Sometimes we want to conditionally show attributes if we're printing a webpage, since the mouse or any other such form of interactivity is not available.

Use the `attr()` function to extract the relevant attributes and slot them in near their elements.

See `print.html`
