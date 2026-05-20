---
title: "EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die TextRenderingHint‑Aufzählung definiert Arten von Text-Hinting und Antialiasing, die die Qualität der Textdarstellung beeinflussen."
type: docs
weight: 52
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

Die TextRenderingHint-Aufzählung definiert Arten von Text-Hinting und Antialiasing, die die Qualität der Textdarstellung beeinflussen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Gibt an, dass jedes Textzeichen MIT der auf dem Betriebssystem konfigurierten Font‑Smoothing‑Einstellung gezeichnet werden SOLLTE. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Gibt an, dass jedes Textzeichen MIT seinem Glyph‑Bitmap gezeichnet werden SOLLTE. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Gibt an, dass jedes Textzeichen MIT seinem Glyph‑Bitmap gezeichnet werden SOLLTE. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Gibt an, dass jedes Textzeichen MIT seinem antialiasierten Glyph‑Bitmap mit Smoothing gezeichnet werden SOLLTE. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Gibt an, dass jedes Textzeichen mit seinem antialiasierten Glyph‑Bitmap ohne Hinting gezeichnet wird. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Gibt an, dass jedes Textzeichen MIT seinem ClearType‑Glyph‑Bitmap mit Smoothing gezeichnet werden SOLLTE. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Gibt an, dass jedes Textzeichen MIT der auf dem Betriebssystem konfigurierten Font‑Smoothing‑Einstellung gezeichnet werden SOLLTE.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Gibt an, dass jedes Textzeichen MIT seinem Glyph‑Bitmap gezeichnet werden SOLLTE. Smoothing KANN verwendet werden, um das Erscheinungsbild von Glyph‑Stämmen und Krümmungen zu verbessern.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Gibt an, dass jedes Textzeichen MIT seinem Glyph‑Bitmap gezeichnet werden SOLLTE. Smoothing wird nicht verwendet.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Gibt an, dass jedes Textzeichen MIT seinem antialiasierten Glyph‑Bitmap mit Smoothing gezeichnet werden SOLLTE. Die Darstellung ist dank Antialiasing von hoher Qualität, verursacht jedoch höhere Leistungskosten.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Gibt an, dass jedes Textzeichen mit seinem antialiasierten Glyph‑Bitmap ohne Hinting gezeichnet wird. Bessere Qualität ergibt sich aus Antialiasing, aber Unterschiede in der Stammansbreite KÖNNEN auffallen, weil Hinting deaktiviert ist.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Gibt an, dass jedes Textzeichen MIT seinem ClearType‑Glyph‑Bitmap mit Smoothing gezeichnet werden SOLLTE. Dies ist die qualitativ hochwertigste Text‑Hinting‑Einstellung, die verwendet wird, um die ClearType‑Schriftmerkmale zu nutzen.

