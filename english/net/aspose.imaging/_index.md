---
title: Aspose.Imaging
second_title: Aspose.Imaging for .NET API Reference
description: The namespace is the core for nested namespaces and the most basic objects used for Aspose.Imaging processing
type: docs
weight: 10
url: /net/aspose.imaging/
---
The namespace is the core for nested namespaces and the most basic objects used for Aspose.Imaging processing.

## Classes

| Class | Description |
| --- | --- |
| [AggregateException](./aggregateexception/) | Aggregates multiple exceptions. |
| [Blend](./blend/) | Defines a blend pattern. This class cannot be inherited. |
| [Brush](./brush/) | The base brush class. |
| [BuildVersionInfo](./buildversioninfo/) | Contains the current build version information. |
| [Cache](./cache/) | Contains cache settings. |
| [CmykColorHelper](./cmykcolorhelper/) | Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the [`CmykColor`](../aspose.imaging/cmykcolor/) struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated [`CmykColor`](../aspose.imaging/cmykcolor/) struct. |
| [ColorBlend](./colorblend/) | Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient. This class cannot be inherited. |
| [ColorMap](./colormap/) | Defines a map for converting colors. Several methods of the [`ImageAttributes`](../aspose.imaging/imageattributes/) class adjust image colors by using a color-remap table, which is an array of [`ColorMap`](../aspose.imaging/colormap/) structures. Not inheritable. |
| [ColorMatrix](./colormatrix/) | Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [`ImageAttributes`](../aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited. |
| [ColorPalette](./colorpalette/) | Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable. |
| [ColorPaletteHelper](./colorpalettehelper/) | Helper class for color palettes manipulation. |
| [ColorTranslator](./colortranslator/) | Translates colors to and from GDI+ Color structures. This class cannot be inherited. |
| [CompositeException](./compositeexception/) | The composite exception |
| [CustomFontSource](./customfontsource/) | Custom font source provider function |
| [CustomLineCap](./customlinecap/) | Encapsulates a custom user-defined line cap. |
| [DataStreamSupporter](./datastreamsupporter/) | The data stream container. |
| [DisposableObject](./disposableobject/) | Represents disposable object. |
| [EmbeddedImage](./embeddedimage/) | The embedded image class |
| [Figure](./figure/) | The figure. A container for shapes. |
| [FileStreamContainer](./filestreamcontainer/) | Helper for file stream processing. |
| [Font](./font/) | Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited. |
| [FontSettings](./fontsettings/) | General imaging vector formats renderer font settings. |
| [Graphics](./graphics/) | Represents the graphics according to the graphics engine used in the current assembly. |
| [GraphicsPath](./graphicspath/) | Represents a series of connected lines and curves. This class cannot be inherited. |
| [Image](./image/) | The image is the base class for all type of images. |
| [ImageAttributes](./imageattributes/) | An [`ImageAttributes`](../aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [`ImageAttributes`](../aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [`ImageAttributes`](../aspose.imaging/imageattributes/) object and pass the path of that [`ImageAttributes`](../aspose.imaging/imageattributes/) object (along with the path of an [`Image`](../aspose.imaging/image/)) to the DrawImage method. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | Represents the image creators registry. |
| [ImageExportersRegistry](./imageexportersregistry/) | Represents the image exporters registry. |
| [ImageLoadersRegistry](./imageloadersregistry/) | Represents the image loaders registry. |
| [ImageOptionsBase](./imageoptionsbase/) | The image base options. |
| [ImageResizeSettings](./imageresizesettings/) | Image resize settings class |
| [IntRange](./intrange/) | Class for representing sequence of elements |
| [License](./license/) | Provides methods to license the component. |
| [LoadOptions](./loadoptions/) | Represents the loading options. |
| [Matrix](./matrix/) | Replaces the GDI+ Matrix. |
| [Metered](./metered/) | Provides metered methods for integration |
| [NonGenericDictionary](./nongenericdictionary/) | Represents a non generic dictionary. |
| [NonGenericList](./nongenericlist/) | Non generic list of objects |
| [ObjectWithBounds](./objectwithbounds/) | The object having bounds. |
| [OpenTypeFontsCache](./opentypefontscache/) | Cache for OpenType fonts that are installed in the system. |
| [PageExportingAction](./pageexportingaction/) | Delegate for firing before page is exported |
| [Pen](./pen/) | Defines an object used to draw lines, curves and figures. |
| [PixelDataFormat](./pixeldataformat/) | The pixel data format. This is an immutable object. |
| [ProgressEventHandler](./progresseventhandler/) | Progress event handler function reference |
| [RasterCachedImage](./rastercachedimage/) | Represents a raster image supporting raster graphics operations. This image caches pixel data when required. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage/) | The raster multipage image |
| [RasterImage](./rasterimage/) | Represents a raster image supporting raster graphics operations. |
| [RawDataSettings](./rawdatasettings/) | The raw data settings |
| [Region](./region/) | Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited. |
| [RemoveBackgroundSettings](./removebackgroundsettings/) | The remve background settings |
| [ResolutionSetting](./resolutionsetting/) | The resolution setting for image save options. |
| [Shape](./shape/) | The shape. A continuous set of points connected using a specific rule. |
| [ShapeSegment](./shapesegment/) | Represents a shape segment. A segment is a line or curve connecting two points. |
| [Source](./source/) | The source is used to contain all relevant information for an object pipe. |
| [SplitStreamContainer](./splitstreamcontainer/) | Represents split stream container which contains the stream and provides stream processing routines. |
| [StreamContainer](./streamcontainer/) | Represents stream container which contains the stream and provides stream processing routines. |
| [StringFormat](./stringformat/) | Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited. |
| [TransparencySupporter](./transparencysupporter/) | The object supporting transparency. |
| [VectorImage](./vectorimage/) | The vector image is the base class for all type of vector images. |
| [VectorMultipageImage](./vectormultipageimage/) | The Vector multipage image |
## Structures

| Structure | Description |
| --- | --- |
| [CmykColor](./cmykcolor/) | The CMYK color of pixel. |
| [Color](./color/) | The color of the pixel. |
| [Point](./point/) | Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane. |
| [PointF](./pointf/) | Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane. |
| [Rectangle](./rectangle/) | Stores a set of four integers that represent the location and size of a rectangle. |
| [RectangleF](./rectanglef/) | Stores a set of four floating-point numbers that represent the location and size of a rectangle. |
| [Size](./size/) | Represents size. |
| [SizeF](./sizef/) | Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | The advanced buffer processor. |
| [IAnimationFrame](./ianimationframe/) | The Animation frame |
| [IBufferProcessor](./ibufferprocessor/) | The buffer processor. |
| [IColorConverter](./icolorconverter/) | The color converter. |
| [IColorPalette](./icolorpalette/) | The color palette interface. |
| [IHasMetadata](./ihasmetadata/) | Image metadata interface. |
| [IImageCreator](./iimagecreator/) | The image creator. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome the necessity to contain each image creator instance in memory and multithreading issues. |
| [IImageDescriptor](./iimagedescriptor/) | The image descriptor. Contains base properties and methods for all other image descriptor types. |
| [IImageExporter](./iimageexporter/) | The image exporter. Can export data from internal Aspose.Imaging format to a specified data format. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance in memory and multithreading issues. |
| [IImageLoader](./iimageloader/) | The image loader. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome the necessity to contain each image loader instance in memory and multithreading issues. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | The color converter for indexed image formats. |
| [IMetadataContainer](./imetadatacontainer/) | Image metadata container interface. |
| [IMultipageImage](./imultipageimage/) | The multipage image interface |
| [IMultipageImageExt](./imultipageimageext/) | The extended multipage image interface |
| [IObjectWithBounds](./iobjectwithbounds/) | Represents an object with bounds. |
| [IOrderedShape](./iorderedshape/) | Represents an ordered shape. An ordered shape is a continuous set of points having a start point and end point. The continuous set of points connected using a specific rule. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | Conforms to the 32-bit ARGB pixels loaded partially. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | The 64-bit ARGB pixels loader. |
| [IPartialPixelLoader](./ipartialpixelloader/) | Conforms to the pixels loaded partially. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | The partial data loader. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | The raster image 32-bit ARGB pixel loader. |
| [IRasterImageArgb64PixelLoader](./irasterimageargb64pixelloader/) | The raster image 64-bit ARGB pixel loader. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | The raster image pixel loader. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | The raster image raw data loader. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods/) | Indicates the way in which the graphic is to be treated after being displayed. |
| [CacheType](./cachetype/) | Specifies the cache type to use. |
| [CharacterSet](./characterset/) | Represents the character set used. |
| [ColorAdjustType](./coloradjusttype/) | Specifies which objects use color adjustment information. |
| [ColorChannelFlag](./colorchannelflag/) | Specifies individual channels in the CMYK (cyan, magenta, yellow, black) color space. This enumeration is used by the SetOutputChannel methods. |
| [ColorCompareMethod](./colorcomparemethod/) | Color comparison method to adjust to nearest neighbor |
| [ColorMatrixFlag](./colormatrixflag/) | Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [`ImageAttributes`](../aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | Colors quantization methods |
| [CompositingQuality](./compositingquality/) | Specifies the quality level to use during compositing. |
| [DashCap](./dashcap/) | Specifies the type of graphic shape to use on both ends of each dash in a dashed line. |
| [DashStyle](./dashstyle/) | Specifies the style of dashed lines drawn with a [`Pen`](../aspose.imaging/pen/) object. |
| [DataRecoveryMode](./datarecoverymode/) | The data recovery mode. |
| [DitheringMethod](./ditheringmethod/) | Dithering method. |
| [DitheringMethods](./ditheringmethods/) | The dithering methods used to control color conversion. |
| [FileFormat](./fileformat/) | One of supported imaging file formats. |
| [FillMode](./fillmode/) | Specifies how the interior of a closed path is filled. |
| [FontStyle](./fontstyle/) | Specifies style information applied to text. |
| [GraphicsUnit](./graphicsunit/) | Specifies the unit of measure for the given data. |
| [HatchStyle](./hatchstyle/) | Specifies the different patterns available for [`HatchBrush`](../aspose.imaging.brushes/hatchbrush/) objects. |
| [HotkeyPrefix](./hotkeyprefix/) | Specifies the type of display for hot-key prefixes that relate to text. |
| [ImageFilterType](./imagefiltertype/) | Image filters to use |
| [InterpolationMode](./interpolationmode/) | The [`InterpolationMode`](../aspose.imaging/interpolationmode/) enumeration specifies the algorithm that is used when images are scaled or rotated. |
| [KnownColor](./knowncolor/) | Specifies the known system colors. |
| [LineCap](./linecap/) | Specifies the available cap styles with which a [`Pen`](../aspose.imaging/pen/) object can end a line. |
| [LineJoin](./linejoin/) | Specifies how to join consecutive line or curve segments in a figure (subpath) contained in a [`GraphicsPath`](../aspose.imaging/graphicspath/) object. |
| [MatrixOrder](./matrixorder/) | Specifies the order for matrix transform operations. |
| [PaletteMiningMethod](./paletteminingmethod/) | The image palette mining method |
| [PdfComplianceVersion](./pdfcomplianceversion/) | Specifies the PDF compliance level to output file. |
| [PenAlignment](./penalignment/) | Specifies the alignment of a [`Pen`](../aspose.imaging/pen/) object in relation to the theoretical, zero-width line. |
| [PenType](./pentype/) | Specifies the type of fill a [`Pen`](../aspose.imaging/pen/) object uses to fill lines. |
| [PixelFormat](./pixelformat/) | The pixel data format actual meaning. |
| [ProcessingType](./processingtype/) | The type of processing. |
| [ResizeType](./resizetype/) | Specifies the resize type. |
| [ResolutionUnit](./resolutionunit/) | Resolution unit enum. |
| [RotateFlipType](./rotatefliptype/) | Specifies how much an image is rotated and the axis used to flip the image. |
| [SeekOrigin](./seekorigin/) | Provides the fields that represent reference points in [`StreamContainer`](../aspose.imaging/streamcontainer/) for seeking. |
| [SmoothingMode](./smoothingmode/) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [StringAlignment](./stringalignment/) | Specifies the alignment of a text string relative to its layout rectangle. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | The enumeration specifies how to substitute digits in a string according to a user's locale or language. |
| [StringFormatFlags](./stringformatflags/) | Specifies the display and layout information for text strings. |
| [StringTrimming](./stringtrimming/) | Specifies how to trim characters from a string that does not completely fit into a layout shape. |
| [TextRenderingHint](./textrenderinghint/) | Specifies the quality of text rendering. |
| [WarpMode](./warpmode/) | Specifies the type of warp transformation applied. |
| [WrapMode](./wrapmode/) | Specifies how a texture or gradient is tiled when it is smaller than the area being filled. |


