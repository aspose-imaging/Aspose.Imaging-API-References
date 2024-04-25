---
title: EmfPlusRecordType
second_title: Aspose.Imaging for Java API Reference
description: The RecordType enumeration defines record types used in EMF metafiles.
type: docs
weight: 45
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

The RecordType enumeration defines record types used in EMF+ metafiles.
## Fields

| Field | Description |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | This record specifies the start of EMF+ data in the metafile. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | This record specifies the end of EMF+ data in the metafile. |
| [EmfPlusComment](#EmfPlusComment) | This record specifies arbitrary private data. |
| [EmfPlusGetDC](#EmfPlusGetDC) | This record specifies that subsequent EMF records encountered in the metafile SHOULD be processed. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | This record is reserved and MUST NOT be used. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | This record is reserved and MUST NOT be used. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | This record is reserved and MUST NOT be used. |
| [EmfPlusObject](#EmfPlusObject) | This record specifies an object for use in graphics operations. |
| [EmfPlusClear](#EmfPlusClear) | This record clears the output `coordinate space` and initializes it with a specified background color and transparency. |
| [EmfPlusFillRects](#EmfPlusFillRects) | This record defines how to fill the interiors of a series of rectangles, using a specified brush. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | This record defines the pen strokes for drawing a series of rectangles. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | This record defines the data to fill the interior of a polygon, using a specified brush. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | This record defines the pen strokes for drawing a series of connected lines. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | This record defines how to fill the interiors of an ellipse, using a specified brush. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | This record defines the pen strokes for drawing an ellipse. |
| [EmfPlusFillPie](#EmfPlusFillPie) | This record defines how to fill a section of an interior section of an ellipse using a specified brush. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | This record defines pen strokes for drawing a section of an ellipse. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | The record defines pen strokes for drawing an arc of an ellipse. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | This record defines how to fill the interior of a region using a specified brush. |
| [EmfPlusFillPath](#EmfPlusFillPath) | The record defines how to fill the interiors of the figures defined in a graphics path with a specified brush. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | The record defines the pen strokes to draw the figures in a graphics path. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | This record defines how to fill the interior of a closed cardinal spline using a specified brush. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | This record defines the pen and strokes for drawing a closed cardinal spline. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | This record defines the pen strokes for drawing a cardinal spline. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | This record defines the pen strokes for drawing a Bezier spline. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | This record defines a scaled [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) object (section 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | This record defines a scaled EmfPlusImage object inside a parallelogram. |
| [EmfPlusDrawString](#EmfPlusDrawString) | This record defines a text string based on a font, a layout rectangle, and a format. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | This record defines the origin of rendering to the specified horizontal and vertical coordinates. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | This record defines whether to enable or disable text anti-aliasing. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | This record defines the process used for rendering text. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | This record sets text contrast according to the specified text gamma value. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | This record defines the interpolation mode of an object according to the specified type of image filtering. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | This record defines the pixel offset mode according to the specified pixel centering value. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | This record defines the compositing mode according to the state of alpha blending, which specifies how source colors are combined with background colors. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | This record defines the compositing quality, which describes the desired level of quality for creating composite images from multiple objects. |
| [EmfPlusSave](#EmfPlusSave) | This record saves the graphics state, identified by a specified index, on a stack of saved graphics states. |
| [EmfPlusRestore](#EmfPlusRestore) | This record restores the graphics state, identified by a specified index, from a stack of saved graphics states. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | This record opens a new graphics state container and specifies a transform for it. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | This record opens a new graphics state container. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | This record closes a graphics state container that was previously opened by a begin container operation. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | This record defines the current world space transform in the playback device\_context, according to a specified transform matrix. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | This record resets the current world space transform to the identify matrix. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | This record multiplies the current world space by a specified transform matrix. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | This record applies a translation transform to the current world space by specified horizontal and vertical distances. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | This record applies a scaling transform to the current world space by specified horizontal and vertical scale factors. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | This record rotates the current world space by a specified angle. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | This record specifies extra scaling factors for the current world space transform. |
| [EmfPlusResetClip](#EmfPlusResetClip) | This record resets the current clipping region for the world space to infinity. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | This record combines the current clipping region with a rectangle. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | This record combines the current clipping region with a graphics path. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | This record combines the current clipping region with another graphics region. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | This record applies a translation transform on the current clipping region of the world space. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | This record specifies text output with character positions. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | This record defines an image effects parameter block that has been serialized into a data buffer. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | This record specifies the state of a graphics device context for a terminal server. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | This record specifies clipping areas in the graphics device context for a terminal server. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


This record specifies the start of EMF+ data in the metafile. It MUST be embedded in the first EMF record after the [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) record ([MS-EMF] section 2.3.4.2 record).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


This record specifies the end of EMF+ data in the metafile.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


This record specifies arbitrary private data.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


This record specifies that subsequent EMF records encountered in the metafile SHOULD be processed. EMF records cease being processed when the next EMF+ record is encountered.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


This record is reserved and MUST NOT be used.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


This record is reserved and MUST NOT be used.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


This record is reserved and MUST NOT be used.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


This record specifies an object for use in graphics operations.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


This record clears the output `coordinate space` and initializes it with a specified background color and transparency.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


This record defines how to fill the interiors of a series of rectangles, using a specified brush.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


This record defines the pen strokes for drawing a series of rectangles.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


This record defines the data to fill the interior of a polygon, using a specified brush.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


This record defines the pen strokes for drawing a series of connected lines.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


This record defines how to fill the interiors of an ellipse, using a specified brush.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


This record defines the pen strokes for drawing an ellipse.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


This record defines how to fill a section of an interior section of an ellipse using a specified brush.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


This record defines pen strokes for drawing a section of an ellipse.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


The record defines pen strokes for drawing an arc of an ellipse.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


This record defines how to fill the interior of a region using a specified brush.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


The record defines how to fill the interiors of the figures defined in a graphics path with a specified brush. A path is an object that defines an arbitrary sequence of lines, curves, and shapes.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


The record defines the pen strokes to draw the figures in a graphics path. A path is an object that defines an arbitrary sequence of lines, curves, and shapes.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


This record defines how to fill the interior of a closed cardinal spline using a specified brush.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


This record defines the pen and strokes for drawing a closed cardinal spline.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


This record defines the pen strokes for drawing a cardinal spline.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


This record defines the pen strokes for drawing a Bezier spline.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


This record defines a scaled [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) object (section 2.2.1.4). An image can consist of either bitmap or metafile data.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


This record defines a scaled EmfPlusImage object inside a parallelogram. An image can consist of either bitmap or metafile data.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


This record defines a text string based on a font, a layout rectangle, and a format.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


This record defines the origin of rendering to the specified horizontal and vertical coordinates. This applies to hatch brushes and to 8 and 16 bits per pixel dither patterns.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


This record defines whether to enable or disable text anti-aliasing. Text anti-aliasing is a method of making lines and edges of character glyphs appear smoother when drawn on an output surface.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


This record defines the process used for rendering text.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


This record sets text contrast according to the specified text gamma value.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


This record defines the interpolation mode of an object according to the specified type of image filtering. The interpolation mode influences how scaling (stretching and shrinking) is performed.

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


This record defines the pixel offset mode according to the specified pixel centering value.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


This record defines the compositing mode according to the state of alpha blending, which specifies how source colors are combined with background colors.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


This record defines the compositing quality, which describes the desired level of quality for creating composite images from multiple objects.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


This record saves the graphics state, identified by a specified index, on a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is used by an [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) record (section 2.3.7.4) to restore the state.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


This record restores the graphics state, identified by a specified index, from a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is defined by an [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) record (section 2.3.7.5) to save the state.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


This record opens a new graphics state container and specifies a transform for it. Graphics containers are used to retain elements of the graphics state.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


This record opens a new graphics state container.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


This record closes a graphics state container that was previously opened by a begin container operation.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


This record defines the current world space transform in the playback device\_context, according to a specified transform matrix.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


This record resets the current world space transform to the identify matrix.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


This record multiplies the current world space by a specified transform matrix.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


This record applies a translation transform to the current world space by specified horizontal and vertical distances.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


This record applies a scaling transform to the current world space by specified horizontal and vertical scale factors.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


This record rotates the current world space by a specified angle.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


This record specifies extra scaling factors for the current world space transform.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


This record resets the current clipping region for the world space to infinity.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


This record combines the current clipping region with a rectangle.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


This record combines the current clipping region with a graphics path.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


This record combines the current clipping region with another graphics region.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


This record applies a translation transform on the current clipping region of the world space.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


This record specifies text output with character positions.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


This record defines an image effects parameter block that has been serialized into a data buffer.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


This record specifies the state of a graphics device context for a terminal server.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


This record specifies clipping areas in the graphics device context for a terminal server.

