---
title: EmfRecordType Enumeration
type: docs
weight: 290
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

The RecordType enumeration defines values that uniquely identify EMF records.<br/>            These values are provided in the Type field of each record.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EMR_ABORTPATH | This record aborts a path bracket or discards the path from a closed path bracket. |
| EMR_ALPHABLEND | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle,<br/>             including alpha transparency data, according to a specified blending operation. |
| EMR_ANGLEARC | This record defines a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter <br/>            of a circle with the given radius and center. The length of the arc is defined by <br/>            the given start and sweep angles. |
| EMR_ARC | This record defines an elliptical arc. |
| EMR_ARCTO | This record defines an elliptical arc. It resets the current position to the <br/>            end point of the arc. |
| EMR_BEGINPATH | This record opens a path bracket in the playback device context. |
| EMR_BITBLT | This record specifies a block transfer of pixels from a source bitmap to a destination<br/>             rectangle, optionally in combination with a brush pattern, according to a specified raster operation. |
| EMR_CHORD | This record defines a chord (a region bounded by the intersection of an ellipse <br/>            and a line segment, called a secant). The chord is outlined by using the current <br/>            pen and filled by using the current brush. |
| EMR_CLOSEFIGURE | This record closes an open figure in a path. |
| EMR_COLORCORRECTPALETTE | This record specifies how to correct the entries of a logical palette object using Windows <br/>            Color System (WCS) 1.0 values |
| EMR_COLORMATCHTOTARGETW | This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters. |
| EMR_COMMENT | This record specifies arbitrary private data. |
| EMR_CREATEBRUSHINDIRECT | This record defines a logical brush for figure filling in graphics operations. |
| EMR_CREATECOLORSPACE | This record creates a logical color space object from a color profile with a name consisting of ASCII characters |
| EMR_CREATECOLORSPACEW | This record creates a logical color space object from a color profile with a name consisting of Unicode characters |
| EMR_CREATEDIBPATTERNBRUSHPT | This record defines a logical brush that has the pattern specified by the DIB. |
| EMR_CREATEMONOBRUSH | This record defines a logical brush with the specified bitmap pattern. The bitmap can<br/>             be a device-independent bitmap (DIB) section bitmap or it can be a device-dependent bitmap. |
| EMR_CREATEPALETTE | This record defines a LogPalette object. |
| EMR_CREATEPEN | This record defines a logical pen that has the specified style, width, and color. <br/>            The pen can subsequently be selected into the playback device context and used to draw lines and curves. |
| EMR_DELETECOLORSPACE | This record deletes a logical color space object. Note An EMR_DELETEOBJECT record SHOULD be <br/>            used instead of EMR_DELETECOLORSPACE to delete a logical color space object |
| EMR_DELETEOBJECT | This record deletes a graphics object, clearing its index in the EMF Object Table. <br/>            If the deleted object is selected in the playback device context, the default object <br/>            for that context property MUST be restored. |
| EMR_DRAWESCAPE | This record passes arbitrary information to the driver. The intent is that the information <br/>            will result in drawing being done. |
| EMR_ELLIPSE | This record defines an ellipse. The center of the ellipse is the center of the <br/>            specified bounding rectangle. The ellipse is outlined by using the current pen and <br/>            is filled by using the current brush. |
| EMR_ENDPATH | This record closes a path bracket and selects the path defined by the bracket <br/>            into the playback device context. |
| EMR_EOF | This record indicates the end of the metafile. |
| EMR_EXCLUDECLIPRECT | This record defines a new clipping region that consists of the existing clipping region <br/>            minus the specified rectangle. |
| EMR_EXTCREATEFONTINDIRECTW | This record defines a logical font that has the specified characteristics. The font <br/>            can subsequently be selected as the current font for the playback device context. |
| EMR_EXTCREATEPEN | This record defines a logical cosmetic or geometric pen that has the specified style, <br/>            width, and brush attributes. |
| EMR_EXTESCAPE | This record passes arbitrary information to the driver. The intent is that the information <br/>            will not result in drawing being done. |
| EMR_EXTFLOODFILL | This record fills an area of the display surface with the current brush. |
| EMR_EXTSELECTCLIPRGN | This record combines the specified region with the current clip region using the <br/>            specified mode. |
| EMR_EXTTEXTOUTA | This record draws an ASCII text string using the current font and text colors.Note <br/>            EMR_EXTTEXTOUTA SHOULD be emulated with an EMR_EXTTEXTOUTW record (section 2.3.5.8).  <br/>            This requires the ASCII text string in the EmrText object to be converted to Unicode UTF16-LE encoding. |
| EMR_EXTTEXTOUTW | This record draws a Unicode text string using the current font and text colors. |
| EMR_FILLPATH | This record closes any open figures in the current path and fills the path's interior <br/>            by using the current brush and polygon-filling mode. |
| EMR_FILLRGN | This record fills the specified region by using the specified brush. |
| EMR_FLATTENPATH | This record transforms any curve in the path that is selected into the playback device <br/>            context, turning each curve into a sequence of lines. |
| EMR_FORCEUFIMAPPING | This record forces the font mapper to match fonts based on their UniversalFontId in <br/>            preference to their LogFont information. |
| EMR_FRAMERGN | This record draws a border around the specified region using the specified brush. |
| EMR_GLSBOUNDEDRECORD | This record specifies an OpenGL function with a bounding rectangle for output. |
| EMR_GLSRECORD | This record specifies an OpenGL function. |
| EMR_GRADIENTFILL | This record specifies filling rectangles or triangles with gradients of color |
| EMR_HEADER | This record defines the start of the metafile and specifies its characteristics; its contents, <br/>            including the dimensions of the embedded image; the number of records in the metafile; and the <br/>            resolution of the device on which the embedded image was created. These values make it possible for the metafile to be device-independent. |
| EMR_INTERSECTCLIPRECT | This record defines a new clipping region from the intersection of the current clipping <br/>            region and the specified rectangle. |
| EMR_INVERTRGN | This record inverts the colors in the specified region. |
| EMR_LINETO | This record defines a line from the current position up to, but not including,<br/>             the specified point. It resets the current position to the specified point. |
| EMR_MASKBLT | This record specifies a block transfer of pixels from a source bitmap to a destination<br/>             rectangle, optionally in combination with a brush pattern and with the application of a <br/>            color mask bitmap, according to specified foreground and background raster operations. |
| EMR_MODIFYWORLDTRANSFORM | This record redefines the world transformation for the playback device context using the specified mode. |
| EMR_MOVETOEX | This record defines coordinates of the new current position, in logical units. |
| EMR_NAMEDESCAPE | This record passes arbitrary information to the given named driver. |
| EMR_OFFSETCLIPRGN | This record redefines the clipping region of the playback device context by the specified offsets. |
| EMR_PAINTRGN | This record paints the specified region by using the brush currently selected into <br/>            the playback device context. |
| EMR_PIE | This record defines a pie-shaped wedge bounded by the intersection of an ellipse <br/>            and two radials. The pie is outlined by using the current pen and filled by using <br/>            the current brush. |
| EMR_PIXELFORMAT | This record specifies the pixel format to use for graphics operations |
| EMR_PLGBLT | This record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap. |
| EMR_POLYBEZIER | This record defines one or more Bezier curves. Cubic Bezier curves are defined using<br/>            specified endpoints and control points, and are stroked with the current pen. |
| EMR_POLYBEZIER16 | This record defines one or more Bezier curves. The curves are drawn using the current pen. |
| EMR_POLYBEZIERTO | This record defines one or more Bezier curves based upon the current position. |
| EMR_POLYBEZIERTO16 | This record defines one or more Bezier curves based on the current position. |
| EMR_POLYDRAW | This record defines a set of line segments and Bezier curves. |
| EMR_POLYDRAW16 | This record defines a set of line segments and Bezier curves. |
| EMR_POLYGON | This record defines a polygon consisting of two or more vertexes connected by straight <br/>            lines. The polygon is outlined by using the current pen and filled by using the current brush <br/>            and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first. |
| EMR_POLYGON16 | This record defines a polygon consisting of two or more vertexes connected by straight lines. <br/>            The polygon is outlined by using the current pen and filled by using the current brush and polygon<br/>             fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first. |
| EMR_POLYLINE | This record defines a series of line segments by connecting the points in the specified <br/>            array. |
| EMR_POLYLINE16 | This record defines a series of line segments by connecting the points in the specified array. |
| EMR_POLYLINETO | This record defines one or more straight lines based upon the current position. <br/>            A line is drawn from the current position to the first point specified by the points field <br/>            by using the current pen. For each additional line, drawing is performed from the ending <br/>            point of the previous line to the next point specified by points. |
| EMR_POLYLINETO16 | This record defines one or more straight lines based upon the current position.<br/>             A line is drawn from the current position to the first point specified by the Points <br/>            field by using the current pen. For each additional line, drawing is performed from the <br/>            ending point of the previous line to the next point specified by Points. |
| EMR_POLYPOLYGON | This record defines a series of closed polygons. Each polygon is outlined by using the <br/>            current pen and filled by using the current brush and polygon fill mode. The polygons defined by this record can overlap. |
| EMR_POLYPOLYGON16 | This record defines a series of closed polygons. Each polygon is outlined by using <br/>            the current pen and filled by using the current brush and polygon fill mode. The polygons<br/>             specified by this record can overlap. |
| EMR_POLYPOLYLINE | This record defines multiple series of connected line segments. The line segments are <br/>            drawn by using the current pen. The figures formed by the segments are not filled. T<br/>            he current position is neither used nor updated by this record. |
| EMR_POLYPOLYLINE16 | This record defines multiple series of connected line segments. |
| EMR_POLYTEXTOUTA | This record draws one or more ASCII text strings using the current font and text colors.<br/>             Note EMR_POLYTEXTOUTA SHOULD be emulated with a series of EMR_EXTTEXTOUTW records, one per string |
| EMR_POLYTEXTOUTW | This record draws one or more Unicode text strings using the current font and text colors.<br/>            Note EMR_POLYTEXTOUTW SHOULD be emulated with a series of EMR_EXTTEXTOUTW records, one per string |
| EMR_REALIZEPALETTE | This record maps entries from the current logical palette to the system palette. |
| EMR_RECTANGLE | This record defines a rectangle. The rectangle is outlined by using the current <br/>            pen and filled by using the current brush. |
| EMR_RESIZEPALETTE | This record increases or decreases the size of a logical palette. |
| EMR_RESTOREDC | This record restores the playback device context to the specified saved state. <br/>            The playback device context is restored by popping state information off a stack of <br/>            saved device contexts created by earlier EMR_SAVEDC (section 2.3.11) records. |
| EMR_ROUNDRECT | This record defines a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush. |
| EMR_SAVEDC | This record saves the current state of the playback device context by copying data <br/>            describing selected objects and graphic modes—including the bitmap, brush, palette, <br/>            font, pen, region, drawing mode, and mapping mode—to a stack of saved device contexts. |
| EMR_SCALEVIEWPORTEXTEX | This record redefines the viewport for the playback device context using the ratios <br/>            formed by the specified multiplicands and divisors. |
| EMR_SCALEWINDOWEXTEX | This record redefines the window for the playback device context using the ratios formed <br/>            by the specified multiplicands and divisors. |
| EMR_SELECTCLIPPATH | This record defines the current path as a clipping region for the playback device <br/>            context, combining the new region with any existing clipping region using the specified mode. |
| EMR_SELECTOBJECT | This record adds an object to the playback device context, identifying it by its <br/>            index in the EMF Object Table (section 3.1.1.1). |
| EMR_SELECTPALETTE | This record adds a LogPalette (section 2.2.17) object to the playback device <br/>            context, identifying it by its index in the EMF Object Table. |
| EMR_SETARCDIRECTION | This record defines the drawing direction to be used for arc and rectangle<br/>             operations. |
| EMR_SETBKCOLOR | This record defines the background color. |
| EMR_SETBKMODE | This record defines the background mix mode of the playback device context. The background mix<br/>             mode is used with text, hatched brushes, and pen styles that are not solid lines. |
| EMR_SETBRUSHORGEX | This record defines the origin of the current brush. |
| EMR_SETCOLORADJUSTMENT | This record defines the color adjustment values for the playback device context using the specified values. |
| EMR_SETCOLORSPACE | This record defines the current logical color space object for graphics operations. |
| EMR_SETDIBITSTODEVICE | This record specifies a block transfer of pixels from specified scan lines of a source<br/>             bitmap to a destination rectangle. |
| EMR_SETICMMODE | This record specifies the mode of Image Color Management (ICM) for graphics operations. |
| EMR_SETICMPROFILEA | This record specifies a color profile in a file with a name consisting of ASCII characters,<br/>             for graphics output. |
| EMR_SETICMPROFILEW | This record specifies a color profile in a file with a name consisting of Unicode characters,<br/>             for graphics output |
| EMR_SETLAYOUT | This record specifies the order in which text and graphics are drawn |
| EMR_SETLINKEDUFIS | This record sets the UniversalFontIds of linked fonts to use during character lookup. |
| EMR_SETMAPMODE | This record defines the mapping mode of the playback device context. The mapping mode<br/>             defines the unit of measure used to transform page space units into device space units,<br/>             and also defines the orientation of the device's x-axis and y-axis. |
| EMR_SETMAPPERFLAGS | This record specifies parameters of the process of matching logical fonts to physical <br/>            fonts, which is performed by the font mapper. |
| EMR_SETMETARGN | This record intersects the current clipping region for the playback device context with the <br/>            current meta region and saves the combined region as the new meta region. The clipping region is reset to a null region. |
| EMR_SETMITERLIMIT | This record defines the limit for the length of miter joins for the playback <br/>            device context. |
| EMR_SETPALETTEENTRIES | This record defines RGB (red-green-blue) color values in a range of entries <br/>            in a LogPalette object. |
| EMR_SETPIXELV | This record defines the color of the pixel at the specified logical coordinates. |
| EMR_SETPOLYFILLMODE | This record defines polygon fill mode. |
| EMR_SETROP2 | This record defines binary raster operation mode. |
| EMR_SETSTRETCHBLTMODE | This record defines bitmap stretch mode. |
| EMR_SETTEXTALIGN | This record defines text alignment. |
| EMR_SETTEXTCOLOR | This record defines the current text color. |
| EMR_SETTEXTJUSTIFICATION | This record specifies the amount of extra space to add to break characters for justification<br/>             purposes. |
| EMR_SETVIEWPORTEXTEX | This record defines the viewport extent. |
| EMR_SETVIEWPORTORGEX | This record defines the viewport origin. |
| EMR_SETWINDOWEXTEX | This record defines the window extent. |
| EMR_SETWINDOWORGEX | This record defines the window origin. |
| EMR_SETWORLDTRANSFORM | This record defines a two-dimensional linear transformation between world space and <br/>            page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. <br/>            This transformation can be used to scale, rotate, shear, or translate graphics output. |
| EMR_SMALLTEXTOUT | This record outputs a string. |
| EMR_STRETCHBLT | This record specifies a block transfer of pixels from a source bitmap to a destination<br/>             rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>             operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| EMR_STRETCHDIBITS | This record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation, <br/>            stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| EMR_STROKEANDFILLPATH | This record closes any open figures in a path, strokes the outline of the path by <br/>            using the current pen, and fills its interior by using the current brush. |
| EMR_STROKEPATH | This record renders the specified path by using the current pen. |
| EMR_TRANSPARENTBLT | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle,<br/>             treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary |
| EMR_WIDENPATH | This record redefines the current path as the area that would be painted if the path <br/>            were stroked using the pen currently selected into the playback device context. |
