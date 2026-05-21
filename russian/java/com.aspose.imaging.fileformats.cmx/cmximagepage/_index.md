---
title: "CmxImagePage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Изображение страницы CMX"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

Изображение страницы CMX
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Инициализирует новый экземпляр класса [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Инициализирует новый экземпляр класса [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Методы

| Метод | Описание |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Получает страницу CMX. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных. |
| [getWidthF()](#getWidthF--) | Получает ширину объекта в дюймах. |
| [getHeightF()](#getHeightF--) | Получает высоту объекта в дюймах. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [cacheData()](#cacheData--) | Кеш не может быть использован. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Инициализирует новый экземпляр класса [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | Страница CMX. |
| container | [Image](../../com.aspose.imaging/image) | Контейнер. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Инициализирует новый экземпляр класса [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | Страница CMX. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Получает страницу CMX.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает значение формата файла

**Returns:**
long — значение формата файла
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — количество бит на пиксель изображения.
### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.

Значение: `true`, если данные объекта закешированы; иначе `false`.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.
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
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получает параметры по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеш не может быть использован.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Загрузить изображение из файла CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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

