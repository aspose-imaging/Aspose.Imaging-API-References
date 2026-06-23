---
title: "RotateFlipType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة."
type: docs
weight: 100
url: /ar/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | يحدد عدم وجود دوران باتجاه عقارب الساعة ولا عكس. |
| [Rotate90FlipNone](#Rotate90FlipNone) | يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة. |
| [Rotate180FlipNone](#Rotate180FlipNone) | يحدد دورانًا باتجاه عقارب الساعة 180 درجة دون عكس. |
| [Rotate270FlipNone](#Rotate270FlipNone) | يحدد دورانًا باتجاه عقارب الساعة 270 درجة دون عكس. |
| [RotateNoneFlipX](#RotateNoneFlipX) | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه عكس أفقي. |
| [Rotate90FlipX](#Rotate90FlipX) | يحدد دورانًا باتجاه عقارب الساعة 90 درجة يليه عكس أفقي. |
| [Rotate180FlipX](#Rotate180FlipX) | يحدد دورانًا باتجاه عقارب الساعة 180 درجة يليه عكس أفقي. |
| [Rotate270FlipX](#Rotate270FlipX) | يحدد دورانًا باتجاه عقارب الساعة 270 درجة يليه عكس أفقي. |
| [RotateNoneFlipY](#RotateNoneFlipY) | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه عكس عمودي. |
| [Rotate90FlipY](#Rotate90FlipY) | يحدد دورانًا باتجاه عقارب الساعة 90 درجة يليه عكس عمودي. |
| [Rotate180FlipY](#Rotate180FlipY) | يحدد دورانًا باتجاه عقارب الساعة 180 درجة يليه عكس عمودي. |
| [Rotate270FlipY](#Rotate270FlipY) | يحدد دورانًا بزاوية 270 درجة باتجاه عقارب الساعة يليه انعكاس عمودي. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي. |
| [Rotate90FlipXY](#Rotate90FlipXY) | يحدد دورانًا بزاوية 90 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي. |
| [Rotate180FlipXY](#Rotate180FlipXY) | يحدد دورانًا بزاوية 180 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي. |
| [Rotate270FlipXY](#Rotate270FlipXY) | يحدد دورانًا بزاوية 270 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي. |

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
    // قم بالدوران، والقلّب، واحفظ إلى ملف الإخراج.
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


يحدد عدم وجود دوران باتجاه عقارب الساعة ولا عكس.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


يحدد دورانًا باتجاه عقارب الساعة 180 درجة دون عكس.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


يحدد دورانًا باتجاه عقارب الساعة 270 درجة دون عكس.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


يحدد عدم وجود دوران باتجاه عقارب الساعة يليه عكس أفقي.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


يحدد دورانًا باتجاه عقارب الساعة 90 درجة يليه عكس أفقي.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


يحدد دورانًا باتجاه عقارب الساعة 180 درجة يليه عكس أفقي.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


يحدد دورانًا باتجاه عقارب الساعة 270 درجة يليه عكس أفقي.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


يحدد عدم وجود دوران باتجاه عقارب الساعة يليه عكس عمودي.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


يحدد دورانًا باتجاه عقارب الساعة 90 درجة يليه عكس عمودي.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


يحدد دورانًا باتجاه عقارب الساعة 180 درجة يليه عكس عمودي.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


يحدد دورانًا بزاوية 270 درجة باتجاه عقارب الساعة يليه انعكاس عمودي.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


يحدد عدم وجود دوران باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


يحدد دورانًا بزاوية 90 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


يحدد دورانًا بزاوية 180 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


يحدد دورانًا بزاوية 270 درجة باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي.

