---
title: EmfModifyWorldTransformMode Enumeration
type: docs
weight: 240
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

The ModifyWorldTransformMode enumeration defines modes for using specified transform data<br/>            to modify the world-space to page-space transform that is currently defined in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| MWT_IDENTITY | Reset the current transform using the identity matrix. In this mode, the specified transform data is ignored |
| MWT_LEFTMULTIPLY | Multiply the current transform. In this mode, the specified transform data is the left multiplicand, and <br/>            the transform that is currently defined in the playback device context is the right multiplicand |
| MWT_RIGHTMULTIPLY | Multiply the current transform. In this mode, the specified transform data is the right multiplicand, <br/>            and the transform that is currently defined in the playback device context is the left multiplicand |
| MWT_SET | Perform the function of an EMR_SETWORLDTRANSFORM record (section 2.3.12.2). |
