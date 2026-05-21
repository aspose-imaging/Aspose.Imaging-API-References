---
title: "EmfPlusTextureBrushData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusTextureBrushData указывает текстурное изображение для графической кисти."
type: docs
weight: 77
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

Объект EmfPlusTextureBrushData указывает текстурное изображение для графической кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [getWrapMode()](#getWrapMode--) | Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, как повторять текстурное изображение по фигуре, когда изображение меньше заполняемой области. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, как повторять текстурное изображение по фигуре, когда изображение меньше заполняемой области. |
| [getOptionalData()](#getOptionalData--) | Получает или задает необязательный объект EmfPlusTextureBrushOptionalData (раздел 2.2.2.46), который указывает дополнительные данные для текстурной кисти. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Получает или задает необязательный объект EmfPlusTextureBrushOptionalData (раздел 2.2.2.46), который указывает дополнительные данные для текстурной кисти. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). Следующие флаги относятся к текстурной кисти: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform.

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). Следующие флаги относятся к текстурной кисти: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, как повторять текстурное изображение по фигуре, когда изображение меньше заполняемой области.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает, как повторять текстурное изображение по фигуре, когда изображение меньше заполняемой области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Получает или задает необязательный объект EmfPlusTextureBrushOptionalData (раздел 2.2.2.46), который указывает дополнительные данные для текстурной кисти. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Получает или задает необязательный объект EmfPlusTextureBrushOptionalData (раздел 2.2.2.46), который указывает дополнительные данные для текстурной кисти. Конкретное содержание этого поля определяется значением поля BrushDataFlags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

