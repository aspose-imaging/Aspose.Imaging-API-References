---
title: Enum TiffTags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.Enums.TiffTags enum. The tiff tag enum
type: docs
weight: 7850
url: /net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

The tiff tag enum.

```csharp
public enum TiffTags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| SubFileType | `254` | Subfile data descriptor. |
| OsubfileType | `255` | [obsoleted by TIFF rev. 5.0] Kind of data in subfile. |
| ImageWidth | `256` | Image width in pixels. |
| ImageLength | `257` | Image height in pixels. |
| BitsPerSample | `258` | Bits per channel (sample). |
| Compression | `259` | Data compression technique. |
| Photometric | `262` | Photometric interpretation. |
| Thresholding | `263` | [obsoleted by TIFF rev. 5.0] Thresholding used on data. |
| CellWidth | `264` | [obsoleted by TIFF rev. 5.0] Dithering matrix width. |
| CellLength | `265` | [obsoleted by TIFF rev. 5.0] Dithering matrix height. |
| FillOrder | `266` | Data order within a byte. |
| DocumentName | `269` | Name of document which holds for image. |
| ImageDescription | `270` | Information about image. |
| Make | `271` | Scanner manufacturer name. |
| Model | `272` | Scanner model name/number. |
| StripOffsets | `273` | Offsets to data strips. |
| Orientation | `274` | [obsoleted by TIFF rev. 5.0] Image orientation. |
| SamplesPerPixel | `277` | Samples per pixel. |
| RowsPerStrip | `278` | Rows per strip of data. |
| StripByteCounts | `279` | Bytes counts for strips. |
| MinSampleValue | `280` | [obsoleted by TIFF rev. 5.0] Minimum sample value. |
| MaxSampleValue | `281` | [obsoleted by TIFF rev. 5.0] Maximum sample value. |
| Xresolution | `282` | Pixels/resolution in x. |
| Yresolution | `283` | Pixels/resolution in y. |
| PlanarConfig | `284` | Storage organization. |
| PageName | `285` | Page name image is from. |
| Xposition | `286` | X page offset of image lhs. |
| Yposition | `287` | Y page offset of image lhs. |
| FreeOffsets | `288` | [obsoleted by TIFF rev. 5.0] Byte offset to free block. |
| FreeByteCounts | `289` | [obsoleted by TIFF rev. 5.0] Sizes of free blocks. |
| GrayResponseUnit | `290` | [obsoleted by TIFF rev. 6.0] Gray scale curve accuracy. |
| GrayResponseCurve | `291` | [obsoleted by TIFF rev. 6.0] Gray scale response curve. |
| T4Options | `292` | TIFF 6.0 proper name alias for GROUP3OPTIONS. Options for CCITT Group 3 fax encoding. 32 flag bits. |
| T6Options | `293` | Options for CCITT Group 4 fax encoding. 32 flag bits. TIFF 6.0 proper name alias for GROUP4OPTIONS. |
| ResolutionUnit | `296` | Units of resolutions. |
| PageNumber | `297` | Page numbers of multi-page. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] Color curve accuracy. |
| TransferFunction | `301` | Colorimetry info. |
| Software | `305` | Name &amp; release. |
| DateTime | `306` | Creation date and time. |
| Artist | `315` | Creator of image. |
| HostComputer | `316` | Machine where created. |
| Predictor | `317` | Prediction scheme w/ LZW. |
| WhitePoint | `318` | Image white point. |
| PrimaryChromaticities | `319` | Primary chromaticities. |
| ColorMap | `320` | RGB map for pallette image. |
| HalftoneHints | `321` | Highlight + shadow info. |
| TileWidth | `322` | Tile width in pixels. |
| TileLength | `323` | Tile height in pixels. |
| TileOffsets | `324` | Offsets to data tiles. |
| TileByteCounts | `325` | Byte counts for tiles. |
| BadFaxLines | `326` | Lines with wrong pixel count. |
| CleanFaxData | `327` | Regenerated line info. |
| ConsecutiveBadFaxLines | `328` | Max consecutive bad lines. |
| SubIfd | `330` | Subimage descriptors. |
| InkSet | `332` | Inks in separated image. |
| InkNames | `333` | ASCII names of inks. |
| NumberOfInks | `334` | Number of inks. |
| DotRange | `336` | 0% and 100% dot codes. |
| TargetPrinter | `337` | Separation target. |
| ExtraSamples | `338` | Information about extra samples. |
| SampleFormat | `339` | Data sample format. |
| SminSampleValue | `340` | Variable MinSampleValue. |
| SmaxSampleValue | `341` | Variable MaxSampleValue. |
| TransferRange | `342` | Variable TransferRange |
| ClipPath | `343` | ClipPath. Introduced post TIFF rev 6.0 by Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Introduced post TIFF rev 6.0 by Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Introduced post TIFF rev 6.0 by Adobe TIFF technote 2. |
| Indexed | `346` | Indexed. Introduced post TIFF rev 6.0 by Adobe TIFF Technote 3. |
| JpegTables | `347` | JPEG table stream. Introduced post TIFF rev 6.0. |
| OpiProxy | `351` | OPI Proxy. Introduced post TIFF rev 6.0 by Adobe TIFF technote. |
| JpegProc | `512` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] JPEG processing algorithm. |
| JpegInerchangeFormat | `513` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Pointer to SOI marker. |
| JpegInterchangeFormatLength | `514` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] JFIF stream length |
| JpegRestartInterval | `515` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Restart interval length. |
| JpegLosslessPredictors | `517` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Lossless proc predictor. |
| JpegPointTransform | `518` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Lossless point transform. |
| JpegQTables | `519` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Q matrice offsets. |
| JpegDCtables | `520` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] DCT table offsets. |
| JpegACtables | `521` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] AC coefficient offsets. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr transform. |
| YcbcrSubSampling | `530` | YCbCr subsampling factors. |
| YcbcrPositioning | `531` | Subsample positioning. |
| ReferenceBlackWhite | `532` | Colorimetry info. |
| XmlPacket | `700` | XML packet. Introduced post TIFF rev 6.0 by Adobe XMP Specification, January 2004. |
| OpiImageid | `32781` | OPI ImageID. Introduced post TIFF rev 6.0 by Adobe TIFF technote. |
| Refpts | `32953` | Image reference points. Private tag registered to Island Graphics. |
| Copyright | `33432` | Copyright string. This tag is listed in the TIFF rev. 6.0 w/ unknown ownership. |
| PhotoshopResources | `34377` | Photoshop image resources. |
| IccProfile | `34675` | The embedded ICC device profile |
| ExifIfdPointer | `34665` | A pointer to the Exif IFD. |
| XPTitle | `40091` | Information about image, used by Windows Explorer. The XPTitle is ignored by Windows Explorer if the ImageDescription tag exists. |
| XPComment | `40092` | Comment on image, used by Windows Explorer. |
| XPAuthor | `40093` | Image Author, used by Windows Explorer. The XPAuthor is ignored by Windows Explorer if the Artist tag exists. |
| XPKeywords | `40094` | Image Keywords, used by Windows Explorer. |
| XPSubject | `40095` | Subject image, used by Windows Explorer. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums/)
* assembly [Aspose.Imaging](../../)


