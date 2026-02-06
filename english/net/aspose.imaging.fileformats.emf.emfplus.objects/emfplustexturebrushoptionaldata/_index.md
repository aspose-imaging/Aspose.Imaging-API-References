---
title: Class EmfPlusTextureBrushOptionalData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushOptionalData class. he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush
type: docs
weight: 5940
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
## EmfPlusTextureBrushOptionalData class

he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

```csharp
public sealed class EmfPlusTextureBrushOptionalData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusTextureBrushOptionalData](emfplustexturebrushoptionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ImageObject](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/imageobject/) { get; set; } | Gets or sets an optional EmfPlusImage object (section 2.2.1.4) that specifies the brush texture. This field MUST be present if the size of the EmfPlusObject record (section 2.3.5.1) that defines this texture brush is large enough to accommodate an EmfPlusImage object in addition to the required fields of the EmfPlusTextureBrushData object and optionally an EmfPlusTransformMatrix object. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/transformmatrix/) { get; set; } | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the texture brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusTextureBrushData object. |

## Remarks

Note Each field of this object is optional and might not be present in the OptionalData field of an EmfPlusTextureBrushData object (section 2.2.2.45), depending on the BrushData flags(section 2.1.2.1) set in its BrushDataFlags field.Although it is not practical to represent every possible combination of fields present or absent, this section specifies their relative order in the object. The implementer is responsible for determining which fields are actually present in a given metafile record, and for unmarshaling the data for individual fields separately and appropriately.

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


