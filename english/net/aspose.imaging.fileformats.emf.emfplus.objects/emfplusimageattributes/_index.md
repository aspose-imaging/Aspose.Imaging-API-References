---
title: Class EmfPlusImageAttributes
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusImageAttributes class. The EmfPlusImageAttributes object specifies how bitmap image colors are manipulated during rendering
type: docs
weight: 5630
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
## EmfPlusImageAttributes class

The EmfPlusImageAttributes object specifies how bitmap image colors are manipulated during rendering.

```csharp
public sealed class EmfPlusImageAttributes : EmfPlusGraphicsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusImageAttributes](emfplusimageattributes/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ClampArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/clampargb32color/) { get; set; } | Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use when the WrapMode value is WrapModeClamp. This color is visible when the source rectangle processed by an EmfPlusDrawImage (section 2.3.4.8) record is larger than the image itself. |
| [ObjectClamp](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/objectclamp/) { get; set; } | Gets or sets 32-bit signed integer that specifies the object clamping behavior. It is not used until this object is applied to an image being drawn. This value MUST be one of the values defined in the following table. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | Gets or sets the version. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/wrapmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with a value from the WrapMode enumeration (section 2.1.1.34). |

### See Also

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


