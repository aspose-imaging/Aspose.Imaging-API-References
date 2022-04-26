---
title: Aspose.Imaging
second_title: Aspose.Imaging for .NET API Reference
description: The namespace is the core for nested namespaces and the most basic objects used for Aspose.Imaging processing.
type: docs
weight: 10
url: /net/aspose.imaging/
---
The namespace is the core for nested namespaces and the most basic objects used for Aspose.Imaging processing.

## Classes

| Class | Description |
| --- | --- |
| class [Blend](./blend) | Defines a blend pattern. This class cannot be inherited. |
| abstract class [Brush](./brush) | The base brush class. |
| static class [BuildVersionInfo](./buildversioninfo) | Contains the current build version information. |
| static class [Cache](./cache) | Contains cache settings. |
| static class [CmykColorHelper](./cmykcolorhelper) | Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the [`CmykColor`](aspose.imaging/cmykcolor) struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated [`CmykColor`](aspose.imaging/cmykcolor) struct. |
| class [ColorBlend](./colorblend) | Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient. This class cannot be inherited. |
| class [ColorMap](./colormap) | Defines a map for converting colors. Several methods of the [`ImageAttributes`](aspose.imaging/imageattributes) class adjust image colors by using a color-remap table, which is an array of [`ColorMap`](aspose.imaging/colormap) structures. Not inheritable. |
| class [ColorMatrix](./colormatrix) | Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [`ImageAttributes`](aspose.imaging/imageattributes) class adjust image colors by using a color matrix. This class cannot be inherited. |
| class [ColorPalette](./colorpalette) | Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable. |
| static class [ColorPaletteHelper](./colorpalettehelper) | Helper class for color palettes manipulation. |
| class [ColorTranslator](./colortranslator) | Translates colors to and from GDI+ Color structures. This class cannot be inherited. |
| delegate [CustomFontSource](./customfontsource) | Custom font source provider function |
| class [CustomLineCap](./customlinecap) | Encapsulates a custom user-defined line cap. |
| abstract class [DataStreamSupporter](./datastreamsupporter) | The data stream container. |
| class [DisposableObject](./disposableobject) | Represents disposable object. |
| class [Figure](./figure) | The figure. A container for shapes. |
| class [FileStreamContainer](./filestreamcontainer) | Helper for file stream processing. |
| class [Font](./font) | Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited. |
| static class [FontSettings](./fontsettings) | General imaging vector formats renderer font settings. |
| class [Graphics](./graphics) | Represents the graphics according to the graphics engine used in the current assembly. |
| class [GraphicsPath](./graphicspath) | Represents a series of connected lines and curves. This class cannot be inherited. |
| abstract class [Image](./image) | The image is the base class for all type of images. |
| class [ImageAttributes](./imageattributes) | An [`ImageAttributes`](aspose.imaging/imageattributes) object contains information about how bitmap and metafile colors are manipulated during rendering. An [`ImageAttributes`](aspose.imaging/imageattributes) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [`ImageAttributes`](aspose.imaging/imageattributes) object and pass the path of that [`ImageAttributes`](aspose.imaging/imageattributes) object (along with the path of an [`Image`](aspose.imaging/image)) to the DrawImage method. |
| static class [ImageCreatorsRegistry](./imagecreatorsregistry) | Represents the image creators registry. |
| static class [ImageExportersRegistry](./imageexportersregistry) | Represents the image exporters registry. |
| static class [ImageLoadersRegistry](./imageloadersregistry) | Represents the image loaders registry. |
| abstract class [ImageOptionsBase](./imageoptionsbase) | The image base options. |
| class [ImageResizeSettings](./imageresizesettings) | Image resize settings class |
| class [IntRange](./intrange) | Class for representing sequence of elements |
| class [License](./license) | Provides methods to license the component. |
| class [LoadOptions](./loadoptions) | Represents the loading options. |
| class [Matrix](./matrix) | Replaces the GDI+ Matrix. |
| class [Metered](./metered) | Provides methods to set metered key. |
| class [NonGenericDictionary](./nongenericdictionary) | Represents a non generic dictionary. |
| class [NonGenericList](./nongenericlist) | Non generic list of objects |
| abstract class [ObjectWithBounds](./objectwithbounds) | The object having bounds. |
| static class [OpenTypeFontsCache](./opentypefontscache) | Cache for OpenType fonts that are installed in the system. |
| delegate [PageExportingAction](./pageexportingaction) | Delegate for firing before page is exported |
| class [Pen](./pen) | Defines an object used to draw lines, curves and figures. |
| class [PixelDataFormat](./pixeldataformat) | The pixel data format. This is an immutable object. |
| delegate [ProgressEventHandler](./progresseventhandler) | Progress event handler function reference |
| abstract class [RasterCachedImage](./rastercachedimage) | Represents a raster image supporting raster graphics operations. This image caches pixel data when required. |
| abstract class [RasterCachedMultipageImage](./rastercachedmultipageimage) | The raster multipage image |
| abstract class [RasterImage](./rasterimage) | Represents a raster image supporting raster graphics operations. |
| class [RawDataSettings](./rawdatasettings) | The raw data settings |
| class [Region](./region) | Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited. |
| class [ResolutionSetting](./resolutionsetting) | The resolution setting for image save options. |
| abstract class [Shape](./shape) | The shape. A continuous set of points connected using a specific rule. |
| abstract class [ShapeSegment](./shapesegment) | Represents a shape segment. A segment is a line or curve connecting two points. |
| abstract class [Source](./source) | The source is used to contain all relevant information for an object pipe. |
| class [SplitStreamContainer](./splitstreamcontainer) | Represents split stream container which contains the stream and provides stream processing routines. |
| class [StreamContainer](./streamcontainer) | Represents stream container which contains the stream and provides stream processing routines. |
| class [StringFormat](./stringformat) | Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited. |
| class [TransparencySupporter](./transparencysupporter) | The object supporting transparency. |
| abstract class [VectorImage](./vectorimage) | The vector image is the base class for all type of vector images. |
| abstract class [VectorMultipageImage](./vectormultipageimage) | The Vector multipage image |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | The advanced buffer processor. |
| interface [IAnimationFrame](./ianimationframe) | The Animation frame |
| interface [IBufferProcessor](./ibufferprocessor) | The buffer processor. |
| interface [IColorConverter](./icolorconverter) | The color converter. |
| interface [IColorPalette](./icolorpalette) | The color palette interface. |
| interface [IImageCreator](./iimagecreator) | The image creator. |
| interface [IImageCreatorDescriptor](./iimagecreatordescriptor) | The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome the necessity to contain each image creator instance in memory and multithreading issues. |
| interface [IImageDescriptor](./iimagedescriptor) | The image descriptor. Contains base properties and methods for all other image descriptor types. |
| interface [IImageExporter](./iimageexporter) | The image exporter. Can export data from internal Aspose.Imaging format to a specified data format. |
| interface [IImageExporterDescriptor](./iimageexporterdescriptor) | Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance in memory and multithreading issues. |
| interface [IImageLoader](./iimageloader) | The image loader. |
| interface [IImageLoaderDescriptor](./iimageloaderdescriptor) | The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome the necessity to contain each image loader instance in memory and multithreading issues. |
| interface [IIndexedColorConverter](./iindexedcolorconverter) | The color converter for indexed image formats. |
| interface [IKeyedObject](./ikeyedobject) | Represents interface for objects with keys. |
| interface [IMultipageImage](./imultipageimage) | The multipage image interface |
| interface [IMultipageImageExt](./imultipageimageext) | The extended multipage image interface |
| interface [IObjectWithBounds](./iobjectwithbounds) | Represents an object with bounds. |
| interface [IOrderedShape](./iorderedshape) | Represents an ordered shape. An ordered shape is a continuous set of points having a start point and end point. The continuous set of points connected using a specific rule. |
| interface [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Conforms to the 32-bit ARGB pixels loaded partially. |
| interface [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | The 64-bit ARGB pixels loader. |
| interface [IPartialPixelLoader](./ipartialpixelloader) | Conforms to the pixels loaded partially. |
| interface [IPartialRawDataLoader](./ipartialrawdataloader) | The partial data loader. |
| interface [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | The raster image 32-bit ARGB pixel loader. |
| interface [IRasterImagePixelLoader](./irasterimagepixelloader) | The raster image pixel loader. |
| interface [IRasterImageRawDataLoader](./irasterimagerawdataloader) | The raster image raw data loader. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [AnimationDisposalMethods](./animationdisposalmethods) | Indicates the way in which the graphic is to be treated after being displayed. |
| enum [CacheType](./cachetype) | Specifies the cache type to use. |
| enum [CharacterSet](./characterset) | Represents the character set used. |
| enum [ColorAdjustType](./coloradjusttype) | Specifies which objects use color adjustment information. |
| enum [ColorChannelFlag](./colorchannelflag) | Specifies individual channels in the CMYK (cyan, magenta, yellow, black) color space. This enumeration is used by the SetOutputChannel methods. |
| enum [ColorCompareMethod](./colorcomparemethod) | Color comparison method to adjust to nearest neighbor |
| enum [ColorMatrixFlag](./colormatrixflag) | Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [`ImageAttributes`](aspose.imaging/imageattributes). |
| enum [ColorQuantizationMethod](./colorquantizationmethod) | Colors quantization methods |
| enum [CompositingQuality](./compositingquality) | Specifies the quality level to use during compositing. |
| enum [DashCap](./dashcap) | Specifies the type of graphic shape to use on both ends of each dash in a dashed line. |
| enum [DashStyle](./dashstyle) | Specifies the style of dashed lines drawn with a [`Pen`](aspose.imaging/pen) object. |
| enum [DataRecoveryMode](./datarecoverymode) | The data recovery mode. |
| enum [DitheringMethod](./ditheringmethod) | Dithering method. |
| enum [DitheringMethods](./ditheringmethods) | The dithering methods used to control color conversion. |
| enum [FileFormat](./fileformat) | One of supported imaging file formats. |
| enum [FillMode](./fillmode) | Specifies how the interior of a closed path is filled. |
| enum [FontStyle](./fontstyle) | Specifies style information applied to text. |
| enum [GraphicsUnit](./graphicsunit) | Specifies the unit of measure for the given data. |
| enum [HatchStyle](./hatchstyle) | Specifies the different patterns available for [`HatchBrush`](aspose.imaging.brushes/hatchbrush) objects. |
| enum [HotkeyPrefix](./hotkeyprefix) | Specifies the type of display for hot-key prefixes that relate to text. |
| enum [ImageFilterType](./imagefiltertype) | Image filters to use |
| enum [InterpolationMode](./interpolationmode) | The [`InterpolationMode`](aspose.imaging/interpolationmode) enumeration specifies the algorithm that is used when images are scaled or rotated. |
| enum [KnownColor](./knowncolor) | Specifies the known system colors. |
| enum [LineCap](./linecap) | Specifies the available cap styles with which a [`Pen`](aspose.imaging/pen) object can end a line. |
| enum [LineJoin](./linejoin) | Specifies how to join consecutive line or curve segments in a figure (subpath) contained in a [`GraphicsPath`](aspose.imaging/graphicspath) object. |
| enum [MatrixOrder](./matrixorder) | Specifies the order for matrix transform operations. |
| enum [PaletteMiningMethod](./paletteminingmethod) | The image palette mining method |
| enum [PdfComplianceVersion](./pdfcomplianceversion) | Specifies the PDF compliance level to output file. |
| enum [PenAlignment](./penalignment) | Specifies the alignment of a [`Pen`](aspose.imaging/pen) object in relation to the theoretical, zero-width line. |
| enum [PenType](./pentype) | Specifies the type of fill a [`Pen`](aspose.imaging/pen) object uses to fill lines. |
| enum [PixelFormat](./pixelformat) | The pixel data format actual meaning. |
| enum [ResizeType](./resizetype) | Specifies the resize type. |
| enum [ResolutionUnit](./resolutionunit) | Resolution unit enum. |
| enum [RotateFlipType](./rotatefliptype) | Specifies how much an image is rotated and the axis used to flip the image. |
| enum [SeekOrigin](./seekorigin) | Provides the fields that represent reference points in [`StreamContainer`](aspose.imaging/streamcontainer) for seeking. |
| enum [SmoothingMode](./smoothingmode) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| enum [StringAlignment](./stringalignment) | Specifies the alignment of a text string relative to its layout rectangle. |
| enum [StringDigitSubstitute](./stringdigitsubstitute) | The enumeration specifies how to substitute digits in a string according to a user's locale or language. |
| enum [StringFormatFlags](./stringformatflags) | Specifies the display and layout information for text strings. |
| enum [StringTrimming](./stringtrimming) | Specifies how to trim characters from a string that does not completely fit into a layout shape. |
| enum [TextRenderingHint](./textrenderinghint) | Specifies the quality of text rendering. |
| enum [WarpMode](./warpmode) | Specifies the type of warp transformation applied. |
| enum [WrapMode](./wrapmode) | Specifies how a texture or gradient is tiled when it is smaller than the area being filled. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
