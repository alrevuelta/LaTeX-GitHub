# Introduction

LaTeX is a great tool for creating documents, and it is widely used in many fields, specially in research. In this repo I will show some quicks demos on how to embed LaTeX formulas in a GitHub readme file, in a very simlpe and easy way. Lets see an example on how it looks like.

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?(a&plus;b)^2&space;=&space;a^2&space;&plus;&space;2ab&space;&plus;&space;b^2">
</p>

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?F(x)&space;=&space;\int^a_b&space;\frac{1}{3}x^3">
</p>

We can also write more complex expressions.

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?(a_1&space;&plus;&space;b_1i&space;&plus;&space;c_1j&space;&plus;&space;d_1k)&space;(a_2&space;&plus;&space;b_2i&space;&plus;&space;c_2j&space;&plus;&space;d_2k)&space;=&space;\\&space;a_1a_2&space;-&space;b_1b_2&space;-&space;c_1c_2&space;-&space;d_1d_2&space;\\&space;&plus;&space;(a_1b_2&space;&plus;&space;b_1a_2&space;&plus;&space;c_1d_2&space;-&space;d_1c_2)i&space;\\&space;&plus;&space;(a_1c_2&space;-&space;b_1d_2&space;&plus;c_1a_2&space;&plus;&space;d_1b_2)j&space;\\&space;&plus;&space;(a_1d_2&space;&plus;&space;b_1c_2&space;-&space;c_1b_2&space;&plus;&space;d_1a_2)k">
</p>

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?\left(&space;\sum_{k=1}^n&space;a_k&space;b_k&space;\right)^2&space;\leq&space;\left(&space;\sum_{k=1}^n&space;a_k^2&space;\right)&space;\left(&space;\sum_{k=1}^n&space;b_k^2&space;\right)">
</p>

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?P(E)&space;=&space;{n&space;\choose&space;k}&space;p^k&space;(1-p)^{&space;n-k}">
</p>

# How to

In order to generate your own formula, first visit the [codecogs online LaTeX editor](https://www.codecogs.com/latex/eqneditor.php). Write your own formula. For example, lets write the following:

`\frac{{\partial ^2 B}}{{\partial x^2 }} = \frac{1}{{c^2 }}\frac{{\partial ^2 B}}{{\partial t^2 }}`

Once we have written that, scroll down a bit, open the combo box and select `URL`. You will see something like "The URL link to this equation is:". Just copy the text below, which in this case is:

```
https://latex.codecogs.com/gif.latex?\frac{{\partial&space;^2&space;B}}{{\partial&space;x^2&space;}}&space;=&space;\frac{1}{{c^2&space;}}\frac{{\partial&space;^2&space;B}}{{\partial&space;t^2&space;}}
```

Now just copy that link and replace `LINK_TO_CODECOGS` with it.

```html
<p align="center">
  <img src="LINK_TO_CODECOGS">
</p>
```

Once you remove the markdown quotes, you will have your formula
<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?\frac{{\partial&space;^2&space;B}}{{\partial&space;x^2&space;}}&space;=&space;\frac{1}{{c^2&space;}}\frac{{\partial&space;^2&space;B}}{{\partial&space;t^2&space;}}">
</p>
