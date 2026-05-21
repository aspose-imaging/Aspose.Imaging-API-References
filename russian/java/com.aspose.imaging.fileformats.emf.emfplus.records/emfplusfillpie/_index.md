---
title: "EmfPlusFillPie"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusFillPie указывает заполнение секции внутренней части эллипса."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

Запись EmfPlusFillPie указывает заполнение секции внутренней части эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusFillPie`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [getStartAngle()](#getStartAngle--) | Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. |
| [setStartAngle(float value)](#setStartAngle-float-) | Получает или задает начальный угол. 32‑битное неотрицательное число с плавающей запятой, определяющее угол между осью X и начальной точкой сектора пирога. |
| [getSweepAngle()](#getSweepAngle--) | Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Получает или задает угол разворота. 32‑битное число с плавающей запятой, определяющее величину дуги, задающей сектор пирога для рисования, в градусах, измеряемых от начальной точки, определенной значением StartAngle. |
| [getRectData()](#getRectData--) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса, содержащего сектор пирога. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusFillPie`.

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

