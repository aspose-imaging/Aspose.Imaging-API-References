---
title: "StretchMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Enumerationen specificerar bitmap‑sträckningsläget som definierar hur systemet kombinerar rader eller kolumner i en bitmap med befintliga pixlar."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

Enumerationen [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) specificerar bitmap‑sträckningsläget, som definierar hur systemet kombinerar rader eller kolumner i en bitmap med befintliga pixlar.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Utför en Boolean AND‑operation genom att använda färgvärdena för de eliminerade och befintliga pixlarna. |
| [WhiteOnBlack](#WhiteOnBlack) | Utför en Boolean OR‑operation genom att använda färgvärdena för de eliminerade och befintliga pixlarna. |
| [ColorOnColor](#ColorOnColor) | Tar bort pixlarna. |
| [HalfTone](#HalfTone) | Mappar pixlar från källrektangeln till block av pixlar i destinationsrektangeln. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Utför en Boolean AND‑operation genom att använda färgvärdena för de eliminerade och befintliga pixlarna. Om bitmapen är en monokrom bitmap bevarar detta läge svarta pixlar på bekostnad av vita pixlar.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Utför en Boolean OR‑operation genom att använda färgvärdena för de eliminerade och befintliga pixlarna. Om bitmapen är en monokrom bitmap bevarar detta läge vita pixlar på bekostnad av svarta pixlar.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Tar bort pixlarna. Detta läge tar bort alla eliminerade pixelrader utan att försöka bevara deras information.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Mappar pixlar från källrektangeln till block av pixlar i destinationsrektangeln. Den genomsnittliga färgen över destinationsblocket av pixlar approximera färgen på källpixlarna.

