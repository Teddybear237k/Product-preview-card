#Product preview card

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- HTML
- CSS

### What I learned

With this I polished my knowledge in the use of font and the use of other units such as rem, vh and vw. I understand now how fonctions different sizes and I can better use clamp. 
For the colors I stayed close as possible to the style-guide and I followed the font too. I think so far this is one of my best first try. The design was quite simple to integrate.

I now also know how to use containers a little better than before and also that cqi and cqb are similar to vw and vh, but instead of caring about the viewport, they care about their containers size instead.

### Continued development

Although I used clamp by myself this time around I still need to read on how to apply it and all it's fonctions, I also need to better my knowlegde on to use implement the Utopia design perfectly including colors too.

I've got to learn how to better follow the fidelity in the design. I still sometimes don't understand why should I use a particular size or even unit at different moments and that's a major problem.

### Useful resources

[https://developerux.com/2026/04/26/best-practices-responsive-typography/]
[Typescale.com]

### Adjustments made:
I redesigned the css with @container and container queries and created a demo version which I named contexts. I corrected the semantics and the fidelity like the card width.

contexts.html (with contexts.css for just the surrounding page chrome — backgrounds, the sidebar column, the modal overlay) drops the same unmodified product-card component into four different boxes on one page:

A wide hero slot (capped at 900px)
A cell in a two-column grid (capped at 1100px total page width)
A fixed 300px sidebar
A fixed 420px modal
