---
title: EmfPlusRecordType Enumeration
type: docs
weight: 360
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

The RecordType enumeration defines record types used in EMF+ metafiles.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | This record opens a new graphics state container and specifies a transform for it. Graphics containers are used to retain elements of the graphics state. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | This record opens a new graphics state container. |
| EMF_PLUS_CLEAR | This record clears the output <c>coordinate space</c> and initializes it with a specified background color and transparency. |
| EMF_PLUS_COMMENT | This record specifies arbitrary private data. |
| EMF_PLUS_DRAW_ARC | The record defines pen strokes for drawing an arc of an ellipse. |
| EMF_PLUS_DRAW_BEZIERS | This record defines the pen strokes for drawing a Bezier spline. |
| EMF_PLUS_DRAW_CLOSED_CURVE | This record defines the pen and strokes for drawing a closed cardinal spline. |
| EMF_PLUS_DRAW_CURVE | This record defines the pen strokes for drawing a cardinal spline. |
| EMF_PLUS_DRAW_DRIVER_STRING | This record specifies text output with character positions. |
| EMF_PLUS_DRAW_ELLIPSE | This record defines the pen strokes for drawing an ellipse. |
| EMF_PLUS_DRAW_IMAGE | This record defines a scaled [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) object (section 2.2.1.4). An image can consist of either bitmap or metafile data. |
| EMF_PLUS_DRAW_IMAGE_POINTS | This record defines a scaled EmfPlusImage object inside a parallelogram. An image can consist of either bitmap or metafile data. |
| EMF_PLUS_DRAW_LINES | This record defines the pen strokes for drawing a series of connected lines. |
| EMF_PLUS_DRAW_PATH | The record defines the pen strokes to draw the figures in a graphics path. A path is an object that defines an arbitrary sequence of lines, curves, and shapes. |
| EMF_PLUS_DRAW_PIE | This record defines pen strokes for drawing a section of an ellipse. |
| EMF_PLUS_DRAW_RECTS | This record defines the pen strokes for drawing a series of rectangles. |
| EMF_PLUS_DRAW_STRING | This record defines a text string based on a font, a layout rectangle, and a format. |
| EMF_PLUS_END_CONTAINER | This record closes a graphics state container that was previously opened by a begin container operation. |
| EMF_PLUS_END_OF_FILE | This record specifies the end of EMF+ data in the metafile. |
| EMF_PLUS_FILL_CLOSED_CURVE | This record defines how to fill the interior of a closed cardinal spline using a specified brush. |
| EMF_PLUS_FILL_ELLIPSE | This record defines how to fill the interiors of an ellipse, using a specified brush. |
| EMF_PLUS_FILL_PATH | The record defines how to fill the interiors of the figures defined in a graphics path with a specified brush. A path is an object that defines an arbitrary sequence of lines, curves, and shapes. |
| EMF_PLUS_FILL_PIE | This record defines how to fill a section of an interior section of an ellipse using a specified brush. |
| EMF_PLUS_FILL_POLYGON | This record defines the data to fill the interior of a polygon, using a specified brush. |
| EMF_PLUS_FILL_RECTS | This record defines how to fill the interiors of a series of rectangles, using a specified brush. |
| EMF_PLUS_FILL_REGION | This record defines how to fill the interior of a region using a specified brush. |
| EMF_PLUS_GET_DC | This record specifies that subsequent EMF records encountered in the metafile SHOULD be processed. EMF records cease being processed when the next EMF+ record is encountered. |
| EMF_PLUS_HEADER | This record specifies the start of EMF+ data in the metafile. It MUST be embedded in the first EMF record after the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) record ([MS-EMF] section 2.3.4.2 record). |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | This record multiplies the current world space by a specified transform matrix. |
| EMF_PLUS_MULTI_FORMAT_END | This record is reserved and MUST NOT be used. |
| EMF_PLUS_MULTI_FORMAT_SECTION | This record is reserved and MUST NOT be used. |
| EMF_PLUS_MULTI_FORMAT_START | This record is reserved and MUST NOT be used. |
| EMF_PLUS_OBJECT | This record specifies an object for use in graphics operations. |
| EMF_PLUS_OFFSET_CLIP | This record applies a translation transform on the current clipping region of the world space. |
| EMF_PLUS_RESET_CLIP | This record resets the current clipping region for the world space to infinity. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | This record resets the current world space transform to the identify matrix. |
| EMF_PLUS_RESTORE | This record restores the graphics state, identified by a specified index, from a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is defined by an [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) record (section 2.3.7.5) to save the state. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | This record rotates the current world space by a specified angle. |
| EMF_PLUS_SAVE | This record saves the graphics state, identified by a specified index, on a stack of saved graphics states. Each stack index is associated with a particular saved state, and the index is used by an [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) record (section 2.3.7.4) to restore the state. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | This record applies a scaling transform to the current world space by specified horizontal and vertical scale factors. |
| EMF_PLUS_SERIALIZABLE_OBJECT | This record defines an image effects parameter block that has been serialized into a data buffer. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | This record defines whether to enable or disable text anti-aliasing. Text anti-aliasing is a method of making lines and edges of character glyphs appear smoother when drawn on an output surface. |
| EMF_PLUS_SET_CLIP_PATH | This record combines the current clipping region with a graphics path. |
| EMF_PLUS_SET_CLIP_RECT | This record combines the current clipping region with a rectangle. |
| EMF_PLUS_SET_CLIP_REGION | This record combines the current clipping region with another graphics region. |
| EMF_PLUS_SET_COMPOSITING_MODE | This record defines the compositing mode according to the state of alpha blending, which specifies how source colors are combined with background colors. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | This record defines the compositing quality, which describes the desired level of quality for creating composite images from multiple objects. |
| EMF_PLUS_SET_INTERPOLATION_MODE | This record defines the interpolation mode of an object according to the specified type of image filtering. The interpolation mode influences how scaling (stretching and shrinking) is performed. |
| EMF_PLUS_SET_PAGE_TRANSFORM | This record specifies extra scaling factors for the current world space transform. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | This record defines the pixel offset mode according to the specified pixel centering value. |
| EMF_PLUS_SET_RENDERING_ORIGIN | This record defines the origin of rendering to the specified horizontal and vertical coordinates. This applies to hatch brushes and to 8 and 16 bits per pixel dither patterns. |
| EMF_PLUS_SET_TEXT_CONTRAST | This record sets text contrast according to the specified text gamma value. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | This record defines the process used for rendering text. |
| EMF_PLUS_SET_TS_CLIP | This record specifies clipping areas in the graphics device context for a terminal server. |
| EMF_PLUS_SET_TS_GRAPHICS | This record specifies the state of a graphics device context for a terminal server. |
| EMF_PLUS_SET_WORLD_TRANSFORM | This record defines the current world space transform in the playback device_context, according to a specified transform matrix. |
| EMF_PLUS_STROKE_FILL_PATH | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | This record applies a translation transform to the current world space by specified horizontal and vertical distances. |
