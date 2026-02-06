---
title: Enum EmfModifyWorldTransformMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfModifyWorldTransformMode enum. The ModifyWorldTransformMode enumeration defines modes for using specified transform data to modify the worldspace to pagespace transform that is currently defined in the playback device context
type: docs
weight: 2860
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
## EmfModifyWorldTransformMode enumeration

The ModifyWorldTransformMode enumeration defines modes for using specified transform data to modify the world-space to page-space transform that is currently defined in the playback device context.

```csharp
public enum EmfModifyWorldTransformMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MWT_IDENTITY | `1` | Reset the current transform using the identity matrix. In this mode, the specified transform data is ignored |
| MWT_LEFTMULTIPLY | `2` | Multiply the current transform. In this mode, the specified transform data is the left multiplicand, and the transform that is currently defined in the playback device context is the right multiplicand |
| MWT_RIGHTMULTIPLY | `3` | Multiply the current transform. In this mode, the specified transform data is the right multiplicand, and the transform that is currently defined in the playback device context is the left multiplicand |
| MWT_SET | `4` | Perform the function of an EMR_SETWORLDTRANSFORM record (section 2.3.12.2). |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


