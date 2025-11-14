---
title: EmfGraphicsMode Enumeration
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

The GraphicsMode enumeration is used to specify how to interpret shape data such as rectangle coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| GM_ADVANCED | TrueType text output MUST fully conform to the current world-to-device transformation in the playback device context.<br/>            Arcs MUST be drawn in the counterclockwise direction in world space; however, both arc control points <br/>            and the arcs themselves MUST fully respect the current world-to-device transformation in the playback device context.<br/>            The world-to-device transform MAY be modified directly by using the EMR_MODIFYWORLDTRANSFORM or <br/>            EMR_SETWORLDTRANSFORM records, or indirectly by changing the window and viewport extents and origins, <br/>            using the EMR_SETWINDOWEXTEX (section 2.3.11.30) and EMR_SETVIEWPORTEXTEX (section 2.3.11.28) records, <br/>            and the EMR_SETWINDOWORGEX (section 2.3.11.31) and EMR_SETVIEWPORTORGEX (section 2.3.11.30) records, respectively.<br/>            In GM_ADVANCED graphics mode, bottom and rightmost edges MUST be included when rectangles are drawn. |
| GM_COMPATIBLE | TrueType text MUST be written from left to right and right side up, even if the rest of the graphics <br/>            are rotated about the x-axis or y-axis because of the current world-to-device transformation in <br/>            the playback device context. Only the height of the text SHOULD be scaled. Arcs MUST be drawn using <br/>            the current arc direction in the playback device context, but they MUST NOT respect the current <br/>            world-to-device transformation, which might require a rotation along the x-axis or y-axis.<br/>            The world-to-device transformation SHOULD only be modified by changing the window and viewport <br/>            extents and origins, using the EMR_SETWINDOWEXTEX (section 2.3.11.30) and EMR_SETVIEWPORTEXTEX <br/>            (section 2.3.11.28) records, and the EMR_SETWINDOWORGEX (section 2.3.11.31) and EMR_SETVIEWPORTORGEX <br/>            (section 2.3.11.30) records, respectively. bChanging the transformation directly by using the <br/>            EMR_MODIFYWORLDTRANSFORM (section 2.3.12.1) or EMR_SETWORLDTRANSFORM (section 2.3.12.2) records MAY NOT be supported.<br/>            In GM_COMPATIBLE graphics mode, bottom and rightmost edges MUST be excluded when rectangles are drawn |
