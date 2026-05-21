---
title: "EmfExtFloodFill"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTFLOODFILL заполняет область поверхности отображения текущей кистью."
type: docs
weight: 54
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

Запись EMR\_EXTFLOODFILL заполняет область поверхности дисплея текущей кистью
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtFloodFill`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStart()](#getStart--) | Получает или задает объект WMF PointL ([MS-WMF] section 2.2.2.15), который определяет координаты в логических единицах, где начинается заполнение. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Получает или задает объект WMF PointL ([MS-WMF] section 2.2.2.15), который определяет координаты в логических единицах, где начинается заполнение. |
| [getArgb32Color()](#getArgb32Color--) | Получает или задает объект WMF ColorRef ([MS-WMF] section 2.2.2.8), который используется вместе с FloodFillMode для определения области заполнения. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] section 2.2.2.8), который используется вместе с FloodFillMode для определения области заполнения. |
| [getFloodFillMode()](#getFloodFillMode--) | Получает или задает 32-битное беззнаковое целое, которое определяет, как использовать значение Color для определения области операции заливки. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет, как использовать значение Color для определения области операции заливки. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExtFloodFill`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getStart() {#getStart--}
```
public Point getStart()
```


Получает или задает объект WMF PointL ([MS-WMF] section 2.2.2.15), который определяет координаты в логических единицах, где начинается заполнение.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Получает или задает объект WMF PointL ([MS-WMF] section 2.2.2.15), который определяет координаты в логических единицах, где начинается заполнение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Получает или задает объект WMF ColorRef ([MS-WMF] section 2.2.2.8), который используется вместе с FloodFillMode для определения области заполнения.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] section 2.2.2.8), который используется вместе с FloodFillMode для определения области заполнения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как использовать значение Color для определения области операции заливки. Значение MUST быть в перечислении FloodFill (section 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как использовать значение Color для определения области операции заливки. Значение MUST быть в перечислении FloodFill (section 2.1.13).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

