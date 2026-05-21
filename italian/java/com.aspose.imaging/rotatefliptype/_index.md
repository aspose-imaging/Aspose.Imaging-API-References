---
title: "RotateFlipType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine."
type: docs
weight: 100
url: /it/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine.
## Campi

| Campo | Descrizione |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Specifica nessuna rotazione in senso orario e nessun ribaltamento. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Specifica una rotazione di 180 gradi in senso orario senza ribaltamento. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Specifica una rotazione di 270 gradi in senso orario senza ribaltamento. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Specifica nessuna rotazione in senso orario seguita da un ribaltamento orizzontale. |
| [Rotate90FlipX](#Rotate90FlipX) | Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento orizzontale. |
| [Rotate180FlipX](#Rotate180FlipX) | Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento orizzontale. |
| [Rotate270FlipX](#Rotate270FlipX) | Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento orizzontale. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Specifica nessuna rotazione in senso orario seguita da un ribaltamento verticale. |
| [Rotate90FlipY](#Rotate90FlipY) | Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento verticale. |
| [Rotate180FlipY](#Rotate180FlipY) | Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento verticale. |
| [Rotate270FlipY](#Rotate270FlipY) | Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento verticale. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Specifica nessuna rotazione in senso orario seguita da un ribaltamento orizzontale e verticale. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento orizzontale e verticale. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento orizzontale e verticale. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento orizzontale e verticale. |

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
    // Ruota, capovolgi e salva nel file di output.
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


Specifica nessuna rotazione in senso orario e nessun ribaltamento.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Specifica una rotazione di 180 gradi in senso orario senza ribaltamento.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Specifica una rotazione di 270 gradi in senso orario senza ribaltamento.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Specifica nessuna rotazione in senso orario seguita da un ribaltamento orizzontale.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento orizzontale.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento orizzontale.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento orizzontale.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Specifica nessuna rotazione in senso orario seguita da un ribaltamento verticale.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento verticale.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento verticale.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento verticale.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Specifica nessuna rotazione in senso orario seguita da un ribaltamento orizzontale e verticale.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Specifica una rotazione di 90 gradi in senso orario seguita da un ribaltamento orizzontale e verticale.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Specifica una rotazione di 180 gradi in senso orario seguita da un ribaltamento orizzontale e verticale.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Specifica una rotazione di 270 gradi in senso orario seguita da un ribaltamento orizzontale e verticale.

