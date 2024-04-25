---
title: EmfRecordType
second_title: Aspose.Imaging for Java API Reference
description: The RecordType enumeration defines values that uniquely identify EMF records.
type: docs
weight: 38
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

The RecordType enumeration defines values that uniquely identify EMF records. These values are provided in the Type field of each record.
## Fields

| Field | Description |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | This record defines the start of the metafile and specifies its characteristics; its contents, including the dimensions of the embedded image; the number of records in the metafile; and the resolution of the device on which the embedded image was created. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | This record defines one or more Bezier curves. |
| [EMR_POLYGON](#EMR-POLYGON) | This record defines a polygon consisting of two or more vertexes connected by straight lines. |
| [EMR_POLYLINE](#EMR-POLYLINE) | This record defines a series of line segments by connecting the points in the specified array. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | This record defines one or more Bezier curves based upon the current position. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | This record defines one or more straight lines based upon the current position. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | This record defines multiple series of connected line segments. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | This record defines a series of closed polygons. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | This record defines the window extent. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | This record defines the window origin. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | This record defines the viewport extent. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | This record defines the viewport origin. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | This record defines the origin of the current brush. |
| [EMR_EOF](#EMR-EOF) | This record indicates the end of the metafile. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | This record defines the color of the pixel at the specified logical coordinates. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | This record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | This record defines the mapping mode of the playback device context. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | This record defines the background mix mode of the playback device context. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | This record defines polygon fill mode. |
| [EMR_SETROP2](#EMR-SETROP2) | This record defines binary raster operation mode. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | This record defines bitmap stretch mode. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | This record defines text alignment. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | This record defines the color adjustment values for the playback device context using the specified values. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | This record defines the current text color. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | This record defines the background color. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | This record redefines the clipping region of the playback device context by the specified offsets. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | This record defines coordinates of the new current position, in logical units. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | This record intersects the current clipping region for the playback device context with the current meta region and saves the combined region as the new meta region. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | This record defines a new clipping region that consists of the existing clipping region minus the specified rectangle. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | This record defines a new clipping region from the intersection of the current clipping region and the specified rectangle. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | This record redefines the viewport for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | This record redefines the window for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| [EMR_SAVEDC](#EMR-SAVEDC) | This record saves the current state of the playback device context by copying data describing selected objects and graphic modes\\u2014including the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode\\u2014to a stack of saved device contexts. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | This record restores the playback device context to the specified saved state. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | This record defines a two-dimensional linear transformation between world space and page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | This record redefines the world transformation for the playback device context using the specified mode. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | This record adds an object to the playback device context, identifying it by its index in the EMF Object Table (section 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | This record defines a logical pen that has the specified style, width, and color. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | This record defines a logical brush for figure filling in graphics operations. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | This record deletes a graphics object, clearing its index in the EMF Object Table. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | This record defines a line segment of an arc. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | This record defines an ellipse. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | This record defines a rectangle. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | This record defines a rectangle with rounded corners. |
| [EMR_ARC](#EMR-ARC) | This record defines an elliptical arc. |
| [EMR_CHORD](#EMR-CHORD) | This record defines a chord (a region bounded by the intersection of an ellipse and a line segment, called a secant). |
| [EMR_PIE](#EMR-PIE) | This record defines a pie-shaped wedge bounded by the intersection of an ellipse and two radials. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | This record adds a LogPalette (section 2.2.17) object to the playback device context, identifying it by its index in the EMF Object Table. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | This record defines a LogPalette object. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | This record defines RGB (red-green-blue) color values in a range of entries in a LogPalette object. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | This record increases or decreases the size of a logical palette. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | This record maps entries from the current logical palette to the system palette. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | This record fills an area of the display surface with the current brush. |
| [EMR_LINETO](#EMR-LINETO) | This record defines a line from the current position up to, but not including, the specified point. |
| [EMR_ARCTO](#EMR-ARCTO) | This record defines an elliptical arc. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | This record defines a set of line segments and Bezier curves. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | This record defines the drawing direction to be used for arc and rectangle operations. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | This record defines the limit for the length of miter joins for the playback device context. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | This record opens a path bracket in the playback device context. |
| [EMR_ENDPATH](#EMR-ENDPATH) | This record closes a path bracket and selects the path defined by the bracket into the playback device context. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | This record closes an open figure in a path. |
| [EMR_FILLPATH](#EMR-FILLPATH) | This record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | This record renders the specified path by using the current pen. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | This record transforms any curve in the path that is selected into the playback device context, turning each curve into a sequence of lines. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | This record redefines the current path as the area that would be painted if the path were stroked using the pen currently selected into the playback device context. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | This record defines the current path as a clipping region for the playback device context, combining the new region with any existing clipping region using the specified mode. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | This record aborts a path bracket or discards the path from a closed path bracket. |
| [EMR_COMMENT](#EMR-COMMENT) | This record specifies arbitrary private data. |
| [EMR_FILLRGN](#EMR-FILLRGN) | This record fills the specified region by using the specified brush. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | This record draws a border around the specified region using the specified brush. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | This record inverts the colors in the specified region. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | This record paints the specified region by using the brush currently selected into the playback device context. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | This record combines the specified region with the current clip region using the specified mode. |
| [EMR_BITBLT](#EMR-BITBLT) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| [EMR_MASKBLT](#EMR-MASKBLT) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations. |
| [EMR_PLGBLT](#EMR-PLGBLT) | This record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | This record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | This record defines a logical font that has the specified characteristics. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | This record draws an ASCII text string using the current font and text colors.Note EMR\_EXTTEXTOUTA SHOULD be emulated with an EMR\_EXTTEXTOUTW record (section 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | This record draws a Unicode text string using the current font and text colors. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | This record defines one or more Bezier curves. |
| [EMR_POLYGON16](#EMR-POLYGON16) | This record defines a polygon consisting of two or more vertexes connected by straight lines. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | This record defines a series of line segments by connecting the points in the specified array. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | This record defines one or more Bezier curves based on the current position. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | This record defines one or more straight lines based upon the current position. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | This record defines multiple series of connected line segments. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | This record defines a series of closed polygons. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | This record defines a set of line segments and Bezier curves. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | This record defines a logical brush with the specified bitmap pattern. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | This record defines a logical brush that has the pattern specified by the DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | This record defines a logical cosmetic or geometric pen that has the specified style, width, and brush attributes. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | This record draws one or more ASCII text strings using the current font and text colors. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | This record draws one or more Unicode text strings using the current font and text colors. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | This record specifies the mode of Image Color Management (ICM) for graphics operations. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | This record creates a logical color space object from a color profile with a name consisting of ASCII characters |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | This record defines the current logical color space object for graphics operations. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | This record deletes a logical color space object. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | This record specifies an OpenGL function. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | This record specifies an OpenGL function with a bounding rectangle for output. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | This record specifies the pixel format to use for graphics operations |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | This record passes arbitrary information to the driver. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | This record passes arbitrary information to the driver. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | This record outputs a string. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | This record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont information. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | This record passes arbitrary information to the given named driver. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | This record specifies how to correct the entries of a logical palette object using Windows Color System (WCS) 1.0 values |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | This record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | This record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | This record specifies the order in which text and graphics are drawn |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | This record specifies filling rectangles or triangles with gradients of color |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | This record sets the UniversalFontIds of linked fonts to use during character lookup. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | This record specifies the amount of extra space to add to break characters for justification purposes. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | This record creates a logical color space object from a color profile with a name consisting of Unicode characters |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


This record defines the start of the metafile and specifies its characteristics; its contents, including the dimensions of the embedded image; the number of records in the metafile; and the resolution of the device on which the embedded image was created. These values make it possible for the metafile to be device-independent.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


This record defines one or more Bezier curves. Cubic Bezier curves are defined using specified endpoints and control points, and are stroked with the current pen.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


This record defines a series of line segments by connecting the points in the specified array.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


This record defines one or more Bezier curves based upon the current position.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by points.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


This record defines multiple series of connected line segments. The line segments are drawn by using the current pen. The figures formed by the segments are not filled. T he current position is neither used nor updated by this record.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons defined by this record can overlap.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


This record defines the window extent.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


This record defines the window origin.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


This record defines the viewport extent.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


This record defines the viewport origin.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


This record defines the origin of the current brush.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


This record indicates the end of the metafile.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


This record defines the color of the pixel at the specified logical coordinates.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


This record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


This record defines the mapping mode of the playback device context. The mapping mode defines the unit of measure used to transform page space units into device space units, and also defines the orientation of the device's x-axis and y-axis.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


This record defines the background mix mode of the playback device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


This record defines polygon fill mode.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


This record defines binary raster operation mode.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


This record defines bitmap stretch mode.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


This record defines text alignment.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


This record defines the color adjustment values for the playback device context using the specified values.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


This record defines the current text color.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


This record defines the background color.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


This record redefines the clipping region of the playback device context by the specified offsets.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


This record defines coordinates of the new current position, in logical units.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


This record intersects the current clipping region for the playback device context with the current meta region and saves the combined region as the new meta region. The clipping region is reset to a null region.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


This record defines a new clipping region that consists of the existing clipping region minus the specified rectangle.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


This record defines a new clipping region from the intersection of the current clipping region and the specified rectangle.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


This record redefines the viewport for the playback device context using the ratios formed by the specified multiplicands and divisors.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


This record redefines the window for the playback device context using the ratios formed by the specified multiplicands and divisors.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


This record saves the current state of the playback device context by copying data describing selected objects and graphic modes\\u2014including the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode\\u2014to a stack of saved device contexts.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


This record restores the playback device context to the specified saved state. The playback device context is restored by popping state information off a stack of saved device contexts created by earlier EMR\_SAVEDC (section 2.3.11) records.

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


This record defines a two-dimensional linear transformation between world space and page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. This transformation can be used to scale, rotate, shear, or translate graphics output.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


This record redefines the world transformation for the playback device context using the specified mode.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


This record adds an object to the playback device context, identifying it by its index in the EMF Object Table (section 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


This record defines a logical pen that has the specified style, width, and color. The pen can subsequently be selected into the playback device context and used to draw lines and curves.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


This record defines a logical brush for figure filling in graphics operations.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


This record deletes a graphics object, clearing its index in the EMF Object Table. If the deleted object is selected in the playback device context, the default object for that context property MUST be restored.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


This record defines a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


This record defines an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


This record defines a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


This record defines a rectangle with rounded corners. The rectangle is outlined by using the current pen and filled by using the current brush.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


This record defines an elliptical arc.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


This record defines a chord (a region bounded by the intersection of an ellipse and a line segment, called a secant). The chord is outlined by using the current pen and filled by using the current brush.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


This record defines a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the current pen and filled by using the current brush.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


This record adds a LogPalette (section 2.2.17) object to the playback device context, identifying it by its index in the EMF Object Table.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


This record defines a LogPalette object.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


This record defines RGB (red-green-blue) color values in a range of entries in a LogPalette object.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


This record increases or decreases the size of a logical palette.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


This record maps entries from the current logical palette to the system palette.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


This record fills an area of the display surface with the current brush.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


This record defines a line from the current position up to, but not including, the specified point. It resets the current position to the specified point.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


This record defines an elliptical arc. It resets the current position to the end point of the arc.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


This record defines a set of line segments and Bezier curves.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


This record defines the drawing direction to be used for arc and rectangle operations.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


This record defines the limit for the length of miter joins for the playback device context.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


This record opens a path bracket in the playback device context.

--------------------

After a path bracket is open, an application can begin processing records to define the points that lie in the path. An application MUST close an open path bracket by processing the EMR\_ENDPATH record. When an application processes the EMR\_BEGINPATH record, all previous paths MUST be discarded from the playback device context.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


This record closes a path bracket and selects the path defined by the bracket into the playback device context.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


This record closes an open figure in a path.

--------------------

Processing the EMR\_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure, and then it MUST connect the lines by using the line join style. If a figure is closed by processing the EMR\_LINETO record instead of the EMR\_CLOSEFIGURE record, end caps are used to create the corner instead of a join. EMR\_LINETO is specified in section 2.3.5.13. The EMR\_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record. Note: A figure can be open even if the current point and the starting point of the figure are the same. After processing the EMR\_CLOSEFIGURE record, adding a line or curve to the path MUST start a new figure.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


This record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


This record renders the specified path by using the current pen.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


This record transforms any curve in the path that is selected into the playback device context, turning each curve into a sequence of lines.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


This record redefines the current path as the area that would be painted if the path were stroked using the pen currently selected into the playback device context.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


This record defines the current path as a clipping region for the playback device context, combining the new region with any existing clipping region using the specified mode.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


This record aborts a path bracket or discards the path from a closed path bracket.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


This record specifies arbitrary private data.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


This record fills the specified region by using the specified brush.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


This record draws a border around the specified region using the specified brush.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


This record inverts the colors in the specified region.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


This record paints the specified region by using the brush currently selected into the playback device context.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


This record combines the specified region with the current clip region using the specified mode.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


This record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


This record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


This record defines a logical font that has the specified characteristics. The font can subsequently be selected as the current font for the playback device context.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


This record draws an ASCII text string using the current font and text colors.Note EMR\_EXTTEXTOUTA SHOULD be emulated with an EMR\_EXTTEXTOUTW record (section 2.3.5.8). This requires the ASCII text string in the EmrText object to be converted to Unicode UTF16-LE encoding.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


This record draws a Unicode text string using the current font and text colors.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


This record defines one or more Bezier curves. The curves are drawn using the current pen.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


This record defines a series of line segments by connecting the points in the specified array.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


This record defines one or more Bezier curves based on the current position.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the Points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


This record defines multiple series of connected line segments.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons specified by this record can overlap.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


This record defines a set of line segments and Bezier curves.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


This record defines a logical brush with the specified bitmap pattern. The bitmap can be a device-independent bitmap (DIB) section bitmap or it can be a device-dependent bitmap.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


This record defines a logical brush that has the pattern specified by the DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


This record defines a logical cosmetic or geometric pen that has the specified style, width, and brush attributes.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


This record draws one or more ASCII text strings using the current font and text colors. Note EMR\_POLYTEXTOUTA SHOULD be emulated with a series of EMR\_EXTTEXTOUTW records, one per string

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


This record draws one or more Unicode text strings using the current font and text colors. Note EMR\_POLYTEXTOUTW SHOULD be emulated with a series of EMR\_EXTTEXTOUTW records, one per string

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


This record specifies the mode of Image Color Management (ICM) for graphics operations.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


This record creates a logical color space object from a color profile with a name consisting of ASCII characters

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


This record defines the current logical color space object for graphics operations.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


This record deletes a logical color space object. Note An EMR\_DELETEOBJECT record SHOULD be used instead of EMR\_DELETECOLORSPACE to delete a logical color space object

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


This record specifies an OpenGL function.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


This record specifies an OpenGL function with a bounding rectangle for output.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


This record specifies the pixel format to use for graphics operations

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


This record passes arbitrary information to the driver. The intent is that the information will result in drawing being done.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


This record passes arbitrary information to the driver. The intent is that the information will not result in drawing being done.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


This record outputs a string.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


This record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont information.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


This record passes arbitrary information to the given named driver.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


This record specifies how to correct the entries of a logical palette object using Windows Color System (WCS) 1.0 values

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


This record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


This record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


This record specifies the order in which text and graphics are drawn

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


This record specifies filling rectangles or triangles with gradients of color

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


This record sets the UniversalFontIds of linked fonts to use during character lookup.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


This record specifies the amount of extra space to add to break characters for justification purposes.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


This record creates a logical color space object from a color profile with a name consisting of Unicode characters

