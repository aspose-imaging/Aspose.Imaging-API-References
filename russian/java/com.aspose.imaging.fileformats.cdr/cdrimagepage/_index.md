---
title: "CdrImagePage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Страница изображения Cdr."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

Страница изображения Cdr.
## Методы

| Метод | Описание |
| --- | --- |
| [getParentImage()](#getParentImage--) | Получает родительское изображение. |
| [getPageNumber()](#getPageNumber--) | Получает номер страницы. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getCdrDocument()](#getCdrDocument--) | Получает документ CDR. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` не будет выполнена. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Получает родительское изображение.

Значение: Родительское изображение.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Получает номер страницы.

Значение: Номер страницы.

**Returns:**
int — номер страницы.
### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — количество бит на пиксель изображения.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает значение формата файла

**Returns:**
long — значение формата файла
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Получает документ CDR.

Значение: Документ CDR.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
public synchronized void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` не будет выполнена.

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

