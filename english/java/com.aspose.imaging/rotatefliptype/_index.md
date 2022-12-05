---
title: RotateFlipType
second_title: Aspose.Imaging for Java API Reference
description: Specifies how much an image is rotated and the axis used to flip the image.
type: docs
weight: 100
url: /java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Specifies how much an image is rotated and the axis used to flip the image.
## Fields

| Field | Description |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Specifies no clockwise rotation and no flipping. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Specifies how much an image is rotated and the axis used to flip the image. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Specifies a 180-degree clockwise rotation without flipping. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Specifies a 270-degree clockwise rotation without flipping. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Specifies no clockwise rotation followed by a horizontal flip. |
| [Rotate90FlipX](#Rotate90FlipX) | Specifies a 90-degree clockwise rotation followed by a horizontal flip. |
| [Rotate180FlipX](#Rotate180FlipX) | Specifies a 180-degree clockwise rotation followed by a horizontal flip. |
| [Rotate270FlipX](#Rotate270FlipX) | Specifies a 270-degree clockwise rotation followed by a horizontal flip. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Specifies no clockwise rotation followed by a vertical flip. |
| [Rotate90FlipY](#Rotate90FlipY) | Specifies a 90-degree clockwise rotation followed by a vertical flip. |
| [Rotate180FlipY](#Rotate180FlipY) | Specifies a 180-degree clockwise rotation followed by a vertical flip. |
| [Rotate270FlipY](#Rotate270FlipY) | Specifies a 270-degree clockwise rotation followed by a vertical flip. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Specifies no clockwise rotation followed by a horizontal and vertical flip. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Specifies a 90-degree clockwise rotation followed by a horizontal and vertical flip. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Specifies a 180-degree clockwise rotation followed by a horizontal and vertical flip. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Specifies a 270-degree clockwise rotation followed by a horizontal and vertical flip. |

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
    // Rotate, flip and save to the output file.
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


Specifies no clockwise rotation and no flipping.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Specifies how much an image is rotated and the axis used to flip the image.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Specifies a 180-degree clockwise rotation without flipping.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Specifies a 270-degree clockwise rotation without flipping.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Specifies no clockwise rotation followed by a horizontal flip.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Specifies a 90-degree clockwise rotation followed by a horizontal flip.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Specifies a 180-degree clockwise rotation followed by a horizontal flip.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Specifies a 270-degree clockwise rotation followed by a horizontal flip.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Specifies no clockwise rotation followed by a vertical flip.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Specifies a 90-degree clockwise rotation followed by a vertical flip.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Specifies a 180-degree clockwise rotation followed by a vertical flip.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Specifies a 270-degree clockwise rotation followed by a vertical flip.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Specifies no clockwise rotation followed by a horizontal and vertical flip.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Specifies a 90-degree clockwise rotation followed by a horizontal and vertical flip.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Specifies a 180-degree clockwise rotation followed by a horizontal and vertical flip.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Specifies a 270-degree clockwise rotation followed by a horizontal and vertical flip.

