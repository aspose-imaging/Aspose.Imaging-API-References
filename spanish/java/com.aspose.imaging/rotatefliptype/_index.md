---
title: "RotateFlipType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica cuánto se rota una imagen y el eje usado para voltear la imagen."
type: docs
weight: 100
url: /es/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Especifica cuánto se rota una imagen y el eje usado para voltear la imagen.
## Campos

| Campo | Descripción |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Especifica sin rotación en sentido horario y sin volteo. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Especifica cuánto se rota una imagen y el eje usado para voltear la imagen. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Especifica una rotación de 180 grados en sentido horario sin volteo. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Especifica una rotación de 270 grados en sentido horario sin volteo. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Especifica sin rotación en sentido horario seguida de un volteo horizontal. |
| [Rotate90FlipX](#Rotate90FlipX) | Especifica una rotación de 90 grados en sentido horario seguida de un volteo horizontal. |
| [Rotate180FlipX](#Rotate180FlipX) | Especifica una rotación de 180 grados en sentido horario seguida de un volteo horizontal. |
| [Rotate270FlipX](#Rotate270FlipX) | Especifica una rotación de 270 grados en sentido horario seguida de un volteo horizontal. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Especifica sin rotación en sentido horario seguida de un volteo vertical. |
| [Rotate90FlipY](#Rotate90FlipY) | Especifica una rotación de 90 grados en sentido horario seguida de un volteo vertical. |
| [Rotate180FlipY](#Rotate180FlipY) | Especifica una rotación de 180 grados en sentido horario seguida de un volteo vertical. |
| [Rotate270FlipY](#Rotate270FlipY) | Especifica una rotación de 270 grados en sentido horario seguida de un volteo vertical. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Especifica sin rotación en sentido horario seguida de un volteo horizontal y vertical. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Especifica una rotación de 90 grados en sentido horario seguida de un volteo horizontal y vertical. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Especifica una rotación de 180 grados en sentido horario seguida de un volteo horizontal y vertical. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Especifica una rotación de 270 grados en sentido horario seguida de un volteo horizontal y vertical. |

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
    // Rotar, voltear y guardar en el archivo de salida.
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


Especifica sin rotación en sentido horario y sin volteo.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Especifica cuánto se rota una imagen y el eje usado para voltear la imagen.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Especifica una rotación de 180 grados en sentido horario sin volteo.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Especifica una rotación de 270 grados en sentido horario sin volteo.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Especifica sin rotación en sentido horario seguida de un volteo horizontal.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Especifica una rotación de 90 grados en sentido horario seguida de un volteo horizontal.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Especifica una rotación de 180 grados en sentido horario seguida de un volteo horizontal.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Especifica una rotación de 270 grados en sentido horario seguida de un volteo horizontal.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Especifica sin rotación en sentido horario seguida de un volteo vertical.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Especifica una rotación de 90 grados en sentido horario seguida de un volteo vertical.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Especifica una rotación de 180 grados en sentido horario seguida de un volteo vertical.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Especifica una rotación de 270 grados en sentido horario seguida de un volteo vertical.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Especifica sin rotación en sentido horario seguida de un volteo horizontal y vertical.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Especifica una rotación de 90 grados en sentido horario seguida de un volteo horizontal y vertical.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Especifica una rotación de 180 grados en sentido horario seguida de un volteo horizontal y vertical.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Especifica una rotación de 270 grados en sentido horario seguida de un volteo horizontal y vertical.

