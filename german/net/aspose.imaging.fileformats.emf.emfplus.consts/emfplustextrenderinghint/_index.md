---
title: EmfPlusTextRenderingHint
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die TextRenderingHint-Enumeration definiert Typen von Texthinweisen und Anti-Aliasing die sich auf die Qualität der Textwiedergabe auswirken.
type: docs
weight: 5100
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
## EmfPlusTextRenderingHint enumeration

Die TextRenderingHint-Enumeration definiert Typen von Texthinweisen und Anti-Aliasing, die sich auf die Qualität der Textwiedergabe auswirken.

```csharp
public enum EmfPlusTextRenderingHint : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| TextRenderingHintSystemDefault | `0` | Gibt an, dass jedes Textzeichen mit den im Betriebssystem konfigurierten Einstellungen zur Schriftglättung gezeichnet werden SOLLTE. |
| TextRenderingHintSingleBitPerPixelGridFit | `1` | Gibt an, dass jedes Textzeichen mit seiner Glyphen-Bitmap gezeichnet werden SOLLTE. Glättung KANN verwendet werden, um das Erscheinungsbild von Schriftzeichenstämmen und -krümmungen zu verbessern. |
| TextRenderingHintSingleBitPerPixel | `2` | Gibt an, dass jedes Textzeichen mit seiner Glyphen-Bitmap gezeichnet werden SOLLTE. Glättung wird nicht verwendet. |
| TextRenderingHintAntialiasGridFit | `3` | Gibt an, dass jedes Textzeichen unter Verwendung seiner Anti-Aliasing-Glyphen-Bitmap mit Glättung gezeichnet werden SOLLTE. Das Rendering ist aufgrund von Anti-Aliasing von hoher Qualität, kostet jedoch mehr Leistung. |
| TextRenderingHintAntialias | `4` | Gibt an, dass jedes Textzeichen unter Verwendung seiner geglätteten Glyphen-Bitmap ohne Hinting gezeichnet wird. Bessere Qualität durch Anti-Aliasing, aber Unterschiede in der Stammbreite KÖNNEN sichtbar sein, da Hinting deaktiviert ist. |
| TextRenderingHintClearTypeGridFit | `5` | Gibt an, dass jedes Textzeichen unter Verwendung seiner ClearType-Glyphen-Bitmap mit Glättung gezeichnet werden SOLLTE. Dies ist die Texthinweiseinstellung mit der höchsten Qualität, die verwendet wird, um die Vorteile von ClearType-Schriftartfunktionen zu nutzen. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
