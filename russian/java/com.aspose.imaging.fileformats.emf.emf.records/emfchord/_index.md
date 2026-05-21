---
title: "EmfChord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CHORD определяет хорду, представляющую собой область, ограниченную пересечением эллипса и отрезка, называемого секущей."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

Запись EMR\_CHORD определяет хорду, представляющую собой область, ограниченную пересечением эллипса и отрезка, называемого секущей. Хорда обводится текущей ручкой и заполняется текущей кистью.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfChord`. |
| [EmfChord()](#EmfChord--) | Инициализирует новый экземпляр класса `EmfChord`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет включительно‑включительный ограничивающий прямоугольник. |
| [getStart()](#getStart--) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты конечной точки радиуса, определяющего начало хорды. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты конечной точки радиуса, определяющего начало хорды. |
| [getEnd()](#getEnd--) | Получает или задает 64‑битный объект WMF PointL, который определяет логические координаты конечной точки радиуса, определяющего конец хорды. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, который определяет логические координаты конечной точки радиуса, определяющего конец хорды. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfChord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Инициализирует новый экземпляр класса `EmfChord`.

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


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты конечной точки радиуса, определяющего начало хорды.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты конечной точки радиуса, определяющего начало хорды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Получает или задает 64‑битный объект WMF PointL, который определяет логические координаты конечной точки радиуса, определяющего конец хорды.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Получает или задает 64‑битный объект WMF PointL, который определяет логические координаты конечной точки радиуса, определяющего конец хорды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

