---
title: "类 Matrix"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Matrix 类。替代 GDI Matrix。"
type: docs
weight: 11100
url: /zh/net/aspose.imaging/matrix/
---
## Matrix class

替代 GDI+ 矩阵。

```csharp
public class Matrix
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 将 Matrix 类初始化为单位矩阵的新实例。 |
| [Matrix](matrix/#constructor_1)(Matrix) | 创建 `Matrix` 类的副本。 |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 将 `Matrix` 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 将 `Matrix` 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | 初始化 `Matrix` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements/) { get; } | 获取一个浮点值数组，表示此 `Matrix` 的元素。 |
| [M11](../../aspose.imaging/matrix/m11/) { get; } | 获取第一行第一列的矩阵元素。表示沿 X 轴的缩放。 |
| [M12](../../aspose.imaging/matrix/m12/) { get; } | 获取矩阵第一行第二列的元素。表示沿 Y 轴的剪切。 |
| [M21](../../aspose.imaging/matrix/m21/) { get; } | 获取矩阵第二行第一列的元素。表示沿 X 轴的剪切。 |
| [M22](../../aspose.imaging/matrix/m22/) { get; } | 获取矩阵第二行第二列的元素。表示沿 Y 轴的缩放。 |
| [M31](../../aspose.imaging/matrix/m31/) { get; } | 获取矩阵第三行第一列的元素。表示沿 X 轴的平移。 |
| [M32](../../aspose.imaging/matrix/m32/) { get; } | 获取矩阵第三行第一列的元素。表示沿 Y 轴的平移。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [GetElements](../../aspose.imaging/matrix/getelements/)() | 获取矩阵元素的副本。 |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode/)() | 返回此实例的哈希码。 |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply)(Matrix) | 使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。 |
| [Reset](../../aspose.imaging/matrix/reset/)() | 将此 Matrix 重置为具有单位矩阵的元素。 |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate)(float) | 在默认（Prepend）顺序下，对此 Matrix 在原点（零 x 和 y 坐标）进行角度参数指定的顺时针旋转。 |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate_1)(float, MatrixOrder) | 在指定的顺序下，对此 Matrix 在原点（零 x 和 y 坐标）进行角度参数指定的顺时针旋转。 |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat)(float, PointF) | 在默认（Prepend）顺序下，对此 Matrix 绕指定点进行顺时针旋转。 |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 在指定的顺序下，对此 Matrix 绕指定点进行顺时针旋转。 |
| [Scale](../../aspose.imaging/matrix/scale/#scale)(float, float) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [Scale](../../aspose.imaging/matrix/scale/#scale_1)(float, float, MatrixOrder) | 使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 `Matrix`。 |
| override [ToString](../../aspose.imaging/matrix/tostring/)() | 返回表示此实例的 String。 |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints/)(PointF[]) | 将此 `Matrix` 表示的几何变换应用于指定的点数组。 |
| [Translate](../../aspose.imaging/matrix/translate/#translate)(float, float) | 使用（默认）Prepend 顺序，将指定的平移向量应用于此 `Matrix`。 |
| [Translate](../../aspose.imaging/matrix/translate/#translate_1)(float, float, MatrixOrder) | 在指定的顺序下，将指定的平移向量应用于此 Matrix。 |
| static [Equals](../../aspose.imaging/matrix/equals/)(Matrix, Matrix) | 确定两个矩阵是否相等。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip/) | 此标志位指示此对象定义的变换在执行关于某轴的镜像翻转时，会将通常的右手坐标系转换为左手坐标系，并且还会进行其他标志位指示的转换。右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，类似于右手拇指指向观察者时手指的卷曲方向。左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，类似于左手拇指指向观察者时手指的卷曲方向。由于在适当的调整旋转下所有翻转角度均相同，无法通过数学方法确定原始翻转或镜像变换的角度。注意：TypeFlip 是在 GENERAL_TRANSFORM 已公开流通后添加的，标志位已无法在不引入外部代码二进制不兼容的情况下方便地重新编号。 |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation/) | 此标志位指示此对象定义的变换在执行任意角度的旋转时，还会进行其他标志位指示的转换。旋转会以相同的量改变向量的角度，而不论向量的原始方向，并且不改变向量的长度。此标志位与 |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale/) | 一般缩放会在 x 和 y 方向上以不同的量乘以向量的长度，而不改变垂直向量之间的角度。此标志位与 TypeUniformScale 标志互斥。 |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform/) | 此常量指示此对象定义的变换执行对输入坐标的任意转换。如果此变换可以由上述任意常量分类，则类型将是常量 TypeIdentity，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity/) | 单位变换是指输出坐标始终与输入坐标相同的变换。如果此变换不是单位变换，则类型将是常量 GENERAL_TRANSFORM，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation/) | 此常量是用于任何旋转标志位的位掩码。 |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale/) | 此常量是用于任意比例标志位的位掩码。 |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation/) | 此标志位表示此对象定义的变换在执行其他标志位指示的转换之外，还会进行以 90 度的整数倍为单位的象限旋转。旋转会以相同的角度改变向量的方向，而不改变向量的长度。此标志位与 TypeGeneralRotation 标志互斥。 |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation/) | 平移会在 x 和 y 方向上以固定量移动坐标，而不改变向量的长度或角度。 |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale/) | 均匀缩放会在 x 和 y 方向上以相同的比例乘以向量的长度，而不改变向量之间的角度。此标志位与 TypeGeneralScale 标志互斥。 |

## 备注

大多数算法取自 Sun 的 AffineTransform.java。内部使用的矩阵元素的 Java 名称。Java 名称到 .NET 名称的映射及说明：m00 M11 缩放 X，m10 M12 剪切 Y，m01 M21 剪切 X，m11 M22 缩放 Y，m02 M31 平移 X，m12 M32 平移 Y

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


