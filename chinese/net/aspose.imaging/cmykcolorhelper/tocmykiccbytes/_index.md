---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。将 RGB 转换为 CMYK，使用自定义 ICC 配置文件"
type: docs
weight: 140
url: /zh/net/aspose.imaging/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
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


