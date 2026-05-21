---
title: "EmfPlusPenOptionalData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPenOptionalData задает дополнительные данные для графической ручки."
type: docs
weight: 65
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

Объект EmfPlusPenOptionalData задает дополнительные данные для графической ручки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для пера. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Получает или задает необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для пера. |
| [getStartCap()](#getStartCap--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму начала линии в поле CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму начала линии в поле CustomStartCapData. |
| [getEndCap()](#getEndCap--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму конца линии в поле CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму конца линии в поле CustomEndCapData. |
| [getJoin()](#getJoin--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает способ соединения двух линий, нарисованных одним и тем же пером и чьи концы соприкасаются. |
| [setJoin(int value)](#setJoin-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает способ соединения двух линий, нарисованных одним и тем же пером и чьи концы соприкасаются. |
| [getMiterLimit()](#getMiterLimit--) | Получает или задает необязательное 32‑битное значение с плавающей точкой, которое указывает предел среза (miter limit), являющийся максимальным допустимым отношением длины среза к ширине линии. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Получает или задает необязательное 32‑битное значение с плавающей точкой, которое указывает предел среза (miter limit), являющийся максимальным допустимым отношением длины среза к ширине линии. |
| [getLineStyle()](#getLineStyle--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает стиль, используемый для линий, нарисованных этим объектом пера. |
| [setLineStyle(int value)](#setLineStyle-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает стиль, используемый для линий, нарисованных этим объектом пера. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму обоих концов каждой черты в пунктирной линии. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму обоих концов каждой черты в пунктирной линии. |
| [getDashOffset()](#getDashOffset--) | Получает или задает необязательное 32‑битное значение с плавающей точкой, которое указывает расстояние от начала линии до начала первого пробела в шаблоне пунктирной линии. |
| [setDashOffset(float value)](#setDashOffset-float-) | Получает или задает необязательное 32‑битное значение с плавающей точкой, которое указывает расстояние от начала линии до начала первого пробела в шаблоне пунктирной линии. |
| [getDashedLineData()](#getDashedLineData--) | Получает или задает необязательный объект EmfPlusDashedLineData (section 2.2.2.16), который определяет длины черт и пробелов в пользовательской пунктирной линии. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Получает или задает необязательный объект EmfPlusDashedLineData (section 2.2.2.16), который определяет длины черт и пробелов в пользовательской пунктирной линии. |
| [getPenAlignment()](#getPenAlignment--) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает распределение ширины пера относительно координат рисуемой линии. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Получает или задает необязательное 32‑битное знаковое целое, которое указывает распределение ширины пера относительно координат рисуемой линии. |
| [getCompoundLineData()](#getCompoundLineData--) | Получает или задает необязательный объект EmfPlusCompoundLineData (section 2.2.2.9), который определяет массив значений с плавающей точкой, задающих составную линию пера, состоящую из параллельных линий и пробелов. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Получает или задает необязательный объект EmfPlusCompoundLineData (section 2.2.2.9), который определяет массив значений с плавающей точкой, задающих составную линию пера, состоящую из параллельных линий и пробелов. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Получает или задает необязательный объект EmfPlusCustomStartCapData (section 2.2.2.15), который определяет форму пользовательской начальной насадки, используемую в начале линии, нарисованной этим пером. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Получает или задает необязательный объект EmfPlusCustomStartCapData (section 2.2.2.15), который определяет форму пользовательской начальной насадки, используемую в начале линии, нарисованной этим пером. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Получает или задает необязательный объект EmfPlusCustomEndCapData (section 2.2.2.11), который определяет форму пользовательской конечной насадки, используемую в конце линии, нарисованной этим пером. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Получает или задает необязательный объект EmfPlusCustomEndCapData (section 2.2.2.11), который определяет форму пользовательской конечной насадки, используемую в конце линии, нарисованной этим пером. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Получает или задает необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataTransform установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Получает или задает необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataTransform установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму начала линии в поле CustomStartCapData. Это поле ДОЛЖНО присутствовать, если флаг PenDataStartCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineCapType (section 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму начала линии в поле CustomStartCapData. Это поле ДОЛЖНО присутствовать, если флаг PenDataStartCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineCapType (section 2.1.1.18).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму конца линии в поле CustomEndCapData. Это поле ДОЛЖНО присутствовать, если флаг PenDataEndCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineCapType.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое указывает форму конца линии в поле CustomEndCapData. Это поле ДОЛЖНО присутствовать, если флаг PenDataEndCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineCapType.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет, как соединять две линии, нарисованные одним и тем же пером и чьи концы встречаются. Это поле ДОЛЖНО присутствовать, если флаг PenDataJoin установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineJoinType (раздел 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет, как соединять две линии, нарисованные одним и тем же пером и чьи концы встречаются. Это поле ДОЛЖНО присутствовать, если флаг PenDataJoin установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineJoinType (раздел 2.1.1.19).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Получает или задает необязательное 32‑битное число с плавающей точкой, которое определяет предел среза (miter limit), то есть максимальное допустимое отношение длины среза к ширине линии. Длина среза — это расстояние от пересечения стенок линии внутри соединения до пересечения стенок линии снаружи соединения. Длина среза может быть большой, когда угол между двумя линиями мал. Это поле ДОЛЖНО присутствовать, если флаг PenDataMiterLimit установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Получает или задает необязательное 32‑битное число с плавающей точкой, которое определяет предел среза (miter limit), то есть максимальное допустимое отношение длины среза к ширине линии. Длина среза — это расстояние от пересечения стенок линии внутри соединения до пересечения стенок линии снаружи соединения. Длина среза может быть большой, когда угол между двумя линиями мал. Это поле ДОЛЖНО присутствовать, если флаг PenDataMiterLimit установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет стиль, используемый для линий, нарисованных этим объектом пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataLineStyle установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineStyle (раздел 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет стиль, используемый для линий, нарисованных этим объектом пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataLineStyle установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении LineStyle (раздел 2.1.1.20).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет форму обоих концов каждой черты в пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении DashedLineCapType (раздел 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет форму обоих концов каждой черты в пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineCap установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении DashedLineCapType (раздел 2.1.1.10).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Получает или задает необязательное 32‑битное число с плавающей точкой, которое определяет расстояние от начала линии до начала первого пробела в шаблоне пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineOffset установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Получает или задает необязательное 32‑битное число с плавающей точкой, которое определяет расстояние от начала линии до начала первого пробела в шаблоне пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineOffset установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Получает или задает необязательный объект EmfPlusDashedLineData (раздел 2.2.2.16), который определяет длины черт и пробелов в пользовательской пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLine установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Получает или задает необязательный объект EmfPlusDashedLineData (раздел 2.2.2.16), который определяет длины черт и пробелов в пользовательской пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLine установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет распределение ширины пера относительно координат рисуемой линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataNonCenter установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении PenAlignment (раздел 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Получает или задает необязательное 32‑битное знаковое целое, которое определяет распределение ширины пера относительно координат рисуемой линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataNonCenter установлен в поле PenDataFlags объекта EmfPlusPenData, и значение ДОЛЖНО быть определено в перечислении PenAlignment (раздел 2.1.1.24).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Получает или задает необязательный объект EmfPlusCompoundLineData (раздел 2.2.2.9), который определяет массив чисел с плавающей точкой, задающих составную линию пера, состоящую из параллельных линий и пробелов. Это поле ДОЛЖНО присутствовать, если флаг PenDataCompoundLine установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Получает или задает необязательный объект EmfPlusCompoundLineData (раздел 2.2.2.9), который определяет массив чисел с плавающей точкой, задающих составную линию пера, состоящую из параллельных линий и пробелов. Это поле ДОЛЖНО присутствовать, если флаг PenDataCompoundLine установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Получает или задает необязательный объект EmfPlusCustomStartCapData (раздел 2.2.2.15), который определяет форму пользовательского начального колпачка, то есть форму, используемую в начале линии, нарисованной этим пером. Это может быть любая из различных форм, например квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomStartCap установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Получает или задает необязательный объект EmfPlusCustomStartCapData (раздел 2.2.2.15), который определяет форму пользовательского начального колпачка, то есть форму, используемую в начале линии, нарисованной этим пером. Это может быть любая из различных форм, например квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomStartCap установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Получает или задает необязательный объект EmfPlusCustomEndCapData (раздел 2.2.2.11), который определяет форму пользовательского конечного колпачка, то есть форму, используемую в конце линии, нарисованной этим пером. Это может быть любая из различных форм, например квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomEndCap установлен в поле PenDataFlags объекта EmfPlusPenData.

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Получает или задает необязательный объект EmfPlusCustomEndCapData (раздел 2.2.2.11), который определяет форму пользовательского конечного колпачка, то есть форму, используемую в конце линии, нарисованной этим пером. Это может быть любая из различных форм, например квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomEndCap установлен в поле PenDataFlags объекта EmfPlusPenData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

