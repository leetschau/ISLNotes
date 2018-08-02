Conceptual Exercises of Chapter 10
================

-   [Question 1](#question-1)
    -   [1a](#a)
    -   [1b](#b)
-   [Question 2](#question-2)

Question 1
==========

1a
--

Prove (10.12):

![
\\frac1{|C\_k|} \\sum\_{i,i' \\in C\_k} \\sum\_{j=1}^p (x\_{ij} - x\_{i'j}) ^ 2
= 2 \\sum\_{i \\in C\_k} \\sum\_{j=1}^p (x\_{ij} - \\bar x\_{kj}) ^ 2
](https://latex.codecogs.com/png.latex?%0A%5Cfrac1%7B%7CC_k%7C%7D%20%5Csum_%7Bi%2Ci%27%20%5Cin%20C_k%7D%20%5Csum_%7Bj%3D1%7D%5Ep%20%28x_%7Bij%7D%20-%20x_%7Bi%27j%7D%29%20%5E%202%0A%3D%202%20%5Csum_%7Bi%20%5Cin%20C_k%7D%20%5Csum_%7Bj%3D1%7D%5Ep%20%28x_%7Bij%7D%20-%20%5Cbar%20x_%7Bkj%7D%29%20%5E%202%0A "
\frac1{|C_k|} \sum_{i,i' \in C_k} \sum_{j=1}^p (x_{ij} - x_{i'j}) ^ 2
= 2 \sum_{i \in C_k} \sum_{j=1}^p (x_{ij} - \bar x_{kj}) ^ 2
")

其中：

![
\\bar x\_{kj} = \\frac1{|C\_k|} \\sum\_{i \\in C\_k} x\_{ij}
](https://latex.codecogs.com/png.latex?%0A%5Cbar%20x_%7Bkj%7D%20%3D%20%5Cfrac1%7B%7CC_k%7C%7D%20%5Csum_%7Bi%20%5Cin%20C_k%7D%20x_%7Bij%7D%0A "
\bar x_{kj} = \frac1{|C_k|} \sum_{i \in C_k} x_{ij}
")

证明：

等式左边引入 ![\\bar x\_{kj}](https://latex.codecogs.com/png.latex?%5Cbar%20x_%7Bkj%7D "\bar x_{kj}") 项并展开： $$ 1{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{i'j}) ^ 2 \\

= 1{|C\_k|} *{i,i' C\_k} *{j=1}^p \[(x\_{ij} - x\_{kj}) - (x\_{i'j} - x\_{kj})\] ^ 2 \\

= 1{|C\_k|} *{i,i' C\_k} *{j=1}^p \[(x\_{ij} - x\_{kj}) ^ 2 + (x\_{i'j} - x\_{kj}) ^ 2 - 2 (x\_{ij} - x\_{kj})(x\_{i'j} - x\_{kj})\] \\

= 1{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{kj}) ^ 2 + 1{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{i'j} - x\_{kj}) ^ 2 - 2{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{kj})(x\_{i'j} - x\_{kj}) $$

由于

![
\\frac1{|C\_k|} \\sum\_{i,i' \\in C\_k} \\sum\_{j=1}^p (x\_{ij} - \\bar x\_{kj}) ^ 2
](https://latex.codecogs.com/png.latex?%0A%5Cfrac1%7B%7CC_k%7C%7D%20%5Csum_%7Bi%2Ci%27%20%5Cin%20C_k%7D%20%5Csum_%7Bj%3D1%7D%5Ep%20%28x_%7Bij%7D%20-%20%5Cbar%20x_%7Bkj%7D%29%20%5E%202%0A "
\frac1{|C_k|} \sum_{i,i' \in C_k} \sum_{j=1}^p (x_{ij} - \bar x_{kj}) ^ 2
")

实际上是

![
\\frac1{|C\_k|} \\sum\_{i=1}^{C\_k} \\sum\_{i'=1}^{C\_k} \\sum\_{j=1}^p (x\_{ij} - \\bar x\_{kj}) ^ 2
](https://latex.codecogs.com/png.latex?%0A%5Cfrac1%7B%7CC_k%7C%7D%20%5Csum_%7Bi%3D1%7D%5E%7BC_k%7D%20%5Csum_%7Bi%27%3D1%7D%5E%7BC_k%7D%20%5Csum_%7Bj%3D1%7D%5Ep%20%28x_%7Bij%7D%20-%20%5Cbar%20x_%7Bkj%7D%29%20%5E%202%0A "
\frac1{|C_k|} \sum_{i=1}^{C_k} \sum_{i'=1}^{C_k} \sum_{j=1}^p (x_{ij} - \bar x_{kj}) ^ 2
")

且 ![(x\_{ij} - \\bar x\_{kj}) ^ 2](https://latex.codecogs.com/png.latex?%28x_%7Bij%7D%20-%20%5Cbar%20x_%7Bkj%7D%29%20%5E%202 "(x_{ij} - \bar x_{kj}) ^ 2") 与 ![i'](https://latex.codecogs.com/png.latex?i%27 "i'") 无关，所以有： $$ 1{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{kj}) ^ 2 \\

= *{i=1}^{C\_k} *{j=1}^p (x\_{ij} - x\_{kj}) ^ 2 \\

= *{i=1}^{C\_k} *{j=1}^p (x\_{ij} - x\_{kj}) ^ 2 $$

对于 ![i'](https://latex.codecogs.com/png.latex?i%27 "i'") 项的处理与上面相同，两项将下标统一为 ![i](https://latex.codecogs.com/png.latex?i "i") 后值相同，可以合并，再代入(1)式得： $$ 1{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{i'j}) ^ 2 \\

= 2*{i=1}^{C\_k} *{j=1}^p (x\_{ij} - x\_{kj}) ^ 2 - 2{|C\_k|} *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{kj})(x\_{i'j} - x\_{kj}) $$

我们看上式中第2项： $$ *{i,i' C\_k} *{j=1}^p (x\_{ij} - x\_{kj})(x\_{i'j} - x\_{kj}) \\

= *{i=1}^{C\_k} *{i'=1}^{C\_k} *{j=1}^p (x*{ij} - x\_{kj})(x\_{i'j} - x\_{kj}) \\

= *{j=1}^p *{i=1}^{C\_k} *{i'=1}^{C\_k} (x*{ij} - x\_{kj})(x\_{i'j} - x\_{kj}) \\

= *{j=1}^p *{i=1}^{C\_k} $$

结合 ![\\bar x\_{kj}](https://latex.codecogs.com/png.latex?%5Cbar%20x_%7Bkj%7D "\bar x_{kj}") 的定义，可知上式中： $$ *{i'=1}^{C\_k} (x*{i'j} - x\_{kj})

= *{i'=1}^{C\_k} x*{i'j} - *{i'=1}^{C\_k} x*{kj}

= 0 $$

所以式 (3) 的值为0，再代入式 (2)，正是书中 (10.12) 式。

证明式 (3) 恒等于0的 R 验证：

``` r
subprodsum <- function(inp) {
  m <- mean(inp)
  x1 <- inp - m
  x2 <- inp - m
  df <- expand.grid(x1 = x1, x2 = x2)
  df$y <- df$x1 * df$x2
  return(sum(df$y))
}

subprodsum(c(1.764, 3.22, 87.22, 232, 29.223, 100.92))
```

    ## [1] -3.439027e-12

``` r
subprodsum(rnorm(100, mean = 5, sd = 8))
```

    ## [1] 1.450506e-13

``` r
subprodsum(runif(33, 3, 8))
```

    ## [1] 1.16053e-15

1b
--

算法10.1每次迭代的第2b步，以离点A最近的质心 ![x\_{km}](https://latex.codecogs.com/png.latex?x_%7Bkm%7D "x_{km}") 代替原来的质心 ![x\_{kq}](https://latex.codecogs.com/png.latex?x_%7Bkq%7D "x_{kq}")，意味着式 (10.12) 右侧 ![\\sum\_{j=1}^p (x\_{ij} - \\bar x\_{kj}) ^2](https://latex.codecogs.com/png.latex?%5Csum_%7Bj%3D1%7D%5Ep%20%28x_%7Bij%7D%20-%20%5Cbar%20x_%7Bkj%7D%29%20%5E2 "\sum_{j=1}^p (x_{ij} - \bar x_{kj}) ^2") 一定会减小，从而保证式 (10.11) 随着迭代的进行而不断减小。

Question 2
==========
