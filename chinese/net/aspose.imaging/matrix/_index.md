---
title: Matrix
second_title: Aspose.Imaging for .NET API 参考
description: 替换 GDI 矩阵
type: docs
weight: 10560
url: /zh/net/aspose.imaging/matrix/
---
## Matrix class

替换 GDI+ 矩阵。

```csharp
public class Matrix
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Matrix](matrix#constructor)() | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix](matrix#constructor_1)(Matrix) | 复制[`Matrix`](../matrix)类。 |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | 将[`Matrix`](../matrix)类的新实例初始化为由指定矩形和点数组定义的几何变换. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | 将[`Matrix`](../matrix)类的新实例初始化为由指定矩形和点数组定义的几何变换. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | 初始化[`Matrix`](../matrix)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements) { get; } | 获取表示此[`Matrix`](../matrix)元素的浮点值数组。 |
| [M11](../../aspose.imaging/matrix/m11) { get; } | 获取第一行第一列的矩阵元素。表示沿 X 轴的比例。 |
| [M12](../../aspose.imaging/matrix/m12) { get; } | 获取第一行第二列的矩阵元素。表示沿 Y 轴的剪切。 |
| [M21](../../aspose.imaging/matrix/m21) { get; } | 获取第二行第一列的矩阵元素。表示沿 X 轴的剪切。 |
| [M22](../../aspose.imaging/matrix/m22) { get; } | 获取第二行第二列的矩阵元素。表示沿 Y 轴的比例。 |
| [M31](../../aspose.imaging/matrix/m31) { get; } | 获取第三行第一列的矩阵元素。表示沿 X 轴的平移。 |
| [M32](../../aspose.imaging/matrix/m32) { get; } | 获取第三行第一列的矩阵元素。表示沿 Y 轴的平移。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals)(object) | 确定指定的Object是否等于此实例。 |
| [GetElements](../../aspose.imaging/matrix/getelements)() | 获取矩阵元素的副本。 |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode)() | 返回此实例的哈希码。 |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply)(Matrix) | 使用（默认）前置顺序将此矩阵乘以在矩阵参数中指定的矩阵。 |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | 将此 Matrix 乘以 matrix 参数中指定的矩阵，并按照 order 参数中指定的顺序。 |
| [Reset](../../aspose.imaging/matrix/reset)() | 重置此矩阵以具有单位矩阵的元素。 |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate)(float) | 以默认（前置）顺序围绕该矩阵的原点（零 x 和 y 坐标）应用角度参数中指定的量的顺时针旋转。 |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate_1)(float, MatrixOrder) | 以指定顺序围绕该矩阵的原点（零 x 和 y 坐标）应用角度参数中指定的量的顺时针旋转。 |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat)(float, PointF) | 以默认（前置）顺序围绕指定点顺时针旋转此矩阵。 |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | 以指定顺序围绕指定点顺时针旋转此矩阵。 |
| [Scale](../../aspose.imaging/matrix/scale#scale)(float, float) | 使用（默认）前置顺序将指定的缩放向量（scaleX 和 scaleY）应用于此矩阵。 |
| [Scale](../../aspose.imaging/matrix/scale#scale_1)(float, float, MatrixOrder) | 使用指定的顺序将指定的比例矢量（scaleX 和 scaleY）应用到这个[`Matrix`](../matrix)。 |
| override [ToString](../../aspose.imaging/matrix/tostring)() | 返回代表此实例的String。 |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints)(PointF[]) | 将此[`Matrix`](../matrix)表示的几何变换应用于指定的点数组。 |
| [Translate](../../aspose.imaging/matrix/translate#translate)(float, float) | 将指定的平移向量应用于此[`Matrix`](../matrix)使用（默认）前置顺序。 |
| [Translate](../../aspose.imaging/matrix/translate#translate_1)(float, float, MatrixOrder) | 以指定的顺序将指定的平移向量应用于此矩阵。 |
| static [Equals](../../aspose.imaging/matrix/equals)(Matrix, Matrix) | 判断两个矩阵是否相等。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip) | 该标志位表示由该对象定义的变换 执行关于某个轴的镜像翻转，从而改变 除了其他标志位指示的转换之外，通常将右手坐标系转换为左手 系统。 右手坐标系是正 X 轴逆时针旋转以覆盖正 Y 轴 的坐标系，类似于您手指的方向右手 当你盯着你的拇指时会卷曲。 左手坐标系是正 X 轴顺时针旋转以覆盖正 Y 轴的坐标系，类似于 左手卷曲。 没有数学方法来确定 原始翻转或镜像变换的角度，因为在适当调整旋转的情况下，翻转的所有角度 都是相同的。 注意:TypeFlip 是在 GENERAL_TRANSFORM 公开后添加的 循环并且标志位不再方便 重新编号而不在外部引入二进制不兼容 代码。 |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation) | 该标志位表示该对象定义的变换 除了:::47::之外还执行任意角度的旋转:其他标志位指示的转换。 旋转以相同的量改变向量的角度 与向量的原始方向无关，并且没有 改变向量的长度。 该标志位与 |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale) | 通用比例将向量的长度乘以不同的 x 和 y 方向的量而不改变角度 垂直向量之间。 此标志位与 TypeUniformScale 标志互斥。 |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform) | 该常量表示该对象定义的变换 执行输入坐标的任意转换。 如果此转换可以按上述任何常量分类，则 类型将是常量 TypeIdentity 或 适当标志位的组合对于此转换执行的各种坐标 转换。 |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity) | 恒等变换是输出坐标为 始终与输入坐标相同的变换。 如果此变换不是恒等变换，则 类型将是常量 GENERAL_TRANSFORM 或 适当标志位的组合此转换执行的各种坐标 转换。 |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation) | 这个常数是任何旋转标志位的位掩码。 |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale) | 此常量是任何比例标志位的位掩码。 |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation) | 该标志位表示该对象定义的变换 在:::47::中执行 90 度的某个倍数的象限旋转:除了其他标志位指示的转换。 旋转以相同的量改变向量的角度 与向量的原始方向无关，并且没有 改变向量的长度。 此标志位与 TypeGeneralRotation 标志互斥。 |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation) | 平移将坐标在 x 和 y 中移动一个常数，而不改变向量的长度或角度。 |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale) | 统一比例将向量的长度乘以相同的量 在 x 和 y 方向上，而不改变:::47 之间的角度:::向量。 此标志位与 TypeGeneralScale 标志互斥。 |

### 评论

大多数算法取自 Sun 的 AffineTransform.java。 Java 内部使用的矩阵元素的名称。 java 名称到 .net 的映射到描述: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 比例 Y m02 M31 平移 X m12 M32 平移 Y

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
