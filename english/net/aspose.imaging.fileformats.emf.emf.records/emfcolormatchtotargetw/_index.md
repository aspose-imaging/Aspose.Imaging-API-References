---
title: Class EmfColorMatchToTargetW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfColorMatchToTargetW class. The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters
type: docs
weight: 3430
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
## EmfColorMatchToTargetW class

The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters.

```csharp
public sealed class EmfColorMatchToTargetW : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfColorMatchToTargetW](emfcolormatchtotargetw/)(EmfRecord) | Initializes a new instance of the `EmfColorMatchToTargetW` class. |

## Properties

| Name | Description |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbdata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target color profile, if it is contained in the Data field. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbname/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/data/) { get; set; } | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [DwAction](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwaction/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace enumeration (section 2.1.7). |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorMatchToTarget enumeration (section 2.1.6). |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/name/) { get; } | Gets the name |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/rawdata/) { get; } | Gets the raw data |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

An EMR_COLORMATCHTOTargetW record can be used to control whether to apply the current color transform in the playback device context. If the dwAction value is CS_ENABLE, color mapping is enabled, and the current color transform SHOULD be applied to subsequent graphics operations. If dwAction is set to CS_DISABLE, the color transform SHOULD NOT be applied. While color mapping to the target is enabled by a dwAction value of CS_ENABLE, changes to the color space or color gamut mapping are not applied. However, those changes MUST take effect when color mapping to the target is disabled. The dwAction field SHOULD NOT be set to CS_DELETE_TRANSFORM unless color management has already been enabled with an EMR_SETICMMODE record (section 2.3.11.14).

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


