---
title: Enum TextRenderingHint
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.TextRenderingHint enum. Specifies the quality of text rendering
type: docs
weight: 11710
url: /net/aspose.imaging/textrenderinghint/
---
## TextRenderingHint enumeration

Specifies the quality of text rendering.

```csharp
public enum TextRenderingHint
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| SystemDefault | `0` | Each character is drawn using its glyph bitmap, with the system default rendering hint. The text will be drawn using whatever font-smoothing settings the user has selected for the system. |
| SingleBitPerPixelGridFit | `1` | Each character is drawn using its glyph bitmap. Hinting is used to improve character appearance on stems and curvature. |
| SingleBitPerPixel | `2` | Each character is drawn using its glyph bitmap. Hinting is not used. |
| AntiAliasGridFit | `3` | Each character is drawn using its antialiased glyph bitmap with hinting. Much better quality due to antialiasing, but at a higher performance cost. |
| AntiAlias | `4` | Each character is drawn using its antialiased glyph bitmap without hinting. Better quality due to antialiasing. Stem width differences may be noticeable because hinting is turned off. |
| ClearTypeGridFit | `5` | Each character is drawn using its glyph ClearType bitmap with hinting. The highest quality setting. Used to take advantage of ClearType font features. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


