## <center> 行内公式
将公式插入到本行内
$ xyz $


## <center>独行公式
将公式插入到新的一行内，并且居中，
$$ xyz \tag{1} $$


## <center>上标、下标与组合

上标符号，符号：^，如：$$ x^4 $$
下标符号，符号：_，如：$$ x_1 $$
组合符号，符号：{}，如：$$ {16}_{8}O{2+}_{2} $$


## <center>汉字、字体与格式

* 汉字形式，符号：\mbox{}
$$V_{\mbox{初始}}$$

* 字体控制，符号：\displaystyle
$$\displaystyle \frac{x+y}{y+z}$$

* 下划线符号，符号：\underline
$$\underline{x+y}$$

* 标签，符号\tag{数字}
$$\tag{11}$$

* 上大括号，符号：\overbrace{算式}
$$\overbrace{a+b+c+d}^{2.0}$$

* 下大括号，符号：\underbrace{算式}
$$ a+\underbrace{b+c}_{1.0}+d $$

* 上位符号，符号：\stacrel{上位符号}{基位符号}
$$ \vec{x}\stackrel{\mathrm{def}}{=}{x_1,\dots,x_n} $$


## <center>占位符

* 两个大空格，符号：\qquad，如：$$x \qquad y$$
* 大空格，符号：\quad，如：$$ x \quad y $$
* 中空格，符号: \: ，如：$$x \: y$$
* 小空格，符号 \, ，如：$$x \, y$$
* 没有空格，如：$$ x y $$
* 紧贴，符号 \! ，如：$$x \! y$$

## <center>定界符与组合

* 括号
$$（a）\big(a\big)  \Big(a\Big)  \bigg(a\bigg)  \Bigg(a\Bigg) $$

* 中括号
$$[x+y]$$

* 大括号
$$\{x+y\}$$

* 自适应括号，符号：\left \right，
$$ \left(xyz\right) $$

* 组合公式，符号：{上位公式 \choose 下位公式}
$$ {n+1 \choose k}={n \choose k}+{n \choose k-1} $$

* 组合公式，符号：{上位公式 \atop 下位公式}
$$ \sum_{k_0,k_1,\ldots>0 \atop k_0+k_1+\cdots=n}A_{k_0}A_{k_1}\cdots $$

## <center>四则运算

* 加法运算，符号：+
$$x+y=z$$

* 减法运算，符号：-
$$x-y=z$$

* 加减运算，符号：\pm
$$x \pm y=z$$

* 减加运算，符号：\mp
$$x \mp y=z$$

* 乘法运算，符号：\times
$$x \times y=z$$

* 点乘运算，符号：\cdot
$$x \cdot y=z$$

* 星乘运算，符号：\ast
$$x \ast y=z$$

* 除法运算，符号：\div
$$x \div y=z$$

* 斜法运算，符号：/
$$x/y=z$$

* 分式表示，符号：\frac{分子}{分母}
$$\frac{x+y}{y+z}$$

* 分式表示，符号：{分子} \over {分母}
$${x+y} \over {y+z}$$

* 绝对值表示，符号：||
$$|x+y|$$

## <center>高级运算

* 平均数运算，符号：\overline{算式}，
$$\overline{xyz}$$

* 开二次方运算，符号：\sqrt，
$$\sqrt x$$

* 开方运算，符号：\sqrt[开方数]{被开方数}
$$\sqrt[3]{x+y}$$

* 对数运算，符号：\log
$$\log(x)$$

* 极限运算，符号：\lim
$$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$

* 极限运算，符号：\displaystyle \lim
$$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$

* 求和运算，符号：\sum
$$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$

* 求和运算，符号：\displaystyle \sum
$$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$

* 积分运算，符号：\int
$$\int^{\infty}_{0}{xdx}$$

* 积分运算，符号：\displaystyle \int
$$\displaystyle \int^{\infty}_{0}{xdx}$$

* 微分运算，符号：\partial
$$\frac{\partial x}{\partial y}$$


## <center>逻辑运算

* 等于运算，符号：=
$$x+y=z$$

* 大于运算，符号：>
$$x+y>z$$

* 小于运算，符号：<
$$x+y<z$$

* 大于等于运算，符号：\geq
$$x+y \geq z$$

* 小于等于运算，符号：\leq
$$x+y \leq z$$

* 不等于运算，符号：\neq
$$x+y \neq z$$

* 不大于运算，符号：\not>
$$x+y \not> z$$

* 不小于运算，符号：\not<
$$x+y \not< z$$

* 不大于等于运算，符号：\ngep
$$x+y \ngeq z$$

* 不小于等于运算，符号：\not\leq
$$x+y \not\leq z$$

* 约等于运算，符号：\approx
$$x+y \approx z$$

* 恒定等于运算，符号：\equiv
$$x+y \equiv z$$

## <center>集合运算

1. 属于运算，符号：\in
$$x \in y$$

2. 不属于运算，符号：\notin
$$x \notin y$$

3. 不属于运算，符号：\not\in
$$x \not\in y$$

4. 子集运算，符号：\subset
$$x \subset y$$

