---
title: "EmfPlusFillRects"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusFillRects указывает заполнение внутренних частей серии прямоугольников."
type: docs
weight: 37
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

Запись EmfPlusFillRects указывает заполнение внутренних частей серии прямоугольников.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusFillRects`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [getCompressed()](#getCompressed--) | Получает или задаёт значение, указывающее, сжат ли данный `EmfPlusFillRects`. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задаёт значение, указывающее, сжат ли данный `EmfPlusFillRects`. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое, которое определяет кисть, содержимое которой определяется битом S в поле Flags. |
| [getRectData()](#getRectData--) | Получает или задаёт данные прямоугольника. Массив из объектов EmfPlusRect или EmfPlusRectF длиной Count, определяющий данные прямоугольника. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Получает или задаёт данные прямоугольника. Массив из объектов EmfPlusRect или EmfPlusRectF длиной Count, определяющий данные прямоугольника. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusFillRects`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает или задаёт значение, указывающее, сжат ли данный `EmfPlusFillRects`. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39) объект.

Значение: `true`, если сжато; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задаёт значение, указывающее, сжат ли данный `EmfPlusFillRects`. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39) объект.

Значение: `true`, если сжато; иначе `false`.

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Получает или задаёт данные прямоугольника. Массив из объектов EmfPlusRect или EmfPlusRectF длиной Count, определяющий данные прямоугольника.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Получает или задаёт данные прямоугольника. Массив из объектов EmfPlusRect или EmfPlusRectF длиной Count, определяющий данные прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

