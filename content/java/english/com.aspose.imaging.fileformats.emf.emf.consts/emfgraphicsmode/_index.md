---
title: EmfGraphicsMode
second_title: Aspose.Imaging for Java API Reference
description: The GraphicsMode enumeration is used to specify how to interpret shape data such as rectangle coordinates.
type: docs
weight: 24
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

The GraphicsMode enumeration is used to specify how to interpret shape data such as rectangle coordinates.
## Fields

| Field | Description |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType text MUST be written from left to right and right side up, even if the rest of the graphics are rotated about the x-axis or y-axis because of the current world-to-device transformation in the playback device context. |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType text output MUST fully conform to the current world-to-device transformation in the playback device context. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType text MUST be written from left to right and right side up, even if the rest of the graphics are rotated about the x-axis or y-axis because of the current world-to-device transformation in the playback device context. Only the height of the text SHOULD be scaled. Arcs MUST be drawn using the current arc direction in the playback device context, but they MUST NOT respect the current world-to-device transformation, which might require a rotation along the x-axis or y-axis. The world-to-device transformation SHOULD only be modified by changing the window and viewport extents and origins, using the EMR\_SETWINDOWEXTEX (section 2.3.11.30) and EMR\_SETVIEWPORTEXTEX (section 2.3.11.28) records, and the EMR\_SETWINDOWORGEX (section 2.3.11.31) and EMR\_SETVIEWPORTORGEX (section 2.3.11.30) records, respectively. bChanging the transformation directly by using the EMR\_MODIFYWORLDTRANSFORM (section 2.3.12.1) or EMR\_SETWORLDTRANSFORM (section 2.3.12.2) records MAY NOT be supported. In GM\_COMPATIBLE graphics mode, bottom and rightmost edges MUST be excluded when rectangles are drawn

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType text output MUST fully conform to the current world-to-device transformation in the playback device context. Arcs MUST be drawn in the counterclockwise direction in world space; however, both arc control points and the arcs themselves MUST fully respect the current world-to-device transformation in the playback device context. The world-to-device transform MAY be modified directly by using the EMR\_MODIFYWORLDTRANSFORM or EMR\_SETWORLDTRANSFORM records, or indirectly by changing the window and viewport extents and origins, using the EMR\_SETWINDOWEXTEX (section 2.3.11.30) and EMR\_SETVIEWPORTEXTEX (section 2.3.11.28) records, and the EMR\_SETWINDOWORGEX (section 2.3.11.31) and EMR\_SETVIEWPORTORGEX (section 2.3.11.30) records, respectively. In GM\_ADVANCED graphics mode, bottom and rightmost edges MUST be included when rectangles are drawn.

