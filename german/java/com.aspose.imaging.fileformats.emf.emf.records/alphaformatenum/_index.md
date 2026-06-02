---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine Struktur, die angibt, wie Quell- und Zielpixel in Bezug auf Alpha-Transparenz interpretiert werden."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Eine Struktur, die angibt, wie Quell- und Zielpixel in Bezug auf Alpha-Transparenz interpretiert werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [NotTransparency](#NotTransparency) | Die Pixel im Quell‑Bitmap geben keine Alpha‑Transparenz an. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Gibt an, dass das Quell‑Bitmap 32 Bit pro Pixel hat und für jedes Pixel einen Alpha‑Transparenzwert festlegt. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Die Pixel im Quell‑Bitmap geben keine Alpha‑Transparenz an. In diesem Fall bestimmt der Wert SrcConstantAlpha die Mischung der Quell‑ und Ziel‑Bitmaps. Beachten Sie, dass in den folgenden Gleichungen SrcConstantAlpha durch 255 geteilt wird, wodurch ein Wert im Bereich von 0 bis 1 entsteht.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Gibt an, dass das Quell‑Bitmap 32 Bit pro Pixel hat und für jedes Pixel einen Alpha‑Transparenzwert festlegt.

