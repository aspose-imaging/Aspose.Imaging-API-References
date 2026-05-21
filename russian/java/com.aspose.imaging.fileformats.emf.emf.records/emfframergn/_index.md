---
title: "EmfFrameRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_FRAMERGN рисует границу вокруг указанного региона, используя указанную кисть."
type: docs
weight: 62
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

Запись EMR\_FRAMERGN рисует границу вокруг указанной области, используя указанную кисть.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Инициализирует новый экземпляр класса [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает 128-битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает 128-битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [getRgnDataSize()](#getRgnDataSize--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [getIhBrush()](#getIhBrush--) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти. |
| [setIhBrush(int value)](#setIhBrush-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти. |
| [getWidth()](#getWidth--) | Получает или задает 32-битное знаковое целое, которое определяет ширину вертикального штриха кисти в логических единицах. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает 32-битное знаковое целое, которое определяет ширину вертикального штриха кисти в логических единицах. |
| [getHeight()](#getHeight--) | Получает или задает 32-битное знаковое целое, которое определяет высоту горизонтального штриха кисти в логических единицах. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает 32-битное знаковое целое, которое определяет высоту горизонтального штриха кисти в логических единицах. |
| [getRgnData()](#getRgnData--) | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfFrameRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Инициализирует новый экземпляр класса [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает 128-битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает 128-битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

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


Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс таблицы объектов EMF кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает 32-битное знаковое целое, которое определяет ширину вертикального штриха кисти в логических единицах.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет ширину вертикального штриха кисти в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задает 32-битное знаковое целое, которое определяет высоту горизонтального штриха кисти в логических единицах.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет высоту горизонтального штриха кисти в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

