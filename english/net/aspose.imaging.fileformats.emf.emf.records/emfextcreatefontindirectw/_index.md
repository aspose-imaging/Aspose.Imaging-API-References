---
title: Class EmfExtCreateFontIndirectW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtCreateFontIndirectW class. The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations
type: docs
weight: 3720
url: /net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
## EmfExtCreateFontIndirectW class

The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

```csharp
public sealed class EmfExtCreateFontIndirectW : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtCreateFontIndirectW](emfextcreatefontindirectw/#constructor)() | Initializes a new instance of the `EmfExtCreateFontIndirectW` class. |
| [EmfExtCreateFontIndirectW](emfextcreatefontindirectw/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfExtCreateFontIndirectW` class. |

## Properties

| Name | Description |
| --- | --- |
| [Elw](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/elw/) { get; set; } | Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. A LogFont object 2.2.13 MAY be present instead.[90]The process for determining the type of object in this field is described below. |
| [IhFonts](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/ihfonts/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


