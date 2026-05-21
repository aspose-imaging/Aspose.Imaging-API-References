---
title: "RotateFlipType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir görüntünün ne kadar döndürüleceğini ve görüntüyü çevirmek için kullanılan ekseni belirtir."
type: docs
weight: 100
url: /tr/java/com.aspose.imaging/rotatefliptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RotateFlipType extends System.Enum
```

Bir görüntünün ne kadar döndürüleceğini ve görüntüyü çevirmek için kullanılan ekseni belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RotateNoneFlipNone](#RotateNoneFlipNone) | Saat yönünde dönüş ve çevirme yapılmadığını belirtir. |
| [Rotate90FlipNone](#Rotate90FlipNone) | Bir görüntünün ne kadar döndürüleceğini ve görüntüyü çevirmek için kullanılan ekseni belirtir. |
| [Rotate180FlipNone](#Rotate180FlipNone) | Saat yönünde 180 derecelik dönüş, çevirme olmadan belirtir. |
| [Rotate270FlipNone](#Rotate270FlipNone) | Saat yönünde 270 derecelik dönüş, çevirme olmadan belirtir. |
| [RotateNoneFlipX](#RotateNoneFlipX) | Saat yönünde dönüş yapılmadan, ardından yatay çevirme yapılacağını belirtir. |
| [Rotate90FlipX](#Rotate90FlipX) | Saat yönünde 90 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir. |
| [Rotate180FlipX](#Rotate180FlipX) | Saat yönünde 180 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir. |
| [Rotate270FlipX](#Rotate270FlipX) | Saat yönünde 270 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir. |
| [RotateNoneFlipY](#RotateNoneFlipY) | Saat yönünde dönüş yapılmadan, ardından dikey çevirme yapılacağını belirtir. |
| [Rotate90FlipY](#Rotate90FlipY) | Saat yönünde 90 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir. |
| [Rotate180FlipY](#Rotate180FlipY) | Saat yönünde 180 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir. |
| [Rotate270FlipY](#Rotate270FlipY) | Saat yönünde 270 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir. |
| [RotateNoneFlipXY](#RotateNoneFlipXY) | Saat yönünde dönüş yapılmadan, ardından yatay ve dikey çevirme yapılacağını belirtir. |
| [Rotate90FlipXY](#Rotate90FlipXY) | Saat yönünde 90 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir. |
| [Rotate180FlipXY](#Rotate180FlipXY) | Saat yönünde 180 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir. |
| [Rotate270FlipXY](#Rotate270FlipXY) | Saat yönünde 270 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir. |

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
    // Döndür, çevir ve çıktıyı dosyaya kaydet.
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


Saat yönünde dönüş ve çevirme yapılmadığını belirtir.

### Rotate90FlipNone {#Rotate90FlipNone}
```
public static final int Rotate90FlipNone
```


Bir görüntünün ne kadar döndürüleceğini ve görüntüyü çevirmek için kullanılan ekseni belirtir.

### Rotate180FlipNone {#Rotate180FlipNone}
```
public static final int Rotate180FlipNone
```


Saat yönünde 180 derecelik dönüş, çevirme olmadan belirtir.

### Rotate270FlipNone {#Rotate270FlipNone}
```
public static final int Rotate270FlipNone
```


Saat yönünde 270 derecelik dönüş, çevirme olmadan belirtir.

### RotateNoneFlipX {#RotateNoneFlipX}
```
public static final int RotateNoneFlipX
```


Saat yönünde dönüş yapılmadan, ardından yatay çevirme yapılacağını belirtir.

### Rotate90FlipX {#Rotate90FlipX}
```
public static final int Rotate90FlipX
```


Saat yönünde 90 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir.

### Rotate180FlipX {#Rotate180FlipX}
```
public static final int Rotate180FlipX
```


Saat yönünde 180 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir.

### Rotate270FlipX {#Rotate270FlipX}
```
public static final int Rotate270FlipX
```


Saat yönünde 270 derecelik dönüş, ardından yatay çevirme yapılacağını belirtir.

### RotateNoneFlipY {#RotateNoneFlipY}
```
public static final int RotateNoneFlipY
```


Saat yönünde dönüş yapılmadan, ardından dikey çevirme yapılacağını belirtir.

### Rotate90FlipY {#Rotate90FlipY}
```
public static final int Rotate90FlipY
```


Saat yönünde 90 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir.

### Rotate180FlipY {#Rotate180FlipY}
```
public static final int Rotate180FlipY
```


Saat yönünde 180 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir.

### Rotate270FlipY {#Rotate270FlipY}
```
public static final int Rotate270FlipY
```


Saat yönünde 270 derecelik dönüş, ardından dikey çevirme yapılacağını belirtir.

### RotateNoneFlipXY {#RotateNoneFlipXY}
```
public static final int RotateNoneFlipXY
```


Saat yönünde dönüş yapılmadan, ardından yatay ve dikey çevirme yapılacağını belirtir.

### Rotate90FlipXY {#Rotate90FlipXY}
```
public static final int Rotate90FlipXY
```


Saat yönünde 90 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir.

### Rotate180FlipXY {#Rotate180FlipXY}
```
public static final int Rotate180FlipXY
```


Saat yönünde 180 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir.

### Rotate270FlipXY {#Rotate270FlipXY}
```
public static final int Rotate270FlipXY
```


Saat yönünde 270 derecelik dönüş, ardından yatay ve dikey çevirme yapılacağını belirtir.

