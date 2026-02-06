---
title: Class EmfPlusGraphicsVersion
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusGraphicsVersion class. The EmfPlusGraphicsVersion object specifies the version of operating system graphics that is used to create an EMF metafile
type: docs
weight: 5590
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
## EmfPlusGraphicsVersion class

The EmfPlusGraphicsVersion object specifies the version of operating system graphics that is used to create an EMF+ metafile.

```csharp
public sealed class EmfPlusGraphicsVersion : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusGraphicsVersion](emfplusgraphicsversion/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicsVersion](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/graphicsversion/) { get; set; } | Gets a GraphicsVersion (12 bits): The version of operating system graphics. This value MUST be defined in the `EmfPlusGraphicsVersion` enumeration |
| [MetafileSignature](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/metafilesignature/) { get; set; } | Gets a MetafileSignature (20 bits): A value that identifies the type of metafile. The value for an EMF+ metafile is 0xDBC01. |

## Remarks

Graphics versions are vendor-extensible; however, to ensure inter-operability, any such extension MUST be implemented in both clients and servers of EMF+ metafiles.

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


