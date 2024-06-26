---
title: CmykColorHelper.ToCmykaIccBytes
second_title: Aspose.Imaging for .NET API Reference
description: CmykColorHelper method. Converts RGB to CMYKA with alpha using custom ICC profiles
type: docs
weight: 110
url: /net/aspose.imaging/cmykcolorhelper/tocmykaiccbytes/
---
## CmykColorHelper.ToCmykaIccBytes method

Converts RGB to CMYKA (with alpha) using custom ICC profiles.

```csharp
public static byte[] ToCmykaIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The RGB colors presented as 32-bit integer values. |
| startIndex | Int32 | The start index of RGB color. |
| length | Int32 | The number of RGB pixels to convert. |
| rgbIccStream | Stream | The RGB profile stream. |
| cmykIccStream | Stream | The CMYK profile stream. |

### Return Value

The CMYK colors presented as a byte array.

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


