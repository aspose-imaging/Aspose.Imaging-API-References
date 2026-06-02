---
title: "RotateFlipType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定图像旋转的角度以及用于翻转图像的轴。"
type: docs
weight: 100
url: /zh/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

指定图像旋转的角度以及用于翻转图像的轴。
## 字段

| 字段 | 描述 |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | 指定不进行顺时针旋转，也不翻转。 |
| [Rotate90FlipNone](#Rotate90FlipNone) | 指定图像旋转的角度以及用于翻转图像的轴。 |
| [Rotate180FlipNone](#Rotate180FlipNone) | 指定顺时针旋转 180 度且不翻转。 |
| [Rotate270FlipNone](#Rotate270FlipNone) | 指定顺时针旋转 270 度且不翻转。 |
| [RotateNoneFlipX](#RotateNoneFlipX) | 指定不进行顺时针旋转，然后进行水平翻转。 |
| [Rotate90FlipX](#Rotate90FlipX) | 指定顺时针旋转 90 度，然后进行水平翻转。 |
| [Rotate180FlipX](#Rotate180FlipX) | 指定顺时针旋转 180 度，然后进行水平翻转。 |
| [Rotate270FlipX](#Rotate270FlipX) | 指定顺时针旋转 270 度，然后进行水平翻转。 |
| [RotateNoneFlipY](#RotateNoneFlipY) | 指定不进行顺时针旋转，然后进行垂直翻转。 |
| [Rotate90FlipY](#Rotate90FlipY) | 指定顺时针旋转 90 度，然后进行垂直翻转。 |
| [Rotate180FlipY](#Rotate180FlipY) | 指定顺时针旋转 180 度，然后进行垂直翻转。 |
| [Rotate270FlipY](#Rotate270FlipY) | 指定顺时针旋转 270 度，然后进行垂直翻转。 |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | 指定不进行顺时针旋转，然后进行水平和垂直翻转。 |
| [Rotate90FlipXY](#Rotate90FlipXY) | 指定顺时针旋转 90 度，然后进行水平和垂直翻转。 |
| [Rotate180FlipXY](#Rotate180FlipXY) | 指定顺时针旋转 180 度，然后进行水平和垂直翻转。 |
| [Rotate270FlipXY](#Rotate270FlipXY) | 指定顺时针旋转 270 度，然后进行水平和垂直翻转。 |

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
    // 旋转、翻转并保存到输出文件。
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


指定不进行顺时针旋转，也不翻转。

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


指定图像旋转的角度以及用于翻转图像的轴。

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


指定顺时针旋转 180 度且不翻转。

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


指定顺时针旋转 270 度且不翻转。

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


指定不进行顺时针旋转，然后进行水平翻转。

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


指定顺时针旋转 90 度，然后进行水平翻转。

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


指定顺时针旋转 180 度，然后进行水平翻转。

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


指定顺时针旋转 270 度，然后进行水平翻转。

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


指定不进行顺时针旋转，然后进行垂直翻转。

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


指定顺时针旋转 90 度，然后进行垂直翻转。

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


指定顺时针旋转 180 度，然后进行垂直翻转。

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


指定顺时针旋转 270 度，然后进行垂直翻转。

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


指定不进行顺时针旋转，然后进行水平和垂直翻转。

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


指定顺时针旋转 90 度，然后进行水平和垂直翻转。

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


指定顺时针旋转 180 度，然后进行水平和垂直翻转。

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


指定顺时针旋转 270 度，然后进行水平和垂直翻转。

