---
title: "类 EmfPlusTextureBrushData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushData 类。EmfPlusTextureBrushData 对象指定用于图形画刷的纹理图像。"
type: docs
weight: 5930
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
## EmfPlusTextureBrushData class

该 EmfPlusTextureBrushData 对象指定图形画刷的纹理图像。

```csharp
public sealed class EmfPlusTextureBrushData : EmfPlusBaseBrushData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusTextureBrushData](emfplustexturebrushdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/brushdataflags/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定 OptionalData 字段中的数据。此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与纹理画刷相关：BrushDataTransform、BrushDataIsGammaCorrected、BrushDataDoNotTransform。 |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/optionaldata/) { get; set; } | 获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），用于指定纹理画刷的附加数据。该字段的具体内容由 BrushDataFlags 字段的值决定。 |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/wrapmode/) { get; set; } | 获取或设置一个来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定当图像小于填充区域时，如何在形状上重复纹理图像。 |

### 另请参见

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


