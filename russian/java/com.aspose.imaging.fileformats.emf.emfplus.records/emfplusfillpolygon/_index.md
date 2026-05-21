---
title: "EmfPlusFillPolygon"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusFillPolygon указывает заполнение внутренней части многоугольника."
type: docs
weight: 36
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

Запись EmfPlusFillPolygon указывает заполнение внутренней части многоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusFillPolygon`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [isCompressed()](#isCompressed--) | Получает или задает значение, указывающее, сжат ли этот экземпляр. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжат ли этот экземпляр. |
| [isRelative()](#isRelative--) | Получает или задает значение, указывающее, является ли этот экземпляр относительным. |
| [setRelative(boolean value)](#setRelative-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр относительным. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
| [getPointData()](#getPointData--) | Получает или задает данные точек — массив из Count точек, определяющих вершины многоугольника. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задает данные точек — массив из Count точек, определяющих вершины многоугольника. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusFillPolygon`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Получает или задает значение, указывающее, сжат ли этот экземпляр. Если установлено, PointData указывает абсолютные положения в координатном пространстве с 16‑битными целочисленными координатами. Если сброшено, PointData указывает абсолютные положения в координатном пространстве с 32‑битными координатами с плавающей точкой.

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжат ли этот экземпляр. Если установлено, PointData указывает абсолютные положения в координатном пространстве с 16‑битными целочисленными координатами. Если сброшено, PointData указывает абсолютные положения в координатном пространстве с 32‑битными координатами с плавающей точкой.

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Получает или задает значение, указывающее, является ли этот экземпляр относительным. Если установлено, каждый элемент в PointData указывает положение в координатном пространстве, относительное к положению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшено, PointData указывает абсолютные положения в соответствии с флагом C.

Значение: `true`, если этот экземпляр относителен; иначе `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Получает или задает значение, указывающее, является ли этот экземпляр относительным. Если установлено, каждый элемент в PointData указывает положение в координатном пространстве, относительное к положению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшено, PointData указывает абсолютные положения в соответствии с флагом C.

Значение: `true`, если этот экземпляр относителен; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает данные точек. Массив из Count точек, определяющих вершины многоугольника. Первые две точки в массиве задают первую сторону многоугольника. Каждая последующая точка задает новую сторону, вершины которой включают текущую точку и предыдущую точку. Если последняя точка и первая точка не совпадают, они задают последнюю сторону многоугольника.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает данные точек. Массив из Count точек, определяющих вершины многоугольника. Первые две точки в массиве задают первую сторону многоугольника. Каждая последующая точка задает новую сторону, вершины которой включают текущую точку и предыдущую точку. Если последняя точка и первая точка не совпадают, они задают последнюю сторону многоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

