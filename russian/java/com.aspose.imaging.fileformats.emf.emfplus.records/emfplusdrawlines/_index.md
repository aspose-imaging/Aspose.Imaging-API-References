---
title: "EmfPlusDrawLines"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawlLines определяет рисование серии соединённых линий"
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawlLines определяет рисование серии соединённых линий
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawLines`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [getRelative()](#getRelative--) | Получает или задает значение, указывающее, является ли эта `EmfPlusDrawClosedCurve` относительной. |
| [setRelative(boolean value)](#setRelative-boolean-) | Получает или задает значение, указывающее, является ли эта `EmfPlusDrawClosedCurve` относительной. |
| [getClosedShape()](#getClosedShape--) | Получает или задает значение, указывающее, является ли [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Получает или задает значение, указывающее, является ли [closed shape]. |
| [getPointData()](#getPointData--) | Получает или задает данные точек — массив из Count точек, определяющих начальные и конечные точки линий, которые будут нарисованы. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задает данные точек — массив из Count точек, определяющих начальные и конечные точки линий, которые будут нарисованы. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawLines`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования линий. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования линий. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает или задает значение, указывающее, сжат ли этот `EmfPlusDrawClosedCurve`. Этот бит указывает, задает ли поле PointData сжатые данные. Если установлен, PointData задает абсолютные положения в системе координат с 16‑битными целочисленными координатами. Если сброшен, PointData задает абсолютные положения в системе координат с 32‑битными координатами с плавающей точкой. Примечание: если флаг Relative (ниже) установлен, этот флаг не определён и ДОЛЖЕН быть проигнорирован.

Значение: `true`, если сжато; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжат ли этот `EmfPlusDrawClosedCurve`. Этот бит указывает, задает ли поле PointData сжатые данные. Если установлен, PointData задает абсолютные положения в системе координат с 16‑битными целочисленными координатами. Если сброшен, PointData задает абсолютные положения в системе координат с 32‑битными координатами с плавающей точкой. Примечание: если флаг Relative (ниже) установлен, этот флаг не определён и ДОЛЖЕН быть проигнорирован.

Значение: `true`, если сжато; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Получает или задает значение, указывающее, является ли этот `EmfPlusDrawClosedCurve` относительным. Этот бит указывает, задает ли поле PointData относительные или абсолютные положения. Если установлен, каждый элемент в PointData задает положение в системе координат, относительное к положению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшен, PointData задает абсолютные положения в соответствии с флагом C. Примечание: если этот флаг установлен, флаг Compressed (выше) не определён и ДОЛЖЕН быть проигнорирован.

Значение: `true`, если относительный; иначе `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Получает или задает значение, указывающее, является ли этот `EmfPlusDrawClosedCurve` относительным. Этот бит указывает, задает ли поле PointData относительные или абсолютные положения. Если установлен, каждый элемент в PointData задает положение в системе координат, относительное к положению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшен, PointData задает абсолютные положения в соответствии с флагом C. Примечание: если этот флаг установлен, флаг Compressed (выше) не определён и ДОЛЖЕН быть проигнорирован.

Значение: `true`, если относительный; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Получает или задает значение, указывающее, является ли [closed shape].

Значение: `true`, если [closed shape]; иначе `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Получает или задает значение, указывающее, является ли [closed shape].

Значение: `true`, если [closed shape]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает данные точек — массив из Count точек, определяющих начальные и конечные точки линий, которые будут нарисованы.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает данные точек — массив из Count точек, определяющих начальные и конечные точки линий, которые будут нарисованы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

