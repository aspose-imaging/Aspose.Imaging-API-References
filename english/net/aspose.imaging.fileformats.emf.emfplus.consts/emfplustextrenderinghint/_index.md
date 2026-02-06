---
title: Enum EmfPlusTextRenderingHint
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusTextRenderingHint enum. The TextRenderingHint enumeration defines types of text hinting and antialiasing which affects the quality of text rendering
type: docs
weight: 5220
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
## EmfPlusTextRenderingHint enumeration

The TextRenderingHint enumeration defines types of text hinting and anti-aliasing, which affects the quality of text rendering.

```csharp
public enum EmfPlusTextRenderingHint : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TextRenderingHintSystemDefault | `0` | Specifies that each text character SHOULD be drawn using whatever font-smoothing settings have been configured on the operating system. |
| TextRenderingHintSingleBitPerPixelGridFit | `1` | Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing MAY be used to improve the appearance of character glyph stems and curvature. |
| TextRenderingHintSingleBitPerPixel | `2` | Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing is not used. |
| TextRenderingHintAntialiasGridFit | `3` | Specifies that each text character SHOULD be drawn using its anti-aliased glyph bitmap with smoothing. The rendering is high quality because of anti-aliasing, but at a higher performance cost. |
| TextRenderingHintAntialias | `4` | Specifies that each text character is drawn using its anti-aliased glyph bitmap without hinting. Better quality results from anti-aliasing, but stem width differences MAY be noticeable because hinting is turned off. |
| TextRenderingHintClearTypeGridFit | `5` | Specifies that each text character SHOULD be drawn using its ClearType glyph bitmap with smoothing. This is the highest-quality text hinting setting, which is used to take advantage of ClearType font features. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


