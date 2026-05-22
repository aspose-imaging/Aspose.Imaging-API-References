---
title: "CmykColorHelper.ToCmykaIccBytes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。使用自定义 ICC 配置文件将 RGB 转换为带 alpha 的 CMYKA"
type: docs
weight: 110
url: /zh/net/aspose.imaging/cmykcolorhelper/tocmykaiccbytes/
---
## CmykColorHelper.ToCmykaIccBytes method

使用自定义 ICC 配置文件，将 RGB 转换为 CMYKA（带 alpha）。

```csharp
public static byte[] ToCmykaIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | RGB 颜色以 32 位整数值的形式呈现。 |
| startIndex | Int32 | RGB 颜色的起始索引。 |
| length | Int32 | 要转换的 RGB 像素数量。 |
| rgbIccStream | Stream | RGB 配置文件流。 |
| cmykIccStream | Stream | CMYK 配置文件流。 |

### 返回值

CMYK 颜色以字节数组的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


