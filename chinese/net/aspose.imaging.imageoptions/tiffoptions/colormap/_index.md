---
title: "TiffOptions.ColorMap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffOptions 属性。获取或设置颜色映射表。"
type: docs
weight: 70
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

获取或设置颜色映射表。

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

颜色映射表。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 值 |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | 颜色映射表只能在每像素样本数等于 1 时定义。或者未定义每样本位数。 |
| ArgumentOutOfRangeException | value;数组长度必须符合以下公式：3 * (2**BitsPerSample)。 |

### 另请参见

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


