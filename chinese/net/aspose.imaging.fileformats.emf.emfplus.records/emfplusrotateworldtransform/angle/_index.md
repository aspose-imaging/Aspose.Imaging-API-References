---
title: "EmfPlusRotateWorldTransform.Angle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusRotateWorldTransform 属性。获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。该操作通过以下图示构建新的变换矩阵来执行   sinAngle  cosAngle  0   cosAngle  sinAngle  0   图 2 旋转变换矩阵。当前世界空间变换与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/
---
## EmfPlusRotateWorldTransform.Angle property

获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。该操作通过从以下图表构建新的变换矩阵来执行： --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- 图 2：旋转变换矩阵 当前的世界空间变换会与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。

```csharp
public float Angle { get; set; }
```

### Property Value

角度。

### 另请参见

* class [EmfPlusRotateWorldTransform](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusrotateworldtransform/)
* assembly [Aspose.Imaging](../../../)


