
### 绘图机工作原理
-  光栅扫描，随机扫描处理
-  二维线画图元
-  扫描转换直线段
-  DDA算法 
-  中点划线法

### 圆弧，椭圆弧扫描转换

  - 中点算法

  - 内接多边形迫近法，直线逼近圆

  - 等面积多边形逼近法

  - 生成圆弧的正负法

  - 扫描转换矩形的基本算法

### 扫描转换多边形方法

  - 多边形表示方法
  - 逐点判断法
    - 射线法
    - 累计角度法
    - 编码法
  - 逐点判断法缺点 如何改进

### 二维线画图元
  - 二维填充图元的生成
  - 边的连贯性， 扫描线的连贯性， 区间连贯性
  - 扫描线算法基本原理
  - 扫描线算法数据结构
  - 扫描线算法步骤
  - 边缘填充算法原理

- 区域填充算法

- 区域表示和类型

  - 内点表示
  - 边界表示
  - 连通性

- 区域种子填充算法原理

- 边界表示填充算法原理



### 二维裁剪

- 直线段裁剪原理
  - 直接求交算法：
    - 编码算法 Cohen-Sutherland算法
    - 细分法 Nicholl-Lee-Nicholl算法
    - 中点算法



### 图形变换

- 二维基本变换
  -  平移变换
  - 比例变换
  - 旋转变换
- 三维几何变换
  - 三维几何变换类型
  - 绕空间任意轴变换矩阵
- 坐标系之间变换



### 投影

- 平面几何投影
  - 平面几何投影类型
  - 最常见几何投影有哪些
- 观察坐标系投影变换
  - 如何定义观察坐标系
  - 投影主要参数
  - 视见体的概念
  - 平行投影变换矩阵
  - 透视投影变换矩阵
- 三维图形显示流程图
  - 规范识见体
  - 平行，透视识见体规范化
- 三维裁剪
  - 三维裁剪的实现过程