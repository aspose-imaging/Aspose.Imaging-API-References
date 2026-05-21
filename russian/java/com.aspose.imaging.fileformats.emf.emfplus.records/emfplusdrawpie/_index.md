---
title: "EmfPlusDrawPie"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawPie определяет рисование секции внутренней части эллипса."
type: docs
weight: 26
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawPie определяет рисование секции внутренней части эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawPie`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getStartAngle()](#getStartAngle--) | Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. |
| [setStartAngle(float value)](#setStartAngle-float-) | Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. |
| [getSweepAngle()](#getSweepAngle--) | Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. |
| [getRectData()](#getRectData--) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawPie`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает или задает значение, указывающее, сжаты ли PointData. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.39).

Значение: `true`, если сжато; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжаты ли PointData. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.39).

Значение: `true`, если сжато; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задаёт идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования сектора. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задаёт идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования сектора. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. Любое значение допускается, но ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне от 0,0 включительно до 360,0 исключая верхнюю границу.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. Любое значение допускается, но ДОЛЖНО интерпретироваться по модулю 360, при этом используемый результат находится в диапазоне от 0,0 включительно до 360,0 исключая верхнюю границу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. Любое значение допускается, но ДОЛЖНО быть ограничено диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что разворот определяется по часовой стрелке, а отрицательное — против часовой стрелки.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. Любое значение допускается, но ДОЛЖНО быть ограничено диапазоном от -360,0 до 360,0 включительно. Положительное значение указывает, что разворот определяется по часовой стрелке, а отрицательное — против часовой стрелки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. Этот прямоугольник определяет позицию, размер и форму сектора. Тип объекта в этом поле указывается значением поля Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. Этот прямоугольник определяет позицию, размер и форму сектора. Тип объекта в этом поле указывается значением поля Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

