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

$$1/(2*pi)(\int_{-\infty}^{\infty} S_x(\omega) d\omega)$$
