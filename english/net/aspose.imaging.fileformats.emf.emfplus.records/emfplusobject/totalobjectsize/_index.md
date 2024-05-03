---
title: EmfPlusObject.TotalObjectSize
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusObject property. Gets or sets the total size of the object. If the record is continuable when the continue bit is set this field will be present. Continuing objects have multiple EMF records starting with EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a TotalObjectSize. Once TotalObjectSize number of bytes has been read the next EMF record will not be treated as part of the continuing object
type: docs
weight: 60
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize/
---
## EmfPlusObject.TotalObjectSize property

Gets or sets the total size of the object. If the record is continuable, when the continue bit is set, this field will be present. Continuing objects have multiple EMF+ records starting with EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+ record will not be treated as part of the continuing object.

```csharp
public int TotalObjectSize { get; set; }
```

### Property Value

The total size of the object.

### See Also

* class [EmfPlusObject](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusobject/)
* assembly [Aspose.Imaging](../../../)


