---
title: "EmfPlusDrawCurve"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawCurve указывает на рисование кардинального сплайна ПРИМЕЧАНИЕ ObjectID 1 байт Индекс объекта EmfPlusPen раздел 2.2.1.7 в таблице объектов EMF для рисования кривой."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawCurve указывает на рисование кардинального сплайна ПРИМЕЧАНИЕ: ObjectID (1 байт): Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для рисования кривой. Значение ДОЛЖНО быть от 0 до 63 включительно.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawCurve`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getTension()](#getTension--) | Получает или задает натяжение — 32-битное число с плавающей точкой, которое определяет, насколько плотно сплайн изгибается при прохождении через точки. |
| [setTension(float value)](#setTension-float-) | Получает или задает натяжение — 32-битное число с плавающей точкой, которое определяет, насколько плотно сплайн изгибается при прохождении через точки. |
| [getNumSegments()](#getNumSegments--) | Получает или задает количество сегментов. 32-битное беззнаковое целое, определяющее число линейных сегментов, составляющих сплайн. |
| [setNumSegments(int value)](#setNumSegments-int-) | Получает или задает количество сегментов. 32-битное беззнаковое целое, определяющее число линейных сегментов, составляющих сплайн. |
| [getPointData()](#getPointData--) | Получает или задает массив из 32-битных знаковых целых или 32-битных чисел с плавающей точкой длиной Count, определяющий координатные значения конечных точек линий для обводки. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задает массив из 32-битных знаковых целых или 32-битных чисел с плавающей точкой длиной Count, определяющий координатные значения конечных точек линий для обводки. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawCurve`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для рисования кривой. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для рисования кривой. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Получает или задает натяжение. 32‑битное число с плавающей запятой, которое определяет, насколько сильно сплайн изгибается при прохождении через точки. Значение 0 указывает, что сплайн представляет собой последовательность прямых линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Получает или задает натяжение. 32‑битное число с плавающей запятой, которое определяет, насколько сильно сплайн изгибается при прохождении через точки. Значение 0 указывает, что сплайн представляет собой последовательность прямых линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Получает или задает количество сегментов. 32-битное беззнаковое целое, определяющее число линейных сегментов, составляющих сплайн.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Получает или задает количество сегментов. 32-битное беззнаковое целое, определяющее число линейных сегментов, составляющих сплайн.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает массив из 32-битных знаковых целых или 32-битных чисел с плавающей точкой длиной Count, определяющий координатные значения конечных точек линий для обводки.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает массив из 32-битных знаковых целых или 32-битных чисел с плавающей точкой длиной Count, определяющий координатные значения конечных точек линий для обводки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

