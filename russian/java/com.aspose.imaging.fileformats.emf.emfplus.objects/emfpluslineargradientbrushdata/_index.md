---
title: "EmfPlusLinearGradientBrushData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusLinearGradientBrushData задает линейный градиент для графической кисти."
type: docs
weight: 53
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

Объект EmfPlusLinearGradientBrushData задает линейный градиент для графической кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Получает или задает флаги данных кисти. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Получает или задает флаги данных кисти. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Получает или задает конечный цвет. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Получает или задает конечный цвет. |
| [getOptionalData()](#getOptionalData--) | Получает или задает необязательные данные. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Получает или задает необязательные данные. |
| [getRectF()](#getRectF--) | Получает или задает rect f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Получает или задает rect f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Получает или задает начальный цвет. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Получает или задает начальный цвет. |
| [getWrapMode()](#getWrapMode--) | Получает или задает режим обтекания. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает режим обтекания. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Получает или задает флаги данных кисти.

Значение: BrushDataFlags (4 байта): 32‑битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО быть составлено из `EmfPlusBrushDataFlags` (раздел 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Получает или задает флаги данных кисти.

Значение: BrushDataFlags (4 байта): 32‑битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО быть составлено из `EmfPlusBrushDataFlags` (раздел 2.1.2.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Получает или задает конечный цвет.

Значение: объект EmfPlusARGB, который определяет цвет в конечной граничной точке линейной градиентной кисти.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Получает или задает конечный цвет.

Значение: объект EmfPlusARGB, который определяет цвет в конечной граничной точке линейной градиентной кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Получает или задает необязательные данные.

Значение: необязательный объект `EmfPlusLinearGradientBrushOptionalData` (раздел 2.2.2.25), который задает дополнительные данные для линейной градиентной кисти. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Получает или задает необязательные данные.

Значение: необязательный объект `EmfPlusLinearGradientBrushOptionalData` (раздел 2.2.2.25), который задает дополнительные данные для линейной градиентной кисти. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Получает или задает rect f.

Значение: объект EmfPlusRectF (раздел 2.2.2.39), который указывает начальные и конечные точки линии градиента. Верхний левый угол прямоугольника — начальная точка. Нижний правый угол — конечная точка.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Получает или задает rect f.

Значение: объект EmfPlusRectF (раздел 2.2.2.39), который указывает начальные и конечные точки линии градиента. Верхний левый угол прямоугольника — начальная точка. Нижний правый угол — конечная точка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Получает или задает начальный цвет.

Значение: объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет в начальной граничной точке линейной градиентной кисти.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Получает или задает начальный цвет.

Значение: объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет в начальной граничной точке линейной градиентной кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает режим обтекания.

Значение: 32‑битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, следует ли закрашивать область за пределами границы кисти. При закраске за пределами границы режим обтекания определяет, как повторяется цветовой градиент.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает режим обтекания.

Значение: 32‑битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, следует ли закрашивать область за пределами границы кисти. При закраске за пределами границы режим обтекания определяет, как повторяется цветовой градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

