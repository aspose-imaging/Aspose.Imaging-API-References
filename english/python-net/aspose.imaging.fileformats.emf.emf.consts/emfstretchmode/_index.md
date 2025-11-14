---
title: EmfStretchMode Enumeration
type: docs
weight: 340
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

The StretchMode enumeration is used to specify how color data is added to or removed from bitmaps that are stretched or compressed.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| STRETCH_ANDSCANS | Performs a Boolean AND operation using the color values for the eliminated and existing pixels.<br/>            If the bitmap is a monochrome bitmap, this mode preserves black pixels at the expense of white pixels |
| STRETCH_DELETESCANS | Deletes the pixels. This mode deletes all eliminated lines of pixels without trying to preserve their information. |
| STRETCH_HALFTONE | Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. <br/>            The average color over the destination block of pixels approximates the color of the source pixels. |
| STRETCH_ORSCANS | Performs a Boolean OR operation using the color values for the eliminated and existing pixels. <br/>            If the bitmap is a monochrome bitmap, this mode preserves white pixels at the expense of black pixels. |
