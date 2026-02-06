---
title: Aspose.Imaging.FileFormats.Wmf.Objects
second_title: Aspose.Imaging for .NET API Reference
description: The namespace contains types MSWMF Windows Metafile Format 2.2 WMF Objects
type: docs
weight: 770
url: /net/aspose.imaging.fileformats.wmf.objects/
---
The `namespace` contains types [MS-WMF]: Windows Metafile Format 2.2 WMF Objects

## Classes

| Class | Description |
| --- | --- |
| [WmfAnimatePalette](./wmfanimatepalette/) | The META_ANIMATEPALETTE record redefines entries in the logical palette that is defined in the playback device context with the specified Palette object (section 2.2.1.3). |
| [WmfArc](./wmfarc/) | The META_ARC record draws an elliptical arc. |
| [WmfBitBlt](./wmfbitblt/) | The META_BITBLT record specifies the transfer of a block of pixels according to a raster operation. The destination of the transfer is the current output region in the playback device context. |
| [WmfBitmap16](./wmfbitmap16/) | The Bitmap16 Object specifies information about the dimensions and color format of a bitmap. |
| [WmfBitmapBaseHeader](./wmfbitmapbaseheader/) | The base bitmap header class. |
| [WmfBitmapCoreHeader](./wmfbitmapcoreheader/) | The BitmapCoreHeader Object contains information about the dimensions and color format of a device-independent bitmap(DIB). |
| [WmfBitmapInfoHeader](./wmfbitmapinfoheader/) | The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent bitmap (DIB). |
| [WmfChord](./wmfchord/) | The META_CHORD record draws a chord, which is defined by a region bounded by the intersection of an ellipse with a line segment. The chord is outlined using the pen and filled using the brush that are defined in the playback device context. |
| [WmfCieXyzTriple](./wmfciexyztriple/) | The CIEXYZTriple Object defines information about the CIEXYZTriple color object. |
| [WmfCreateBrushInDirect](./wmfcreatebrushindirect/) | The Create brush in direct |
| [WmfCreateFontInDirect](./wmfcreatefontindirect/) | The Create font |
| [WmfCreatePalette](./wmfcreatepalette/) | The META_CREATEPALETTE record creates a Palette Object (section 2.2.1.3). |
| [WmfCreatePatternBrush](./wmfcreatepatternbrush/) | The META_CREATEPATTERNBRUSH record creates a brush object with a pattern specified by a bitmap. |
| [WmfCreatePenInDirect](./wmfcreatepenindirect/) | The create pen in direct |
| [WmfCreateRegion](./wmfcreateregion/) | The META_CREATEREGION record creates a Region Object (section 2.2.1.5). |
| [WmfDeleteObject](./wmfdeleteobject/) | The Delete object |
| [WmfDeviceIndependentBitmap](./wmfdeviceindependentbitmap/) | The DeviceIndependentBitmap Object defines an image in device-independent bitmap (DIB) format |
| [WmfDibBitBlt](./wmfdibbitblt/) | The META_DIBBITBLT record specifies the transfer of a block of pixels in device-independent format according to a raster operation. |
| [WmfDibCreatePatternBrush](./wmfdibcreatepatternbrush/) | The META_DIBCREATEPATTERNBRUSH record creates a Brush Object (section 2.2.1.1) with a pattern specified by a DeviceIndependentBitmap (DIB) Object (section 2.2.2.9). |
| [WmfDibStrechBlt](./wmfdibstrechblt/) | The META_DIBSTRETCHBLT record specifies the transfer of a block of pixels in device-independent format according to a raster operation, with possible expansion or contraction. |
| [WmfEllipse](./wmfellipse/) | The META_ELLIPSE record draws an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the pen and is filled by using the brush; these are defined in the playback device context. |
| [WmfEof](./wmfeof/) | The Eof object. |
| [WmfEscape](./wmfescape/) | The wmf escape object. |
| [WmfExcludeClipRect](./wmfexcludecliprect/) | The META_EXCLUDECLIPRECT record sets the clipping region in the playback device context to the existing clipping region minus the specified rectangle. |
| [WmfExtFloodFill](./wmfextfloodfill/) | The META_EXTFLOODFILL record fills an area with the brush that is defined in the playback device context. |
| [WmfExtTextOut](./wmfexttextout/) | Wmf ext text out |
| [WmfFillRegion](./wmffillregion/) | The META_FILLREGION record fills a region using a specified brush. |
| [WmfFloodFill](./wmffloodfill/) | The META_FLOODFILL record fills an area of the output surface with the brush that is defined in the playback device context. |
| [WmfFrameRegion](./wmfframeregion/) | The wmf frame region object. |
| [WmfGraphicObject](./wmfgraphicobject/) | The WMF Graphics Objects specify parameters for graphics output. |
| [WmfIntersectClipRect](./wmfintersectcliprect/) | The META_INTERSECTCLIPRECT record sets the clipping region in the playback device context to the intersection of the existing clipping region and the specified rectangle. |
| [WmfInvertRegion](./wmfinvertregion/) | The META_INVERTREGION record draws a region in which the colors are inverted. |
| [WmfLineTo](./wmflineto/) | The META_LINETO record draws a line from the drawing position that is defined in the playback device context up to, but not including, the specified point. |
| [WmfLogColorSpace](./wmflogcolorspace/) | The LogColorSpace object specifies a logical color space for the playback device context, which can be the name of a color profile in ASCII characters. |
| [WmfLogColorSpaceW](./wmflogcolorspacew/) | The LogColorSpaceW object specifies a logical color space, which can be defined by a color profile file with a name consisting of Unicode 16-bit characters. |
| [WmfMoveTo](./wmfmoveto/) | The META_MOVETO record sets the output position in the playback device context to a specified point. |
| [WmfObject](./wmfobject/) | The base wmf object. |
| [WmfOffsetClipRgn](./wmfoffsetcliprgn/) | The META_OFFSETCLIPRGN record moves the clipping region in the playback device context by the specified offsets. |
| [WmfOffsetViewPortOrg](./wmfoffsetviewportorg/) | The META_OFFSETVIEWPORTORG record moves the viewport origin in the playback device context by specified horizontal and vertical offsets. |
| [WmfOffsetWindowOrg](./wmfoffsetwindoworg/) | The META_OFFSETWINDOWORG record moves the output window origin in the playback device context by specified horizontal and vertical offsets. |
| [WmfPaintRegion](./wmfpaintregion/) | The META_PAINTREGION record paints the specified region by using the brush that is defined in the playback device context. |
| [WmfPatBlt](./wmfpatblt/) | The META_PATBLT record paints a specified rectangle using the brush that is defined in the playback device context. The brush color and the surface color or colors are combined using the specified raster operation. |
| [WmfPie](./wmfpie/) | The META_PIE record draws a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the pen and filled by using the brush that are defined in the playback device context. |
| [WmfPointObject](./wmfpointobject/) | The Point object. |
| [WmfPolygon](./wmfpolygon/) | The polygon object |
| [WmfPolyLine](./wmfpolyline/) | The poly line object. |
| [WmfPolyPolygon](./wmfpolypolygon/) | The PolyPolygon Object defines a series of closed polygons. |
| [WmfRealizePalette](./wmfrealizepalette/) | The META_REALIZEPALETTE record maps entries from the logical palette that is defined in the playback device context to the system palette. |
| [WmfRecord](./wmfrecord/) | The Wmf Record |
| [WmfRectangle](./wmfrectangle/) | The META_RECTANGLE record paints a rectangle. The rectangle is outlined by using the pen and filled by using the brush that are defined in the playback device context. |
| [WmfRegion](./wmfregion/) | The Region Object defines a potentially non-rectilinear shape defined by an array of scanlines. |
| [WmfResizePalette](./wmfresizepalette/) | The META_RESIZEPALETTE record redefines the size of the logical palette that is defined in the playback device context. |
| [WmfRestoreDc](./wmfrestoredc/) | The restore DC object |
| [WmfRoundRect](./wmfroundrect/) | The rectangle object. |
| [WmfSaveDc](./wmfsavedc/) | The META_SAVEDC record saves the playback device context for later retrieval. |
| [WmfScaleViewportExt](./wmfscaleviewportext/) | The META_SCALEVIEWPORTEXT record scales the horizontal and vertical extents of the viewport that is defined in the playback device context by using the ratios formed by the specified multiplicands and divisors. |
| [WmfScaleWindowExt](./wmfscalewindowext/) | The META_SCALEWINDOWEXT record scales the horizontal and vertical extents of the output window that is defined in the playback device context by using the ratios formed by specified multiplicands and divisors. |
| [WmfScanObject](./wmfscanobject/) | The Scan Object specifies a collection of scanlines. |
| [WmfSelectClipRegion](./wmfselectclipregion/) | The META_SELECTCLIPREGION record specifies a Region Object (section 2.2.1.5) to be the current clipping region. |
| [WmfSelectObject](./wmfselectobject/) | The select object. |
| [WmfSelectPalette](./wmfselectpalette/) | The META_SELECTPALETTE record defines the current logical palette with a specified Palette Object. |
| [WmfSetBkColor](./wmfsetbkcolor/) | The META_SETBKCOLOR record sets the background color in the playback device context to a specified color, or to the nearest physical color if the device cannot represent the specified color. |
| [WmfSetBkMode](./wmfsetbkmode/) | The set bk mode. |
| [WmfSetDibToDev](./wmfsetdibtodev/) | The META_SETDIBTODEV record sets a block of pixels in the playback device context using device-independent color data. The source of the color data is a DIB. |
| [WmfSetLayout](./wmfsetlayout/) | The META_SETLAYOUT record defines the layout orientation in the playback device context. The layout orientation determines the direction in which text and graphics are drawn |
| [WmfSetMapMode](./wmfsetmapmode/) | The set map mode. |
| [WmfSetMapperFlags](./wmfsetmapperflags/) | The META_SETMAPPERFLAGS record defines the algorithm that the font mapper uses when it maps logical fonts to physical fonts. |
| [WmfSetPalentries](./wmfsetpalentries/) | The META_SETPALENTRIES record defines RGB color values in a range of entries in the logical palette that is defined in the playback device context. |
| [WmfSetPixel](./wmfsetpixel/) | The META_SETPIXEL record sets the pixel at the specified coordinates to the specified color. |
| [WmfSetPolyFillMode](./wmfsetpolyfillmode/) | The set poly fill mode. |
| [WmfSetRelabs](./wmfsetrelabs/) | The META_SETRELABS record is reserved and not supported. |
| [WmfSetRop2](./wmfsetrop2/) | The set rop2 |
| [WmfSetStretchbltMode](./wmfsetstretchbltmode/) | The META_SETSTRETCHBLTMODE record defines the bitmap stretching mode in the playback device context. |
| [WmfSetTextAlign](./wmfsettextalign/) | The Set text align |
| [WmfSetTextCharExtra](./wmfsettextcharextra/) | The META_SETTEXTCHAREXTRA record defines inter-character spacing for text justification in the playback device context. Spacing is added to the white space between each character, including `break` characters, when a line of justified text is output. |
| [WmfSetTextColor](./wmfsettextcolor/) | The Set text color. |
| [WmfSetTextJustification](./wmfsettextjustification/) | The META_SETTEXTJUSTIFICATION record defines the amount of space to add to `break` characters in a string of justified text. |
| [WmfSetViewportExt](./wmfsetviewportext/) | The META_SETVIEWPORTEXT record sets the horizontal and vertical extents of the viewport in the playback device context. |
| [WmfSetViewportOrg](./wmfsetviewportorg/) | The META_SETVIEWPORTORG record defines the viewport origin in the playback device context. |
| [WmfSetWindowExt](./wmfsetwindowext/) | The set window object. |
| [WmfSetWindowOrg](./wmfsetwindoworg/) | The set window org object |
| [WmfStretchBlt](./wmfstretchblt/) | The META_STRETCHBLT record specifies the transfer of a block of pixels according to a raster operation, with possible expansion or contraction. |
| [WmfStretchDib](./wmfstretchdib/) | The wmf Stretch DIB objetc. |
| [WmfTextOut](./wmftextout/) | The META_EXTTEXTOUT record outputs text by using the font, background color, and text color that are defined in the playback device context. Optionally, dimensions can be provided for clipping, opaquing, or both. |
| [WmfUntyped](./wmfuntyped/) | The wmf untyped object |
## Structures

| Structure | Description |
| --- | --- |
| [WmfCieXyz](./wmfciexyz/) | The CIEXYZ Object defines information about the CIEXYZ chromaticity object. |
| [WmfPitchAndFamily](./wmfpitchandfamily/) | The PitchAndFamily object specifies the pitch and family properties of a Font object (section 2.2.1.2). Pitch refers to the width of the characters, and family refers to the general appearance of a font. |


