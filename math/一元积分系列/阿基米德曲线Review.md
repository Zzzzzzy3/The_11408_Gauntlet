求积分曲线  

$$r=\theta,~\theta\in(0,2\pi)$$

由极坐标积分曲线积分公式得

$$s=\int_0^{2\pi}\sqrt{1+\theta^2}d\theta$$

不妨设为求

$$I=\int\sqrt{1+x^2}dx=x\sqrt{1+x^2}-\int\frac{x^2}{\sqrt{1+x
^2}}dx$$

由后项

$$\int\frac{x^2}{\sqrt{1+x
^2}}dx=\int\sqrt{1+x^2}dx-\int\frac{1}{\sqrt{1+x
^2}}dx$$

即

$$2I=x\sqrt{1+x^2}+\int\frac{1}{\sqrt{1+x
^2}}dx$$

上式后项由x=tanθ换元积分可得

$$\int sec\theta ~d\theta=ln|tan\theta+sec\theta|+C=ln|x+\sqrt{1+x^2}|+C$$

综上所述

$$I=\frac{1}{2}(x\sqrt{1+x^2}+ln|x+\sqrt{1+x^2}|)+C$$

则

$$s=2\pi\sqrt{1+4\pi^2}+\frac{1}{2}ln(2\pi+\sqrt{1+4\pi^2})$$

---

**Findings**

###### 关于secx积分

$$secx'=secxtanx~ ,~tanx'=sec^2x$$

式子相加后作变换得

$$secx=\frac{(secx+tanx)'}{(secx+tanx)}$$

可得secx积分为

$$\int secx dx=ln|secx+tanx|+C$$

###### 关于曲线极坐标公式

由

$$ds=\sqrt{(dx)^2+(dy)^2} ~~,~~r=r(\theta)$$

得

$$ds=\sqrt{1+[r'(\theta)]^2}d\theta$$



