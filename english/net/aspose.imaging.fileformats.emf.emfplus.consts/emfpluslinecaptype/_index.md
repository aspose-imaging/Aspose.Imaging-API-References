---
title: Enum EmfPlusLineCapType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusLineCapType enum. The LineCapType enumeration defines types of line caps to use at the ends of lines that are drawn with graphics pens
type: docs
weight: 5010
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
## EmfPlusLineCapType enumeration

The LineCapType enumeration defines types of line caps to use at the ends of lines that are drawn with graphics pens.

```csharp
public enum EmfPlusLineCapType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| LineCapTypeFlat | `0` | Specifies a squared-off line cap. The end of the line MUST be the last point in the line. |
| LineCapTypeSquare | `1` | Specifies a square line cap. The center of the square MUST be located at the last point in the line. The width of the square is the line width. |
| LineCapTypeRound | `2` | Specifies a circular line cap. The center of the circle MUST be located at the last point in the line. The diameter of the circle is the line width. |
| LineCapTypeTriangle | `3` | Specifies a triangular line cap. The base of the triangle MUST be located at the last point in the line. The base of the triangle is the line width. |
| LineCapTypeNoAnchor | `16` | Specifies that the line end is not anchored. |
| LineCapTypeSquareAnchor | `17` | Specifies that the line end is anchored with a square line cap. The center of the square MUST be located at the last point in the line. The height and width of the square are the line width. |
| LineCapTypeRoundAnchor | `18` | Specifies that the line end is anchored with a circular line cap. The center of the circle MUST be located at the last point in the line. The circle SHOULD be wider than the line. |
| LineCapTypeDiamondAnchor | `19` | Specifies that the line end is anchored with a diamond-shaped line cap, which is a square turned at 45 degrees. The center of the diamond MUST be located at the last point in the line. The diamond SHOULD be wider than the line. |
| LineCapTypeArrowAnchor | `20` | Specifies that the line end is anchored with an arrowhead shape. The arrowhead point MUST be located at the last point in the line. The arrowhead SHOULD be wider than the line. |
| LineCapTypeAnchorMask | `240` | Mask used to check whether a line cap is an anchor cap. |
| LineCapTypeCustom | `255` | Specifies a custom line cap. |

## Remarks

Graphics line caps are specified by [`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/) objects (section 2.2.1.7).

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


