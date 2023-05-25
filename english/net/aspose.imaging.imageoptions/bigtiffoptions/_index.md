---
title: BigTiffOptions
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10010
url: /net/aspose.imaging.imageoptions/bigtiffoptions/
---
## BigTiffOptions class

The BigTiff image options.

```csharp
public sealed class BigTiffOptions : TiffOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [BigTiffOptions](bigtiffoptions)(TiffDataType[]) | Initializes a new instance of the [`BigTiffOptions`](../bigtiffoptions) class. |
| [BigTiffOptions](bigtiffoptions)(TiffExpectedFormat) | Initializes a new instance of the [`BigTiffOptions`](../bigtiffoptions) class. By default little endian convention is used. |
| [BigTiffOptions](bigtiffoptions)(TiffOptions) | Initializes a new instance of the [`BigTiffOptions`](../bigtiffoptions) class. |
| [BigTiffOptions](bigtiffoptions)(TiffExpectedFormat, TiffByteOrder) | Initializes a new instance of the [`BigTiffOptions`](../bigtiffoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Gets or sets the alpha storage option. Options other than Unspecified are used when there are more than 3 [`SamplesPerPixel`](../tiffoptions/samplesperpixel) defined. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Gets or sets the artist. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Gets the bits per pixel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Gets or sets the bits per sample. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Gets or sets a value indicating the tiff byte order. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Gets or sets the color map. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Gets or sets compressed image quality. Used with the Jpeg compression. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Gets or sets the compression. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Gets or sets the copyright. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Gets or sets the date and time. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Gets or sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Gets or sets the name of the document. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Gets or sets the pointer to EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Gets the extra samples values. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Gets or sets the fax t4 options. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Gets or sets the TIFF file standard. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Gets or sets the byte bits fill order. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Gets or sets the halftone hints. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Gets or sets the Icc profile stream. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Gets or sets the image description. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Gets or sets the image length. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Gets or sets the image width. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Gets or sets the ink names. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Gets a value indicating whether the extra samples is present. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Gets a value indicating whether image is tiled. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Gets a value indicating whether the [`TiffOptions`](../tiffoptions) have been properly configured. Use Validate method as to find the failure reason. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Gets or sets the max sample value. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Gets or sets the min sample value. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | The multipage options |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Gets or sets the orientation. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Gets or sets the page name. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Gets or sets the page number tag. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Gets or sets the color palette. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Gets or sets the photometric. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Gets or sets the planar configuration. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Gets or sets the predictor for LZW compression. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Gets or sets a value indicating whether components must be premultiplied. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Gets or sets the progress event handler. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Gets or sets the resolution settings. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Gets or sets the resolution unit. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Gets or sets the rows per strip. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Gets or sets the sample format. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Gets the samples per pixel. To change this property value use the [`BitsPerSample`](../tiffoptions/bitspersample) property setter. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Gets or sets the scanner manufacturer. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Gets or sets the scanner model. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Gets or sets the software type. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Gets or sets the source to create image in. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Gets or sets the strip byte counts. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Gets or sets the strip offsets. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Gets or sets a general indication of the kind of data contained in this subfile. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Gets or sets the tags. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Gets or sets the target printer. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Gets or sets the threshholding. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Gets or sets the tile byte counts. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Gets ot sets tile length. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Gets or sets the tile offsets. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Gets ot sets tile width. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Gets the total pages. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Gets or sets the vector rasterization options. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Gets or sets the XMP metadata container. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Gets or sets image author, which used by Windows Explorer. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Gets or sets comment on image, which used by Windows Explorer. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Gets or sets subject image, which used by Windows Explorer. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Gets or sets the x position. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Gets or sets the x resolution. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Gets or sets the YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Gets or sets the subsampling factors for YCbCr photometric. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Gets or sets the y position. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Gets or sets the y resolution. |

## Methods

| Name | Description |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Adds a new tag. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Adds the tags. |
| override [Clone](../../aspose.imaging.imageoptions/bigtiffoptions/clone)() | Clones this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Gets the instance of the tag by type. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Determines whether tag is present in the options or not. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Removes the tag. |
| [RemoveTags](../../aspose.imaging.imageoptions/tiffoptions/removetags)(params TiffTags[]) | Removes the tags. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Validates if options have valid combination of tags |

### See Also

* class [TiffOptions](../tiffoptions)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
