---
title: Enum EmfPlusRecordType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusRecordType enum. The RecordType enumeration defines record types used in EMF metafiles
type: docs
weight: 5150
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

The RecordType enumeration defines record types used in EMF+ metafiles.

```csharp
public enum EmfPlusRecordType : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EmfPlusHeader | `16385` | This record specifies the start of EMF+ data in the metafile. It MUST be embedded in the first EMF record after the [`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) record ([MS-EMF] section 2.3.4.2 record). |
| EmfPlusEndOfFile | `16386` | This record specifies the end of EMF+ data in the metafile. |
| EmfPlusComment | `16387` | This record specifies arbitrary private data. |
| EmfPlusGetDC | `16388` | This record specifies that subsequent EMF records encountered in the metafile SHOULD be processed. EMF records cease being processed when the next EMF+ record is encountered. |
| EmfPlusMultiFormatStart | `16389` | This record is reserved and MUST NOT be used. |
| EmfPlusMultiFormatSection | `16390` | This record is reserved and MUST NOT be used. |
| EmfPlusMultiFormatEnd | `16391` | This record is reserved and MUST NOT be used. |
| EmfPlusObject | `16392` | This record specifies an object for use in graphics operations. |
| EmfPlusClear | `16393` | This record clears the output `coordinate space` and initializes it with a specified background color and transparency. |
| EmfPlusFillRects | `16394` | This record defines how to fill the interiors of a series of rectangles, using a specified brush. |
| EmfPlusDrawRects | `16395` | This record defines the pen strokes for drawing a series of rectangles. |
| EmfPlusFillPolygon | `16396` | This record defines the data to fill the interior of a polygon, using a specified brush. |
| EmfPlusDrawLines | `16397` | This record defines the pen strokes for drawing a series of connected lines. |
| EmfPlusFillEllipse | `16398` | This record defines how to fill the interiors of an ellipse, using a specified brush. |
| EmfPlusDrawEllipse | `16399` | This record defines the pen strokes for drawing an ellipse. |
| EmfPlusFillPie | `16400` | This record defines how to fill a section of an interior section of an ellipse using a specified brush. |
| EmfPlusDrawPie | `16401` | This record defines pen strokes for drawing a section of an ellipse. |
| EmfPlusDrawArc | `16402` | The record defines pen strokes for drawing an arc of an ellipse. |
| EmfPlusFillRegion | `16403` | This record defines how to fill the interior of a region using a specified brush. |
| EmfPlusFillPath | `16404` | The record defines how to fill the interiors of the figures defined in a graphics path with a specified brush. A path is an object that defines an arbitrary sequence of lines, curves, and shapes. |
| EmfPlusDrawPath | `16405` | The record defines the pen strokes to draw the figures in a graphics path. A path is an object that defines an arbitrary sequence of lines, curves, and shapes. |
| EmfPlusFillClosedCurve | `16406` | This record defines how to fill the interior of a closed cardinal spline using a specified brush. |
| EmfPlusDrawClosedCurve | `16407` | This record defines the pen and strokes for drawing a closed cardinal spline. |
| EmfPlusDrawCurve | `16408` | This record defines the pen strokes for drawing a cardinal spline. |
| EmfPlusDrawBeziers | `16409` | This record defines the pen strokes for drawing a Bezier spline. |
| EmfPlusDrawImage | `16410` | This record defines a scaled [`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) object (section 2.2.1.4). An image can consist of either bitmap or metafile data. |
| EmfPlusDrawImagePoints | `16411` | This record defines a scaled EmfPlusImage object inside a parallelogram. An image can consist of either bitmap or metafile data. |
| EmfPlusDrawString | `16412` | This record defines a text string based on a font, a layout rectangle, and a format. |
| EmfPlusSetRenderingOrigin | `16413` | This record defines the origin of rendering to the specified horizontal and vertical coordinates. This applies to hatch brushes and to 8 and 16 bits per pixel dither patterns. |
| EmfPlusSetAntiAliasMode | `16414` | This record defines whether to enable or disable text anti-aliasing. Text anti-aliasing is a method of making lines and edges of character glyphs appear smoother when drawn on an output surface. |
| EmfPlusSetTextRenderingHint | `16415` | This record defines the process used for rendering text. |
| EmfPlusSetTextContrast | `16416` | This record sets text contrast according to the specified text gamma value. |
| EmfPlusSetInterpolationMode | `16417` | This record defines the interpolation mode of an object according to the specified type of image filtering. The interpolation mode influences how scaling (stretching and shrinking) is performed. |
| EmfPlusSetPixelOffsetMode | `16418` | This record defines the pixel offset mode according to the specified pixel centering value. |
| EmfPlusSetCompositingMode | `16419` | This record defines the compositing mode according to the state of alpha blending, which specifies how source colors are combined with background colors. |
| EmfPlusSetCompositingQuality | `16420` | This record defines the compositing quality, which describes the desired level of quality for creating composite images from multiple objects. |
| EmfPlusSave | `16421` | This record saves the graphics state, identified by a specified index, on a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is used by an [`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) record (section 2.3.7.4) to restore the state. |
| EmfPlusRestore | `16422` | This record restores the graphics state, identified by a specified index, from a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is defined by an [`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) record (section 2.3.7.5) to save the state. |
| EmfPlusBeginContainer | `16423` | This record opens a new graphics state container and specifies a transform for it. Graphics containers are used to retain elements of the graphics state. |
| EmfPlusBeginContainerNoParams | `16424` | This record opens a new graphics state container. |
| EmfPlusEndContainer | `16425` | This record closes a graphics state container that was previously opened by a begin container operation. |
| EmfPlusSetWorldTransform | `16426` | This record defines the current world space transform in the playback device_context, according to a specified transform matrix. |
| EmfPlusResetWorldTransform | `16427` | This record resets the current world space transform to the identify matrix. |
| EmfPlusMultiplyWorldTransform | `16428` | This record multiplies the current world space by a specified transform matrix. |
| EmfPlusTranslateWorldTransform | `16429` | This record applies a translation transform to the current world space by specified horizontal and vertical distances. |
| EmfPlusScaleWorldTransform | `16430` | This record applies a scaling transform to the current world space by specified horizontal and vertical scale factors. |
| EmfPlusRotateWorldTransform | `16431` | This record rotates the current world space by a specified angle. |
| EmfPlusSetPageTransform | `16432` | This record specifies extra scaling factors for the current world space transform. |
| EmfPlusResetClip | `16433` | This record resets the current clipping region for the world space to infinity. |
| EmfPlusSetClipRect | `16434` | This record combines the current clipping region with a rectangle. |
| EmfPlusSetClipPath | `16435` | This record combines the current clipping region with a graphics path. |
| EmfPlusSetClipRegion | `16436` | This record combines the current clipping region with another graphics region. |
| EmfPlusOffsetClip | `16437` | This record applies a translation transform on the current clipping region of the world space. |
| EmfPlusDrawDriverString | `16438` | This record specifies text output with character positions. |
| EmfPlusStrokeFillPath | `16439` | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| EmfPlusSerializableObject | `16440` | This record defines an image effects parameter block that has been serialized into a data buffer. |
| EmfPlusSetTSGraphics | `16441` | This record specifies the state of a graphics device context for a terminal server. |
| EmfPlusSetTSClip | `16442` | This record specifies clipping areas in the graphics device context for a terminal server. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


