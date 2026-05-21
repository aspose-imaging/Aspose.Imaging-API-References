---
title: "EmfPlusDrawImagePoints"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawImagePoints определяет рисование масштабированного изображения внутри параллелограмма."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawImagePoints определяет рисование масштабированного изображения внутри параллелограмма.

Объект EmfPlusImage может указывать либо растровое изображение, либо метафайл. Цвета изображения могут быть изменены во время рендеринга. Их можно корректировать, затемнять, осветлять и удалять.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawImagePoints`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Получает или задает значение, указывающее, применяется ли [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Получает или задает значение, указывающее, применяется ли [applying an effect]. |
| [getRelative()](#getRelative--) | Получает или задает значение, указывающее, является ли этот `EmfPlusDrawImagePoints` относительным. |
| [setRelative(boolean value)](#setRelative-boolean-) | Получает или задает значение, указывающее, является ли этот `EmfPlusDrawImagePoints` относительным. |
| [getImageAttributesId()](#getImageAttributesId--) | Получает или задает 32-битное беззнаковое целое, содержащее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Получает или задает 32-битное беззнаковое целое, содержащее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| [getSrcUnit()](#getSrcUnit--) | Получает или задает 32-битное знаковое целое, определяющее единицы измерения поля SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Получает или задает 32-битное знаковое целое, определяющее единицы измерения поля SrcRect. |
| [getSrcRect()](#getSrcRect--) | Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), определяющий часть изображения для рендеринга. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), определяющий часть изображения для рендеринга. |
| [getPointData()](#getPointData--) | Получает или задает массив точек Count, определяющих три точки параллелограмма. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задает массив точек Count, определяющих три точки параллелограмма. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawImagePoints`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает или задает значение, указывающее, сжаты ли данные PointData. Этот бит указывает, содержит ли поле PointData сжатые данные. Если установлен, PointData задаёт абсолютные координаты в пространстве координат с 16‑битными целочисленными координатами. Если сброшен, PointData задаёт абсолютные координаты в пространстве координат с 32‑битными координатами с плавающей точкой. Примечание: если установлен флаг P (ниже), этот бит не определён и ДОЛЖЕН игнорироваться.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжаты ли данные PointData. Этот бит указывает, содержит ли поле PointData сжатые данные. Если установлен, PointData задаёт абсолютные координаты в пространстве координат с 16‑битными целочисленными координатами. Если сброшен, PointData задаёт абсолютные координаты в пространстве координат с 32‑битными координатами с плавающей точкой. Примечание: если установлен флаг P (ниже), этот бит не определён и ДОЛЖЕН игнорироваться.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Получает или задает значение, указывающее, применяется ли [applying an effect]. Этот бит указывает, что отрисовка изображения включает применение эффекта. Если установлен, объект класса Effect ДОЛЖЕН быть указан в более ранней записи EmfPlusSerializableObject (раздел 2.3.5.2).

Значение: `true`, если [applying an effect]; иначе `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Получает или задает значение, указывающее, применяется ли [applying an effect]. Этот бит указывает, что отрисовка изображения включает применение эффекта. Если установлен, объект класса Effect ДОЛЖЕН быть указан в более ранней записи EmfPlusSerializableObject (раздел 2.3.5.2).

Значение: `true`, если [applying an effect]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Получает или задает значение, указывающее, является ли этот `EmfPlusDrawImagePoints` относительным. Этот бит указывает, задает ли поле PointData относительные или абсолютные координаты. Если установлен, каждый элемент в PointData указывает расположение в системе координат, относительное к расположению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее расположение с координатами (0,0). Если бит сброшен, PointData задает абсолютные координаты в соответствии с флагом C. Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если относительный; иначе `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Получает или задает значение, указывающее, является ли этот `EmfPlusDrawImagePoints` относительным. Этот бит указывает, задает ли поле PointData относительные или абсолютные координаты. Если установлен, каждый элемент в PointData указывает расположение в системе координат, относительное к расположению, указанному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее расположение с координатами (0,0). Если бит сброшен, PointData задает абсолютные координаты в соответствии с флагом C. Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если относительный; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Получает или задает 32-битное беззнаковое целое, содержащее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+.

Значение: идентификатор атрибутов изображения.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Получает или задает 32-битное беззнаковое целое, содержащее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+.

Значение: идентификатор атрибутов изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Получает или задает 32‑разрядное знаковое целое, определяющее единицы поля SrcRect. Оно ДОЛЖНО быть значением UnitPixel из перечисления UnitType (раздел 2.1.1.33).

Значение: исходная единица.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Получает или задает 32‑разрядное знаковое целое, определяющее единицы поля SrcRect. Оно ДОЛЖНО быть значением UnitPixel из перечисления UnitType (раздел 2.1.1.33).

Значение: исходная единица.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), определяющий часть изображения для рендеринга.

Значение: исходный прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), определяющий часть изображения для рендеринга.

Значение: исходный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает массив из Count точек, определяющих три вершины параллелограмма. Три точки представляют левый верхний, правый верхний и левый нижний углы параллелограмма. Четвёртая вершина параллелограмма вычисляется экстраполяцией из первых трёх. Часть изображения, указанная полем SrcRect, ДОЛЖНА быть масштабирована и сдвинута при необходимости, чтобы поместиться внутри параллелограмма.

Значение: данные точек.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает массив из Count точек, определяющих три вершины параллелограмма. Три точки представляют левый верхний, правый верхний и левый нижний углы параллелограмма. Четвёртая вершина параллелограмма вычисляется экстраполяцией из первых трёх. Часть изображения, указанная полем SrcRect, ДОЛЖНА быть масштабирована и сдвинута при необходимости, чтобы поместиться внутри параллелограмма.

Значение: данные точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

