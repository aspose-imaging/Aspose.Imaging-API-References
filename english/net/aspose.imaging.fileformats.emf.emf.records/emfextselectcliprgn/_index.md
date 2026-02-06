---
title: Class EmfExtSelectClipRgn
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtSelectClipRgn class. The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region using the specified mode. Note Fields that are not described in this section are specified in section 2.3.2
type: docs
weight: 3760
url: /net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
## EmfExtSelectClipRgn class

The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region using the specified mode. Note Fields that are not described in this section are specified in section 2.3.2.

```csharp
public sealed class EmfExtSelectClipRgn : EmfClippingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor)() | Initializes a new instance of the `EmfExtSelectClipRgn` class. |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfExtSelectClipRgn` class. |

## Properties

| Name | Description |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/regionmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the way to use the region. The value MUST be in the RegionMode (section 2.1.29) enumeration. |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndata/) { get; set; } | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object in logical units. If RegionMode is RGN_COPY, this data can be omitted and the clip region SHOULD be set to the default (NULL) clip region. |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndatasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfClippingRecordType](../emfclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


