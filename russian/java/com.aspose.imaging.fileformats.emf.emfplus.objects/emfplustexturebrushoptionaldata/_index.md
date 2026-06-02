---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusTextureBrushOptionalData указывает необязательные данные для текстурной кисти."
type: docs
weight: 78
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

Объект EmfPlusTextureBrushOptionalData указывает необязательные данные для текстурной кисти.

Примечание: каждое поле этого объекта является необязательным и может отсутствовать в поле OptionalData объекта EmfPlusTextureBrushData (раздел 2.2.2.45), в зависимости от флагов BrushData (раздел 2.1.2.1), установленных в его поле BrushDataFlags. Хотя не практично представлять каждую возможную комбинацию присутствующих или отсутствующих полей, в этом разделе указан их относительный порядок в объекте. Реализатор отвечает за определение, какие поля действительно присутствуют в данной записи метафайла, и за отдельное и корректное десериализование данных каждого поля.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для текстурной кисти. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для текстурной кисти. |
| [getImageObject()](#getImageObject--) | Получает или задает необязательный объект EmfPlusImage (раздел 2.2.1.4), который определяет текстуру кисти. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Получает или задает необязательный объект EmfPlusImage (раздел 2.2.1.4), который определяет текстуру кисти. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для текстурной кисти. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для текстурной кисти. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusTextureBrushData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Получает или задает необязательный объект EmfPlusImage (раздел 2.2.1.4), который определяет текстуру кисти. Это поле ДОЛЖНО присутствовать, если размер записи EmfPlusObject (раздел 2.3.5.1), определяющей эту текстурную кисть, достаточно велик, чтобы вместить объект EmfPlusImage в дополнение к обязательным полям объекта EmfPlusTextureBrushData и, при необходимости, объекту EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Получает или задает необязательный объект EmfPlusImage (раздел 2.2.1.4), который определяет текстуру кисти. Это поле ДОЛЖНО присутствовать, если размер записи EmfPlusObject (раздел 2.3.5.1), определяющей эту текстурную кисть, достаточно велик, чтобы вместить объект EmfPlusImage в дополнение к обязательным полям объекта EmfPlusTextureBrushData и, при необходимости, объекту EmfPlusTransformMatrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

