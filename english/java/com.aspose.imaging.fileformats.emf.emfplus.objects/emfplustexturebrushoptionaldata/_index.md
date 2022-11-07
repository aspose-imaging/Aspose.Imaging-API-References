---
title: EmfPlusTextureBrushOptionalData
second_title: Aspose.Imaging for Java API Reference
description: he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.
type: docs
weight: 78
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

Note Each field of this object is optional and might not be present in the OptionalData field of an EmfPlusTextureBrushData object (section 2.2.2.45), depending on the BrushData flags(section 2.1.2.1) set in its BrushDataFlags field.Although it is not practical to represent every possible combination of fields present or absent, this section specifies their relative order in the object. The implementer is responsible for determining which fields are actually present in a given metafile record, and for unmarshaling the data for individual fields separately and appropriately.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the texture brush. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the texture brush. |
| [getImageObject()](#getImageObject--) | Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the brush texture. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the brush texture. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the texture brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusTextureBrushData object.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the texture brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusTextureBrushData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the brush texture. This field MUST be present if the size of the EmfPlusObject record (section 2.3.5.1) that defines this texture brush is large enough to accommodate an EmfPlusImage object in addition to the required fields of the EmfPlusTextureBrushData object and optionally an EmfPlusTransformMatrix object.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the brush texture. This field MUST be present if the size of the EmfPlusObject record (section 2.3.5.1) that defines this texture brush is large enough to accommodate an EmfPlusImage object in addition to the required fields of the EmfPlusTextureBrushData object and optionally an EmfPlusTransformMatrix object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

