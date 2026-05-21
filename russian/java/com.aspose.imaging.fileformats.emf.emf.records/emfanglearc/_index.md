---
title: "EmfAngleArc"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_ANGLEARC указывает отрезок дуги."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

Запись EMR\_ANGLEARC указывает отрезок дуги. Отрезок рисуется от текущей позиции до начала дуги. Дуга рисуется вдоль периметра круга с заданным радиусом и центром. Длина дуги определяется заданными начальными и конечными (углами охвата) углами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | Инициализирует новый экземпляр класса `EmfAngleArc`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCenter()](#getCenter--) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты центра круга. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты центра круга. |
| [getRadius()](#getRadius--) | Получает или задает 32‑битное беззнаковое целое, определяющее радиус круга в логических единицах. |
| [setRadius(int value)](#setRadius-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее радиус круга в логических единицах. |
| [getStartAngle()](#getStartAngle--) | Получает или задает 32‑битное число с плавающей точкой, определяющее начальный угол дуги в градусах. |
| [setStartAngle(float value)](#setStartAngle-float-) | Получает или задает 32‑битное число с плавающей точкой, определяющее начальный угол дуги в градусах. |
| [getSweepAngle()](#getSweepAngle--) | Получает или задает 32‑битное число с плавающей точкой, определяющее угол охвата дуги в градусах. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Получает или задает 32‑битное число с плавающей точкой, определяющее угол охвата дуги в градусах. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfAngleArc`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Инициализирует новый экземпляр класса `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты центра круга.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Получает или задает 64‑битный объект WMF PointL, указанный в [MS-WMF] раздел 2.2.2.15, который определяет логические координаты центра круга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Получает или задает 32‑битное беззнаковое целое, определяющее радиус круга в логических единицах.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее радиус круга в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Получает или задает 32‑битное число с плавающей точкой, определяющее начальный угол дуги в градусах.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Получает или задает 32‑битное число с плавающей точкой, определяющее начальный угол дуги в градусах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Получает или задает 32‑битное число с плавающей точкой, определяющее угол охвата дуги в градусах.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Получает или задает 32‑битное число с плавающей точкой, определяющее угол охвата дуги в градусах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

