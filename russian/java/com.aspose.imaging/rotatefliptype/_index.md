---
title: "RotateFlipType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает степень вращения изображения и ось, используемую для его отражения."
type: docs
weight: 100
url: /ru/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Указывает степень вращения изображения и ось, используемую для его отражения.
## Поля

| Поле | Описание |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Указывает отсутствие вращения по часовой стрелке и отсутствие отражения. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Указывает степень вращения изображения и ось, используемую для его отражения. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Указывает вращение на 180 градусов по часовой стрелке без отражения. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Указывает вращение на 270 градусов по часовой стрелке без отражения. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Указывает отсутствие вращения по часовой стрелке, за которым следует горизонтальное отражение. |
| [Rotate90FlipX](#Rotate90FlipX) | Указывает вращение на 90 градусов по часовой стрелке, за которым следует горизонтальное отражение. |
| [Rotate180FlipX](#Rotate180FlipX) | Указывает вращение на 180 градусов по часовой стрелке, за которым следует горизонтальное отражение. |
| [Rotate270FlipX](#Rotate270FlipX) | Указывает вращение на 270 градусов по часовой стрелке, за которым следует горизонтальное отражение. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Указывает отсутствие вращения по часовой стрелке, за которым следует вертикальное отражение. |
| [Rotate90FlipY](#Rotate90FlipY) | Указывает вращение на 90 градусов по часовой стрелке, за которым следует вертикальное отражение. |
| [Rotate180FlipY](#Rotate180FlipY) | Указывает вращение на 180 градусов по часовой стрелке, за которым следует вертикальное отражение. |
| [Rotate270FlipY](#Rotate270FlipY) | Указывает вращение на 270 градусов по часовой стрелке, за которым следует вертикальное отражение. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Указывает отсутствие вращения по часовой стрелке, за которым следует горизонтальное и вертикальное отражение. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Указывает вращение на 90 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Указывает вращение на 180 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Указывает вращение на 270 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение. |

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
    // Поверните, отразите и сохраните в выходной файл.
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


Указывает отсутствие вращения по часовой стрелке и отсутствие отражения.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Указывает степень вращения изображения и ось, используемую для его отражения.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Указывает вращение на 180 градусов по часовой стрелке без отражения.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Указывает вращение на 270 градусов по часовой стрелке без отражения.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Указывает отсутствие вращения по часовой стрелке, за которым следует горизонтальное отражение.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Указывает вращение на 90 градусов по часовой стрелке, за которым следует горизонтальное отражение.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Указывает вращение на 180 градусов по часовой стрелке, за которым следует горизонтальное отражение.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Указывает вращение на 270 градусов по часовой стрелке, за которым следует горизонтальное отражение.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Указывает отсутствие вращения по часовой стрелке, за которым следует вертикальное отражение.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Указывает вращение на 90 градусов по часовой стрелке, за которым следует вертикальное отражение.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Указывает вращение на 180 градусов по часовой стрелке, за которым следует вертикальное отражение.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Указывает вращение на 270 градусов по часовой стрелке, за которым следует вертикальное отражение.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Указывает отсутствие вращения по часовой стрелке, за которым следует горизонтальное и вертикальное отражение.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Указывает вращение на 90 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Указывает вращение на 180 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Указывает вращение на 270 градусов по часовой стрелке, за которым следует горизонтальное и вертикальное отражение.

