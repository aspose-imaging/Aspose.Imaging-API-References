---
title: "BitmapCompression"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает различные методы сжатия битмапа."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Указывает различные методы сжатия битмапа.
## Поля

| Поле | Описание |
| --- | --- |
| [Rgb](#Rgb) | Без сжатия. |
| [Rle8](#Rle8) | Сжатие RLE 8‑бит/пиксель. |
| [Rle4](#Rle4) | Сжатие RLE 4‑бит/пиксель. |
| [Bitfields](#Bitfields) | Битовые поля RGB. |
| [Jpeg](#Jpeg) | Сжатие JPEG. |
| [Png](#Png) | Сжатие PNG. |
| [AlphaBitfields](#AlphaBitfields) | Битовые поля RGBA. |
| [Dxt1](#Dxt1) | Сжатие DXT1. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Загрузить PNG‑изображение из файла.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑изображение сохраняется с поддержкой прозрачности по умолчанию.
    // Если вы хотите явно указать такой режим, свойство Compression объекта BmpOptions должно быть установлено в BitmapCompression.Bitfields.
    // Метод сжатия BitmapCompression.Bitfields является методом сжатия по умолчанию в BmpOptions.
    // Таким образом, тот же результат экспорта BMP‑изображения с прозрачностью можно достичь любым из следующих способов.
    // С неявными параметрами по умолчанию:
    pngImage.save(outputPathPng);
    // С явными параметрами по умолчанию:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Указание метода сжатия BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Загрузить PNG‑изображение из файла.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑изображение сохраняется с поддержкой прозрачности по умолчанию, что достигается использованием метода сжатия BitmapCompression.Bitfields.
    // Чтобы сохранить BMP‑изображение с методом сжатия Rgb, необходимо указать BmpOptions со свойством Compression, установленным в BitmapCompression.Rgb.
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


Без сжатия.

### Rle8 {#Rle8}
```
public static final long Rle8
```


Сжатие RLE 8‑бит/пиксель. Может использоваться только с 8‑бит/пиксель битмапами.

### Rle4 {#Rle4}
```
public static final long Rle4
```


Сжатие RLE 4‑бит/пиксель. Может использоваться только с 4‑бит/пиксель битмапами.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


Битовые поля RGB. Может использоваться только с 16‑ и 32‑бит/пиксель битмапами.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Сжатие JPEG. Битмап содержит изображение JPEG.

### Png {#Png}
```
public static final long Png
```


Сжатие PNG. Битмап содержит изображение PNG.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


Битовые поля RGBA. Может использоваться только с 16‑ и 32‑бит/пиксель битмапами.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


Сжатие DXT1. Битмап содержит текстуру.

