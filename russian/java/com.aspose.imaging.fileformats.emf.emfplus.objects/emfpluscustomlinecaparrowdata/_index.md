---
title: "EmfPlusCustomLineCapArrowData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusCustomLineCapArrowData указывает регулируемые данные стрелки для пользовательского окончания линии."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapArrowData extends EmfPlusCustomBaseLineCap
```

Объект EmfPlusCustomLineCapArrowData указывает регулируемые данные стрелки для пользовательского окончания линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получает или задает 32-битное значение с плавающей запятой, определяющее ширину наконечника стрелки |
| [setWidth(float value)](#setWidth-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее ширину наконечника стрелки |
| [getHeight()](#getHeight--) | Получает или задает 32-битное значение с плавающей запятой, определяющее высоту наконечника стрелки. |
| [setHeight(float value)](#setHeight-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее высоту наконечника стрелки. |
| [getMiddleInset()](#getMiddleInset--) | Получает или задает 32-битное значение с плавающей запятой, определяющее количество пикселей между контуром наконечника стрелки и его заполнением. |
| [setMiddleInset(float value)](#setMiddleInset-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее количество пикселей между контуром наконечника стрелки и его заполнением. |
| [getFillState()](#getFillState--) | Получает или задает 32-битное логическое значение, определяющее, заполнен ли наконечник стрелки. |
| [setFillState(boolean value)](#setFillState-boolean-) | Получает или задает 32-битное логическое значение, определяющее, заполнен ли наконечник стрелки. |
| [getLineStartCap()](#getLineStartCap--) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в начале рисуемой линии |
| [setLineStartCap(int value)](#setLineStartCap-int-) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в начале рисуемой линии |
| [getLineEndCap()](#getLineEndCap--) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в конце рисуемой линии |
| [setLineEndCap(int value)](#setLineEndCap-int-) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в конце рисуемой линии |
| [getLineJoin()](#getLineJoin--) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineJoin, указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие общие концы. |
| [setLineJoin(int value)](#setLineJoin-int-) | Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineJoin, указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие общие концы. |
| [getLineMiterLimit()](#getLineMiterLimit--) | Получает или задает 32-битное значение с плавающей запятой, определяющее предел толщины соединения на скошенном угле путем установки максимального допустимого отношения длины среза к ширине линии |
| [setLineMiterLimit(float value)](#setLineMiterLimit-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее предел толщины соединения на скошенном угле путем установки максимального допустимого отношения длины среза к ширине линии |
| [getWidthScale()](#getWidthScale--) | Получает или задает 32-битное значение с плавающей запятой, определяющее степень масштабирования объекта EmfPlusCustomLineCap относительно ширины графической ручки, используемой для рисования линий |
| [setWidthScale(float value)](#setWidthScale-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее степень масштабирования объекта EmfPlusCustomLineCap относительно ширины графической ручки, используемой для рисования линий |
| [getFillHotSpot()](#getFillHotSpot--) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [getLineHotSpot()](#getLineHotSpot--) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [setLineHotSpot(PointF value)](#setLineHotSpot-com.aspose.imaging.PointF-) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
### EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData--}
```
public EmfPlusCustomLineCapArrowData()
```


### getWidth() {#getWidth--}
```
public float getWidth()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее ширину наконечника стрелки

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее ширину наконечника стрелки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее высоту наконечника стрелки.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее высоту наконечника стрелки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getMiddleInset() {#getMiddleInset--}
```
public float getMiddleInset()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее количество пикселей между контуром наконечника стрелки и его заполнением.

**Returns:**
float
### setMiddleInset(float value) {#setMiddleInset-float-}
```
public void setMiddleInset(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее количество пикселей между контуром наконечника стрелки и его заполнением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFillState() {#getFillState--}
```
public boolean getFillState()
```


Получает или задает 32-битное логическое значение, определяющее, заполнен ли наконечник стрелки. Если наконечник стрелки не заполнен, рисуется только контур.

**Returns:**
boolean
### setFillState(boolean value) {#setFillState-boolean-}
```
public void setFillState(boolean value)
```


Получает или задает 32-битное логическое значение, определяющее, заполнен ли наконечник стрелки. Если наконечник стрелки не заполнен, рисуется только контур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLineStartCap() {#getLineStartCap--}
```
public int getLineStartCap()
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в начале рисуемой линии

**Returns:**
int
### setLineStartCap(int value) {#setLineStartCap-int-}
```
public void setLineStartCap(int value)
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в начале рисуемой линии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLineEndCap() {#getLineEndCap--}
```
public int getLineEndCap()
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в конце рисуемой линии

**Returns:**
int
### setLineEndCap(int value) {#setLineEndCap-int-}
```
public void setLineEndCap(int value)
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineCap, указывающее, какой тип окончания линии использовать в конце рисуемой линии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineJoin, указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие общие концы. На пересечении двух концов линий соединение делает соединение более непрерывным.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Получает или задает 32-битное беззнаковое целое значение, определяющее значение в перечислении LineJoin, указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие общие концы. На пересечении двух концов линий соединение делает соединение более непрерывным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLineMiterLimit() {#getLineMiterLimit--}
```
public float getLineMiterLimit()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее предел толщины соединения на скошенном угле путем установки максимального допустимого отношения длины среза к ширине линии

**Returns:**
float
### setLineMiterLimit(float value) {#setLineMiterLimit-float-}
```
public void setLineMiterLimit(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее предел толщины соединения на скошенном угле путем установки максимального допустимого отношения длины среза к ширине линии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее степень масштабирования объекта EmfPlusCustomLineCap относительно ширины графической ручки, используемой для рисования линий

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее степень масштабирования объекта EmfPlusCustomLineCap относительно ширины графической ручки, используемой для рисования линий

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getLineHotSpot() {#getLineHotSpot--}
```
public PointF getLineHotSpot()
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setLineHotSpot(PointF value) {#setLineHotSpot-com.aspose.imaging.PointF-}
```
public void setLineHotSpot(PointF value)
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

