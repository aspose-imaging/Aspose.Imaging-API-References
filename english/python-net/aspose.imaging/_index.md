---
title: aspose.imaging
type: docs
weight: 10
url: /python-net/aspose.imaging/
---


The module is the core for nested modules and the most basic objects used for Aspose.Imaging processing.

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Defines a blend pattern. This class cannot be inherited. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | The base brush class. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Contains the current build version information. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Contains cache settings. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | The CMYK color of pixel. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct. |
| [Color](/imaging/python-net/aspose.imaging/color/) | The color of the pixel. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient. This class cannot be inherited. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Defines a map for converting colors. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color-remap table, which is an array of [ColorMap](/imaging/python-net/aspose.imaging/colormap/) structures. Not inheritable. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Helper class for color palettes manipulation. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Translates colors to and from GDI+ Color structures. This class cannot be inherited. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Encapsulates a custom user-defined line cap. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | The data stream container. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Represents disposable object. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | The embedded image class |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | The figure. A container for shapes. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Helper for file stream processing. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | General imaging vector formats renderer font settings. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Represents the graphics according to the graphics engine used in the current assembly. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Represents a series of connected lines and curves. This class cannot be inherited. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | The advanced buffer processor. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | The Animation frame |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | The buffer processor. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | The color converter. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette interface. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Image metadata interface. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | The image creator. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | The image descriptor. Contains base properties and methods for all other image descriptor types. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | The image exporter. Can export data from internal Aspose.Imaging format to a specified data format. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | The image loader. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | The color converter for indexed image formats. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Image metadata container interface. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | The multipage image interface |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | The extended multipage image interface |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Represents an object with bounds. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Represents an ordered shape. An ordered shape is a continuous set of points having a start point and end point.<br/>            The continuous set of points connected using a specific rule. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Conforms to the 32-bit ARGB pixels loaded partially. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | The 64-bit ARGB pixels loader. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Conforms to the pixels loaded partially. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | The partial data loader. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | The raster image 32-bit ARGB pixel loader. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | The raster image 64-bit ARGB pixel loader. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | The raster image pixel loader. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | The raster image raw data loader. |
| [Image](/imaging/python-net/aspose.imaging/image/) | The image is the base class for all type of images. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Represents the image creators registry. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Represents the image exporters registry. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Represents the image loaders registry. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image base options. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Image resize settings class |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Class for representing sequence of elements |
| [License](/imaging/python-net/aspose.imaging/license/) | Provides methods to license the component. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Represents the loading options. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Replaces the GDI+ Matrix. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Provides metered methods for integration |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Represents a non generic dictionary. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Non generic list of objects |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | The object having bounds. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Cache for OpenType fonts that are installed in the system. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Defines an object used to draw lines, curves and figures. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | The pixel data format. This is an immutable object. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Represents a raster image supporting raster graphics operations. This image caches pixel data when required. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | The raster multipage image |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Represents a raster image supporting raster graphics operations. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Stores a set of four integers that represent the location and size of a rectangle. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Stores a set of four floating-point numbers that represent the location and size of a rectangle. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | The remve background settings |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | The resolution setting for image save options. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | The shape. A continuous set of points connected using a specific rule. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Represents a shape segment. A segment is a line or curve connecting two points. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Represents size. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle. |
| [Source](/imaging/python-net/aspose.imaging/source/) | The source is used to contain all relevant information for an object pipe. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Represents split stream container which contains the stream and provides stream processing routines. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Represents stream container which contains the stream and provides stream processing routines. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | The object supporting transparency. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | The vector image is the base class for all type of vector images. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | The Vector multipage image |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Indicates the way in which the graphic is to be treated after being displayed. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Specifies the cache type to use. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Represents the character set used. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Specifies which objects use color adjustment information. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Specifies individual channels in the CMYK (cyan, magenta, yellow, black) color space. This enumeration is used by the SetOutputChannel methods. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Color comparison method to adjust to nearest neighbor |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Colors quantization  methods |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Specifies the quality level to use during compositing. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Specifies the type of graphic shape to use on both ends of each dash in a dashed line. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Specifies the style of dashed lines drawn with a [Pen](/imaging/python-net/aspose.imaging/pen/) object. |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | The data recovery mode. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering method. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | The dithering methods used to control color conversion. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | One of supported imaging file formats. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Specifies how the interior of a closed path is filled. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Specifies style information applied to text. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Specifies the unit of measure for the given data. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Specifies the different patterns available for [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/) objects. |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Specifies the type of display for hot-key prefixes that relate to text. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Image filters to use |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | The [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) enumeration specifies the algorithm that is used when images are scaled or rotated. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Specifies the known system colors. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Specifies the available cap styles with which a [Pen](/imaging/python-net/aspose.imaging/pen/) object can end a line. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Specifies how to join consecutive line or curve segments in a figure (subpath) contained in a [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) object. |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifies the order for matrix transform operations. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | The image palette mining method |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Specifies the PDF compliance level to output file. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Specifies the alignment of a [Pen](/imaging/python-net/aspose.imaging/pen/) object in relation to the theoretical, zero-width line. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Specifies the type of fill a [Pen](/imaging/python-net/aspose.imaging/pen/) object uses to fill lines. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | The pixel data format actual meaning. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | The type of processing. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Specifies the resize type. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Resolution unit enum. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Specifies how much an image is rotated and the axis used to flip the image. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Provides the fields that represent reference points in [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) for seeking. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Specifies the alignment of a text string relative to its layout rectangle. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | The enumeration specifies how to substitute digits in a string according to a user's locale or language. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Specifies the display and layout information for text strings. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Specifies how to trim characters from a string that does not completely fit into a layout shape. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Specifies the quality of text rendering. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Specifies the type of warp transformation applied. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Specifies how a texture or gradient is tiled when it is smaller than the area being filled. |
