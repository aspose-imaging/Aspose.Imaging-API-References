---
title: "EmfSetPixelV"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETPIXELV определяет цвет пикселя в указанных логических координатах."
type: docs
weight: 135
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

Запись EMR\_SETPIXELV задает цвет пикселя в указанных логических координатах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetPixelV`. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Инициализирует новый экземпляр класса [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv). |
## Методы

| Метод | Описание |
| --- | --- |
| [getPixel()](#getPixel--) | Получает или задает 64‑битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет логические координаты пикселя. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет логические координаты пикселя. |
| [getArgb32Color()](#getArgb32Color--) | Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет пикселя. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет пикселя. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetPixelV`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Инициализирует новый экземпляр класса [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv).

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Получает или задает 64‑битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет логические координаты пикселя.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Получает или задает 64‑битный объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который определяет логические координаты пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет пикселя.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

