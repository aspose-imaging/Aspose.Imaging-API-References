---
title: "WebPOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте современные растровые веб‑изображения WebP с помощью нашего API, обеспечивая надёжную поддержку как без потерь, так и с потерями, а также альфа‑каналы и циклы анимации."
type: docs
weight: 53
url: /ru/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Создавайте современные растровые веб‑изображения WebP с помощью нашего API, обеспечивая надёжную поддержку как без потерь, так и с потерями, а также альфа‑каналы и циклы анимации. Улучшайте веб‑контент динамическими визуальными элементами, оптимизируя размер файлов для повышения скорости загрузки и улучшения пользовательского опыта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getLossless()](#getLossless--) | Получает или задаёт значение, указывающее, является ли этот `WebPOptions` без потерь. |
| [setLossless(boolean value)](#setLossless-boolean-) | Получает или задаёт значение, указывающее, является ли этот `WebPOptions` без потерь. |
| [getQuality()](#getQuality--) | Получает или задаёт качество. |
| [setQuality(float value)](#setQuality-float-) | Получает или задаёт качество. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Получает или задаёт количество циклов анимации. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Получает или задаёт количество циклов анимации. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Получает или задаёт цвет фона анимации. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Получает или задаёт цвет фона анимации. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортируйте только первые две страницы. Эти страницы будут представлены как анимированные кадры в выходном файле WEBP.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Получает или задаёт значение, указывающее, является ли этот `WebPOptions` без потерь.

**Returns:**
boolean — `true`, если без потерь; иначе `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Получает или задаёт значение, указывающее, является ли этот `WebPOptions` без потерь.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если без потерь; иначе `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Получает или задаёт качество.

**Returns:**
float — Качество.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Получает или задаёт качество.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Качество. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Получает или задаёт количество циклов анимации.

**Returns:**
int — Количество циклов анимации, 0 — бесконечность.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Получает или задаёт количество циклов анимации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Количество циклов анимации, 0 — бесконечность. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Получает или задаёт цвет фона анимации.

**Returns:**
long — Цвет фона анимации.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Получает или задаёт цвет фона анимации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Цвет фона анимации. |

