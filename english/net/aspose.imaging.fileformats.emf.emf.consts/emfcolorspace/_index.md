---
title: Enum EmfColorSpace
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfColorSpace enum. The ColorSpace enumeration is used to specify when to turn color proofing on and off and when to delete transforms
type: docs
weight: 2680
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
## EmfColorSpace enumeration

The ColorSpace enumeration is used to specify when to turn color proofing on and off, and when to delete transforms.

```csharp
public enum EmfColorSpace
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CS_ENABLE | `1` | Maps colors to the target device's color gamut. This enables color proofing. All subsequent draw commands to the playback device context will render colors as they would appear on the target device. |
| CS_DISABLE | `2` | Disables color proofing. |
| CS_DELETE_TRANSFORM | `3` | If color management is enabled for the target profile, disables it and deletes the concatenated transform. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


