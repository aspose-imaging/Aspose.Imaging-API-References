---
title: "EmfPlusBeginContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusBeginContainer открывает новый контейнер графического состояния и задает для него преобразование."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

Запись EmfPlusBeginContainer открывает новый контейнер графического состояния и задает для него преобразование.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusBeginContainer`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Получает единицу измерения страницы. |
| [getDestRect()](#getDestRect--) | Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), который вместе с SrcRect задает преобразование для контейнера. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), который вместе с SrcRect задает преобразование для контейнера. |
| [getSrcRect()](#getSrcRect--) | Получает или задает прямоугольник EmfPlusRectF, который вместе с DestRect задает преобразование для контейнера. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Получает или задает прямоугольник EmfPlusRectF, который вместе с DestRect задает преобразование для контейнера. |
| [getStackIndex()](#getStackIndex--) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. |
| [setStackIndex(int value)](#setStackIndex-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusBeginContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Получает единицу измерения страницы.

Значение: единица измерения страницы.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), который вместе с SrcRect задает преобразование для контейнера. Это преобразование приводит к SrcRect при применении к DestRect.

Значение: целевой прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), который вместе с SrcRect задает преобразование для контейнера. Это преобразование приводит к SrcRect при применении к DestRect.

Значение: целевой прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Получает или задает прямоугольник EmfPlusRectF, который вместе с DestRect задает преобразование для контейнера. Это преобразование приводит к SrcRect при применении к DestRect.

Значение: исходный прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Получает или задает прямоугольник EmfPlusRectF, который вместе с DestRect задает преобразование для контейнера. Это преобразование приводит к SrcRect при применении к DestRect.

Значение: исходный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. Индекс ДОЛЖЕН быть использован последующей записью EmfPlusEndContainer (раздел 2.3.7.3) для закрытия контейнера состояния графики.

Значение: Индекс стека.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. Индекс ДОЛЖЕН быть использован последующей записью EmfPlusEndContainer (раздел 2.3.7.3) для закрытия контейнера состояния графики.

Значение: Индекс стека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

