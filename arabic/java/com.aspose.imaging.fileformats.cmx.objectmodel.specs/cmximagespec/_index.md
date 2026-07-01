---
title: "CmxImageSpec"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثّل المعلومات المحددة للصور النقطية."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

يمثّل المعلومات المحددة للصور النقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | يحصل على الصندوق الحدودي. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | يضبط الصندوق الحدودي. |
| [getCropBox()](#getCropBox--) | يحصل على صندوق القص. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | يضبط مربع القص. |
| [getMatrix()](#getMatrix--) | يحصل على مصفوفة التحويل. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | يضبط مصفوفة التحويل. |
| [getImageType()](#getImageType--) | يحصل على نوع الصورة. |
| [setImageType(int value)](#setImageType-int-) | يضبط نوع الصورة. |
| [getImages()](#getImages--) | يحصل على الصور. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | يضبط الصور. |
| [isCmx3Image()](#isCmx3Image--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3. |
| [toString()](#toString--) | يرجع String يمثل هذه المثيلة. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


يحصل على الصندوق الحدودي.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


يضبط الصندوق الحدودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | مربع الإحاطة. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


يحصل على صندوق القص.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


يضبط مربع القص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | مربع القص. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


يحصل على مصفوفة التحويل.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


يضبط مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | مصفوفة التحويل. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


يحصل على نوع الصورة.

**Returns:**
int - نوع الصورة.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


يضبط نوع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نوع الصورة. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


يحصل على الصور.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - الصور.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


يضبط الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | الصور. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3.

القيمة: `true` إذا كان هذا الكائن صورة CMX3؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3.

القيمة: `true` إذا كان هذا الكائن صورة CMX3؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان هذا الكائن صورة CMX3. |

### toString() {#toString--}
```
public String toString()
```


يرجع String يمثل هذه المثيلة.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### toArray() {#toArray--}
```
public CmxRasterImage[] toArray()
```




**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
