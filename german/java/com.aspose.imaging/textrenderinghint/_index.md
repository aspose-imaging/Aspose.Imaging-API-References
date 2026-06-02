---
title: "TextRenderingHint"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt die Qualität der Textdarstellung an."
type: docs
weight: 115
url: /de/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Gibt die Qualität der Textdarstellung an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [SystemDefault](#SystemDefault) | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet, mit dem systemweiten Standard‑Rendering‑Hinweis. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap und Hinting gezeichnet. |
| [AntiAlias](#AntiAlias) | Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap ohne Hinting gezeichnet. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Jedes Zeichen wird mit seiner Glyphen‑ClearType‑Bitmap und Hinting gezeichnet. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet, mit dem systemweiten Standard‑Rendering‑Hinweis. Der Text wird mit den vom Benutzer für das System gewählten Schriftglättungseinstellungen gezeichnet.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. Hinting wird verwendet, um das Aussehen von Zeichenstämmen und Krümmungen zu verbessern.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. Hinting wird nicht verwendet.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap und Hinting gezeichnet. Viel bessere Qualität durch Antialiasing, jedoch mit höheren Leistungsaufwand.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap ohne Hinting gezeichnet. Bessere Qualität durch Antialiasing. Unterschiede in der Strichstärke können auffallen, da Hinting deaktiviert ist.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Jedes Zeichen wird mit seiner Glyphen‑ClearType‑Bitmap und Hinting gezeichnet. Die höchste Qualitätseinstellung. Wird verwendet, um die ClearType‑Schriftmerkmale zu nutzen.

