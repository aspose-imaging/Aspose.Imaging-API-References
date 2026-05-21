---
title: "CmxEllipseSpec"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет геометрическую информацию, указанную для эллипса."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Представляет геометрическую информацию, указанную для эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getAngle1()](#getAngle1--) | Получает первый угол, используемый для определения сектора пирога. |
| [setAngle1(float value)](#setAngle1-float-) | Устанавливает первый угол, используемый для определения сектора пирога. |
| [getAngle2()](#getAngle2--) | Получает второй угол, используемый для определения сектора пирога. |
| [setAngle2(float value)](#setAngle2-float-) | Устанавливает второй угол, используемый для определения сектора пирога. |
| [getRotation()](#getRotation--) | Получает угол вращения эллипса. |
| [setRotation(float value)](#setRotation-float-) | Устанавливает угол вращения эллипса. |
| [getPie()](#getPie--) | Получает значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) сектором. |
| [setPie(boolean value)](#setPie-boolean-) | Устанавливает значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) сектором. |
| [getCenterX()](#getCenterX--) | Получает координату X центра прямоугольника. |
| [setCenterX(float value)](#setCenterX-float-) | Устанавливает координату X центра прямоугольника. |
| [getCenterY()](#getCenterY--) | Получает координату Y центра прямоугольника. |
| [setCenterY(float value)](#setCenterY-float-) | Устанавливает координату Y центра прямоугольника. |
| [getDiameterX()](#getDiameterX--) | Получает диаметр по оси X прямоугольника. |
| [setDiameterX(float value)](#setDiameterX-float-) | Устанавливает диаметр по оси X прямоугольника. |
| [getDiameterY()](#getDiameterY--) | Получает диаметр по оси Y прямоугольника. |
| [setDiameterY(float value)](#setDiameterY-float-) | Устанавливает диаметр по оси Y прямоугольника. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Устанавливает ограничивающий прямоугольник. |
| [toString()](#toString--) | Возвращает строку, представляющую этот экземпляр. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Получает первый угол, используемый для определения сектора пирога. Не влияет, если `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) равно `false`. Измеряется в радианах.

**Returns:**
float - первый угол, используемый для определения сектора пирога.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Устанавливает первый угол, используемый для определения сектора пирога. Не влияет, если `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) равно `false`. Измеряется в радианах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | первый угол, используемый для определения сектора пирога. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Получает второй угол, используемый для определения сектора пирога. Не влияет, если `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) равно `false`. Измеряется в радианах.

**Returns:**
float - второй угол, используемый для определения сектора пирога.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Устанавливает второй угол, используемый для определения сектора пирога. Не влияет, если `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) равно `false`. Измеряется в радианах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | второй угол, используемый для определения сектора пирога. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Получает угол вращения эллипса. Измеряется в радианах.

**Returns:**
float - угол вращения эллипса.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Устанавливает угол вращения эллипса. Измеряется в радианах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | угол вращения эллипса. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Получает значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) сектором.

**Returns:**
boolean - значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) pie.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Устанавливает значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) сектором.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, является ли этот [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) pie. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Получает координату X центра прямоугольника. Измеряется в общих единицах расстояния документа.

**Returns:**
float - координата X центра прямоугольника.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Устанавливает координату X центра прямоугольника. Измеряется в общих единицах расстояния документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | координата X центра прямоугольника. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Получает координату Y центра прямоугольника. Измеряется в общих единицах расстояния документа.

**Returns:**
float — координата Y центра прямоугольника.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Устанавливает координату Y центра прямоугольника. Измеряется в общих единицах расстояния документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | координата Y центра прямоугольника. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Получает диаметр по оси X прямоугольника. Измеряется в общих единицах длины документа.

**Returns:**
float - диаметр по оси X прямоугольника.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Устанавливает диаметр по оси X прямоугольника. Измеряется в общих единицах длины документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | диаметр по оси X прямоугольника. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Получает диаметр по оси Y прямоугольника. Измеряется в общих единицах длины документа.

**Returns:**
float - диаметр по оси Y прямоугольника.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Устанавливает диаметр по оси Y прямоугольника. Измеряется в общих единицах длины документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | диаметр по оси Y прямоугольника. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Получает ограничивающий прямоугольник.

Значение: ограничивающий прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Устанавливает ограничивающий прямоугольник.

Значение: ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | ограничивающий прямоугольник. |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую этот экземпляр.

**Returns:**
java.lang.String - Строка, представляющая этот экземпляр.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
