---
title: "RotateFlipType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt an, um wie viel ein Bild gedreht wird und welche Achse zum Spiegeln des Bildes verwendet wird."
type: docs
weight: 100
url: /de/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Gibt an, um wie viel ein Bild gedreht wird und welche Achse zum Spiegeln des Bildes verwendet wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Gibt an, dass keine Drehung im Uhrzeigersinn und kein Spiegeln erfolgt. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Gibt an, um wie viel ein Bild gedreht wird und welche Achse zum Spiegeln des Bildes verwendet wird. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Gibt eine 180-Grad-Drehung im Uhrzeigersinn ohne Spiegeln an. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Gibt eine 270-Grad-Drehung im Uhrzeigersinn ohne Spiegeln an. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer horizontalen Spiegelung. |
| [Rotate90FlipX](#Rotate90FlipX) | Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung. |
| [Rotate180FlipX](#Rotate180FlipX) | Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung. |
| [Rotate270FlipX](#Rotate270FlipX) | Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer vertikalen Spiegelung. |
| [Rotate90FlipY](#Rotate90FlipY) | Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung. |
| [Rotate180FlipY](#Rotate180FlipY) | Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung. |
| [Rotate270FlipY](#Rotate270FlipY) | Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer horizontalen und vertikalen Spiegelung. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung. |

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
    // Drehen, spiegeln und in die Ausgabedatei speichern.
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


Gibt an, dass keine Drehung im Uhrzeigersinn und kein Spiegeln erfolgt.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Gibt an, um wie viel ein Bild gedreht wird und welche Achse zum Spiegeln des Bildes verwendet wird.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Gibt eine 180-Grad-Drehung im Uhrzeigersinn ohne Spiegeln an.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Gibt eine 270-Grad-Drehung im Uhrzeigersinn ohne Spiegeln an.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer horizontalen Spiegelung.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen Spiegelung.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer vertikalen Spiegelung.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer vertikalen Spiegelung.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Gibt an, dass keine Drehung im Uhrzeigersinn erfolgt, gefolgt von einer horizontalen und vertikalen Spiegelung.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Gibt eine 90-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Gibt eine 180-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Gibt eine 270-Grad-Drehung im Uhrzeigersinn an, gefolgt von einer horizontalen und vertikalen Spiegelung.

