---
title: "EmfPlusFillEllipse"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusFillEllipse указывает заполнение внутренней части эллипса"
type: docs
weight: 33
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

Запись EmfPlusFillEllipse указывает заполнение внутренней части эллипса
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusFillEllipse`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [isCompressed()](#isCompressed--) | Получает или задает значение, указывающее, сжат ли этот экземпляр. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжат ли этот экземпляр. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. |
| [getRectData()](#getRectData--) | Получает или задает данные прямоугольника. Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Получает или задает данные прямоугольника. Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса. |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusFillEllipse`.

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


Получает или задает значение, указывающее, сжат ли этот экземпляр. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39).

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжат ли этот экземпляр. Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38). Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39).

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Получает или задает идентификатор кисти — 32‑разрядное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags. Это определение используется для заполнения внутренней части эллипса.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Получает или задает идентификатор кисти — 32‑разрядное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags. Это определение используется для заполнения внутренней части эллипса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Получает или задает данные прямоугольника. Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Получает или задает данные прямоугольника. Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

