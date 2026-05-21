---
title: "EmfPaintRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_PAINTRGN рисует указанный регион, используя кисть, в данный момент выбранную в контексте устройства воспроизведения."
type: docs
weight: 80
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

Запись EMR_PAINTRGN закрашивает указанную область, используя кисть, текущую выбранную в контексте устройства воспроизведения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Инициализирует новый экземпляр класса `EmfPaintRgn`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает 128-битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Задает 128-битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [getRgnDataSize()](#getRgnDataSize--) | Получает 32-битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Задает 32-битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [getRgnData()](#getRgnData--) | Получает массив байтов длиной RgnDataSize, который определяет объект RegionData (раздел 2.2.24) в логических единицах. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Задает массив байтов длиной RgnDataSize, который определяет объект RegionData (раздел 2.2.24) в логических единицах. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPaintRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Инициализирует новый экземпляр класса `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает 128-битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Задает 128-битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Получает 32-битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Задает 32-битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Получает массив байтов длиной RgnDataSize, который определяет объект RegionData (раздел 2.2.24) в логических единицах.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Задает массив байтов длиной RgnDataSize, который определяет объект RegionData (раздел 2.2.24) в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

