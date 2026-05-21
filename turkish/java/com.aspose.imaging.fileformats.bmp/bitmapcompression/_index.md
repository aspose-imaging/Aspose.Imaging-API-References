---
title: "BitmapCompression"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Farklı bitmap sıkıştırma yöntemlerini belirtir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Farklı bitmap sıkıştırma yöntemlerini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Rgb](#Rgb) | Sıkıştırma yok. |
| [Rle8](#Rle8) | RLE 8-bit/piksel sıkıştırması. |
| [Rle4](#Rle4) | RLE 4-bit/piksel sıkıştırması. |
| [Bitfields](#Bitfields) | RGB bit alanları. |
| [Jpeg](#Jpeg) | JPEG sıkıştırması. |
| [Png](#Png) | PNG sıkıştırması. |
| [AlphaBitfields](#AlphaBitfields) | RGBA bit alanları. |
| [Dxt1](#Dxt1) | DXT1 sıkıştırması. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir.
    // Bu modu açıkça belirtmek istiyorsanız, BmpOptions'ın Compression özelliği BitmapCompression.Bitfields olarak ayarlanmalıdır.
    // BitmapCompression.Bitfields sıkıştırma yöntemi BmpOptions içinde varsayılan sıkıştırma yöntemidir.
    // Bu nedenle, şeffaflıkla bir Bmp görüntüsü dışa aktarmanın aynı sonucu aşağıdaki yöntemlerden biriyle elde edilebilir.
    // Örtük bir varsayılan seçenekle:
    pngImage.save(outputPathPng);
    // Açık bir varsayılan seçenekle:
    pngImage.save(outputPathBmp, new BmpOptions());
    // BitmapCompression.Bitfields sıkıştırma yöntemini belirterek:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir, bu BitmapCompression.Bitfields sıkıştırma yöntemi kullanılarak sağlanır.
    // RGB sıkıştırma yöntemiyle bir BMP görüntüsü kaydetmek için, Compression özelliği BitmapCompression.Rgb olarak ayarlanmış BmpOptions belirtilmelidir.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

### Rgb {#Rgb}
```
public static final long Rgb
```


Sıkıştırma yok.

### Rle8 {#Rle8}
```
public static final long Rle8
```


RLE 8-bit/pixel sıkıştırması. Yalnızca 8-bit/pixel bitmaplerde kullanılabilir.

### Rle4 {#Rle4}
```
public static final long Rle4
```


RLE 4-bit/pixel sıkıştırması. Yalnızca 4-bit/pixel bitmaplerde kullanılabilir.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


RGB bit alanları. Yalnızca 16 ve 32-bit/pixel bitmaplerde kullanılabilir.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


JPEG sıkıştırması. Bitmap bir JPEG görüntüsü içerir.

### Png {#Png}
```
public static final long Png
```


PNG sıkıştırması. Bitmap bir PNG görüntüsü içerir.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


RGBA bit alanları. Yalnızca 16 ve 32-bit/pixel bitmaplerde kullanılabilir.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


DXT1 sıkıştırması. Bitmap bir doku içerir.

