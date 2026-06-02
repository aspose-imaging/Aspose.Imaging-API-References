---
title: "VectorImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Векторное изображение является базовым классом для всех типов векторных изображений."
type: docs
weight: 117
url: /ru/java/com.aspose.imaging/vectorimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.interfaces.IObjectWithSizeF](../../com.aspose.imaging.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

Векторное изображение является базовым классом для всех типов векторных изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер до указанной новой ширины. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения с расширенными параметрами. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает указанный прямоугольник. |
| [rotate(float angle)](#rotate-float-) | Поворачивает изображение вокруг центра. |
| [getSizeF()](#getSizeF--) | Получает размер объекта в дюймах. |
| [getWidthF()](#getWidthF--) | Получает ширину объекта в дюймах. |
| [getHeightF()](#getHeightF--) | Получает высоту объекта в дюймах. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры изображения по умолчанию. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Получает встроенные изображения. |
| [removeBackground()](#removeBackground--) | Удаляет фон. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Удаляет фон. |

## Example: The following example shows how to export a multipage vector image to another format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\java\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы
    com.aspose.imaging.IMultipageImage multipageImage = image instanceof com.aspose.imaging.IMultipageImage ? (com.aspose.imaging.IMultipageImage)image : null;
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

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер до указанной новой ширины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения с расширенными параметрами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезает указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


Получает размер объекта в дюймах.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the object size, in inches.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Получает ширину объекта в дюймах.

**Returns:**
float — ширина объекта в дюймах.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Получает высоту объекта в дюймах.

**Returns:**
float — высота объекта в дюймах.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

**Returns:**
int — ширина изображения.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

**Returns:**
int — высота изображения.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получает параметры изображения по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The default image options.
### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Получает встроенные изображения.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - массив изображений

**Example: Support extracting embedded raster images from a vector image**

``` java
String inputFileName = "test.cdr";
try (Image image = com.aspose.imaging.Image.load(inputFileName))
{
    com.aspose.imaging.VectorImage vectorImage = ((com.aspose.imaging.VectorImage) image);
    EmbeddedImage[] images = vectorImage.getEmbeddedImages();
    for (int i = 0; i < images.length; i++)
    {
        String outFileName = String.format("image%d.png", i++);
        try
        {
            images[i].getImage().save(outFileName, new PngOptions());
        }
        finally
        {
            images[i].close();
        }
    }
}
```

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Удаляет фон.

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Удаляет фон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Настройки. |

