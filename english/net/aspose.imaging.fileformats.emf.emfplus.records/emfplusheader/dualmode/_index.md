---
title: EmfPlusHeader.DualMode
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusHeader property. Gets or sets a value indicating whether dual mode. If set this flag indicates that this metafile is dualmode which means that it contains two sets of records each of which completely specifies the graphics content. If clear the graphics content is specified by EMF records and possibly EMF records that are preceded by an EmfPlusGetDC record. If this flag is set EMF records alone SHOULD suffice to define the graphics content. Note that whether the dualmode flag is set or not some EMF records are always present namely EMF control records and the EMF records that contain EMF records. EMF control records are specified in MSEMF section 2.3.4
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/
---
## EmfPlusHeader.DualMode property

Gets or sets a value indicating whether [dual mode]. If set, this flag indicates that this metafile is "dual-mode", which means that it contains two sets of records, each of which completely specifies the graphics content. If clear, the graphics content is specified by EMF+ records, and possibly EMF records that are preceded by an EmfPlusGetDC record. If this flag is set, EMF records alone SHOULD suffice to define the graphics content. Note that whether the "dual-mode" flag is set or not, some EMF records are always present, namely EMF control records and the EMF records that contain EMF+ records. EMF control records are specified in [MS-EMF] section 2.3.4.

```csharp
public bool DualMode { get; set; }
```

### Property Value

`true` if [dual mode]; otherwise, `false`.

### See Also

* class [EmfPlusHeader](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusheader/)
* assembly [Aspose.Imaging](../../../)


