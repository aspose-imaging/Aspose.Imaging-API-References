---
title: EmfPlusTextRenderingHint
second_title: Aspose.Imaging for Java API Reference
description: The TextRenderingHint enumeration defines types of text hinting and anti-aliasing which affects the quality of text rendering.
type: docs
weight: 52
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

The TextRenderingHint enumeration defines types of text hinting and anti-aliasing, which affects the quality of text rendering.
## Fields

| Field | Description |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Specifies that each text character SHOULD be drawn using whatever font-smoothing settings have been configured on the operating system. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Specifies that each text character SHOULD be drawn using its glyph bitmap. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Specifies that each text character SHOULD be drawn using its glyph bitmap. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Specifies that each text character SHOULD be drawn using its anti-aliased glyph bitmap with smoothing. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Specifies that each text character is drawn using its anti-aliased glyph bitmap without hinting. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Specifies that each text character SHOULD be drawn using its ClearType glyph bitmap with smoothing. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Specifies that each text character SHOULD be drawn using whatever font-smoothing settings have been configured on the operating system.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing MAY be used to improve the appearance of character glyph stems and curvature.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing is not used.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Specifies that each text character SHOULD be drawn using its anti-aliased glyph bitmap with smoothing. The rendering is high quality because of anti-aliasing, but at a higher performance cost.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Specifies that each text character is drawn using its anti-aliased glyph bitmap without hinting. Better quality results from anti-aliasing, but stem width differences MAY be noticeable because hinting is turned off.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Specifies that each text character SHOULD be drawn using its ClearType glyph bitmap with smoothing. This is the highest-quality text hinting setting, which is used to take advantage of ClearType font features.

