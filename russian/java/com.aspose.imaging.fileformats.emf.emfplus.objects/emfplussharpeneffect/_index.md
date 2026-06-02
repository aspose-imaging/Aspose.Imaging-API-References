---
title: "EmfPlusSharpenEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект SharpenEffect указывает увеличение разницы интенсивности между пикселями изображения."
type: docs
weight: 72
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

Объект SharpenEffect указывает увеличение разницы интенсивности между пикселями изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Получает или задает 32-битное число с плавающей запятой, которое определяет радиус резкости в пикселях, определяющий количество пикселей, участвующих в расчёте нового значения данного пикселя. |
| [setRadius(float value)](#setRadius-float-) | Получает или задает 32-битное число с плавающей запятой, которое определяет радиус резкости в пикселях, определяющий количество пикселей, участвующих в расчёте нового значения данного пикселя. |
| [getAmount()](#getAmount--) | Получает или задает 32-битное число с плавающей запятой, которое определяет разницу интенсивности между данным пикселем и окружающими пикселями. |
| [setAmount(float value)](#setAmount-float-) | Получает или задает 32-битное число с плавающей запятой, которое определяет разницу интенсивности между данным пикселем и окружающими пикселями. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Получает или задает 32-битное число с плавающей запятой, которое определяет радиус резкости в пикселях, определяющий количество пикселей, участвующих в расчёте нового значения данного пикселя. По мере увеличения этого значения количество пикселей, участвующих в расчёте, увеличивается, и получаемый битмап SHOULD стать резче.

Value: Радиус.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Получает или задает 32-битное число с плавающей запятой, которое определяет радиус резкости в пикселях, определяющий количество пикселей, участвующих в расчёте нового значения данного пикселя. По мере увеличения этого значения количество пикселей, участвующих в расчёте, увеличивается, и получаемый битмап SHOULD стать резче.

Value: Радиус.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Получает или задает 32-битное число с плавающей запятой, которое определяет разницу интенсивности между данным пикселем и окружающими пикселями. 0 указывает, что резкость НЕ ДОЛЖНА выполняться. 0 < value \\u2264 100 По мере увеличения этого значения разница интенсивности между пикселями SHOULD увеличиваться.

Value: Величина.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Получает или задает 32-битное число с плавающей запятой, которое определяет разницу интенсивности между данным пикселем и окружающими пикселями. 0 указывает, что резкость НЕ ДОЛЖНА выполняться. 0 < value \\u2264 100 По мере увеличения этого значения разница интенсивности между пикселями SHOULD увеличиваться.

Value: Величина.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

