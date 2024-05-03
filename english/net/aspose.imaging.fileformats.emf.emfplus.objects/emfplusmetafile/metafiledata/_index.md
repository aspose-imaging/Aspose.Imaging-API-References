---
title: EmfPlusMetafile.MetafileData
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusMetafile property. Gets or sets variablelength data that specifies the embedded metafile. The content and format of the data can be different for each metafile type
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/metafiledata/
---
## EmfPlusMetafile.MetafileData property

Gets or sets variable-length data that specifies the embedded metafile. The content and format of the data can be different for each metafile type.

```csharp
public byte[] MetafileData { get; set; }
```

## Remarks

Graphics images are specified by EmfPlusImage objects (section 2.2.1.4). An EmfPlusMetafile object MUST be present in the ImageData field of an EmfPlusImage object if ImageTypeMetafile is specified in its Type field. This object is generic and is used for different types of data, including: A WMF metafile [MS-WMF]; WMF metafile which can be placed; An EMF metafile [MS-EMF]; An EMF+ metafile that specifies graphics operations with EMF+ records only; and An EMF+ metafile that specifies graphics operations with both EMF+ and EMF records. See section 2.2.2 for the specification of additional structure objects.

### See Also

* class [EmfPlusMetafile](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusmetafile/)
* assembly [Aspose.Imaging](../../../)


