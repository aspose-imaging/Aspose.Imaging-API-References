---
title: WmfBitmapInfoHeader.ColorUsed
second_title: Aspose.Imaging for .NET API Reference
description: WmfBitmapInfoHeader property. Gets or sets a 32bit unsigned integer that specifies the number of indexes in the color table used by the DIB as follows If this value is zero the DIB uses the maximum number of colors that correspond to the BitCount value. If this value is nonzero and the BitCount value is less than 16 this value specifies the number of colors used by the DIB. If this value is nonzero and the BitCount value is 16 or greater this value specifies the size of the color table used to optimize performance of the system palette. Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount value the maximum color table size SHOULD be assumed
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused/
---
## WmfBitmapInfoHeader.ColorUsed property

Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. If this value is nonzero and the BitCount value is less than 16, this value specifies the number of colors used by the DIB. If this value is nonzero and the BitCount value is 16 or greater, this value specifies the size of the color table used to optimize performance of the system palette. Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount value, the maximum color table size SHOULD be assumed.

```csharp
public int ColorUsed { get; set; }
```

### See Also

* class [WmfBitmapInfoHeader](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfbitmapinfoheader/)
* assembly [Aspose.Imaging](../../../)


