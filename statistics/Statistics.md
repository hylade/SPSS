# Statistics

## mid-range

最大数和最小数总和的二分之一



##pictograph（象形统计图）



## 茎叶图

将十位作为stem，将个位作为leaf



## Box-and-whisker（盒须图）

将所有数据的范围在坐标轴上标识出来，然后将中间两个四分位点作为box的两边，作图box；再将中位数在box中表示出来（在median处用直线）；再把四分位点处的box边外伸箭头，指向开头和结尾数据，作为图的whisker



## 样本和总体

样本均值（sample mean）：$\overline{X} = \frac{\sum\limits_{i=1}^n x_i} n$

总体均值（population mean）：$\mu = \frac{\sum\limits_{i=1}^N x_i} N$



## 总体方差

$\sigma^2 = \frac{\sum\limits_{i=1}^N(x_i-\mu)^2}N$

 化简后得到$\sigma^2=\frac{\sum_\limits{n=1}^N(x_i)^2}{N}-\mu^2$



## 样本方差

$S^2 = \frac{\sum\limits_{i=1}^n(x_i-\mu)^2}n$,为了与总体方差更为接近，可以使用$S^2 = \frac{\sum\limits_{i=1}^N(x_i-\mu)^2}{N-1}$



## 标准差

$\sigma=\sqrt{\sigma^2}$



##随机变量(Random Variable)

一般采用大写字母表示

$Random Variable = \begin{cases} Discrete\ Variable,&\text{离散随机变量} \\ Continuous \ Variable, & \text{连续随机变量} \end{cases}$



## 二项分布

$P(X=n) = \frac{N！}{n！\cdot(N-n)!}\cdot(P)^n\cdot(1-P)^{N-n}$

### 期望值

$E(X) = n\cdot p$



## 期望值

期望值与总体均值实质上是一样的，但是由于总体均值无法除以总数N，故而以频率作为权重来计算加权平均值



## 泊松分布

$P(X=k) = \lim\limits_{n \to \infty}\begin{pmatrix} n\\k \\ \end{pmatrix} \cdot (\frac{\lambda}{n})^k \cdot (1-\frac{\lambda}{n})^{n-k} = \frac{\lambda^k}{k!} \cdot e^{-\lambda}$



## 大数定律

当样本数量足够大时，样本均值趋近于期望值



## 正态分布

$p(x) = \frac{1}{\sigma \sqrt{2 \pi}} e^{{-\frac{1}{2}}(\frac{x-\mu}{\sigma})^2}$



###z分数

$z = \frac{x-\mu}{\sigma}$

​	

##均值标准误差（standard error of the mean）

$\sigma_{\overline{X}}^2 = \frac{\sigma^2}{n}$



## 伯努利分布

### 均值

$\mu = p$



### 方差

$\sigma^2 = p-p^2$



## 随机变量的方差

$E(x) = \mu_x$

$E((X-\mu_x)^2) = \sigma_x^2$

$Z = X + Y;E(Z) = E(X+Y)= E(X) +E(Y);\mu_z = \mu_x + \mu_y;\sigma_z^2=\sigma_x^2+\sigma_y^2;\sigma_{x-y}^2 = \sigma_x^2+\sigma_y^2$



## 线性回归问题

### 最小误差条件(即最佳回归线)

$m = \frac{\overline{x}\ \overline{y}-\overline{xy}}{(\overline{x})^2-\overline{x^2}}$

$b = \overline{y}-m\overline{x}$



### 决定系数

$r^2 = 1-\frac{SE_{line}}{SE_{\overline{y}}}$



## 协方差

$Cov(X,Y) = E[(X-E[X])(Y-E[Y])]=E[XY]-E[X]\cdot E[Y]=\overline{XY}-\overline{X}\ \overline{Y}$



##$\chi^2 分布$

### 列联表

自由度位（行数-1）*（列数-1）