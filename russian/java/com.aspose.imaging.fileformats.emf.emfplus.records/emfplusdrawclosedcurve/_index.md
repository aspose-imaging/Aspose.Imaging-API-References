---
title: "EmfPlusDrawClosedCurve"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawClosedCurve определяет рисование замкнутой кардинальной сплайны"
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawClosedCurve определяет рисование замкнутой кардинальной сплайны
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawClosedCurve`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжата ли эта `EmfPlusDrawClosedCurve`. |
| [getRelative()](#getRelative--) | Получает или задает значение, указывающее, является ли эта `EmfPlusDrawClosedCurve` относительной. |
| [setRelative(boolean value)](#setRelative-boolean-) | Получает или задает значение, указывающее, является ли эта `EmfPlusDrawClosedCurve` относительной. |
| [getTension()](#getTension--) | Получает или задает натяжение — 32-битное число с плавающей точкой, которое определяет, насколько плотно сплайн изгибается при прохождении через точки. |
| [setTension(float value)](#setTension-float-) | Получает или задает натяжение — 32-битное число с плавающей точкой, которое определяет, насколько плотно сплайн изгибается при прохождении через точки. |
| [getPointData()](#getPointData--) | Получает или задаёт данные точек — массив из Count точек, которые задают конечные точки линий, определяющих сплайн. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задаёт данные точек — массив из Count точек, которые задают конечные точки линий, определяющих сплайн. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawClosedCurve`. RecordType — 16-битное беззнаковое целое, которое идентифицирует этот тип записи как EmfPlusDrawClosedCurve из перечисления RecordType (раздел 2.1.1.1). Значение ДОЛЖНО быть 0x4017.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования замкнутой кривой. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования замкнутой кривой. Значение ДОЛЖНО быть от 0 до 63 включительно.

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает данные точек. Массив из Count точек, определяющих конечные точки линий, образующих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку массива PointData и соединяется с первой точкой массива. Тип данных в этом массиве указывается полем Flags следующим образом: Тип данных Значение Описание EmfPlusPointR объект (раздел 2.2.2.37) Если флаг P установлен в Flags, точки задают относительные координаты. EmfPlusPointF объект (раздел 2.2.2.36) Если биты P и C установлены в поле Flags, точки задают абсолютные координаты. EmfPlusPoint объект (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в поле Flags, точки задают относительные координаты.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает данные точек. Массив из Count точек, определяющих конечные точки линий, образующих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку массива PointData и соединяется с первой точкой массива. Тип данных в этом массиве указывается полем Flags следующим образом: Тип данных Значение Описание EmfPlusPointR объект (раздел 2.2.2.37) Если флаг P установлен в Flags, точки задают относительные координаты. EmfPlusPointF объект (раздел 2.2.2.36) Если биты P и C установлены в поле Flags, точки задают абсолютные координаты. EmfPlusPoint объект (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в поле Flags, точки задают относительные координаты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

