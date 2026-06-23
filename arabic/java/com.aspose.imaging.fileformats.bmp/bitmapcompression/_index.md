---
title: "BitmapCompression"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد طرق ضغط البت ماب المختلفة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

يحدد طرق ضغط البت ماب المختلفة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Rgb](#Rgb) | بدون ضغط. |
| [Rle8](#Rle8) | ضغط RLE 8-بت/بكسل. |
| [Rle4](#Rle4) | ضغط RLE 4-بت/بكسل. |
| [Bitfields](#Bitfields) | حقول بت RGB. |
| [Jpeg](#Jpeg) | ضغط JPEG. |
| [Png](#Png) | ضغط PNG. |
| [AlphaBitfields](#AlphaBitfields) | حقول بت RGBA. |
| [Dxt1](#Dxt1) | ضغط DXT1. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت تريد تحديد هذا الوضع صراحةً، يجب تعيين خاصية Compression في BmpOptions إلى BitmapCompression.Bitfields.
    // طريقة ضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.save(outputPathPng);
    // مع خيارات افتراضية صريحة:
    pngImage.save(outputPathBmp, new BmpOptions());
    // تحديد طريقة ضغط BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة ضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة ضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
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


بدون ضغط.

### Rle8 {#Rle8}
```
public static final long Rle8
```


ضغط RLE 8-بت/بكسل. يمكن استخدامه فقط مع صور bitmap بدقة 8-بت/بكسل.

### Rle4 {#Rle4}
```
public static final long Rle4
```


ضغط RLE 4-بت/بكسل. يمكن استخدامه فقط مع صور bitmap بدقة 4-بت/بكسل.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


حقول بت RGB. يمكن استخدامها فقط مع صور bitmap بدقة 16 و 32-بت/بكسل.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


ضغط JPEG. يحتوي bitmap على صورة JPEG.

### Png {#Png}
```
public static final long Png
```


ضغط PNG. يحتوي bitmap على صورة PNG.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


حقول بت RGBA. يمكن استخدامها فقط مع صور bitmap بدقة 16 و 32-بت/بكسل.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


ضغط DXT1. يحتوي bitmap على نسيج.

