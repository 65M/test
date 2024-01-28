# 头戴式MR眼镜的显示原理

## 1. MR相关的基本概念

### 1.1 AR、VR和MR介绍

AR(Augment Reality): 通过数字信息扩展现实世界

VR(Virtual Reality): 完全沉溺在虚拟世界中

MR(Mixed Reality): 现实世界和虚拟世界交互

![image-20240128204742129](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204742129.png)![image-20240128204747390](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204747390.png)![image-20240128204751466](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204751466.png)

![image-20240128204805564](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204805564.png)![image-20240128204809240](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204809240.png)![image-20240128204812874](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204812874.png)

### 1.2 显示方式介绍

完全沉浸型：虚拟数字信息   

光学透视型：虚拟数字信息+真实的物理世界信息

视频透视型：虚拟数位信息+Camera拍摄到的真实的物理世界信息

![image-20240128204901497](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128204901497.png)

​    		

### 1.3 显示参数介绍

**Eyebox** ：(眼动范围)眼球可移动观看的范围

![image-20240128205257735](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128205257735.png)

**FOV** (视场角)：影像投射出来的角度

![image-20240128205301111](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128205301111.png)

**Eye Relief** (出瞳距离)：眼镜到显示器的距离

![image-20240128205305103](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128205305103.png)

**PPD** **(**Pixels Per Degree)：每一度视场角的像素数

![image-20240128205308853](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128205308853.png)

## 2. 进眼显示

### 2.1 进眼显示模组结构

![image-20240128211024380](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128211024380.png)

### 2.2 微型显示器

通过控制每个像素的颜色和亮度最终形成色彩各异的画面

![image-20240128212713094](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128212713094.png)

自发光型：每个像素都由R/G/B三个sub-pixel组成，通过控制sub-pixel亮度合成像素颜色

投影型：通过电路控制每个像素点将投影的图象光源进行反射实现画面显示

### 2.3 光学成像元件

通过透镜使得虚拟图像光源在折射光作用下被放大数倍以虚像的形式在人眼视网膜上成像

![image-20240128212845569](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128212845569.png)

VR(左边): 微型显示器发出的光源直接经由Imaging Optics后成像在人眼中

AR(右边): 微型显示器发出的光源直接经由Imaging Optics后由AR镜片的Combiner optics折，反射后进入人眼成像

### 2.4 光学传导元件

通過控制每個像素的顏色和亮度最終形成色彩各異的畫面

![image-20240128213033465](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240128213033465.png)

## 3. 常见显示技术

### 3.1 投影显示

投影显示是通过在眼镜内部集成微型投影仪，将虚拟图像投射到用户眼睛上方的透明镜片上，再反射到视网膜上，实现虚拟图像的显示。

### 3.2 透明显示

透明显示技术通过在眼镜上方或内部嵌入微型显示屏，将图像以透明形式呈现，用户可以透过显示屏看到虚拟图像，同时也能看到背景环境，实现虚拟与现实的融合显示。

### 3.3 光学波导显示

光学波导显示是通过在眼镜上嵌入微型波导，利用全息或衍射原理，将虚拟图像以全息投影或衍射方式投射到用户视野中，实现虚拟图像的显示。

### 3.4 全息显示

全息显示技术利用全息光学原理，在眼镜内部嵌入全息光栅或全息显示元件，将光场信息分解并重建，通过干涉和衍射效应，实现真实感极强的虚拟图像显示。

