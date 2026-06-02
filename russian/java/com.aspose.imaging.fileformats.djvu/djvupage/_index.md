---
title: "DjvuPage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс страницы Djvu"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Класс страницы Djvu
## Поля

| Поле | Описание |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Происходит, когда [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Происходит, когда значение свойства изменяется. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getParentImage()](#getParentImage--) | Получает родительское изображение, к которому принадлежит страница |
| [getWidth()](#getWidth--) | Получает ширину страницы |
| [getHeight()](#getHeight--) | Получает высоту страницы |
| [getImage()](#getImage--) | Получает изображение. |
| [getThumbnailImage()](#getThumbnailImage--) | Получает или задает миниатюрное изображение для страницы |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Получает или задает миниатюрное изображение для страницы |
| [getPageNumber()](#getPageNumber--) | Получает номер страницы. |
| [isColor()](#isColor--) | Получает значение, указывающее, является ли этот экземпляр цветным. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Получает текст для расположения прямоугольника |
| [getForegroundImage()](#getForegroundImage--) | Получает изображение переднего плана страницы |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Получает изображение переднего плана страницы |
| [getTextImage()](#getTextImage--) | Получает текстовое изображение. |
| [getTextImage(int subsample)](#getTextImage-int-) | Получает текстовое изображение. |
| [getBackgroundImage()](#getBackgroundImage--) | Получает изображение фона. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Извлекает миниатюрное изображение из страницы Djvu. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Происходит, когда [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Происходит, когда значение свойства изменяется.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Получает родительское изображение, к которому принадлежит страница

Значение: Документ.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину страницы

Значение: Ширина.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту страницы

Значение: Высота.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Получает изображение.

Значение: Изображение.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Получает или задает миниатюрное изображение для страницы

Значение: Миниатюрное изображение.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Получает или задает миниатюрное изображение для страницы

Значение: Миниатюрное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает номер страницы.

Значение: Номер страницы.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы:    1
//Номер первой страницы:     1
//Номер последней страницы:      2
//--------------------------------------------------
//Номер страницы:     1
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
//--------------------------------------------------
//Номер страницы:     2
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает значение, указывающее, является ли этот экземпляр цветным.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Получает текст для расположения прямоугольника

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник расположения. |

**Returns:**
java.lang.String - Текст, найденный в месте
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Получает изображение переднего плана страницы

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Получает изображение переднего плана страницы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| подвыборка | int | Подвыборка. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Получает текстовое изображение.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Получает текстовое изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| подвыборка | int | Подвыборка. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Получает изображение фона.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Извлекает миниатюрное изображение из страницы Djvu.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
