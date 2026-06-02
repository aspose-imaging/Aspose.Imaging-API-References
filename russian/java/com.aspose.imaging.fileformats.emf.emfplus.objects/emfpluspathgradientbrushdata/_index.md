---
title: "EmfPlusPathGradientBrushData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPathGradientBrushData задает градиент по пути для графической кисти."
type: docs
weight: 59
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

Объект EmfPlusPathGradientBrushData задает градиент по пути для графической кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [getWrapMode()](#getWrapMode--) | Получает или задает 32‑битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, следует ли закрашивать область за пределами границы кисти. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает 32‑битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, следует ли закрашивать область за пределами границы кисти. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. |
| [getCenterPointF()](#getCenterPointF--) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Получает или задает массив объектов EmfPlusARGB с количеством SurroundingColorCount, которые определяют цвета для отдельных точек на границе кисти. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Получает или задает массив объектов EmfPlusARGB с количеством SurroundingColorCount, которые определяют цвета для отдельных точек на границе кисти. |
| [getBoundaryData()](#getBoundaryData--) | Получает или задает границу кисти градиента пути, которая задаётся либо путем, либо замкнутым кардинальным сплайном. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Получает или задает границу кисти градиента пути, которая задаётся либо путем, либо замкнутым кардинальным сплайном. |
| [getOptionalData()](#getOptionalData--) | Получает или задает необязательный объект EmfPlusPathGradientBrushOptionalData (раздел 2.2.2.30), который определяет дополнительные данные для кисти градиента пути. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Получает или задает необязательный объект EmfPlusPathGradientBrushOptionalData (раздел 2.2.2.30), который определяет дополнительные данные для кисти градиента пути. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Получает или задает 32-битное беззнаковое целое, которое определяет данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). Следующие флаги относятся к кисти градиента пути:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). Следующие флаги относятся к кисти градиента пути:

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое определяет, следует ли рисовать область за пределами границы кисти. При рисовании за пределами границы режим обёртки определяет, как повторяется цветовой градиент.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое определяет, следует ли рисовать область за пределами границы кисти. При рисовании за пределами границы режим обёртки определяет, как повторяется цветовой градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. Цвет кисти постепенно меняется от цвета границы к центральному цвету при переходе от границы к центру.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. Цвет кисти постепенно меняется от цвета границы к центральному цвету при переходе от границы к центру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. Цвет кисти постепенно меняется от цвета границы к центральному цвету при переходе от границы к центру.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, т.е. цвет, который отображается в центральной точке кисти. Цвет кисти постепенно меняется от цвета границы к центральному цвету при переходе от границы к центру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Получает или задает массив объектов EmfPlusARGB с количеством SurroundingColorCount, которые определяют цвета для отдельных точек на границе кисти.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Получает или задает массив объектов EmfPlusARGB с количеством SurroundingColorCount, которые определяют цвета для отдельных точек на границе кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Получает или задает границу кисти градиента пути, которая задаётся либо путем, либо замкнутым кардинальным сплайном. Если флаг BrushDataPath установлен в поле BrushDataFlags, это поле ДОЛЖНО содержать объект EmfPlusBoundaryPathData (раздел 2.2.2.6); в противном случае это поле ДОЛЖНО содержать объект EmfPlusBoundaryPointData (раздел 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Получает или задает границу кисти градиента пути, которая задаётся либо путем, либо замкнутым кардинальным сплайном. Если флаг BrushDataPath установлен в поле BrushDataFlags, это поле ДОЛЖНО содержать объект EmfPlusBoundaryPathData (раздел 2.2.2.6); в противном случае это поле ДОЛЖНО содержать объект EmfPlusBoundaryPointData (раздел 2.2.2.7).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Получает или задает необязательный объект EmfPlusPathGradientBrushOptionalData (раздел 2.2.2.30), который определяет дополнительные данные для кисти градиента пути. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Получает или задает необязательный объект EmfPlusPathGradientBrushOptionalData (раздел 2.2.2.30), который определяет дополнительные данные для кисти градиента пути. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

