---
title: Class EmfSetWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetWorldTransform class. The EMR_SETWORLDTRANSFORM record specifies a transform for the current worldspace to page space transform in the playback device context
type: docs
weight: 4680
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---
## EmfSetWorldTransform class

The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

```csharp
public sealed class EmfSetWorldTransform : EmfTransformRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetWorldTransform](emfsetworldtransform/#constructor)() | Initializes a new instance of the `EmfSetWorldTransform` class. |
| [EmfSetWorldTransform](emfsetworldtransform/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSetWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform/) { get; set; } | Gets or sets an XForm object (section 2.2.28), which defines a world-space to page space transform. |

## Remarks

For more information concerning transforms and coordinate spaces, see [MSDN-WRLDPGSPC]. See section 2.3.12 for the specification of other transform record types.

### See Also

* class [EmfTransformRecordType](../emftransformrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


