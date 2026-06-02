---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusTextureBrushOptionalData nesnesi, bir doku fırçası için isteğe bağlı verileri belirtir."
type: docs
weight: 78
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusTextureBrushOptionalData nesnesi, bir doku fırçası için isteğe bağlı verileri belirtir.

Not Bu nesnenin her alanı isteğe bağlıdır ve bir EmfPlusTextureBrushData nesnesinin OptionalData alanında bulunmayabilir (bölüm 2.2.2.45), BrushData bayraklarına (bölüm 2.1.2.1) bağlı olarak BrushDataFlags alanında ayarlanır. Tüm olası alan kombinasyonlarını temsil etmek pratik olmadığından, bu bölüm nesnedeki göreceli sıralarını belirtir. Uygulayıcı, belirli bir metafile kaydında hangi alanların gerçekten mevcut olduğunu belirlemek ve bireysel alanların verilerini ayrı ayrı ve uygun şekilde ayrıştırmaktan sorumludur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Bir isteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar; bu nesne doku fırçası için dünya uzayından aygıt uzayına dönüşümü belirtir. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Bir isteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar; bu nesne doku fırçası için dünya uzayından aygıt uzayına dönüşümü belirtir. |
| [getImageObject()](#getImageObject--) | Bir isteğe bağlı EmfPlusImage nesnesi (bölüm 2.2.1.4) alır veya ayarlar; bu nesne fırça dokusunu belirtir. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Bir isteğe bağlı EmfPlusImage nesnesi (bölüm 2.2.1.4) alır veya ayarlar; bu nesne fırça dokusunu belirtir. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Bir isteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar; bu nesne doku fırçası için dünya uzayından aygıt uzayına dönüşümü belirtir. Bu alan, EmfPlusTextureBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa VAR OLMALIDIR.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Bir isteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar; bu nesne doku fırçası için dünya uzayından aygıt uzayına dönüşümü belirtir. Bu alan, EmfPlusTextureBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa VAR OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Bir isteğe bağlı EmfPlusImage nesnesi (bölüm 2.2.1.4) alır veya ayarlar; bu nesne fırça dokusunu belirtir. Bu alan, bu doku fırçasını tanımlayan EmfPlusObject kaydının (bölüm 2.3.5.1) boyutu, EmfPlusTextureBrushData nesnesinin gerekli alanlarına ek olarak bir EmfPlusImage nesnesi ve isteğe bağlı bir EmfPlusTransformMatrix nesnesi barındıracak kadar büyükse VAR OLMALIDIR.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Bir isteğe bağlı EmfPlusImage nesnesi (bölüm 2.2.1.4) alır veya ayarlar; bu nesne fırça dokusunu belirtir. Bu alan, bu doku fırçasını tanımlayan EmfPlusObject kaydının (bölüm 2.3.5.1) boyutu, EmfPlusTextureBrushData nesnesinin gerekli alanlarına ek olarak bir EmfPlusImage nesnesi ve isteğe bağlı bir EmfPlusTransformMatrix nesnesi barındıracak kadar büyükse VAR OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

