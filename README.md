<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is italic

__This text__ is italic

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal Rule -->

---
___

<!-- Blockquote -->
> This is a quote

<!-- Links -->
[Coding Aliens](http://www.codingaliens.com)

[Coding Aliens](http://www.codingaliens.com "Coding Aliens")

<!-- UL -->
* Item 1
* Item 2
* Item 3
  * Nested Item 1
  * Nested Item 2

<!-- OL -->
1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`

<!-- Github Markdown -->

<!-- Code Blocks -->
```bash
  npm install

  npm start
```

```javascript
  function add(num1, num2) {
    return num1 + num2;
  }
```

```python
  def add(num1, num2):
    return num1 + num2
```

<!-- Tables -->
| Name     | Email          |
| -------- | -------------- |
| coding aliens | aliens@gmail.com |
| coding aliens | aliens@gmail.com |

<!-- Task List -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3

<!-- Images -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- Math -->
My math is so rusty that I barely remember the _quadratic equation_:
$-b \pm \sqrt{b^2 - 4ac} \over 2a$

---
This is just a sample. You can play around with your own text right here.

Markdown
-------------

...is really just ordinary text, *plain and simple*. How is it good for you?

- You just **type naturally**, and the result looks good.
- You **don't have to worry** about clicking formatting buttons.
  - Or fiddling with indentation. (Two spaces is all you need.)

To see what else you can do with Markdown (including **tables**, **images**, **numbered lists**, and more) take a look at the [Cheatsheet][1]. And then try it out by typing in this box!

[1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet

---

#### Code

Code can be inline, `using backticks`. Or it can be in blocks, either with backtick "fences" or with indents of four spaces. (I prefer fences.)

```python
print('You get syntax highlighting...')
print('...if you include the language name')
```

You can also syntax-highlight some other cool stuff, like file diffs:
```diff
- This line got removed
+ This line got added
```

#### Math

Math forumlae use TeX. Some examples:

##### The quadratic equation
$-b \pm \sqrt{b^2 - 4ac} \over 2a$

##### The probability of getting (k) heads when flipping (n) coins
$\[P(E)   = {n \choose k} p^k (1-p)^{ n-k} \]$

##### The Lorenz Equations
$\dot{x} = \sigma(y-x) \\ \dot{y} = \rho x - y - xz \\ \dot{z} = -\beta z + xy$

##### The Cauchy-Schwarz Inequality
$\[ \left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right) \]$

[Math examples are from here](http://www.mathjax.org/demos/tex-samples/)
