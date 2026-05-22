---
title: "类 EmfPlusColorMatrixEffect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorMatrixEffect 类。ColorMatrixEffect 对象指定要应用于图像的仿射变换"
type: docs
weight: 5440
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
## EmfPlusColorMatrixEffect class

ColorMatrixEffect 对象指定要应用于图像的仿射变换。

```csharp
public sealed class EmfPlusColorMatrixEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusColorMatrixEffect](emfpluscolormatrixeffect/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Matrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrix/) { get; set; } | 获取或设置矩阵。 |
| [MatrixN0](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn0/) { get; set; } | 获取或设置 5x5 颜色矩阵的 Matrix[N][0]。此行用于变换。 |
| [MatrixN1](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn1/) { get; set; } | 获取或设置 5x5 颜色矩阵的 Matrix[N][1]。此行用于变换。 |
| [MatrixN2](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn2/) { get; set; } | 获取或设置 5x5 颜色矩阵的 Matrix[N][2]。此行用于变换。 |
| [MatrixN3](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn3/) { get; set; } | 获取或设置 5x5 颜色矩阵的 Matrix[N][3]。此行用于变换。 |
| [MatrixN4](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn4/) { get; set; } | 获取或设置 5x5 颜色矩阵的 Matrix[N][4]。此行用于颜色平移。 |

## 备注

位图图像由 EmfPlusBitmap 对象指定（section 2.2.2.2）。颜色矩阵效果通过将颜色向量乘以 ColorMatrixEffect 对象来实现。5x5 颜色矩阵可以执行线性变换，包括反射、旋转、剪切或缩放后再平移。

### 另请参见

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


