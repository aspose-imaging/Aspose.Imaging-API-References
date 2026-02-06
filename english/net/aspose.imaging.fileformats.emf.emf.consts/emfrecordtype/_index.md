---
title: Enum EmfRecordType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfRecordType enum. The RecordType enumeration defines values that uniquely identify EMF records. These values are provided in the Type field of each record
type: docs
weight: 2910
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

The RecordType enumeration defines values that uniquely identify EMF records. These values are provided in the Type field of each record.

```csharp
public enum EmfRecordType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EMR_HEADER | `1` | This record defines the start of the metafile and specifies its characteristics; its contents, including the dimensions of the embedded image; the number of records in the metafile; and the resolution of the device on which the embedded image was created. These values make it possible for the metafile to be device-independent. |
| EMR_POLYBEZIER | `2` | This record defines one or more Bezier curves. Cubic Bezier curves are defined using specified endpoints and control points, and are stroked with the current pen. |
| EMR_POLYGON | `3` | This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first. |
| EMR_POLYLINE | `4` | This record defines a series of line segments by connecting the points in the specified array. |
| EMR_POLYBEZIERTO | `5` | This record defines one or more Bezier curves based upon the current position. |
| EMR_POLYLINETO | `6` | This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by points. |
| EMR_POLYPOLYLINE | `7` | This record defines multiple series of connected line segments. The line segments are drawn by using the current pen. The figures formed by the segments are not filled. T he current position is neither used nor updated by this record. |
| EMR_POLYPOLYGON | `8` | This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons defined by this record can overlap. |
| EMR_SETWINDOWEXTEX | `9` | This record defines the window extent. |
| EMR_SETWINDOWORGEX | `10` | This record defines the window origin. |
| EMR_SETVIEWPORTEXTEX | `11` | This record defines the viewport extent. |
| EMR_SETVIEWPORTORGEX | `12` | This record defines the viewport origin. |
| EMR_SETBRUSHORGEX | `13` | This record defines the origin of the current brush. |
| EMR_EOF | `14` | This record indicates the end of the metafile. |
| EMR_SETPIXELV | `15` | This record defines the color of the pixel at the specified logical coordinates. |
| EMR_SETMAPPERFLAGS | `16` | This record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper. |
| EMR_SETMAPMODE | `17` | This record defines the mapping mode of the playback device context. The mapping mode defines the unit of measure used to transform page space units into device space units, and also defines the orientation of the device's x-axis and y-axis. |
| EMR_SETBKMODE | `18` | This record defines the background mix mode of the playback device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines. |
| EMR_SETPOLYFILLMODE | `19` | This record defines polygon fill mode. |
| EMR_SETROP2 | `20` | This record defines binary raster operation mode. |
| EMR_SETSTRETCHBLTMODE | `21` | This record defines bitmap stretch mode. |
| EMR_SETTEXTALIGN | `22` | This record defines text alignment. |
| EMR_SETCOLORADJUSTMENT | `23` | This record defines the color adjustment values for the playback device context using the specified values. |
| EMR_SETTEXTCOLOR | `24` | This record defines the current text color. |
| EMR_SETBKCOLOR | `25` | This record defines the background color. |
| EMR_OFFSETCLIPRGN | `26` | This record redefines the clipping region of the playback device context by the specified offsets. |
| EMR_MOVETOEX | `27` | This record defines coordinates of the new current position, in logical units. |
| EMR_SETMETARGN | `28` | This record intersects the current clipping region for the playback device context with the current meta region and saves the combined region as the new meta region. The clipping region is reset to a null region. |
| EMR_EXCLUDECLIPRECT | `29` | This record defines a new clipping region that consists of the existing clipping region minus the specified rectangle. |
| EMR_INTERSECTCLIPRECT | `30` | This record defines a new clipping region from the intersection of the current clipping region and the specified rectangle. |
| EMR_SCALEVIEWPORTEXTEX | `31` | This record redefines the viewport for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| EMR_SCALEWINDOWEXTEX | `32` | This record redefines the window for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| EMR_SAVEDC | `33` | This record saves the current state of the playback device context by copying data describing selected objects and graphic modes—including the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode—to a stack of saved device contexts. |
| EMR_RESTOREDC | `34` | This record restores the playback device context to the specified saved state. The playback device context is restored by popping state information off a stack of saved device contexts created by earlier EMR_SAVEDC (section 2.3.11) records. |
| EMR_SETWORLDTRANSFORM | `35` | This record defines a two-dimensional linear transformation between world space and page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. This transformation can be used to scale, rotate, shear, or translate graphics output. |
| EMR_MODIFYWORLDTRANSFORM | `36` | This record redefines the world transformation for the playback device context using the specified mode. |
| EMR_SELECTOBJECT | `37` | This record adds an object to the playback device context, identifying it by its index in the EMF Object Table (section 3.1.1.1). |
| EMR_CREATEPEN | `38` | This record defines a logical pen that has the specified style, width, and color. The pen can subsequently be selected into the playback device context and used to draw lines and curves. |
| EMR_CREATEBRUSHINDIRECT | `39` | This record defines a logical brush for figure filling in graphics operations. |
| EMR_DELETEOBJECT | `40` | This record deletes a graphics object, clearing its index in the EMF Object Table. If the deleted object is selected in the playback device context, the default object for that context property MUST be restored. |
| EMR_ANGLEARC | `41` | This record defines a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles. |
| EMR_ELLIPSE | `42` | This record defines an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush. |
| EMR_RECTANGLE | `43` | This record defines a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush. |
| EMR_ROUNDRECT | `44` | This record defines a rectangle with rounded corners. The rectangle is outlined by using the current pen and filled by using the current brush. |
| EMR_ARC | `45` | This record defines an elliptical arc. |
| EMR_CHORD | `46` | This record defines a chord (a region bounded by the intersection of an ellipse and a line segment, called a secant). The chord is outlined by using the current pen and filled by using the current brush. |
| EMR_PIE | `47` | This record defines a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the current pen and filled by using the current brush. |
| EMR_SELECTPALETTE | `48` | This record adds a LogPalette (section 2.2.17) object to the playback device context, identifying it by its index in the EMF Object Table. |
| EMR_CREATEPALETTE | `49` | This record defines a LogPalette object. |
| EMR_SETPALETTEENTRIES | `50` | This record defines RGB (red-green-blue) color values in a range of entries in a LogPalette object. |
| EMR_RESIZEPALETTE | `51` | This record increases or decreases the size of a logical palette. |
| EMR_REALIZEPALETTE | `52` | This record maps entries from the current logical palette to the system palette. |
| EMR_EXTFLOODFILL | `53` | This record fills an area of the display surface with the current brush. |
| EMR_LINETO | `54` | This record defines a line from the current position up to, but not including, the specified point. It resets the current position to the specified point. |
| EMR_ARCTO | `55` | This record defines an elliptical arc. It resets the current position to the end point of the arc. |
| EMR_POLYDRAW | `56` | This record defines a set of line segments and Bezier curves. |
| EMR_SETARCDIRECTION | `57` | This record defines the drawing direction to be used for arc and rectangle operations. |
| EMR_SETMITERLIMIT | `58` | This record defines the limit for the length of miter joins for the playback device context. |
| EMR_BEGINPATH | `59` | This record opens a path bracket in the playback device context. |
| EMR_ENDPATH | `60` | This record closes a path bracket and selects the path defined by the bracket into the playback device context. |
| EMR_CLOSEFIGURE | `61` | This record closes an open figure in a path. |
| EMR_FILLPATH | `62` | This record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode. |
| EMR_STROKEANDFILLPATH | `63` | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| EMR_STROKEPATH | `64` | This record renders the specified path by using the current pen. |
| EMR_FLATTENPATH | `65` | This record transforms any curve in the path that is selected into the playback device context, turning each curve into a sequence of lines. |
| EMR_WIDENPATH | `66` | This record redefines the current path as the area that would be painted if the path were stroked using the pen currently selected into the playback device context. |
| EMR_SELECTCLIPPATH | `67` | This record defines the current path as a clipping region for the playback device context, combining the new region with any existing clipping region using the specified mode. |
| EMR_ABORTPATH | `68` | This record aborts a path bracket or discards the path from a closed path bracket. |
| EMR_COMMENT | `70` | This record specifies arbitrary private data. |
| EMR_FILLRGN | `71` | This record fills the specified region by using the specified brush. |
| EMR_FRAMERGN | `72` | This record draws a border around the specified region using the specified brush. |
| EMR_INVERTRGN | `73` | This record inverts the colors in the specified region. |
| EMR_PAINTRGN | `74` | This record paints the specified region by using the brush currently selected into the playback device context. |
| EMR_EXTSELECTCLIPRGN | `75` | This record combines the specified region with the current clip region using the specified mode. |
| EMR_BITBLT | `76` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation. |
| EMR_STRETCHBLT | `77` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| EMR_MASKBLT | `78` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations. |
| EMR_PLGBLT | `79` | This record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap. |
| EMR_SETDIBITSTODEVICE | `80` | This record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle. |
| EMR_STRETCHDIBITS | `81` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| EMR_EXTCREATEFONTINDIRECTW | `82` | This record defines a logical font that has the specified characteristics. The font can subsequently be selected as the current font for the playback device context. |
| EMR_EXTTEXTOUTA | `83` | This record draws an ASCII text string using the current font and text colors.Note EMR_EXTTEXTOUTA SHOULD be emulated with an EMR_EXTTEXTOUTW record (section 2.3.5.8). This requires the ASCII text string in the EmrText object to be converted to Unicode UTF16-LE encoding. |
| EMR_EXTTEXTOUTW | `84` | This record draws a Unicode text string using the current font and text colors. |
| EMR_POLYBEZIER16 | `85` | This record defines one or more Bezier curves. The curves are drawn using the current pen. |
| EMR_POLYGON16 | `86` | This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first. |
| EMR_POLYLINE16 | `87` | This record defines a series of line segments by connecting the points in the specified array. |
| EMR_POLYBEZIERTO16 | `88` | This record defines one or more Bezier curves based on the current position. |
| EMR_POLYLINETO16 | `89` | This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the Points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by Points. |
| EMR_POLYPOLYLINE16 | `90` | This record defines multiple series of connected line segments. |
| EMR_POLYPOLYGON16 | `91` | This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons specified by this record can overlap. |
| EMR_POLYDRAW16 | `92` | This record defines a set of line segments and Bezier curves. |
| EMR_CREATEMONOBRUSH | `93` | This record defines a logical brush with the specified bitmap pattern. The bitmap can be a device-independent bitmap (DIB) section bitmap or it can be a device-dependent bitmap. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | This record defines a logical brush that has the pattern specified by the DIB. |
| EMR_EXTCREATEPEN | `95` | This record defines a logical cosmetic or geometric pen that has the specified style, width, and brush attributes. |
| EMR_POLYTEXTOUTA | `96` | This record draws one or more ASCII text strings using the current font and text colors. Note EMR_POLYTEXTOUTA SHOULD be emulated with a series of EMR_EXTTEXTOUTW records, one per string |
| EMR_POLYTEXTOUTW | `97` | This record draws one or more Unicode text strings using the current font and text colors. Note EMR_POLYTEXTOUTW SHOULD be emulated with a series of EMR_EXTTEXTOUTW records, one per string |
| EMR_SETICMMODE | `98` | This record specifies the mode of Image Color Management (ICM) for graphics operations. |
| EMR_CREATECOLORSPACE | `99` | This record creates a logical color space object from a color profile with a name consisting of ASCII characters |
| EMR_SETCOLORSPACE | `100` | This record defines the current logical color space object for graphics operations. |
| EMR_DELETECOLORSPACE | `101` | This record deletes a logical color space object. Note An EMR_DELETEOBJECT record SHOULD be used instead of EMR_DELETECOLORSPACE to delete a logical color space object |
| EMR_GLSRECORD | `102` | This record specifies an OpenGL function. |
| EMR_GLSBOUNDEDRECORD | `103` | This record specifies an OpenGL function with a bounding rectangle for output. |
| EMR_PIXELFORMAT | `104` | This record specifies the pixel format to use for graphics operations |
| EMR_DRAWESCAPE | `105` | This record passes arbitrary information to the driver. The intent is that the information will result in drawing being done. |
| EMR_EXTESCAPE | `106` | This record passes arbitrary information to the driver. The intent is that the information will not result in drawing being done. |
| EMR_SMALLTEXTOUT | `108` | This record outputs a string. |
| EMR_FORCEUFIMAPPING | `109` | This record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont information. |
| EMR_NAMEDESCAPE | `110` | This record passes arbitrary information to the given named driver. |
| EMR_COLORCORRECTPALETTE | `111` | This record specifies how to correct the entries of a logical palette object using Windows Color System (WCS) 1.0 values |
| EMR_SETICMPROFILEA | `112` | This record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output. |
| EMR_SETICMPROFILEW | `113` | This record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output |
| EMR_ALPHABLEND | `114` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation. |
| EMR_SETLAYOUT | `115` | This record specifies the order in which text and graphics are drawn |
| EMR_TRANSPARENTBLT | `116` | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary |
| EMR_GRADIENTFILL | `118` | This record specifies filling rectangles or triangles with gradients of color |
| EMR_SETLINKEDUFIS | `119` | This record sets the UniversalFontIds of linked fonts to use during character lookup. |
| EMR_SETTEXTJUSTIFICATION | `120` | This record specifies the amount of extra space to add to break characters for justification purposes. |
| EMR_COLORMATCHTOTARGETW | `121` | This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters. |
| EMR_CREATECOLORSPACEW | `122` | This record creates a logical color space object from a color profile with a name consisting of Unicode characters |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


