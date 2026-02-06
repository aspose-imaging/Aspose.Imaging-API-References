---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging for .NET API Reference
description: The namespace contains types MSEMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 430
url: /net/aspose.imaging.fileformats.emf.emfplus.records/
---
The namespace contains types [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Classes

| Class | Description |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer/) | The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams/) | The EmfPlusBeginContainerNoParams record opens a new graphics state container. |
| [EmfPlusClear](./emfplusclear/) | The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype/) | The clipping record types specify clipping regions and operations. |
| [EmfPlusComment](./emfpluscomment/) | The EmfPlusComment record specifies arbitrary private data. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype/) | The control record types specify global parameters for EMF+ metafile processing. |
| [EmfPlusDrawArc](./emfplusdrawarc/) | The EmfPlusDrawArc record specifies drawing the arc of an ellipse. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers/) | The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. The order for Bezier data points is the start point, control point 1, control point 2 and end point. For more information see [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve/) | The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline |
| [EmfPlusDrawCurve](./emfplusdrawcurve/) | The EmfPlusDrawCurve record specifies drawing a cardinal spline NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring/) | The EmfPlusDrawDriverString record specifies text output with character positions. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse/) | The EmfPlusDrawEllipse record specifies drawing an ellipse. |
| [EmfPlusDrawImage](./emfplusdrawimage/) | The EmfPlusDrawImage record specifies drawing a scaled image. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints/) | The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype/) | The drawing record types specify graphics output. |
| [EmfPlusDrawLines](./emfplusdrawlines/) | The EmfPlusDrawlLines record specifies drawing a series of connected lines |
| [EmfPlusDrawPath](./emfplusdrawpath/) | The EmfPlusDrawPath record specifies drawing a graphics path. |
| [EmfPlusDrawPie](./emfplusdrawpie/) | The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse. |
| [EmfPlusDrawRects](./emfplusdrawrects/) | The EmfPlusDrawRects record specifies drawing a series of rectangles |
| [EmfPlusDrawString](./emfplusdrawstring/) | The EmfPlusDrawString record specifies text output with string formatting |
| [EmfPlusEndContainer](./emfplusendcontainer/) | The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation. |
| [EmfPlusEndOfFile](./emfplusendoffile/) | The EmfPlusEndOfFile record specifies the end of EMF+ data in the metafile. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve/) | The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline |
| [EmfPlusFillEllipse](./emfplusfillellipse/) | The EmfPlusFillEllipse record specifies filling the interior of an ellipse |
| [EmfPlusFillPath](./emfplusfillpath/) | Fill path record FLAGS: 16-bit unsigned integer that provides information about how the operation is to be performed, and about the structure of the record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (1 bit): This bit indicates the type of data in the BrushId field. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. X (1 bit): Reserved and MUST be ignored. ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive. |
| [EmfPlusFillPie](./emfplusfillpie/) | The EmfPlusFillPie record specifies filling a section of the interior of an ellipse |
| [EmfPlusFillPolygon](./emfplusfillpolygon/) | The EmfPlusFillPolygon record specifies filling the interior of a polygon. |
| [EmfPlusFillRects](./emfplusfillrects/) | The EmfPlusFillRects record specifies filling the interiors of a series of rectangles |
| [EmfPlusFillRegion](./emfplusfillregion/) | The EmfPlusFillRegion record specifies filling the interior of a graphics region |
| [EmfPlusGetDc](./emfplusgetdc/) | The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed. |
| [EmfPlusHeader](./emfplusheader/) | The EmfPlusHeader record specifies the start of EMF+ data in the metafile. The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record, which MUST be the record immediately following the EMF header in the metafile. The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform/) | The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a specified transform matrix. |
| [EmfPlusObject](./emfplusobject/) | The EmfPlusObject record specifies an object for use in graphics operations. The object definition can span multiple records, which is indicated by the value of the Flags field. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype/) | The Object Record Types define reusable graphics objects. |
| [EmfPlusOffsetClip](./emfplusoffsetclip/) | The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space. The new current clipping region is set to the result of the translation transform. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype/) | The Property Record Types specify properties of the playback device context. |
| [EmfPlusRecord](./emfplusrecord/) | The Emf+ base record type. |
| [EmfPlusResetClip](./emfplusresetclip/) | The EmfPlusResetClip record resets the current clipping region for the world space to infinity. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform/) | The EmfPlusResetWorldTransform record resets the current world space transform to the identify matrix. |
| [EmfPlusRestore](./emfplusrestore/) | The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform/) | The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform. |
| [EmfPlusSave](./emfplussave/) | The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform/) | The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform. |
| [EmfPlusSerializableObject](./emfplusserializableobject/) | The EmfPlusSerializableObject record defines an image effects parameter block that has been serialized into a data buffer. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode/) | The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output. |
| [EmfPlusSetClipPath](./emfplussetclippath/) | The EmfPlusSetClipPath record combines the current clipping region with a graphics path. The new current clipping region is set to the result of the CombineMode operation. |
| [EmfPlusSetClipRect](./emfplussetcliprect/) | The EmfPlusSetClipRect record combines the current clipping region with a rectangle. |
| [EmfPlusSetClipRegion](./emfplussetclipregion/) | The EmfPlusSetClipRegion record combines the current clipping region with another graphics region. The new current clipping region is set to the result of performing the CombineMode operation on the previous current clipping region and the specified EmfPlusRegion object. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode/) | The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality/) | The EmfPlusSetCompositingQuality record specifies the desired level of quality for creating composite images from multiple objects. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode/) | The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform/) | The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space coordinates to device space coordinates. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode/) | The EmfPlusSetPixelOffsetMode record specifies how pixels are centered with respect to the coordinates of the drawing surface. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin/) | The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast/) | The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint/) | The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing. |
| [EmfPlusSetTsClip](./emfplussettsclip/) | The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics/) | The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform/) | The EmfPlusSetWorldTransform record sets the world transform according to the values in a specified transform matrix. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype/) | The State Record Types specify operations on the state of the playback device context. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype/) | The Terminal Server Record Types specify graphics processing on a terminal server. The following are EMF+ terminal server record types. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype/) | The Transform Record Types specify properties and transforms on coordinate spaces. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform/) | The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform. |


