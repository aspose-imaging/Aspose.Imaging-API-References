---
title: "EmfPlusBlurEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект BlurEffect указывает уменьшение разницы интенсивности между пикселями изображения."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

Объект BlurEffect указывает уменьшение разницы интенсивности между пикселями изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Получает или задает 32-битное число с плавающей точкой, которое определяет радиус размытия в пикселях, определяющий количество пикселей, участвующих в вычислении нового значения данного пикселя. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Получает или задает 32-битное число с плавающей точкой, которое определяет радиус размытия в пикселях, определяющий количество пикселей, участвующих в вычислении нового значения данного пикселя. |
| [getExpandEdge()](#getExpandEdge--) | Получает или задает 32-битное логическое значение, которое определяет, расширяется ли bitmap на величину, равную значению BlurRadius, для создания мягких краев. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Получает или задает 32-битное логическое значение, которое определяет, расширяется ли bitmap на величину, равную значению BlurRadius, для создания мягких краев. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Получает или задает 32-битное число с плавающей точкой, которое определяет радиус размытия в пикселях, определяющий количество пикселей, участвующих в вычислении нового значения данного пикселя. Это значение ДОЛЖНО находиться в диапазоне от 0.0 до 255.0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Получает или задает 32-битное число с плавающей точкой, которое определяет радиус размытия в пикселях, определяющий количество пикселей, участвующих в вычислении нового значения данного пикселя. Это значение ДОЛЖНО находиться в диапазоне от 0.0 до 255.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Получает или задает 32-битное логическое значение, которое определяет, расширяется ли bitmap на величину, равную значению BlurRadius, для создания мягких краев. Это значение ДОЛЖНО быть одним из следующих: FALSE 0x00000000 Размер bitmap НЕ ДОЛЖЕН изменяться, и его мягкие края ДОЛЖНЫ быть обрезаны до размера BlurRadius. TRUE 0x00000001 Размер bitmap ДОЛЖЕН расширяться на величину, равную BlurRadius, для создания мягких краев.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Получает или задает 32-битное логическое значение, которое определяет, расширяется ли bitmap на величину, равную значению BlurRadius, для создания мягких краев. Это значение ДОЛЖНО быть одним из следующих: FALSE 0x00000000 Размер bitmap НЕ ДОЛЖЕН изменяться, и его мягкие края ДОЛЖНЫ быть обрезаны до размера BlurRadius. TRUE 0x00000001 Размер bitmap ДОЛЖЕН расширяться на величину, равную BlurRadius, для создания мягких краев.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

