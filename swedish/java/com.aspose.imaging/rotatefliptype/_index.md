---
title: "RotateFlipType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger hur mycket en bild roteras och vilken axel som används för att vända bilden."
type: docs
weight: 100
url: /sv/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Anger hur mycket en bild roteras och vilken axel som används för att vända bilden.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Anger ingen medurs rotation och ingen spegling. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Anger hur mycket en bild roteras och vilken axel som används för att vända bilden. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Anger en 180-graders medurs rotation utan spegling. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Anger en 270-graders medurs rotation utan spegling. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Anger ingen medurs rotation följt av en horisontell spegling. |
| [Rotate90FlipX](#Rotate90FlipX) | Anger en 90-graders medurs rotation följt av en horisontell spegling. |
| [Rotate180FlipX](#Rotate180FlipX) | Anger en 180-graders medurs rotation följt av en horisontell spegling. |
| [Rotate270FlipX](#Rotate270FlipX) | Anger en 270-graders medurs rotation följt av en horisontell spegling. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Anger ingen medurs rotation följt av en vertikal spegling. |
| [Rotate90FlipY](#Rotate90FlipY) | Anger en 90-graders medurs rotation följt av en vertikal spegling. |
| [Rotate180FlipY](#Rotate180FlipY) | Anger en 180-graders medurs rotation följt av en vertikal spegling. |
| [Rotate270FlipY](#Rotate270FlipY) | Anger en 270-graders medurs rotation följt av en vertikal spegling. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Anger ingen medurs rotation följt av en horisontell och vertikal spegling. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Anger en 90-graders medurs rotation följt av en horisontell och vertikal spegling. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Anger en 180-graders medurs rotation följt av en horisontell och vertikal spegling. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Anger en 270-graders medurs rotation följt av en horisontell och vertikal spegling. |

## Example: This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotera, vänd och spara till utdatafilen.
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### RotateNoneFlipNone {#RotateNoneFlipNone}
```
public static final int RotateNoneFlipNone
```


Anger ingen medurs rotation och ingen spegling.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Anger hur mycket en bild roteras och vilken axel som används för att vända bilden.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Anger en 180-graders medurs rotation utan spegling.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Anger en 270-graders medurs rotation utan spegling.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Anger ingen medurs rotation följt av en horisontell spegling.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Anger en 90-graders medurs rotation följt av en horisontell spegling.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Anger en 180-graders medurs rotation följt av en horisontell spegling.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Anger en 270-graders medurs rotation följt av en horisontell spegling.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Anger ingen medurs rotation följt av en vertikal spegling.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Anger en 90-graders medurs rotation följt av en vertikal spegling.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Anger en 180-graders medurs rotation följt av en vertikal spegling.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Anger en 270-graders medurs rotation följt av en vertikal spegling.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Anger ingen medurs rotation följt av en horisontell och vertikal spegling.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Anger en 90-graders medurs rotation följt av en horisontell och vertikal spegling.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Anger en 180-graders medurs rotation följt av en horisontell och vertikal spegling.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Anger en 270-graders medurs rotation följt av en horisontell och vertikal spegling.

