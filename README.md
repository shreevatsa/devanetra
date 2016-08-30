# devanetra
vapourware :-)

## What

In this repo I hope to have some code for (haven't written a single line of code yet):

1. A browser extension that users can install, which will let them read, on any webpage, text detected as Indic (or marked up as such) transliterated into the script of their choice.
2. A Javascript library (like MathJax, or translipi) such that any website developer can, by simply adding a single line on their page, make the contents available to readers in whatever script they prefer (as if they had installed the extension).

For this, need these components:

1. Some code that can transliterate between Indic/Brahmic scripts and a few common Latin scripts, e.g. Bengali to Gurmukhi, Devanagari to Kannada, Tamil to ISO 15919, etc.
2. Some code that can scan through the text elements on a webpage and detect runs of Brahmic text (and which alphabet they are in). (I am planning to look at the MathJax preprocessors documentation for how they do this.)
3. Some code to save user preferences in localstorage, and the associated CSS and JS stuff to make it sit as an unobtrusive button in a corner of the page, when clicked pop a box asking for the user's preferred scripts, etc. (This probably exists already.)

This is as I [commented earlier](https://groups.google.com/d/msg/sanskrit-programmers/ybDO8l3dw6w/CeQ-x_FuDQAJ).

The actual text-replacement should be easy as there are lots of joke extensions that do this (or search for something like [FoxReplace Chrome]).

Something like the Unicode conversion gateway ([1](http://www.innovatrix.co.in/converter/), [2](http://unigateway.sourceforge.net/Main_Page)) (itself based on "Padma") may also be relevant.
