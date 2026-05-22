---
title: "WmfBitmapInfoHeader.ColorUsed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfBitmapInfoHeader 属性。获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果该值为零，DIB 使用与 BitCount 值对应的最大颜色数；如果该值非零且 BitCount 值小于 16，则该值指定 DIB 使用的颜色数；如果该值非零且 BitCount 值为 16 或更大，则该值指定用于优化系统调色板性能的颜色表大小。注意：如果该值非零且大于基于 BitCount 值的颜色表最大可能大小，则应假定为最大颜色表大小。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused/
---
## WmfBitmapInfoHeader.ColorUsed property

获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果此值为零，DIB 使用与 BitCount 值对应的最大颜色数。如果此值非零且 BitCount 值小于 16，则此值指定 DIB 使用的颜色数量。如果此值非零且 BitCount 值大于等于 16，则此值指定用于优化系统调色板性能的颜色表大小。注意：如果此值非零且大于基于 BitCount 值的颜色表最大可能大小，则应假定最大颜色表大小。

```csharp
public int ColorUsed { get; set; }
```

### 另请参见

* class [WmfBitmapInfoHeader](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfbitmapinfoheader/)
* assembly [Aspose.Imaging](../../../)


