---
title: Class EmfModifyWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfModifyWorldTransform class. The EMR_MODIFYWORLDTRANSFORM record modifies the current worldspace to pagespace transform in the playback device context
type: docs
weight: 3940
url: /net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
## EmfModifyWorldTransform class

The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context.

```csharp
public sealed class EmfModifyWorldTransform : EmfTransformRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor)() | Initializes a new instance of the `EmfModifyWorldTransform` class. |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfModifyWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| [ModifyWorldTransformMode](../../aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/modifyworldtransformmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how the transform specified in Xform is used. This value MUST be in the ModifyWorldTransformMode enumeration (section 2.1.24). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform/) { get; set; } | Gets or sets an XForm object (section 2.2.28), which defines a world-space to page space transform. |

## Remarks

For more information concerning transforms and coordinate spaces, see [MSDN-WRLDPGSPC]. See section 2.3.12 for the specification of other transform record types.

### See Also

* class [EmfTransformRecordType](../emftransformrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


