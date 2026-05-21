---
title: "EmfFillRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_FILLRGN заполняет указанную область, используя указанную кисть."
type: docs
weight: 59
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

Запись EMR\_FILLRGN заполняет указанную область, используя указанную кисть.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Инициализирует новый экземпляр класса `EmfFillRgn`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [getRgnDataSize()](#getRgnDataSize--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [getIhBrush()](#getIhBrush--) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти для заполнения области. |
| [setIhBrush(int value)](#setIhBrush-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти для заполнения области. |
| [getRgnData()](#getRgnData--) | Получает или задает массив байтов длиной RgnDataSize, который содержит объект RegionData (section 2.2.24). |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Получает или задает массив байтов длиной RgnDataSize, который содержит объект RegionData (section 2.2.24). |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfFillRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Инициализирует новый экземпляр класса `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти для заполнения области.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти для заполнения области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Получает или задает массив байтов длиной RgnDataSize, который содержит объект RegionData (section 2.2.24).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Получает или задает массив байтов длиной RgnDataSize, который содержит объект RegionData (section 2.2.24).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

