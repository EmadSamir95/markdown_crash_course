

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*this text* is italic

~~~
you can assign \ with * to avoid italic as follows


 \*this text\* is not italic
 ~~~

_this text_ is also italic

<!-- Strong -->

**this text** is strong

__this text__ is also strong

<!-- StrikeThrough-->

~~This text~~ is strikethrough

<!-- Separate content -->

you can use
___ 

or 

---

<!--Blockquote-->

>this is a quote by ~Emad Samir


<!--for Links-->

[Facebook](www.facebook.com)

[Twitter](www.twitter.com "Twitter")

<!-- Ul-->
__unordered list__
* item1
* Item2
  * Nested item1
  * nested item2
* [facebook link](www.facebook.com "facebook")

<!-- Ol -->
__an ordered list__
1. item1
2. item2
3. item3
4. item4

<!-- inline code block-->

 `<p> here is a paragraph tag </p>`

 <!-- image-->

 ![image](https://markdown-here.com/img/icon256.png)


<!-- github markdown -->

```bash
$commit -- changes are done
```

```javascript
function add(num1,num2){
    return num1+num2;
}
```

```python
def add(num1,num3):
return num1 + num3
```

<!-- tables -->

| Name     | Email                   |
| ---------|-------------------------|
|Emad Samir|emadsamirgirges@gmail.com|
|john Doe  |Johndoe@gmail.com|
|Domson james|domsonjames@gmail.com|


<!-- task list-->

* [x] Task1
* [x] Task2
* [ ] Task3

<!--Mathematical Formulas-->

insert anything you need inside two dollar signs, use the \ and it will suggest many options to you

$\sqrt{2x+2y} * \cos^{-1}(2x) * \alpha * x_{to,a1} *\sqrt{s^{2+3s}} * \frac{2x}{3y} * \bar{y_1} \leq \log_5(10)$





<!--additives-->


We can write fractions: $\frac{2}{3}$. We can also handle things like estimated population growth rate, e.g., $\hat{\lambda}=1.02$. And, $\sqrt{4}=2$.

$$\alpha, \beta,  \gamma, \Gamma$$

$$a \pm b$$
$$x \ge 15$$
$$a_i \ge 0~~~\forall i$$



## Matrix

$$A_{m,n} =
 \begin{pmatrix}
  a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
  a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
  \vdots  & \vdots  & \ddots & \vdots  \\
  a_{m,1} & a_{m,2} & \cdots & a_{m,n}
 \end{pmatrix}$$



## Statistics


The binomial probability: 
$$f(y|N,p) = \frac{N!}{y!(N-y)!}\cdot p^y \cdot (1-p)^{N-y} = {{N}\choose{y}} \cdot p^y \cdot (1-p)^{N-y}$$


To calculate the **mean** of \textit{n} observations of variable \textit{x}, you can use: 
$$\bar{x} = \frac{1}{n} \sum_{i=1}^{n}x_{i}$$ 


Note that this equation looks quite nice above where it's in display math mode. It is more compact but not quite as nice looking if we present it using inline mode, e.g., $\bar{x} = \frac{1}{n} \sum_{i=1}^{n}x_{i}$.


Let's do the same with the equation for **variance**. First the inline version, which is 
$\sigma^{2} = \frac{\sum\limits_{i=1}^{n} \left(x_{i} - \bar{x}\right)^{2}} {n-1}$. And then the display mode version: 
$$\sigma^{2} = \frac{\sum_{i=1}^{n} 
  \left(x_{i} - \bar{x}\right)^{2}}
  {n-1}$$
  

Next, it's good to look at the equation for **covariance** to see how it is just a generalization of variance to two variables. An inline version of the equation is $cov_{x,y} = \frac{\sum\limits_{i=1}^{n}{(x_i-\overline{x}) \cdot (y_i-\overline{y})} }{n-1}$. And, the display mode is: $$cov_{x,y} = \frac{\sum\limits_{i=1}^{n}{(x_i-\overline{x}) \cdot (y_i-\overline{y})} }{n-1}$$
  

And, finally, we'll end with the **standard deviation**. Here's the inline version, $\sigma = \sqrt{\frac{\sum\limits_{i=1}^{n} \left(x_{i} - \bar{x}\right)^{2}} {n-1}}$. And here's the display version.
$$\sigma = \sqrt{\frac{\sum\limits_{i=1}^{n} \left(x_{i} - \bar{x}\right)^{2}} {n-1}}$$