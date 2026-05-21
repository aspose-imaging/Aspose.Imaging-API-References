---
title: "EmfPlusDrawEllipse"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawEllipse определяет рисование эллипса."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawEllipse определяет рисование эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawEllipse`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [getRectData()](#getRectData--) | Получает или задает данные прямоугольника — объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Получает или задает данные прямоугольника — объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawEllipse`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования эллипса. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для рисования эллипса. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

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

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Получает или задает данные прямоугольника — объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Получает или задает данные прямоугольника — объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

