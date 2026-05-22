---
title: "枚举 EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunctionAlphaFormatEnum 枚举。一个结构，指定在 alpha 透明度方面如何解释源像素和目标像素。"
type: docs
weight: 3370
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
## EmfBlendFunction.AlphaFormatEnum enumeration

一种结构，指定源像素和目标像素相对于 alpha 透明度的解释方式。

```csharp
public enum AlphaFormatEnum : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NotTransparency | `0` | 源位图中的像素未指定 alpha 透明度。在这种情况下，SrcConstantAlpha 值决定源位图和目标位图的混合。注意，在下列公式中，SrcConstantAlpha 被除以 255，产生 0 到 1 范围的值。 |
| AC_SRC_ALPHA | `1` | 指示源位图为每像素 32 位，并为每个像素指定 alpha 透明度值。 |

### 另请参见

* struct [EmfBlendFunction](../emfblendfunction/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


