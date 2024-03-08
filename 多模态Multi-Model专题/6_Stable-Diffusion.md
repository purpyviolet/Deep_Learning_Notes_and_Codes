# Stable-Diffusion

通过文本来生成图片

## 模型架构

![image-20240308165002340](6_Stable-Diffusion.assets/image-20240308165002340.png)

在输入了文字之后，传入Text Encoder，然后形成向量（用Clip编码器）

向量之后传入Image Generator后生成图片



## Image Generator

![image-20240308165223068](6_Stable-Diffusion.assets/image-20240308165223068.png)

首先传入噪声图片（随机生成），每一个像素点都是随机生成的。通过