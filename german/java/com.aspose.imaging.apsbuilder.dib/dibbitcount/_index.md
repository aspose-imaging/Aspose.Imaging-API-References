---
title: "DibBitCount"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die BitCount‑Aufzählung gibt die Anzahl der Bits an, die jedes Pixel definieren, und die maximale Anzahl von Farben in einem geräteunabhängigen Bitmap (DIB)."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

Die BitCount‑Aufzählung gibt die Anzahl der Bits an, die jedes Pixel definieren, sowie die maximale Anzahl von Farben in einer geräteunabhängigen Bitmap (DIB).
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | Die Anzahl der Bits pro Pixel ist undefiniert. |
| [BIT_COUNT_1](#BIT-COUNT-1) | Das Bild ist mit zwei Farben angegeben. Jeder Pixel im Bitmap wird durch ein einzelnes Bit dargestellt. |
| [BIT_COUNT_2](#BIT-COUNT-2) | Das Bild ist mit maximal 16 Farben angegeben. |
| [BIT_COUNT_3](#BIT-COUNT-3) | Das Bild ist mit maximal 256 Farben angegeben. |
| [BIT_COUNT_4](#BIT-COUNT-4) | Das Bild ist mit maximal 2^16 Farben angegeben. |
| [BIT_COUNT_5](#BIT-COUNT-5) | Das Bitmap hat maximal 2^24 Farben, und das Colors‑Feld des DIB ist NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | Das Bitmap hat maximal 2^24 Farben |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


Die Anzahl der Bits pro Pixel ist undefiniert. Das Bild SOLLTE entweder im JPEG- oder PNG-Format vorliegen. Keines dieser Formate enthält eine Farbpalette, sodass dieser Wert angibt, dass keine Farbpalette vorhanden ist. Siehe [JFIF] und [RFC2083] für weitere Informationen zu JPEG- und PNG-Komprimierungsformaten.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


Das Bild ist mit zwei Farben angegeben. Jeder Pixel im Bitmap wird durch ein einzelnes Bit dargestellt. Ist das Bit gelöscht, wird der Pixel mit der Farbe des ersten Eintrags in der Farbpalette angezeigt; ist das Bit gesetzt, hat der Pixel die Farbe des zweiten Eintrags in der Palette.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


Das Bild ist mit maximal 16 Farben angegeben. Jeder Pixel im Bitmap wird durch einen 4‑Bit‑Index in die Farbpalette dargestellt, und jedes Byte enthält 2 Pixel.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


Das Bild ist mit maximal 256 Farben angegeben. Jeder Pixel im Bitmap wird durch einen 8‑Bit‑Index in die Farbpalette dargestellt, und jedes Byte enthält 1 Pixel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


Das Bild ist mit maximal 2^16 Farben angegeben. Jeder Pixel im Bitmap wird durch einen 16‑Bit‑Wert dargestellt.

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


Das Bitmap hat maximal 2^24 Farben, und das Feld Colors des DIB ist NULL. Jeder 3‑Byte‑Tripel im Bitmap‑Array stellt die relativen Intensitäten von Blau, Grün und Rot für einen Pixel dar. Die Colors‑Farbpalette wird zur Optimierung der auf palettenbasierten Geräten verwendeten Farben genutzt und MUSS die Anzahl der Einträge enthalten, die im Feld ColorUsed des BitmapInfoHeader‑Objekts angegeben ist.

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


Das Bitmap hat maximal 2^24 Farben

