
<!-- toc orderedList:0 -->

- [颜色](#颜色)
- [原色](#原色)
	- [叠加型原色](#叠加型原色)
	- [消减型原色](#消减型原色)
- [牛顿色环](#牛顿色环)
	- [色环](#色环)
	- [颜色关系](#颜色关系)
		- [基础变化](#基础变化)
		- [单色](#单色)
		- [相似](#相似)
		- [补色](#补色)
		- [三色组](#三色组)
- [颜色的三要素](#颜色的三要素)
	- [色相](#色相)
	- [饱和度](#饱和度)
	- [明度](#明度)
- [色温与白平衡](#色温与白平衡)
	- [色温](#色温)
	- [白平衡](#白平衡)
- [参考](#参考)

<!-- tocstop -->
# 颜色

颜色要怎么样去定义？

相较于将颜色定义成一种物理属性，其实将其归划为生理现象会更加的合适。这种说法取决于我们看到颜色的原理和过程。人类的视网膜中存在一种视觉细胞称之为[视锥细胞](http://baike.baidu.com/view/852250.htm)，在视锥细胞中含有特殊的感光色素可以让其具备辨别颜色的能力。在基本认识中都会知道，人眼可以分辨`红橙黄绿青蓝紫`七种不同颜色；但是在实际的检测中会发现，人眼在可见光谱范围内可以区分出来的颜色不下150种，这也就意味着在可以见光光波范围内波长只要有3-5nm的增减都会被视觉系统判别为不同的颜色。那么是否可以认为人眼的视锥细胞种存在着150种以上的感光色素，在这里需要引入`视觉三原色学说`

> 设想在视网膜中存在着分别对红、绿、蓝的光线特别敏感的三种视锥细胞或相应的三种感光色素，并且设想当光谱上的波和介于这三者之间的光线作用于视网膜时，这些光线可对敏感波长与之相近两种视锥细胞或感光色素起不同程度的刺激作用，于是在中枢引起介于此二原色之间的其他颜色的感觉。

这个学说用比较简答的生理系统解释了复杂的颜色视觉形成的原因，虽然在到目前位置都不能够直接地通过找出三种不同类型地视锥细胞或者是感光色素来论证整个学说地成立，但是也存在大量地临床试验证明了该学说地可靠性。



# 原色

> 原色是指不能透过其他颜色的混合调配而得出的“基本色”

首先原色应该是一个生物学概念而不是物理上的概念，原因在介绍介绍颜色视觉的时候已经讲过了。那么是否可以直接从颜色视觉的成因直接将`RGB`定义成原色？其实，原色并没有统一的选法，在不同的颜色空间中就会存在不同的原色组合。最常见的两种系统是`叠加型原色`和`消减型原色`。

## 叠加型原色

一般来说以光源投射时所使用的色彩是属于“叠加型”的原色系统，此系统中包含了红、绿、蓝三种原色，亦称为“三原色”。使用这三种原色可以产生其他颜色，例如红色与绿色混合可以产生黄色或橙色，绿色与蓝色混合可以产生青色（Cyan），蓝色与红色混合可以产生紫色或品红色（Magenta）。当这三种原色以等比例叠加在一起时，会变成灰色；若将此三原色的强度均调至最大并且等量重叠时，则会呈现白色。
这套原色系统常被称为“RGB色彩空间”，亦即由红（R）绿（G）蓝（B）所组合出的色彩系统

## 消减型原色

消减型原色又称为减色原色。一般来说以反射光源或颜料着色时所使用的色彩是属于“消减型”的原色系统，此系统中包含了黄色、青色（Cyan）、品红（Magenta）三种原色[4]，是另一套“三原色”系统。在传统的颜料着色技术上，通常红、黄、蓝会被视为原色颜料，这种系统较受艺术家的欢迎[5]。（现代的美术书已不采用这种说法，而采用消减型的三原色。）当这三种原色混合时可以产生其他颜色，例如黄色与青色混合可以产生绿色，黄色与品红色混合可以产生红色，品红色与青色混合可以产生蓝色。当这三种原色以等比例叠加在一起时，会变成灰色；若将此三原色的饱和度均调至最大并且等量混合时，理论上会呈现黑色，但实际上由于颜料的原因呈现的是浊褐色。
正因如此，在印刷技术上，人们采用了第四种“原色”——黑色，以弥补三原色之不足。这套原色系统常被称为“CMYK色彩空间”，亦即由青（C）品红（M）黄（Y）以及黑（K）所组合出的色彩系统。

# 牛顿色环

## 色环

色环是将可以见光区域的颜色以圆环来表示，在1666年由`艾萨克·牛顿`首创之后一直不断演变沿用至今。

![不同时期的色环](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/color-wheel-01.jpeg)


在色环上将颜色分成了三个等级`原色、二级色、三集色`

**原色**
红、黄、蓝，这三个颜色不能通过任何其他颜色混合形成，而其他颜色都是通过这三个颜色混合而成

**二级色**
绿（黄与蓝混合）、橙（红与黄混合）、紫（蓝与红混合）

**三级色**
橙黄、橙红、红紫、蓝紫、蓝绿以及黄绿，这六种颜色都是一个原色与一个二级色混合而成，从颜色的名字就可以看出来了

![色环颜色等级划分](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/color-wheel-02.jpeg)

**有彩色系**
指包括在可见光谱中的全部色彩，它以红、橙、黄、绿、青、蓝、紫等为基本色。基本色之间不同量的混合、基本色与无彩色之间不同量的混合说产生的千千万万种色彩都属于有彩色系。有彩色系是由光的波长和振幅决定的，波长决定色相，振幅决定色调。有彩色系中的任何一种颜色都具有三大属性，即色相、明度和纯度。也就是说一种颜色只要具有以上三种属性都属于有彩色系。

**无彩色系**
指由黑色、白色及黑白两色相融而成的各种深浅不同的灰色系列。从物理学的角度看，它们不包括在可见光谱之中，故不能称之为色彩。但是从视觉生理学和心理学上来说，它们具有完整的色彩性，应该包括在色彩体系之中。
无彩色系按照一定的变化规律，由白色渐变到浅灰、中灰、深灰直至黑色，色彩学上称为黑白系列。黑白系列中由白到黑的变化，可以用一条垂直轴表示，一端为白，一端为黑，中间有各种过渡的灰色。纯白是理想的完全反射物体，纯黑是理想的完全吸收物体。可是在现实生活中并不存在纯白和纯黑的物体，颜料中采用的锌白和铅白只能接近纯白，煤黑只能接近纯黑。
无彩色系的颜色只有明度上的变化，而不具备色相与纯度的性质，也就是说它们的色相和纯度在理论时等于零。二色彩的明度可以用黑白度来表示，愈接近白色，明度越高;越接近黑色，明度愈低。

## 颜色关系

### 基础变化

- 减淡(Tint)，将某种颜色和白色混合
- 加深(Shade)，将某种颜色和黑色混合
- 变灰(Tone)，将某种颜色和灰色混合

![基础变化](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/monochrome-01.png)

### 单色

单色指的是某种颜色经历上述所有基础变化的颜色之间的关系

![单一色](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/monochrome-03.png)

### 相似

相似指的是在色轮上相邻的颜色，这些颜色会过渡的比较自然

![相似色](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/analogous-01.png)

### 补色

补色指的是在色轮上处于对称位置的颜色，这种关系的颜色混合使用的时候会形成比较突出的效果。

![补色](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/complementary-01.png)

### 三色组

三色组指的是在色环中取得三点平衡的颜色关系

![三色组](http://s0-weizhifeng-net.b0.upaiyun.com/images/design/basic-color-theory/triadic-01.png)


# 颜色的三要素

## 色相

色相即色彩的相貌名称，例如红色、绿色、蓝色等等称谓。色相是色彩的首要特征，是区别不同色彩最准确的标准。除黑白灰以外的其他颜色都有色相属性。色相从本质上来说是不同波长的光线进入人眼睛之后，人对此产生的不同视觉感受的一种描述。蓝色和绿色之所以能够被我们区分，正是因为蓝色和绿色对应的光线具有不同的波长。

## 饱和度

饱和度是指色彩的纯度，一种颜色的饱和度越高，它就越鲜艳；反之，一种颜色的饱和度越低，它就越接近于灰色。

![饱和度](http://mmbiz.qpic.cn/mmbiz_png/Yf3ZyUvU9QAr2InBHV4j7nP0ojdLiaQnaxaVh5U13rNdQoWqIh5veBlbl5I6jyktc2EiayajpRLI2tSRgNbsh7nQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1)

## 明度

明度即是指一种颜色的明亮程度。同一种颜色有明暗之分，例如浅蓝色和深蓝色，不同颜色之间也有明暗之分，例如黄色的明度就相对比较高，紫色的明度就相对比较低。

![明度对比1](http://mmbiz.qpic.cn/mmbiz_png/Yf3ZyUvU9QDibFUYFeOMNZScPt84wMKSvN9b6fiasr2umnL6UlwHicPdgdhia9mZFDdE8mLtmDkEqFT0iaJgyhhnaeA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1)

通过颜色的三个基本属性，可以在某些具体具体的颜色空间模型中确定唯一的一个颜色

![颜色空间模型](http://a0.att.hudong.com/56/56/01300000179261122969567819117.jpg)

# 色温与白平衡

## 色温

**黑体理论**
英国著名物理学家开尔文认为，假定某一黑体物质，能够将落在其上的所有热量吸收，而没有损失，同时又能够将热量生成的能量全部以“光”的形式释放出来的话，它便会因受到热力的高低而变成不同的颜色。

![色温表示](https://upload.wikimedia.org/wikipedia/commons/0/0e/Color_temperature.svg)

所以当光源和某个温度的热黑体辐射体具有相同颜色时，就可以将该温度称为该光源的色温，用开尔文(K)作为单位。

## 白平衡

由于人眼具有独特的适应性，使我们有的时候不能发现色温的变化。比如在钨丝灯下呆久了，并不会觉得钨丝灯下的白纸偏红，如果突然把日光灯改为钨丝灯照明，就会觉查到白纸的颜色偏红了，但这种感觉也只能够持续一会儿。摄像机的CCD并不能像人眼那样具有适应性，所以如果摄像机的色彩调整同景物照明的色温不一致就会发生偏色。那么什么是白平衡呢？白平衡就是针对不同色温条件下，通过调整摄像机内部的色彩电路使拍摄出来的影像抵消偏色，更接近人眼的视觉习惯。白平衡可以简单地理解为在任意色温条件下，摄像机镜头所拍摄的标准白色经过电路的调整，使之成像后仍然为白色。

# 参考

- [视锥细胞-百度百科](http://baike.baidu.com/view/852250.htm)
- [原色-维基百科](https://zh.wikipedia.org/wiki/%E5%8E%9F%E8%89%B2)
- [白平衡与色温](https://www.douban.com/note/93264756/)
