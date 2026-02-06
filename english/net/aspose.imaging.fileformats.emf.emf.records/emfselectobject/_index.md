---
title: Class EmfSelectObject
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject class. The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device context. The object is specified either by its index in the EMF Object Tablesection 3.1.1.1 or by its value from the StockObject enumerationsection 2.1.31
type: docs
weight: 4370
url: /net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
## EmfSelectObject class

The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its value from the StockObject enumeration(section 2.1.31).

```csharp
public sealed class EmfSelectObject : EmfRecord
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSelectObject](emfselectobject/#constructor)() | Initializes a new instance of the `EmfSelectObject` class. |
| [EmfSelectObject](emfselectobject/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSelectObject` class. |

## Properties

| Name | Description |
| --- | --- |
| [ObjectHandle](../../aspose.imaging.fileformats.emf.emf.records/emfselectobject/objecthandle/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the [`EmfStockObject`](../../aspose.imaging.fileformats.emf.emf.consts/emfstockobject/) enumeration. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


