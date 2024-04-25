---
title: EmfColorSpace
second_title: Aspose.Imaging for Java API Reference
description: The ColorSpace enumeration is used to specify when to turn color proofing on and off and when to delete transforms.
type: docs
weight: 15
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

The ColorSpace enumeration is used to specify when to turn color proofing on and off, and when to delete transforms.
## Fields

| Field | Description |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Maps colors to the target device's color gamut. |
| [CS_DISABLE](#CS-DISABLE) | Disables color proofing. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | If color management is enabled for the target profile, disables it and deletes the concatenated transform. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Maps colors to the target device's color gamut. This enables color proofing. All subsequent draw commands to the playback device context will render colors as they would appear on the target device.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Disables color proofing.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


If color management is enabled for the target profile, disables it and deletes the concatenated transform.

