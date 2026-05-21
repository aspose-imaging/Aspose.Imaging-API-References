---
title: "RotateFlipType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner."
type: docs
weight: 100
url: /fr/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner.
## Champs

| Champ | Description |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Spécifie aucune rotation horaire et aucune inversion. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Spécifie une rotation horaire de 180 degrés sans inversion. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Spécifie une rotation horaire de 270 degrés sans inversion. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Spécifie aucune rotation horaire suivie d'une inversion horizontale. |
| [Rotate90FlipX](#Rotate90FlipX) | Spécifie une rotation horaire de 90 degrés suivie d'une inversion horizontale. |
| [Rotate180FlipX](#Rotate180FlipX) | Spécifie une rotation horaire de 180 degrés suivie d'une inversion horizontale. |
| [Rotate270FlipX](#Rotate270FlipX) | Spécifie une rotation horaire de 270 degrés suivie d'une inversion horizontale. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Spécifie aucune rotation horaire suivie d'une inversion verticale. |
| [Rotate90FlipY](#Rotate90FlipY) | Spécifie une rotation horaire de 90 degrés suivie d'une inversion verticale. |
| [Rotate180FlipY](#Rotate180FlipY) | Spécifie une rotation horaire de 180 degrés suivie d'une inversion verticale. |
| [Rotate270FlipY](#Rotate270FlipY) | Spécifie une rotation horaire de 270 degrés suivie d'une inversion verticale. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Spécifie aucune rotation horaire suivie d'une inversion horizontale et verticale. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Spécifie une rotation horaire de 90 degrés suivie d'une inversion horizontale et verticale. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Spécifie une rotation horaire de 180 degrés suivie d'une inversion horizontale et verticale. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Spécifie une rotation horaire de 270 degrés suivie d'une inversion horizontale et verticale. |

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
    // Faites pivoter, retournez et enregistrez dans le fichier de sortie.
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


Spécifie aucune rotation horaire et aucune inversion.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Spécifie une rotation horaire de 180 degrés sans inversion.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Spécifie une rotation horaire de 270 degrés sans inversion.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Spécifie aucune rotation horaire suivie d'une inversion horizontale.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Spécifie une rotation horaire de 90 degrés suivie d'une inversion horizontale.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Spécifie une rotation horaire de 180 degrés suivie d'une inversion horizontale.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Spécifie une rotation horaire de 270 degrés suivie d'une inversion horizontale.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Spécifie aucune rotation horaire suivie d'une inversion verticale.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Spécifie une rotation horaire de 90 degrés suivie d'une inversion verticale.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Spécifie une rotation horaire de 180 degrés suivie d'une inversion verticale.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Spécifie une rotation horaire de 270 degrés suivie d'une inversion verticale.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Spécifie aucune rotation horaire suivie d'une inversion horizontale et verticale.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Spécifie une rotation horaire de 90 degrés suivie d'une inversion horizontale et verticale.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Spécifie une rotation horaire de 180 degrés suivie d'une inversion horizontale et verticale.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Spécifie une rotation horaire de 270 degrés suivie d'une inversion horizontale et verticale.

