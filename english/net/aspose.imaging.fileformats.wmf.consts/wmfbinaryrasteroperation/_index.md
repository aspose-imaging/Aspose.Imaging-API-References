---
title: Enum WmfBinaryRasterOperation
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfBinaryRasterOperation enum. The BinaryRasterOperation Enumeration section lists the binary rasteroperation codes. Raster operation codes define how metafile processing combines the bits from the selected pen with the bits in the destination bitmap
type: docs
weight: 8280
url: /net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
## WmfBinaryRasterOperation enumeration

The BinaryRasterOperation Enumeration section lists the binary raster-operation codes. Raster operation codes define how metafile processing combines the bits from the selected pen with the bits in the destination bitmap.

```csharp
public enum WmfBinaryRasterOperation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Black | `1` | 0, Pixel is always 0. |
| Notmergepen | `2` | DPon, Pixel is the inverse of the MERGEPEN color |
| Masknotpen | `3` | DPna, Pixel is a combination of the screen color and the inverse of the pen color. |
| Notcopypen | `4` | Pn, Pixel is the inverse of the pen color. |
| Maskpennot | `5` | PDna, Pixel is a combination of the colors common to both the pen and the inverse of the screen. |
| Not | `6` | Dn, Pixel is the inverse of the screen color. |
| Xorpen | `7` | DPx, Pixel is a combination of the colors in the pen or in the screen, but not in both. |
| Notmaskpen | `8` | DPan, Pixel is the inverse of the MASKPEN color. |
| Maskpen | `9` | DPa, Pixel is a combination of the colors common to both the pen and the screen. |
| Notxorpen | `10` | DPxn, Pixel is the inverse of the XORPEN color. |
| Nop | `11` | D, Pixel remains unchanged. |
| Mergenotpen | `12` | DPno, Pixel is a combination of the colors common to both the screen and the inverse of the pen. |
| Copypen | `13` | P, Pixel is the pen color. |
| Mergepennot | `14` | PDno, Pixel is a combination of the pen color and the inverse of the screen color. |
| Mergepen | `15` | DPo, Pixel is a combination of the pen color and the screen color. |
| White | `16` | 1, Pixel is always 1 |

## Remarks

Each raster-operation code represents a Boolean operation in which the values of the pixels in the selected pen and the destination bitmap are combined. Following are the two operands used in these operations. Operand Meaning P Selected pen D Destination bitmap a Bitwise AND n Bitwise NOT (inverse) o Bitwise OR x Bitwise exclusive OR (XOR)

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


