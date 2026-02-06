---
title: Class EmfRecord
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord class. Base class for EMF records All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the generic structures of the preceding EMF record types by including AlignmentPadding fields where appropriate at the ends of these structures. The contents of AlignmentPadding fields MUST always be ignored. For brevity these fields are not shown in every individual EMF record definition
type: docs
weight: 4270
url: /net/aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
## EmfRecord class

Base class for EMF records All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the generic structures of the preceding EMF record types by including AlignmentPadding fields where appropriate at the ends of these structures. The contents of AlignmentPadding fields MUST always be ignored. For brevity, these fields are not shown in every individual EMF record definition.

```csharp
public class EmfRecord : MetaObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfRecord](emfrecord/#constructor)() | Initializes a new instance of the `EmfRecord` class. |
| [EmfRecord](emfrecord/#constructor_2)(EmfRecord) | Initializes a new instance of the `EmfRecord` class. |
| [EmfRecord](emfrecord/#constructor_1)(EmfRecordType) | Initializes a new instance of the `EmfRecord` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


