---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts
second_title: Aspose.Imaging for .NET API Reference
description: The namespace contains types MSEMFPLUS Enhanced Metafile Format Plus Extensions 2.1 EMF Constants
type: docs
weight: 410
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/
---
The namespace contains types [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.1 EMF+ Constants

## Classes

| Class | Description |
| --- | --- |
| [EmfPlusImageEffectsIdentifiers](./emfplusimageeffectsidentifiers/) | The ImageEffects identifiers define standard GUIDs for specifying graphics image effects. These identifiers are used by device drivers to publish their levels of support for these effects. The identifier constants are defined using the GUID curly-braced string representation ([MS-DTYP] section 2.3.4.3). |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [EmfPlusBitmapDataType](./emfplusbitmapdatatype/) | The BitmapDataType enumeration defines types of bitmap data formats. |
| [EmfPlusBrushDataFlags](./emfplusbrushdataflags/) | The BrushData flags specify properties of graphics brushes, including the presence of optional data fields. These flags can be combined to specify multiple options. |
| [EmfPlusBrushType](./emfplusbrushtype/) | The BrushType enumeration defines types of graphics brushes, which are used to fill graphics regions. |
| [EmfPlusCombineMode](./emfpluscombinemode/) | The CombineMode enumeration defines modes for combining two graphics regions. In the following descriptions, the regions to be combined are referred to as the "existing" and "new" regions. |
| [EmfPlusCompositingMode](./emfpluscompositingmode/) | The CompositingMode enumeration defines modes for combining source colors with background colors. The compositing mode represents the enable state of alpha blending. |
| [EmfPlusCompositingQuality](./emfpluscompositingquality/) | The CompositingQuality enumeration defines levels of quality for creating composite images |
| [EmfPlusCurveAdjustments](./emfpluscurveadjustments/) | The CurveAdjustments enumeration defines adjustments that can be applied to the color curve of an image. |
| [EmfPlusCurveChannel](./emfpluscurvechannel/) | The CurveChannel enumeration defines color channels that can be affected by a color curve effect adjustment to an image. |
| [EmfPlusCustomLineCapDataFlags](./emfpluscustomlinecapdataflags/) | The CustomLineCapData flags specify data for custom line caps. These flags can be combined to specify multiple options. |
| [EmfPlusCustomLineCapDataType](./emfpluscustomlinecapdatatype/) | The CustomLineCapDataType enumeration defines types of custom line cap data, which specify styles and shapes for the ends of graphics lines. |
| [EmfPlusDashedLineCapType](./emfplusdashedlinecaptype/) | The DashedLineCapType enumeration defines types of line caps to use at the ends of dashed lines that are drawn with graphics pens. |
| [EmfPlusDriverStringOptionsFlags](./emfplusdriverstringoptionsflags/) | The DriverStringOptions flags specify properties of graphics text positioning and rendering. These flags can be combined to specify multiple options. |
| [EmfPlusFilterType](./emfplusfiltertype/) | The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering. |
| [EmfPlusFontStyleFlags](./emfplusfontstyleflags/) | The FontStyle flags specify styles of graphics font typefaces. These flags can be combined to specify multiple options. |
| [EmfPlusGraphicsVersionEnum](./emfplusgraphicsversionenum/) | The GraphicsVersion enumeration defines versions of operating system graphics that are used to create EMF+ metafiles. |
| [EmfPlusHatchStyle](./emfplushatchstyle/) | The HatchStyle enumeration defines hatch patterns used by graphics brushes. A hatch pattern consists of a solid background color and lines drawn over the background. |
| [EmfPlusHotkeyPrefix](./emfplushotkeyprefix/) | The HotkeyPrefix enumeration defines output options for hotkey prefixes in graphics text. |
| [EmfPlusImageDataType](./emfplusimagedatatype/) | The ImageDataType enumeration defines types of image data formats. |
| [EmfPlusInterpolationMode](./emfplusinterpolationmode/) | The InterpolationMode enumeration defines ways to perform scaling, including stretching and shrinking. |
| [EmfPlusLanguageIdentifierType](./emfpluslanguageidentifiertype/) | The LanguageIdentifier enumeration defines identifiers for natural languages in locales, including countries, geographical regions, and administrative districts. |
| [EmfPlusLineCapType](./emfpluslinecaptype/) | The LineCapType enumeration defines types of line caps to use at the ends of lines that are drawn with graphics pens. |
| [EmfPlusLineJoinType](./emfpluslinejointype/) | The LineJoinType enumeration defines ways to join two lines that are drawn by the same graphics pen and whose ends meet. |
| [EmfPlusLineStyle](./emfpluslinestyle/) | The LineStyle enumeration defines styles of lines that are drawn with graphics pens. |
| [EmfPlusMetafileDataType](./emfplusmetafiledatatype/) | The MetafileDataType enumeration defines types of metafiles data that can be embedded in an EMF+ metafile. |
| [EmfPlusObjectClamp](./emfplusobjectclamp/) | EmfPlusObjectClamp specifies the object clamping behavior. It is not used until this object is applied to an image being drawn. |
| [EmfPlusObjectType](./emfplusobjecttype/) | The ObjectType enumeration defines types of graphics objects that can be created and used in graphics operations. |
| [EmfPlusPaletteStyleFlags](./emfpluspalettestyleflags/) | The PaletteStyle flags specify properties of graphics palettes. These flags can be combined to specify multiple options. |
| [EmfPlusPathPointFlags](./emfpluspathpointflags/) | A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object. C (1 bit): If set, the PathPoints array specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, the PathPoints array specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag MAY be clear and MUST be ignored. R (1 bit): If set, the point types in the PathPointTypes array are specified by EmfPlusPathPointTypeRle objects (section 2.2.2.32), which use run-length encoding (RLE) compression, and/or EmfPlusPathPointType objects (section 2.2.2.31). See [MS-WMF] section 3.1.6 for more information on RLE compression. If clear, the point types in the PathPointTypes array are specified by EmfPlusPathPointType objects. P (1 bit): If set, each element in the PathPoints array specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PathPoints, a previous location at coordinates (0,0) is assumed. If clear, each element in the PathPoints array specifies an absolute location. |
| [EmfPlusPathPointTypeEnum](./emfpluspathpointtypeenum/) | The PathPointType enumeration defines types of points on a graphics path. |
| [EmfPlusPathPointTypeFlags](./emfpluspathpointtypeflags/) | The PathPointType flags specify type properties of points on graphics paths. These flags can be combined to specify multiple options. |
| [EmfPlusPenAlignment](./emfpluspenalignment/) | The PenAlignment enumeration defines the distribution of the width of the pen with respect to the line being drawn. |
| [EmfPlusPenDataFlags](./emfpluspendataflags/) | The PenData flags specify properties of graphics pens, including the presence of optional data fields. These flags can be combined to specify multiple options. |
| [EmfPlusPixelFormat](./emfpluspixelformat/) | The PixelFormat enumeration defines pixel formats that are supported in EMF+ bitmaps. |
| [EmfPlusPixelOffsetMode](./emfpluspixeloffsetmode/) | The PixelOffsetMode enumeration defines how pixels are offset, which specifies the trade-off between rendering speed and quality. |
| [EmfPlusRecordType](./emfplusrecordtype/) | The RecordType enumeration defines record types used in EMF+ metafiles. |
| [EmfPlusRegionNodeDataType](./emfplusregionnodedatatype/) | The RegionNodeDataType enumeration defines types of region node data. |
| [EmfPlusSmoothingMode](./emfplussmoothingmode/) | The SmoothingMode enumeration defines smoothing modes to apply to lines, curves, and the edges of filled areas to make them appear more continuous or sharply defined. |
| [EmfPlusStringAlignment](./emfplusstringalignment/) | The StringAlignment enumeration defines ways to align strings with respect to a text layout rectangle. |
| [EmfPlusStringDigitSubstitution](./emfplusstringdigitsubstitution/) | The StringDigitSubstitution enumeration defines ways to substitute digits in a string according to a user's locale or language. |
| [EmfPlusStringFormatFlags](./emfplusstringformatflags/) | The StringFormat flags specify options for graphics text layout, including direction, clipping and font handling. These flags can be combined to specify multiple options. |
| [EmfPlusStringTrimming](./emfplusstringtrimming/) | The StringTrimming enumeration defines how to trim characters from a string that is too large for the text layout rectangle. |
| [EmfPlusTextRenderingHint](./emfplustextrenderinghint/) | The TextRenderingHint enumeration defines types of text hinting and anti-aliasing, which affects the quality of text rendering. |
| [EmfPlusUnitType](./emfplusunittype/) | The UnitType enumeration defines units of measurement in different coordinate systems. |
| [EmfPlusWrapMode](./emfpluswrapmode/) | The WrapMode enumeration defines how the pattern from a texture or gradient brush is tiled across a shape or at shape boundaries, when it is smaller than the area being filled. |


