---
title: "StretchMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Enumeration gibt den Bitma-Streckungsmodus an, der definiert, wie das System Zeilen oder Spalten eines Bitmaps mit vorhandenen Pixeln kombiniert."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

Die [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) Enumeration gibt den Bitmap-Streckungsmodus an, der definiert, wie das System Zeilen oder Spalten eines Bitmaps mit vorhandenen Pixeln kombiniert.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Führt eine boolesche UND-Operation aus, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. |
| [WhiteOnBlack](#WhiteOnBlack) | Führt eine boolesche ODER-Operation aus, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. |
| [ColorOnColor](#ColorOnColor) | Löscht die Pixel. |
| [HalfTone](#HalfTone) | Mappt Pixel vom Quellrechteck in Blöcke von Pixeln im Zielrechteck. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Führt eine boolesche UND-Operation aus, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. Wenn das Bitmap ein monochromes Bitmap ist, bewahrt dieser Modus schwarze Pixel auf Kosten weißer Pixel.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Führt eine boolesche ODER-Operation aus, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. Wenn das Bitmap ein monochromes Bitmap ist, bewahrt dieser Modus weiße Pixel auf Kosten schwarzer Pixel.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Löscht die Pixel. Dieser Modus löscht alle eliminierten Pixelzeilen, ohne zu versuchen, deren Informationen zu erhalten.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Mappt Pixel vom Quellrechteck in Blöcke von Pixeln im Zielrechteck. Die durchschnittliche Farbe über den Zielblock von Pixeln approximiert die Farbe der Quellpixel.

