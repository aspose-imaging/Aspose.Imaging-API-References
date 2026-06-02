---
title: "EmfPlusBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusBrush указывает графическую кисть для заполнения областей."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

Объект EmfPlusBrush указывает графическую кисть для заполнения областей.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrushData()](#getBrushData--) | Получает или задает данные кисти переменной длины, которые определяют объект кисти, указанный в поле Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Получает или задает данные кисти переменной длины, которые определяют объект кисти, указанный в поле Type. |
| [getType()](#getType--) | Получает или задает тип. |
| [setType(int value)](#setType-int-) | Получает или задает тип. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Получает или задает данные кисти переменной длины, которые определяют объект кисти, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа кисти. EmfPlusHatchBrushData (section 2.2.2.20) (done) объект EmfPlusLinearGradientBrushData (section 2.2.2.24) (done) объект EmfPlusPathGradientBrushData (section 2.2.2.29) (done) объект EmfPlusSolidBrushData (section 2.2.2.43) (done) объект EmfPlusTextureBrushData (section 2.2.2.45) (done)

Значение: Данные кисти.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Получает или задает данные кисти переменной длины, которые определяют объект кисти, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа кисти. EmfPlusHatchBrushData (section 2.2.2.20) (done) объект EmfPlusLinearGradientBrushData (section 2.2.2.24) (done) объект EmfPlusPathGradientBrushData (section 2.2.2.29) (done) объект EmfPlusSolidBrushData (section 2.2.2.43) (done) объект EmfPlusTextureBrushData (section 2.2.2.45) (done)

Значение: Данные кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Получает или задает тип.

Значение: 32‑битное беззнаковое целое, которое указывает тип кисти, определяющий содержимое поля BrushData. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает тип.

Значение: 32‑битное беззнаковое целое, которое указывает тип кисти, определяющий содержимое поля BrushData. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusBrushType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

