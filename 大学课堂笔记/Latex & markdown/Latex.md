# Latex的语法

---

## 常用的文本格式

### 标题

用“#”来表示标题，前面的#越多，代表标题越小。

### 加粗，斜体等
用**来加粗，用*来斜体，用==来高亮
例：**我是加粗**，*我是斜体*， ==我是高亮==

### 分割线

三条横线来表示分割线，如：

---

### 有序无序列表
使用*来无序列表，使用1.来有序列表

### 引用文本
使用">"进行引用
例：
> 你会死。——吴享平

### 注释
使用"<!--注释>"进行注释
例：
<!--你看不见我-->

## 数学公式

### 大于小于号
    使用\le,\leq进行小于
    使用\ge,\geq进行大于

小于：$\le$
大于：$\ge$
不等于：$\ne$
### 上下标
    使用"^"和"_"进行上下标
    $x_1^2+y_1^2=1$
    使用单引号‘进行求导
$x_1^2+y_1^2=1$
$y=x^2\to y'=2x$

### 分式
    较小的行内行分数 $\frac{1}{2}$
    展示型的分式 $\displaystyle\frac{x+1}{x-1}$
$\frac{1}{2}$, $\displaystyle\frac{x+1}{x-1}$

### 根式
    开平方 $\sqrt{2}$
    开 n 次方 $\sqrt[n]{2}$
$\sqrt{2}$
$\sqrt[n]{2}$

### 三圆点
    下标圆点$\ldots$
    居中圆点$\cdots$
下标圆点$\ldots$
居中圆点$\cdots$

### 空格
    数学公式中的空将被忽略
    紧贴 $a\!b$
    没有空格 $ab$
    小空格 $a\,b$
    中等空格 $a\;b$
    大空格 $a\ b$
    quad 空格 $a\quad b$
    两个 quad 空格 $a\qquad b$
    紧贴 $a\!b$
紧贴$a\!b$
没有空格 $ab$
小空格 $a\,b$
中等空格 $a\;b$
大空格 $a\ b$
quad 空格 $a\quad b$
两个 quad 空格 $a\qquad b$

###极限
    极限：$$\lim_{n\to \infty} \frac{1}{n}$$
极限：$$\lim_{n\to \infty} \frac{1}{n}$$


### 累加，累乘与积分
    累加 $\sum_{k=1}^n\frac{1}{k}  \quad  \displaystyle\sum_{k=1}^n\frac{1}{k}$

    累乘 $\prod_{k=1}^n\frac{1}{k}  \quad  \displaystyle\prod_{k=1}^n\frac{1}{k}$

    积分 $\displaystyle \int_0^1x{\rm d}x  \quad  \iint_{D_{xy}}  \quad  \iiint_{\Omega_{xyz}}$
累加 $$\sum_{k=1}^n\frac{1}{k}  \quad  \displaystyle\sum_{k=1}^n\frac{1}{k}$$

累乘 $$\prod_{k=1}^n\frac{1}{k}  \quad  \displaystyle\prod_{k=1}^n\frac{1}{k}$$

积分 $$\displaystyle \int_0^1x{\rm d}x  \quad  \iint_{D_{xy}}  \quad  \iiint_{\Omega_{xyz}}$$

