一些前置知识
- 期望
- 方差
- 协方差
- 相关系数

### **求相关系数**

$$
\rho_{XY} = \frac{\text{Cov}(X,Y)}{\sigma_X \sigma_Y}
$$

### **协方差**

对于随机变量 $X$ 和 $Y$：

$$
\text{Cov}(X,Y) = E[(X - E[X])(Y - E[Y])]
$$

$$
\text{Cov}(X,Y) = E[XY] - E[X]E[Y]
$$

- **对称性**：$\text{Cov}(X,Y) = \text{Cov}(Y,X)$
- **自协方差**：$\text{Cov}(X,X) = \text{Var}(X)$
- **与常数**：$\text{Cov}(X,c) = 0$（$c$ 为常数）
- **线性性质**：$\text{Cov}(aX + b, cY + d) = ac\text{Cov}(X,Y)$


**协方差的双线性性质**

$$
\begin{aligned}
\text{Cov}(a_1X_1 + a_2X_2, b_1Y_1 + b_2Y_2) = &\ a_1b_1\text{Cov}(X_1, Y_1) \\
& + a_1b_2\text{Cov}(X_1, Y_2) \\
& + a_2b_1\text{Cov}(X_2, Y_1) \\
& + a_2b_2\text{Cov}(X_2, Y_2)
\end{aligned}
$$

协方差:偏离各自期望乘积的期望

**当 $X$ 与 $Y$ 独立时**

$$\text{Cov}(X,Y) = 0$$

