---
title: "VectorMultipageImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Векторное многостраничное изображение"
type: docs
weight: 118
url: /ru/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

Векторное многостраничное изображение
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getDefaultPage()](#getDefaultPage--) | Получает страницу по умолчанию. |
| [getPageExportingAction()](#getPageExportingAction--) | Получает действие экспорта страницы. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Устанавливает действие экспорта страницы. |
| [getMetadata()](#getMetadata--) | Получает метаданные изображения. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает указанный прямоугольник. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [rotate(float angle)](#rotate-float-) | Поворачивает изображение вокруг центра. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Удаляет фон. |
| [removeBackground()](#removeBackground--) | Удаляет фон. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Получает встроенные изображения. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.

Значение: `true`, если данные объекта закешированы; иначе `false`.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int — количество бит на пиксель изображения.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

Значение: ширина изображения.

**Returns:**
int — ширина изображения.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

Значение: высота изображения.

**Returns:**
int — высота изображения.
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


Получает страницу по умолчанию.

Значение: страница по умолчанию.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Получает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освободит ресурсы страницы после его выполнения. Он будет выполнен непосредственно перед сохранением каждой страницы.

Значение: действие экспорта страницы.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Устанавливает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освободит ресурсы страницы после его выполнения. Он будет выполнен непосредственно перед сохранением каждой страницы.

Значение: действие экспорта страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | действие экспорта страницы. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Получает метаданные изображения.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезает указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения.

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

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Удаляет фон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Настройки. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Удаляет фон.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Получает встроенные изображения.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - массив изображений
