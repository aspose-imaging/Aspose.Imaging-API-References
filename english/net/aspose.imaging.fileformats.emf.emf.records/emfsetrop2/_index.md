---
title: Class EmfSetRop2
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetRop2 class. The EMR_SETROP2 record defines a binary raster operation mode
type: docs
weight: 4590
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
## EmfSetRop2 class

The EMR_SETROP2 record defines a binary raster operation mode.

```csharp
public sealed class EmfSetRop2 : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetRop2](emfsetrop2/#constructor)() | Initializes a new instance of the `EmfSetRop2` class. |
| [EmfSetRop2](emfsetrop2/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSetRop2` class. |

## Properties

| Name | Description |
| --- | --- |
| [Rop2Mode](../../aspose.imaging.fileformats.emf.emf.records/emfsetrop2/rop2mode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Binary raster operation mix modes define how to combine source and destination colors when drawing with the current pen. The mix modes are binary raster operation codes, representing all possible Boolean functions of two variables, using the binary operations AND, OR, and XOR (exclusive OR), and the unary operation NOT. The mix mode is for raster devices only; it is not available for vector devices.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


