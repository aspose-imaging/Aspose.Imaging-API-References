---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging for .NET API Reference
description: The namespace contains types [MS-EMF] Enhanced Metafile Format. 2.3 EMF Records
type: docs
weight: 360
url: /net/aspose.imaging.fileformats.emf.emf.records/
---
The namespace contains types [MS-EMF]: Enhanced Metafile Format. 2.3 EMF Records

## Classes

| Class | Description |
| --- | --- |
| class [EmfAbortPath](./emfabortpath) | This record aborts a path bracket or discards the path from a closed path bracket. |
| class [EmfAlphaBlend](./emfalphablend) | The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation. |
| class [EmfAngleArc](./emfanglearc) | The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles |
| class [EmfArc](./emfarc) | The EMR_ARC record specifies an elliptical arc. |
| class [EmfArcTo](./emfarcto) | The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc. |
| class [EmfBeginPath](./emfbeginpath) | This record opens a path bracket in the current playback device context. After a path bracket is open, an application can begin processing records to define the points that lie in the path.An application MUST close an open path bracket by processing the EMR_ENDPATH record. When an application processes the EMR_BEGINPATH record, all previous paths MUST be discarded from the playback device context. |
| class [EmfBitBlt](./emfbitblt) | The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation. |
| abstract class [EmfBitmapRecordType](./emfbitmaprecordtype) | The bitmap record types perform block transfers of bitmap images. |
| class [EmfChord](./emfchord) | The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled by using the current brush. |
| abstract class [EmfClippingRecordType](./emfclippingrecordtype) | The clipping record types specify and manage clipping regions. Note The EMR_SETMETARGN record does not specify parameters. |
| class [EmfCloseFigure](./emfclosefigure) | This record closes an open figure in a path. Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure, and then it MUST connect the lines by using the line join style.If a figure is closed by processing the EMR_LINETO record instead of the EMR_CLOSEFIGURE record, end caps are used to create the corner instead of a join.EMR_LINETO is specified in section 2.3.5.13. The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record. |
| class [EmfColorCorrectPalette](./emfcolorcorrectpalette) | The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette object using WCS 1.0 values. |
| class [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters. |
| class [EmfComment](./emfcomment) | The EMR_COMMENT record contains arbitrary private data. Note Fields that are not described in this section are specified in section 2.3.3. |
| class [EmfCommentBeginGroup](./emfcommentbegingroup) | The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records. |
| class [EmfCommentEmfPlus](./emfcommentemfplus) | The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. Note Fields that are not described in this section are specified in section 2.3.3. |
| class [EmfCommentEmfSpool](./emfcommentemfspool) | The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. Note Fields that are not described in this section are specified in section 2.3.3. |
| class [EmfCommentEndGroup](./emfcommentendgroup) | The EMR_COMMENT_ENDGROUP record specifies the end of a group of drawing records. |
| class [EmfCommentMultiFormats](./emfcommentmultiformats) | The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats. |
| abstract class [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing. |
| abstract class [EmfCommentRecordType](./emfcommentrecordtype) | The comment record types define formats for specifying arbitrary private data, embedding records in other metafile formats, and adding new or special-purpose commands. |
| class [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile. |
| abstract class [EmfControlRecordType](./emfcontrolrecordtype) | The control record types define the start and end of an EMF metafile and properties of the metafile. |
| class [EmfCreateBrushIndirect](./emfcreatebrushindirect) | The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations. |
| class [EmfCreateColorSpace](./emfcreatecolorspace) | The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a name consisting of ASCII characters. |
| class [EmfCreateColorSpaceW](./emfcreatecolorspacew) | The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with a name consisting of Unicode characters. |
| class [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The pattern is specified by a DIB. |
| class [EmfCreateMonoBrush](./emfcreatemonobrush) | The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations. The pattern is specified by a monochrome DIB. |
| class [EmfCreatePalette](./emfcreatepalette) | The EMR_CREATEPALETTE record defines a logical palette for graphics operations. |
| class [EmfCreatePen](./emfcreatepen) | The EMR_CREATEPEN record defines a logical pen for graphics operations. |
| class [EmfDeleteColorSpace](./emfdeletecolorspace) | The EMR_DELETECOLORSPACE record deletes a logical color space object. |
| class [EmfDeleteObject](./emfdeleteobject) | The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1). |
| class [EmfDrawEscape](./emfdrawescape) | The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the information will result in drawing being done. |
| abstract class [EmfDrawingRecordType](./emfdrawingrecordtype) | The drawing record types perform graphics drawing. |
| class [EmfEllipse](./emfellipse) | The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush. |
| class [EmfEndPath](./emfendpath) | This record closes a path bracket and selects the path defined by the bracket into the playback device context. |
| class [EmfEof](./emfeof) | The EMR_EOF record indicates the end of the metafile and specifies a palette. |
| abstract class [EmfEscapeRecordType](./emfescaperecordtype) | The escape record types execute printer driver functions. |
| class [EmfExcludeClipRect](./emfexcludecliprect) | The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing clipping region minus the specified rectangle. Note Fields that are not described in this section are specified in section 2.3.2. |
| class [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations. |
| class [EmfExtCreatePen](./emfextcreatepen) | The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An optional DIB can be specified to use as the line style. |
| class [EmfExtEscape](./emfextescape) | The EMR_EXTESCAPE record passes arbitrary information to a printer driver. The intent is that the information will not result in drawing being done. |
| class [EmfExtFloodFill](./emfextfloodfill) | The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush |
| class [EmfExtSelectClipRgn](./emfextselectcliprgn) | The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region using the specified mode. Note Fields that are not described in this section are specified in section 2.3.2. |
| class [EmfExtTextOutA](./emfexttextouta) | The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors. |
| class [EmfExtTextOutW](./emfexttextoutw) | The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors. |
| class [EmfFillPath](./emffillpath) | The EMR_FILLPATH record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode. |
| class [EmfFillRgn](./emffillrgn) | The EMR_FILLRGN record fills the specified region by using the specified brush. |
| class [EmfFlatternPath](./emfflatternpath) | This record transforms any curves in the selected path into the playback device context; each curve MUST be turned into a sequence of lines. |
| class [EmfForceUfiMapping](./emfforceufimapping) | The EMR_FORCEUFIMAPPING record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont (section 2.2.13) information. |
| class [EmfFrameRgn](./emfframergn) | The EMR_FRAMERGN record draws a border around the specified region using the specified brush. |
| class [EmfGlsBoundedRecord](./emfglsboundedrecord) | The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output. |
| class [EmfGlsRecord](./emfglsrecord) | The EMR_GLSRECORD record specifies an OpenGL function. |
| class [EmfGradientFill](./emfgradientfill) | The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color. |
| class [EmfIntersectClipRect](./emfintersectcliprect) | The EMR_INTERSECTCLIPRECT record specifies a new clipping region from the intersection of the current clipping region and the specified rectangle. Note Fields that are not described in this section are specified in section 2.3.2. |
| class [EmfInvertRgn](./emfinvertrgn) | The EMR_INVERTRGN record inverts the colors in the specified region. |
| class [EmfLineTo](./emflineto) | The EMR_LINETO record specifies a line from the current position up to, but not including, the specified point.It resets the current position to the specified point. |
| class [EmfMaskBlt](./emfmaskblt) | The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations. |
| class [EmfMetafileHeader](./emfmetafileheader) | The EMR_HEADER record types define the starting points of EMF metafiles and specify properties of the device on which the image in the metafile was created. The information in the header record makes it possible for EMF metafiles to be independent of any specific output device. The value of the Size field can be used to distinguish between the different EMR_HEADER record types listed earlier in this section. There are three possible headers: The base header, which is the EmfMetafileHeader record. The fixed-size part of this header is 88 bytes, and it contains a Header object. The first extension header, which is the EmfMetafileHeaderExtension1 record. The fixed-size part of this header is 100 bytes, and it contains a Header object and a HeaderExtension1 object (section 2.2.10). The second extension header, which is the EmfMetafileHeaderExtension2 record. The fixed-size part of this header is 108 bytes, and it contains a Header object, a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11). |
| class [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles. Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order. |
| class [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and can be present in any order. |
| class [EmfModifyWorldTransform](./emfmodifyworldtransform) | The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context. |
| class [EmfMoveToEx](./emfmovetoex) | The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units. |
| class [EmfNamedEscape](./emfnamedescape) | The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver. |
| abstract class [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | The object creation record types create graphics objects. |
| abstract class [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | The object manipulation record types manage and modify graphics objects. |
| class [EmfOffsetClipRgn](./emfoffsetcliprgn) | The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context by the specified offsets. |
| abstract class [EmfOpenGlRecordType](./emfopenglrecordtype) | The OpenGL record types specify OpenGL functions. |
| class [EmfPaintRgn](./emfpaintrgn) | The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the playback device context. |
| abstract class [EmfPathBracketRecordType](./emfpathbracketrecordtype) | The path bracket record types specify and manipulate paths in path brackets. Note: None of the path bracket records specify parameters. |
| class [EmfPie](./emfpie) | The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the current pen and filled by using the current brush. |
| class [EmfPixelFormat](./emfpixelformat) | The EMR_PIXELFORMAT record specifies the pixel format to use for graphics operations. |
| class [EmfPlgBlt](./emfplgblt) | The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap. |
| class [EmfPolyBezier](./emfpolybezier) | The EMR_POLYBEZIER record specifies one or more Bezier curves. |
| class [EmfPolyBezier16](./emfpolybezier16) | The EMR_POLYBEZIER16 record specifies one or more Bezier curves. The curves are drawn using the current pen. |
| class [EmfPolyBezierTo](./emfpolybezierto) | The EMR_POLYBEZIERTO record specifies one or more Bezier curves based upon the current position. |
| class [EmfPolyBezierTo16](./emfpolybezierto16) | The EMR_POLYBEZIERTO16 record specifies one or more Bezier curves based on the current position. |
| class [EmfPolyDraw](./emfpolydraw) | The EMR_POLYDRAW record specifies a set of line segments and Bezier curves. |
| class [EmfPolyDraw16](./emfpolydraw16) | The EMR_POLYDRAW16 record specifies a set of line segments and Bezier curves. |
| class [EmfPolygon](./emfpolygon) | The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines. |
| class [EmfPolygon16](./emfpolygon16) | The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first. |
| class [EmfPolyline](./emfpolyline) | The EMR_POLYLINE record specifies a series of line segments by connecting the points in the specified array. |
| class [EmfPolyline16](./emfpolyline16) | The EMR_POLYLINE16 record specifies a series of line segments by connecting the points in the specified array. |
| class [EmfPolylineTo](./emfpolylineto) | The EMR_POLYLINETO record specifies one or more straight lines based upon the current position. |
| class [EmfPolylineTo16](./emfpolylineto16) | The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the aPoints field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by aPoints. |
| class [EmfPolyPolygon](./emfpolypolygon) | The EMR_POLYPOLYGON record specifies a series of closed polygons. |
| class [EmfPolyPolygon16](./emfpolypolygon16) | The EMR_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn by this record can overlap. |
| class [EmfPolyPolyline](./emfpolypolyline) | The EMR_POLYPOLYLINE record specifies multiple series of connected line segments. |
| class [EmfPolyPolyline16](./emfpolypolyline16) | The EMR_POLYPOLYLINE16 record specifies multiple series of connected line segments. |
| class [EmfPolyTextOutA](./emfpolytextouta) | The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors. |
| class [EmfPolyTextOutW](./emfpolytextoutw) | The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors. |
| class [EmfRealizePalette](./emfrealizepalette) | This record maps palette entries from the current LogPalette object (section 2.2.17) to the system_palette. This EMF record specifies no parameters. |
| class [EmfRecord](./emfrecord) | Base class for EMF records All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the generic structures of the preceding EMF record types by including AlignmentPadding fields where appropriate at the ends of these structures. The contents of AlignmentPadding fields MUST always be ignored. For brevity, these fields are not shown in every individual EMF record definition. |
| class [EmfRectangle](./emfrectangle) | The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush. |
| class [EmfResizePalette](./emfresizepalette) | The EMR_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object (section 2.2.17). |
| class [EmfRestoreDc](./emfrestoredc) | The EMR_RESTOREDC record restores the playback device context to the specified state. The playback device context is restored by popping state information off a stack that was created by prior EMR_SAVEDC records (section 2.3.11). |
| class [EmfRop4](./emfrop4) | A quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. These values define how the color data of the source rectangle is to be combined with the color data of the destination rectangle. |
| class [EmfRoundRect](./emfroundrect) | The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined by using the current pen and filled by using the current brush. |
| class [EmfSaveDc](./emfsavedc) | Saves the current state of playback device context on a stack of states saved by preceding EMR_SAVEDC records, if any. The state consists of graphics properties and objects, including the currently selected bitmap, brush, palette, font, pen, and region. An EMR_RESTOREDC record is used to restore the state. This EMF record specifies no parameters. |
| class [EmfScaleViewportExtex](./emfscaleviewportextex) | The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the ratios formed by the specified multiplicands and divisors. |
| class [EmfScaleWindowExtex](./emfscalewindowextex) | The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by using the ratios formed by the specified multiplicands and divisors. |
| class [EmfSelectClipPath](./emfselectclippath) | The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback device context, combining the new region with any existing clipping region using the specified mode. |
| class [EmfSelectObject](./emfselectobject) | The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its value from the StockObject enumeration(section 2.1.31). |
| class [EmfSelectPalette](./emfselectpalette) | The EMR_SELECTPALETTE record specifies a logical palette for the playback device context. |
| class [EmfSetArcDirection](./emfsetarcdirection) | The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output. |
| class [EmfSetBkColor](./emfsetbkcolor) | The EMR_SETBKCOLOR record specifies the background color. |
| class [EmfSetBkMode](./emfsetbkmode) | The EMR_SETBKMODE record specifies the background mix mode of the playback device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines. |
| class [EmfSetBrushOrgEx](./emfsetbrushorgex) | The EMR_SETBRUSHORGEX record specifies the origin of the current brush. |
| class [EmfSetColorAdjustment](./emfsetcoloradjustment) | The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback device context. |
| class [EmfSetColorSpace](./emfsetcolorspace) | The EMR_SETCOLORSPACE record defines the current logical color space object for graphics operations. |
| class [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle. |
| class [EmfSetIcmMode](./emfseticmmode) | The EMR_SETICMMODE record specifies the mode of Image Color Management (ICM) for graphics operations. |
| class [EmfSetIcmProfileA](./emfseticmprofilea) | The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output. |
| class [EmfSetIcmProfileW](./emfseticmprofilew) | The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output. |
| class [EmfSetLayout](./emfsetlayout) | The EMR_SETLAYOUT record specifies the order in which text and graphics are drawn. |
| class [EmfSetLinkedUfis](./emfsetlinkedufis) | The EMR_SETLINKEDUFIS record sets the UniversalFontIds (section 2.2.27) of the linked fonts to use during character lookup. |
| class [EmfSetMapMode](./emfsetmapmode) | The EMR_SETMAPMODE record specifies the mapping mode of the playback device context. The mapping mode specifies the unit of measure used to transform page space units into device space units, and also specifies the orientation of the device's x-axis and y-axis. |
| class [EmfSetMapperFlags](./emfsetmapperflags) | The EMR_SETMAPPERFLAGS record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper. |
| class [EmfSetMetaRgn](./emfsetmetargn) | Inter sets the current meta region with the current clipping region to form a new meta region for the playback device context. The current clipping region SHOULD be reset to null. This EMF record specifies no parameters. |
| class [EmfSetMiterLimit](./emfsetmiterlimit) | The EMR_SETMITERLIMIT record specifies the limit for the length of miter joins for the playback device context. |
| class [EmfSetPaletteEntries](./emfsetpaletteentries) | The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing LogPalette (section 2.2.17) object. |
| class [EmfSetPixelV](./emfsetpixelv) | The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates. |
| class [EmfSetPolyFillMode](./emfsetpolyfillmode) | The EMR_SETPOLYFILLMODE record defines polygon fill mode. |
| class [EmfSetRop2](./emfsetrop2) | The EMR_SETROP2 record defines a binary raster operation mode. |
| class [EmfSetStrechBltMode](./emfsetstrechbltmode) | The EMR_SETSTRETCHBLTMODE record specifies bitmap stretch mode. |
| class [EmfSetTextAlign](./emfsettextalign) | The EMR_SETTEXTALIGN record specifies text alignment. |
| class [EmfSetTextColor](./emfsettextcolor) | The EMR_SETTEXTCOLOR record defines the current text color. |
| class [EmfSetTextJustification](./emfsettextjustification) | The EMR_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break characters for text justification. |
| class [EmfSetViewportExtEx](./emfsetviewportextex) | The EMR_SETVIEWPORTEXTEX record defines the viewport extent. |
| class [EmfSetViewportOrgEx](./emfsetviewportorgex) | The EMR_SETVIEWPORTORGEX record defines the viewport origin. |
| class [EmfSetWindowExtEx](./emfsetwindowextex) | The EMR_SETWINDOWEXTEX record defines the window extent. |
| class [EmfSetWindowOrgEx](./emfsetwindoworgex) | The EMR_SETWINDOWORGEX record defines the window origin. |
| class [EmfSetWorldTransform](./emfsetworldtransform) | The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context. |
| class [EmfSmallTextOut](./emfsmalltextout) | The EMR_SMALLTEXTOUT record outputs a string. |
| abstract class [EmfStateRecordType](./emfstaterecordtype) | The state record types specify and manage graphics properties that define the state of the playback device context. |
| class [EmfStretchBlt](./emfstretchblt) | The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| class [EmfStretchDiBits](./emfstretchdibits) | The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| class [EmfStrokeAndFillPath](./emfstrokeandfillpath) | The EMR_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| class [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH class |
| abstract class [EmfTransformRecordType](./emftransformrecordtype) | The transform record types specify and modify world-space to page-space transforms. |
| class [EmfTransparentBlt](./emftransparentblt) | The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary |
| class [EmfVertexData](./emfvertexdata) | Objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them. |
| class [EmfWidenPath](./emfwidenpath) | This record redefines the current path as the area that would be painted if the path were drawn using the pen currently selected into the playback device context. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
