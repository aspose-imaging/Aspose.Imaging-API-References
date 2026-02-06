---
title: Class EmfLogBrushEx
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx class. The LogBrushEx object defines the style color and pattern of a deviceindependent brush
type: docs
weight: 3110
url: /net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
## EmfLogBrushEx class

The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

```csharp
public sealed class EmfLogBrushEx : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfLogBrushEx](emflogbrushex/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/argb32colorref/) { get; set; } | Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. The interpretation of this field depends on the value of BrushStyle, as explained in the following table. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushhatch/) { get; set; } | Gets or sets a 32-bit unsigned field that contains the brush hatch data. Its interpretation depends on the value of BrushStyle, |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushstyle/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the brush style. The value MUST be an enumeration from WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). The style values that are supported in this structure are listed later in this section. The BS_NULL style SHOULD be used to specify a brush that has no effect. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


