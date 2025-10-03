---
title: Class TiffOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.TiffOptions class. The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method
type: docs
weight: 10520
url: /net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initializes a new instance of the `TiffOptions` class. By default little endian convention is used. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initializes a new instance of the `TiffOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage/) { get; set; } | Gets or sets the alpha storage option. Options other than Unspecified are used when there are more than 3 [`SamplesPerPixel`](./samplesperpixel/) defined. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist/) { get; set; } | Gets or sets the artist. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel/) { get; } | Gets the bits per pixel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample/) { get; set; } | Gets or sets the bits per sample. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder/) { get; set; } | Gets or sets a value indicating the tiff byte order. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap/) { get; set; } | Gets or sets the color map. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality/) { get; set; } | Gets or sets compressed image quality. Used with the Jpeg compression. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression/) { get; set; } | Gets or sets the compression. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright/) { get; set; } | Gets or sets the copyright. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime/) { get; set; } | Gets or sets the date and time. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport/) { get; set; } | Gets or sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname/) { get; set; } | Gets or sets the name of the document. |
| override [ExifData](../../aspose.imaging.imageoptions/tiffoptions/exifdata/) { get; set; } | Gets or sets Exif data. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd/) { get; } | Gets or sets the pointer to EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples/) { get; } | Gets the extra samples values. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options/) { get; set; } | Gets or sets the fax t4 options. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard/) { get; set; } | Gets or sets the TIFF file standard. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder/) { get; set; } | Gets or sets the byte bits fill order. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints/) { get; set; } | Gets or sets the halftone hints. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile/) { get; set; } | Gets or sets the Icc profile stream. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription/) { get; set; } | Gets or sets the image description. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength/) { get; set; } | Gets or sets the image length. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth/) { get; set; } | Gets or sets the image width. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames/) { get; set; } | Gets or sets the ink names. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Gets a value indicating whether the extra samples is present. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled/) { get; } | Gets a value indicating whether image is tiled. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid/) { get; } | Gets a value indicating whether the `TiffOptions` have been properly configured. Use Validate method as to find the failure reason. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Gets or sets the max sample value. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Gets or sets the min sample value. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation/) { get; set; } | Gets or sets the orientation. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename/) { get; set; } | Gets or sets the page name. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber/) { get; set; } | Gets or sets the page number tag. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette/) { get; set; } | Gets or sets the color palette. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric/) { get; set; } | Gets or sets the photometric. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Gets or sets the planar configuration. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor/) { get; set; } | Gets or sets the predictor for LZW compression. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether components must be premultiplied. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Gets or sets the resolution unit. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Gets or sets the rows per strip. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat/) { get; set; } | Gets or sets the sample format. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel/) { get; } | Gets the samples per pixel. To change this property value use the [`BitsPerSample`](./bitspersample/) property setter. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Gets or sets the scanner manufacturer. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel/) { get; set; } | Gets or sets the scanner model. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype/) { get; set; } | Gets or sets the software type. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Gets or sets the strip byte counts. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Gets or sets the strip offsets. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype/) { get; set; } | Gets or sets a general indication of the kind of data contained in this subfile. |
| [TagCount](../../aspose.imaging.imageoptions/tiffoptions/tagcount/) { get; } | Gets the tag count. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags/) { get; set; } | Gets or sets the tags. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter/) { get; set; } | Gets or sets the target printer. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding/) { get; set; } | Gets or sets the threshholding. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Gets or sets the tile byte counts. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength/) { get; set; } | Gets ot sets tile length. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Gets or sets the tile offsets. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth/) { get; set; } | Gets ot sets tile width. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages/) { get; } | Gets the total pages. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount/) { get; } | Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor/) { get; set; } | Gets or sets image author, which used by Windows Explorer. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment/) { get; set; } | Gets or sets comment on image, which used by Windows Explorer. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Gets or sets subject image, which used by Windows Explorer. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition/) { get; set; } | Gets or sets the x position. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject/) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle/) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution/) { get; set; } | Gets or sets the x resolution. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Gets or sets the YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Gets or sets the subsampling factors for YCbCr photometric. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition/) { get; set; } | Gets or sets the y position. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution/) { get; set; } | Gets or sets the y resolution. |

## Methods

| Name | Description |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag/)(TiffDataType) | Adds a new tag. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Adds the tags. |
| override [Clone](../../aspose.imaging.imageoptions/tiffoptions/clone/)() | Clones this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Gets the instance of the tag by type. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Determines whether tag is present in the options or not. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag/)(TiffTags) | Removes the tag. |
| [RemoveTags](../../aspose.imaging.imageoptions/tiffoptions/removetags/)(params TiffTags[]) | Removes the tags. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate/)() | Validates if options have valid combination of tags |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Gets the valid tags count. |

## Examples

This example demonstrates the use of different classes from SaveOptions Namespace for export purposes. An image of type Gif is loaded into an instance of Image and then exported out to several formats.

```csharp
[C#]

string dir = "c:\\temp\\";

//Load an existing image (of type Gif) in an instance of Image class
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Export to BMP file format using the default options
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Export to JPEG file format using the default options
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Export to PNG file format using the default options
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Export to TIFF file format using the default options
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. These pages will be presented as frames in the output TIFF.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface.

```csharp
[C#]

//Create an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Create an instance of TiffOptions and set its various properties
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Set the source for the instance of ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Create and initialize an instance of Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Clear Graphics surface
        graphics.Clear(Color.Wheat);

        //Create an instance of GraphicsPath class
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Create an instance of Figure class
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Add Shapes to Figure object
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Add Figure object to GraphicsPath
        graphicspath.AddFigure(figure);

        //Draw path with Pen object of color Black
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // save all changes.
        image.Save();
    }
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


