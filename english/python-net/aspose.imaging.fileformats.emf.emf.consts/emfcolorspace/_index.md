---
title: EmfColorSpace Enumeration
type: docs
weight: 60
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---

The ColorSpace enumeration is used to specify when to turn color proofing on and off, and when to delete transforms.

**Namespace:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfColorSpace

**Assembly:**  Aspose.Imaging Version: 23.3.0

## **Members**
|**Member name**|**Description**|
| :- | :- |
|CS_ENABLE|Maps colors to the target device's color gamut. This enables color proofing. <br/>            All subsequent draw commands to the playback device context will render colors as they would appear on the target device.|
|CS_DISABLE|Disables color proofing.|
|CS_DELETE_TRANSFORM|If color management is enabled for the target profile, disables it and deletes the concatenated transform.|
