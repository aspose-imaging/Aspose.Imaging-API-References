---
title: TextRenderingHint
second_title: Aspose.Imaging for Java API Reference
description: Specifies the quality of text rendering.
type: docs
weight: 116
url: /java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Specifies the quality of text rendering.
## Fields

| Field | Description |
| --- | --- |
| [SystemDefault](#SystemDefault) | Each character is drawn using its glyph bitmap, with the system default rendering hint. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Each character is drawn using its glyph bitmap. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Each character is drawn using its glyph bitmap. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Each character is drawn using its antialiased glyph bitmap with hinting. |
| [AntiAlias](#AntiAlias) | Each character is drawn using its antialiased glyph bitmap without hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Each character is drawn using its glyph ClearType bitmap with hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Each character is drawn using its glyph bitmap, with the system default rendering hint. The text will be drawn using whatever font-smoothing settings the user has selected for the system.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Each character is drawn using its glyph bitmap. Hinting is used to improve character appearance on stems and curvature.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Each character is drawn using its glyph bitmap. Hinting is not used.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Each character is drawn using its antialiased glyph bitmap with hinting. Much better quality due to antialiasing, but at a higher performance cost.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Each character is drawn using its antialiased glyph bitmap without hinting. Better quality due to antialiasing. Stem width differences may be noticeable because hinting is turned off.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Each character is drawn using its glyph ClearType bitmap with hinting. The highest quality setting. Used to take advantage of ClearType font features.

