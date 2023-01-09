# AI-Deep-learning
Thanks for the class - Project Design of Deep Learning, 09/2022-01/2023

致謝 - 深度學習專案課程, 09/2022-01/2023

I want to share knowledge about AI and Deep Learning here!

希望在這裡分享關於AI和深度學習的知識

Hoping to help anyone interested in this "Super and Crazy AI".

希望讓每個人都對AI抱持開放與熱忱

(內有詳細中文註釋!)

宽意义平稳随机过程的数学定义是：对于任意的时间偏移量 $\tau$，过程 $x(t)$ 的自相关函数 $\mathbb{E}[x(t) \cdot x(t-\tau)]$ 不随 $t$ 的变化而变化。

一般的非平稳随机过程的自相关函数比较复杂，因为它们的平均值和方差会随时间的变化而变化。而宽意义平稳随机过程的自相关函数比较简单，因为它们的平均值和方差不随时间的变化而变化。

自相关函数 $\mathbb{E}[x(t) \cdot x(t-\tau)]$ 的傅里叶变换称为功率谱密度函数，其物理意义是表示信号 $x(t)$ 的能量在不同频率范围内的分布情况。

我们将功率谱密度函数的傅里叶变换记为 $S_x(\omega)$，则以下积分表示信号 $x(t)$ 在频率 $\omega$ 处的能量：

$$1/(2*pi)\int_{-\infty}^{\infty} S_x(\omega) d\omega$$


广义平稳随机过程是指一个随机过稳，使得它的统计性质（例如均值和自相关函数）在时间上是不变的。这意味着，对于任意的时间点 t，过程 x(t) 在统计意义上与 x(t+k) 具有相同的分布。

自相关函数 R(tau) 是指一个过程的时间延迟相关性的度量。它被定义为期望值，即 E[x(t) * x(t-tau)]。由于广义平稳随机过稳的统计性质是不变的，因此它的自相关函数也是不变的。这使得自相关函数比一般非平稳随机过稳的自相关函数更简单。

Fourier变换是一种数学工具，用于将信号从时间域转换到频率域。Fourier变换 R(tau) 被称为频谱。它描述了在不同频率下信号的能量分布。

称$$1/(2*pi)\int_{-\infty}^{\infty} S_x(\omega) d\omega$$ 为信号 x 的带宽。它表示在信号中所有有效能量所覆盖的频率范围。
