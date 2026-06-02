---
title: "Shape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Форма."
type: docs
weight: 102
url: /ru/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Фигура. Непрерывный набор точек, соединённых по определённому правилу.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Shape()](#Shape--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCenter()](#getCenter--) | Получает центр фигуры. |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, есть ли у фигуры сегменты. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Получает центр фигуры.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Получает сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Сегменты фигуры.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Получает значение, указывающее, есть ли у фигуры сегменты.

**Returns:**
boolean - `True`, если у фигуры есть сегменты; иначе `false`.
