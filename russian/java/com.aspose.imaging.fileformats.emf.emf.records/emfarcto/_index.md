---
title: "EmfArcTo"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_ARCTO определяет эллиптическую дугу."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

Запись EMR\_ARCTO определяет эллиптическую дугу. Она сбрасывает текущую позицию к конечной точке дуги.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | Инициализирует новый экземпляр класса `EmfArcTo`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [getStart()](#getStart--) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет координаты первой конечной точки радиуса в логических единицах. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет координаты первой конечной точки радиуса в логических единицах. |
| [getEnd()](#getEnd--) | Получает или задает 64-битный объект WMF PointL, который определяет координаты второй конечной точки радиуса в логических единицах. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Получает или задает 64-битный объект WMF PointL, который определяет координаты второй конечной точки радиуса в логических единицах. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfArcTo`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Инициализирует новый экземпляр класса `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет координаты первой конечной точки радиуса в логических единицах.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет координаты первой конечной точки радиуса в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Получает или задает 64-битный объект WMF PointL, который определяет координаты второй конечной точки радиуса в логических единицах.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Получает или задает 64-битный объект WMF PointL, который определяет координаты второй конечной точки радиуса в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

