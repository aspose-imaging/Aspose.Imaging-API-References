---
title: "EmfArc"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_ARC определяет эллиптическую дугу."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

Запись EMR\_ARC определяет эллиптическую дугу.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfArc`. |
| [EmfArc()](#EmfArc--) | Инициализирует новый экземпляр класса `EmfArc`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [getStart()](#getStart--) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей начальную точку дуги. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей начальную точку дуги. |
| [getEnd()](#getEnd--) | Получает или задает 64‑битный объект WMF PointL, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей конечную точку дуги. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей конечную точку дуги. |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfArc`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


Инициализирует новый экземпляр класса `EmfArc`.

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


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей начальную точку дуги.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] разделе 2.2.2.15, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей начальную точку дуги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Получает или задает 64‑битный объект WMF PointL, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей конечную точку дуги.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Получает или задает 64‑битный объект WMF PointL, который определяет координаты, в логических единицах, конечной точки радиальной линии, задающей конечную точку дуги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

