---
title: "EmfPlusDrawImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawImage определяет рисование масштабированного изображения."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawImage определяет рисование масштабированного изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawImage`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getImageAttributesId()](#getImageAttributesId--) | Получает или задает идентификатор атрибутов изображения. 32-битное беззнаковое целое, определяющее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Получает или задает идентификатор атрибутов изображения. 32-битное беззнаковое целое, определяющее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| [getRectData()](#getRectData--) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник изображения. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник изображения. |
| [getSrcRect()](#getSrcRect--) | Получает или задает исходный прямоугольник. Объект EmfPlusRectF, определяющий часть изображения для отрисовки. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Получает или задает исходный прямоугольник. Объект EmfPlusRectF, определяющий часть изображения для отрисовки. |
| [getSrcUnit()](#getSrcUnit--) | Получает или задает единицу исходного прямоугольника. 32-битное знаковое целое, определяющее единицы поля SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Получает или задает единицу исходного прямоугольника. 32-битное знаковое целое, определяющее единицы поля SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawImage`.

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


Получает или задает идентификатор объекта. Индекс объекта EmfPlusImage (раздел 2.2.1.4) в таблице объектов EMF+, который указывает изображение для рендеринга. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusImage (раздел 2.2.1.4) в таблице объектов EMF+, который указывает изображение для рендеринга. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Получает или задает идентификатор атрибутов изображения. 32-битное беззнаковое целое, определяющее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Получает или задает идентификатор атрибутов изображения. 32-битное беззнаковое целое, определяющее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник изображения. Часть изображения, указанная в поле SrcRect, масштабируется, чтобы вписаться в этот прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Получает или задает данные прямоугольника. Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник изображения. Часть изображения, указанная в поле SrcRect, масштабируется, чтобы вписаться в этот прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Получает или задает исходный прямоугольник. Объект EmfPlusRectF, определяющий часть изображения для отрисовки. Часть изображения, указанная этим прямоугольником, масштабируется, чтобы вписаться в целевой прямоугольник, указанный в поле RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Получает или задает исходный прямоугольник. Объект EmfPlusRectF, определяющий часть изображения для отрисовки. Часть изображения, указанная этим прямоугольником, масштабируется, чтобы вписаться в целевой прямоугольник, указанный в поле RectData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Получает или задает единицу исходного прямоугольника. 32-битное знаковое целое, определяющее единицы поля SrcRect. Оно ДОЛЖНО быть членом UnitTypePixel перечисления UnitType (раздел 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Получает или задает единицу исходного прямоугольника. 32-битное знаковое целое, определяющее единицы поля SrcRect. Оно ДОЛЖНО быть членом UnitTypePixel перечисления UnitType (раздел 2.1.1.33).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

