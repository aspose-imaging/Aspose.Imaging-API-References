---
title: Enum EmfGraphicsMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfGraphicsMode enum. The GraphicsMode enumeration is used to specify how to interpret shape data such as rectangle coordinates
type: docs
weight: 2770
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
## EmfGraphicsMode enumeration

The GraphicsMode enumeration is used to specify how to interpret shape data such as rectangle coordinates.

```csharp
public enum EmfGraphicsMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| GM_COMPATIBLE | `1` | TrueType text MUST be written from left to right and right side up, even if the rest of the graphics are rotated about the x-axis or y-axis because of the current world-to-device transformation in the playback device context. Only the height of the text SHOULD be scaled. Arcs MUST be drawn using the current arc direction in the playback device context, but they MUST NOT respect the current world-to-device transformation, which might require a rotation along the x-axis or y-axis. The world-to-device transformation SHOULD only be modified by changing the window and viewport extents and origins, using the EMR_SETWINDOWEXTEX (section 2.3.11.30) and EMR_SETVIEWPORTEXTEX (section 2.3.11.28) records, and the EMR_SETWINDOWORGEX (section 2.3.11.31) and EMR_SETVIEWPORTORGEX (section 2.3.11.30) records, respectively. bChanging the transformation directly by using the EMR_MODIFYWORLDTRANSFORM (section 2.3.12.1) or EMR_SETWORLDTRANSFORM (section 2.3.12.2) records MAY NOT be supported. In GM_COMPATIBLE graphics mode, bottom and rightmost edges MUST be excluded when rectangles are drawn |
| GM_ADVANCED | `2` | TrueType text output MUST fully conform to the current world-to-device transformation in the playback device context. Arcs MUST be drawn in the counterclockwise direction in world space; however, both arc control points and the arcs themselves MUST fully respect the current world-to-device transformation in the playback device context. The world-to-device transform MAY be modified directly by using the EMR_MODIFYWORLDTRANSFORM or EMR_SETWORLDTRANSFORM records, or indirectly by changing the window and viewport extents and origins, using the EMR_SETWINDOWEXTEX (section 2.3.11.30) and EMR_SETVIEWPORTEXTEX (section 2.3.11.28) records, and the EMR_SETWINDOWORGEX (section 2.3.11.31) and EMR_SETVIEWPORTORGEX (section 2.3.11.30) records, respectively. In GM_ADVANCED graphics mode, bottom and rightmost edges MUST be included when rectangles are drawn. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