5. 子集运算，符号：\supset
$$x \supset y$$

6. 真子集运算，符号：\subseteq
$$x \subseteq y$$

7. 非真子集运算，符号：\subsetneq
$$x \subsetneq y$$

8. 真子集运算，符号：\supseteq
$$x \supseteq y$$

9. 非真子集运算，符号：\supsetneq
$$x \supsetneq y$$

10. 非子集运算，符号：\not\subset
$$x \not\subset y$$

11. 非子集运算，符号：\not\supset
$$x \not\supset y$$

12. 并集运算，符号：\cup
$$x \cup y$$

13. 交集运算，符号：\cap
$$x \cap y$$

14. 差集运算，符号：\setminus
$$x \setminus y$$

15. 同或运算，符号：\bigodot
$$x \bigodot y$$

16. 同与运算，符号：\bigotimes
$$x \bigotimes y$$

17. 实数集合，符号：\mathbb{R}
$$\mathbb{R}$$

18. 自然数集合，符号：\mathbb{Z}
$$\mathbb{Z}$$

19. 空集，符号：\emptyset
$$\emptyset$$


## <center>数学符号

* 无穷，符号：\infty
$$\infty$$

* 虚数，符号：\imath
$$\imath$$

* 虚数，符号：\jmath
$$\jmath$$

* 数学符号，符号\hat{a}
$$\hat{a}$$

* 数学符号，符号\check{a}
$$\check{a}$$

* 数学符号，符号\breve{a}
$$\breve{a}$$

* 数学符号，符号\tilde{a}
$$\tilde{a}$$

* 数学符号，符号\bar{a}
$$\bar{a}$$

* 矢量符号，符号\vec{a}
$$\vec{a}$$

* 数学符号，符号\acute{a}
$$\acute{a}$$

* 数学符号，符号\grave{a}
$$\grave{a}$$

* 数学符号，符号\mathring{a}
$$\mathring{a}$$

* 一阶导数符号，符号\dot{a}
$$\dot{a}$$

* 二阶导数符号，符号\ddot{a}
$$\ddot{a}$$

* 上箭头，符号：\uparrow
$$\uparrow$$

* 上箭头，符号：\Uparrow
$$\Uparrow$$

* 下箭头，符号：\downarrow
$$\downarrow$$

* 下箭头，符号：\Downarrow
$$\Downarrow$$

* 左箭头，符号：\leftarrow
$$\leftarrow$$

* 左箭头，符号：\Leftarrow
$$\Leftarrow$$
 
* 右箭头，符号：\rightarrow
$$\rightarrow$$

* 右箭头，符号：\Rightarrow
$$\Rightarrow$$

* 底端对齐的省略号，符号：\ldots
$$1,2,\ldots,n$$

* 中线对齐的省略号，符号：\cdots
$$x_1^2 + x_2^2 + \cdots + x_n^2$$

* 竖直对齐的省略号，符号：\vdots
$$\vdots$$

* 斜对齐的省略号，符号：\ddots
$$\ddots$$


## <center>矩阵表示

 * 普通矩阵
$$ \begin{matrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{matrix} $$

- 单线矩阵
$$\begin{vmatrix} 1&2&3\\ 4&5&6\\ 7&8&9 \end{vmatrix}$$

- 双线矩阵
$$\begin{Vmatrix} 1&2&3\\ 4&5&6\\ 7&8&9 \end{Vmatrix}$$

- 带括号[]的矩阵
$$\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} $$  
$$ \left[ \begin{matrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{matrix} \right] $$

- 带括号{}的矩阵
$$\begin{Bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{Bmatrix} $$

- 带省略号的矩阵  
\vdots表示与文本底线对齐的省略号  
\cdots表示与文本中线对齐的省略号  
\ddots 斜着的省略号  
$$\begin{bmatrix} 1 & 2 & \cdots & 4 \\ 7 & 6 & \cdots & 5 \\ \vdots & \vdots & \ddots & \vdots \\ 8 & 9 & \cdots & 0 \\ \end{bmatrix}$$

* 带参数的矩阵  
如果希望在矩阵中画出一条分割线，以强调最右侧一列的特殊性。  
其中\begin{array}{cc|c}中的c表示元素  
$$ \left[ {\begin{array}{cc|c} 1 & 2 & 3 \\ 4 & 5 & 6 \end{array}} \right] $$

- 多元方程对齐
$$ \begin{cases} a_{11}x_1&+&a_{12}x_2&+&\cdots&+a_{1n}x_n&=&b_1\\ &&&&\vdots\\ a_{n1}x_1&+&a_{n2}x_2&+&\cdots&+a_{nn}x_n&=&b_n& \end{cases} $$

- 大括号右多行赋值
$$ \left\{\begin{array}{cc} 1, & x=f(Pa_{x})\\ 0, & other\ values \end{array}\right. $$

- 用 cases
$$ P(x|Pa_x)=\begin{cases} 1, & x=f(Pa_{x})\\ 0, & other\ values \end{cases} $$

## <center>希腊字母表
![图片](assets/IMG_1.png)