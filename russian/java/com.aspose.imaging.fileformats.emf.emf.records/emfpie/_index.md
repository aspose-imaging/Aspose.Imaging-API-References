---
title: "EmfPie"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_PIE определяет сектор в виде куска пирога, ограниченный пересечением эллипса и двух радиалей."
type: docs
weight: 82
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

Запись EMR\\_PIE определяет сектор в виде куска пирога, ограниченный пересечением эллипса и двух радиалей. Пирог обводится текущим пером и заполняется текущей кистью.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPie`. |
| [EmfPie()](#EmfPie--) | Инициализирует новый экземпляр класса `EmfPie`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [getStart()](#getStart--) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки первого радиала. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки первого радиала. |
| [getEnd()](#getEnd--) | Получает или задает 64‑битный объект PointL, который определяет координаты, в логических единицах, конечной точки второго радиала. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект PointL, который определяет координаты, в логических единицах, конечной точки второго радиала. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPie`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Инициализирует новый экземпляр класса `EmfPie`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки первого радиала.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки первого радиала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Получает или задает 64‑битный объект PointL, который определяет координаты, в логических единицах, конечной точки второго радиала.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Получает или задает 64‑битный объект PointL, который определяет координаты, в логических единицах, конечной точки второго радиала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

