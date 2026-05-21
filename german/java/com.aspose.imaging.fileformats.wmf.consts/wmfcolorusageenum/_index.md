---
title: "WmfColorUsageEnum"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die ColorUsage‑Aufzählung gibt an, ob eine Farbpalette in einem geräteunabhängigen Bitmap (DIB) vorhanden ist und wie ihre Werte zu interpretieren sind."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

Die ColorUsage‑Aufzählung gibt an, ob eine Farbpalette in einer geräteunabhängigen Bitmap (DIB) existiert und wie ihre Werte zu interpretieren sind.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | Die Farbpalette enthält RGB‑Werte, die von RGBQuad‑Objekten (Abschnitt 2.2.2.20) angegeben werden. |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | Die Farbpalette enthält 16‑Bit‑Indizes in die aktuelle logische Palette im Wiedergabegeräte‑Kontext. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Es existiert keine Farbpalette. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


Die Farbpalette enthält RGB‑Werte, die von RGBQuad‑Objekten (Abschnitt 2.2.2.20) angegeben werden.

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


Die Farbpalette enthält 16‑Bit‑Indizes in die aktuelle logische Palette im Wiedergabegeräte‑Kontext.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Es existiert keine Farbpalette. Die Pixel im DIB sind Indizes in die aktuelle logische Palette im Wiedergabegerätekontext.

