---
title: "EmfPlusCustomLineCapData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusCustomLineCapData указывает данные по умолчанию для пользовательского окончания линии."
type: docs
weight: 36
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

Объект EmfPlusCustomLineCapData указывает данные по умолчанию для пользовательского окончания линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [getBaseCap()](#getBaseCap--) | Получает или задает 32-битное беззнаковое целое, которое указывает значение из перечисления LineCap (раздел 2.1.1.18), на основе которого построена пользовательская конечная линия. |
| [setBaseCap(int value)](#setBaseCap-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает значение из перечисления LineCap (раздел 2.1.1.18), на основе которого построена пользовательская конечная линия. |
| [getBaseInset()](#getBaseInset--) | Получает или задает 32-битное значение с плавающей точкой, которое указывает расстояние между началом конечной линии и её концом. |
| [setBaseInset(float value)](#setBaseInset-float-) | Получает или задает 32-битное значение с плавающей точкой, которое указывает расстояние между началом конечной линии и её концом. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее конечную линию, используемую в начале рисуемой линии. |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее конечную линию, используемую в начале рисуемой линии. |
| [getStrokeEndCap()](#getStrokeEndCap--) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее, какая конечная линия должна использоваться в конце рисуемой линии. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее, какая конечная линия должна использоваться в конце рисуемой линии. |
| [getStrokeJoin()](#getStrokeJoin--) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineJoin (раздел 2.1.1.19), определяющее способ соединения двух линий, нарисованных одной и той же ручкой и имеющих соприкасающиеся концы. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineJoin (раздел 2.1.1.19), определяющее способ соединения двух линий, нарисованных одной и той же ручкой и имеющих соприкасающиеся концы. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Получает или задает 32-битное значение с плавающей точкой, которое содержит предел толщины соединения на срезанном угле, устанавливая максимальное допустимое соотношение длины среза к ширине линии. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Получает или задает 32-битное значение с плавающей точкой, которое содержит предел толщины соединения на срезанном угле, устанавливая максимальное допустимое соотношение длины среза к ширине линии. |
| [getWidthScale()](#getWidthScale--) | Получает или задает 32-битное значение с плавающей точкой, которое определяет величину масштабирования пользовательской заглавной линии относительно ширины объекта EmfPlusPen (раздел 2.2.1.7), используемого для рисования линий. |
| [setWidthScale(float value)](#setWidthScale-float-) | Получает или задает 32-битное значение с плавающей точкой, которое определяет величину масштабирования пользовательской заглавной линии относительно ширины объекта EmfPlusPen (раздел 2.2.1.7), используемого для рисования линий. |
| [getFillHotSpot()](#getFillHotSpot--) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. |
| [getOptionalData()](#getOptionalData--) | Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (раздел 2.2.2.14), который определяет дополнительные данные для пользовательской графической заглавной линии. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (раздел 2.2.2.14), который определяет дополнительные данные для пользовательской графической заглавной линии. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData.

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение из перечисления LineCap (раздел 2.1.1.18), на основе которого построена пользовательская конечная линия.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение из перечисления LineCap (раздел 2.1.1.18), на основе которого построена пользовательская конечная линия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Получает или задает 32-битное значение с плавающей точкой, которое указывает расстояние между началом конечной линии и её концом.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое указывает расстояние между началом конечной линии и её концом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее конечную линию, используемую в начале рисуемой линии.

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее конечную линию, используемую в начале рисуемой линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее, какая конечная линия должна использоваться в конце рисуемой линии.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает значение в перечислении LineCap, обозначающее, какая конечная линия должна использоваться в конце рисуемой линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Получает или задает 32-битное беззнаковое целое, которое определяет значение в перечислении LineJoin (раздел 2.1.1.19), указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие совпадающие концы. На пересечении концов двух линий соединение делает связь более непрерывной.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет значение в перечислении LineJoin (раздел 2.1.1.19), указывающее, как соединять две линии, нарисованные одной и той же ручкой и имеющие совпадающие концы. На пересечении концов двух линий соединение делает связь более непрерывной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Получает или задает 32-битное значение с плавающей точкой, которое содержит предел толщины соединения на срезанном угле, устанавливая максимальное допустимое соотношение длины среза к ширине линии.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое содержит предел толщины соединения на срезанном угле, устанавливая максимальное допустимое соотношение длины среза к ширине линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет величину масштабирования пользовательской заглавной линии относительно ширины объекта EmfPlusPen (раздел 2.2.1.7), используемого для рисования линий.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет величину масштабирования пользовательской заглавной линии относительно ширины объекта EmfPlusPen (раздел 2.2.1.7), используемого для рисования линий.

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

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в \{0.0, 0.0\}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (раздел 2.2.2.14), который определяет дополнительные данные для пользовательской графической заглавной линии. Конкретное содержимое этого поля определяется значением поля CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (раздел 2.2.2.14), который определяет дополнительные данные для пользовательской графической заглавной линии. Конкретное содержимое этого поля определяется значением поля CustomLineCapDataFlags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

