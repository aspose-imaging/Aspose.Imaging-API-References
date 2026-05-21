---
title: "EmfPlusDrawArc"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawArc определяет рисование дуги эллипса."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawArc определяет рисование дуги эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawArc`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDataSize()](#getDataSize--) | Получает размер данных. |
| [setDataSize(int value)](#setDataSize-int-) | Задает размер данных. |
| [getRectFloat()](#getRectFloat--) | Получает значение, указывающее, содержит ли данные записи EmfPlusRectF или EmfPlusRect. Этот бит указывает, сжаты ли данные в поле RectData. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Задает значение, указывающее, содержит ли данные записи EmfPlusRectF или EmfPlusRect. Этот бит указывает, сжаты ли данные в поле RectData. |
| [getObjectId()](#getObjectId--) | Получает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Задает идентификатор объекта. |
| [getSize()](#getSize--) | Получает размер. |
| [setSize(int value)](#setSize-int-) | Задает размер. |
| [getStartAngle()](#getStartAngle--) | Получает начальный угол. 32-битное неотрицательное число с плавающей точкой, которое задает угол между осью x и начальной точкой дуги. |
| [setStartAngle(float value)](#setStartAngle-float-) | Задает начальный угол. 32-битное неотрицательное число с плавающей точкой, которое задает угол между осью x и начальной точкой дуги. |
| [getSweepAngle()](#getSweepAngle--) | Получает угол разворота. 32-битное число с плавающей точкой, которое задает протяженность дуги для рисования, как угол в градусах, измеряемый от начальной точки, определенной значением StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Задает угол разворота. 32-битное число с плавающей точкой, которое задает протяженность дуги для рисования, как угол в градусах, измеряемый от начальной точки, определенной значением StartAngle. |
| [getRectangleData()](#getRectangleData--) | Получает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, коллинеарного дуге. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, коллинеарного дуге. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawArc`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Получает размер данных. 32-битное беззнаковое целое, которое указывает количество байтов, выровненных по 32-битам, специфичных для записи, следующих за ним. Для этого типа записи значение ДОЛЖНО быть одним из следующих: 0x00000010, если бит C установлен в поле Flags; 0x00000018, если бит C сброшен в поле Flags.

**Returns:**
int - Размер данных.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Задает размер данных. 32-битное беззнаковое целое, которое указывает количество байтов, выровненных по 32-битам, специфичных для записи, следующих за ним. Для этого типа записи значение ДОЛЖНО быть одним из следующих: 0x00000010, если бит C установлен в поле Flags; 0x00000018, если бит C сброшен в поле Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Размер данных. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Получает значение, указывающее, содержит ли данные записи EmfPlusRectF или EmfPlusRect. Этот бит указывает, сжаты ли данные в поле RectData. Если установлен, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшен, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39).

**Returns:**
логический - `true`, если float; иначе `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Устанавливает значение, указывающее, содержит ли данные записи EmfPlusRectF или EmfPlusRect. Этот бит указывает, сжаты ли данные в поле RectData. Если установлен, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшен, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если float; иначе `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования дуги. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Returns:**
byte — идентификатор объекта.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Устанавливает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования дуги. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Идентификатор объекта. |

### getSize() {#getSize--}
```
public int getSize()
```


Получает размер. 32‑битное беззнаковое целое, указывающее количество байтов, выровненное по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. Для этого типа записи значение ДОЛЖНО быть одним из следующих: 0x0000001C, если бит C установлен в поле Flags; 0x00000024, если бит C сброшен в поле Flags.

**Returns:**
int - Размер.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Устанавливает размер. 32‑битное беззнаковое целое, указывающее количество байтов, выровненное по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. Для этого типа записи значение ДОЛЖНО быть одним из следующих: 0x0000001C, если бит C установлен в поле Flags; 0x00000024, если бит C сброшен в поле Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Размер. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Получает начальный угол. 32‑битное неотрицательное число с плавающей точкой, указывающее угол между осью X и начальной точкой дуги. Любое значение допускается, но оно ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне от 0,0 включительно до 360,0 исключая.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Устанавливает начальный угол. 32‑битное неотрицательное число с плавающей точкой, указывающее угол между осью X и начальной точкой дуги. Любое значение допускается, но оно ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне от 0,0 включительно до 360,0 исключая.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Получает угол охвата. 32‑битное число с плавающей точкой, указывающее протяжённость дуги для рисования, как угол в градусах, измеряемый от начальной точки, определённой значением StartAngle. Любое значение допускается, но оно ДОЛЖНО быть ограничено диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что охват определяется по часовой стрелке, а отрицательное — против часовой стрелки.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Устанавливает угол охвата. 32‑битное число с плавающей точкой, указывающее протяжённость дуги для рисования, как угол в градусах, измеряемый от начальной точки, определённой значением StartAngle. Любое значение допускается, но оно ДОЛЖНО быть ограничено диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что охват определяется по часовой стрелке, а отрицательное — против часовой стрелки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Получает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, коллинеарного дуге. Этот прямоугольник задаёт позицию, размер и форму дуги. Тип объекта в этом поле задаётся значением поля Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Устанавливает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, коллинеарного дуге. Этот прямоугольник задаёт позицию, размер и форму дуги. Тип объекта в этом поле задаётся значением поля Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

