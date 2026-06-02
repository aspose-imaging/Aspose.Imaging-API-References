---
title: "类 EmfPlusBitmapData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBitmapData 类。EmfPlusBitmapData 对象指定具有像素数据的位图图像"
type: docs
weight: 5300
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
## EmfPlusBitmapData class

EmfPlusBitmapData 对象指定了带有像素数据的位图图像。

```csharp
public sealed class EmfPlusBitmapData : EmfPlusBaseBitmapData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBitmapData](emfplusbitmapdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/colors/) { get; set; } | 获取或设置 调色板颜色 Colors（可变）：一个可选的 [`EmfPlusPalette`](../emfpluspalette/) 对象（第 2.2.2.28 节），该对象指定像素数据中使用的颜色调色板。如果在 [`EmfPlusBitmap`](../emfplusbitmap/) 对象的 PixelFormat 字段中设置了 I 标志，则此字段必须存在。 |
| [PixelData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/pixeldata/) { get; set; } | 获取或设置像素数据 PixelData（变量）：一个字节数组，用于指定像素数据。可以根据 EmfPlusBitmap 对象中的字段计算此数据的大小和格式，包括来自[`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) 枚举的像素格式（第 2.1.1.25 节）。 |

### 另请参见

* class [EmfPlusBaseBitmapData](../emfplusbasebitmapdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


