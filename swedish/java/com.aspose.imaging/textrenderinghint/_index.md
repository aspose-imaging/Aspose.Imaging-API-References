---
title: "TextRenderingHint"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger kvaliteten på textåtergivning."
type: docs
weight: 115
url: /sv/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Anger kvaliteten på textåtergivning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SystemDefault](#SystemDefault) | Varje tecken ritas med sin glyf-bitmap, med systemets standardrenderingstips. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Varje tecken ritas med sin glyf-bitmap. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Varje tecken ritas med sin glyf-bitmap. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Varje tecken ritas med sin antialiasade glyf-bitmap med hintning. |
| [AntiAlias](#AntiAlias) | Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Varje tecken ritas med sin glyf ClearType-bitmap med hintning. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Varje tecken ritas med sin glyf-bitmap, med systemets standardrenderingstips. Texten kommer att ritas med de fontutjämningsinställningar som användaren har valt för systemet.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Varje tecken ritas med sin glyf-bitmap. Hintning används för att förbättra teckenutseendet på stjälkar och kurvor.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Varje tecken ritas med sin glyf-bitmap. Hintning används inte.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Varje tecken ritas med sin antialiasade glyf-bitmap med hintning. Mycket bättre kvalitet på grund av antialiasing, men med högre prestandakostnad.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. Bättre kvalitet på grund av antialiasing. Skillnader i stjälkbredd kan märkas eftersom hintning är avstängd.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Varje tecken ritas med sin glyf ClearType-bitmap med hintning. Den högsta kvalitetsinställningen. Används för att utnyttja ClearType-fontegenskaper.

