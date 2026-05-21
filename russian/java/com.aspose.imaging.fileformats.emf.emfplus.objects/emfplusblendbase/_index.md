---
title: "EmfPlusBlendBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый объект для объектов blend."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Базовый объект для объектов blend.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Получает или задает позиции смешивания массивом из PositionCount 32-битных чисел с плавающей запятой, которые определяют пропорции расстояния вдоль линии градиента. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Получает или задает позиции смешивания массивом из PositionCount 32-битных чисел с плавающей запятой, которые определяют пропорции расстояния вдоль линии градиента. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Получает или задает позиции смешивания массивом из PositionCount 32-битных чисел с плавающей запятой, которые определяют пропорции расстояния вдоль линии градиента. Каждый элемент MUST быть числом от 0.0 до 1.0 включительно. Для кисти линейного градиента 0.0 представляет начальную точку, а 1.0 — конечную точку. Для кисти градиента пути 0.0 представляет середину, а 1.0 — конечную точку.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Получает или задает позиции смешивания массивом из PositionCount 32-битных чисел с плавающей запятой, которые определяют пропорции расстояния вдоль линии градиента. Каждый элемент MUST быть числом от 0.0 до 1.0 включительно. Для кисти линейного градиента 0.0 представляет начальную точку, а 1.0 — конечную точку. Для кисти градиента пути 0.0 представляет середину, а 1.0 — конечную точку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

