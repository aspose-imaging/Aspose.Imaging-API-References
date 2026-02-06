---
title: Struct EmfBlendFunction
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunction struct. A structure that specifies the blending operations for source and destination bitmaps
type: docs
weight: 3360
url: /net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
## EmfBlendFunction structure

A structure that specifies the blending operations for source and destination bitmaps.

```csharp
public struct EmfBlendFunction
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfBlendFunction](emfblendfunction/)(int) | Initializes a new instance of the `EmfBlendFunction` class. |

## Properties

| Name | Description |
| --- | --- |
| [AlphaFormat](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/alphaformat/) { get; } | Gets a structure that specifies how source and destination pixels are interpreted with respect to alpha transparency. |
| [BlendFlags](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendflags/) { get; } | Gets the blend flags. This value MUST be 0x00 and MUST be ignored. |
| [BlendOperation](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendoperation/) { get; } | Gets the blend operation code. The only source and destination blend operation that has been defined is 0x00, which specifies that the source bitmap MUST be combined with the destination bitmap based on the alpha transparency values of the source pixels. See the following equations for details. |
| [SrcConstantAlpha](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/srcconstantalpha/) { get; } | Gets an 8-bit unsigned integer that specifies alpha transparency, which determines the blend of the source and destination bitmaps. This value MUST be used on the entire source bitmap. The minimum alpha transparency value, zero, corresponds to completely transparent the maximum value, 0xFF, corresponds to completely opaque. In effect, a value of 0xFF specifies that the per-pixel alpha values determine the blend of the source and destination bitmaps. See the equations later in this section for details. |

## Methods

| Name | Description |
| --- | --- |
| [ToInt](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/toint/)() | Converts the string representation of a number to an integer. |

## Other Members

| Name | Description |
| --- | --- |
| enum [AlphaFormatEnum](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum) | A structure that specifies how source and destination pixels are interpreted with respect to alpha transparency. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


