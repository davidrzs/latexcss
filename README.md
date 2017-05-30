# LatexCSS

latex.css is a classless CSS file which can be attached to any html document to make it look like latex.

[ An example can be found here ](https://davidrzs.github.io/latexcss/example.html)


## How to use it?
Just open your html file and add the following to your document head:
```html
<link rel="stylesheet" type="text/css" href="latex.css">
```
(Of course you still need to download the latex.css file and place it in the same directory)
The whole document should now look similar to [ this example ](https://davidrzs.github.io/latexcss/example.html) .

## Examples

1. [The project website](https://davidrzs.github.io/latexcss/) 
2. [A text example](https://davidrzs.github.io/latexcss/example.html)
3. [A math example](https://davidrzs.github.io/latexcss/math_example.html)

## Theorems, Definitions and Proofs
Theorems, Definitions, Remarks and Proofs are supported. Just wrap your content in a `div` and add the corresponding class to the `div` like in the following example. 

```html
<div class="theorem">...</div>
<div class="definition">...</div>
<div class="lemma">...</div>
<div class="proof">...</div>
```

### Numbered vs Not-numbered
There are two latex.css files in this repository. 
 1. latex.css -> This is the normal one and numbers the theorems etc.
 2. latex_no_numbers.css -> Exactly the same as latex.css but doesn't number the theorems etc. 

## Credits:
This repository is more or less just a combination of other projects:
- The latex styling has been taken from the awesome  [  WiTeX Github project ](https://github.com/AndrewBelt/WiTeX).
- Theorem, Definition, Lemma and Proof environments have been inspired by [  this great blog post ](http://drz.ac/2013/01/17/latex-theorem-like-environments-for-the-web/). 
- The Theorem, Lemma and Definition counter has been inspired by a comment on [  this blog post ](http://drz.ac/2013/01/17/latex-theorem-like-environments-for-the-web/). 
