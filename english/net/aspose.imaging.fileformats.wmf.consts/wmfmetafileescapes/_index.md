---
title: Enum WmfMetafileEscapes
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfMetafileEscapes enum. The MetafileEscapes Enumeration specifies printer driver functionality that might not be directly accessible through WMF records defined in the RecordType Enumeration section 2.1.1.1
type: docs
weight: 8410
url: /net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

The MetafileEscapes Enumeration specifies printer driver functionality that might not be directly accessible through WMF records defined in the RecordType Enumeration (section 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Newframe | `1` | Notifies the printer driver that the application has finished writing to a page. |
| Abortdoc | `2` | Stops processing the current document. |
| Nextband | `3` | Notifies the printer driver that the application has finished writing to a band. |
| Setcolortable | `4` | Sets color table values. |
| Getcolortable | `5` | Gets color table values. |
| Flushout | `6` | Causes all pending output to be flushed to the output device. |
| Draftmode | `7` | Indicates that the printer driver SHOULD print text only, and no graphics. |
| Queryescsupport | `8` | Queries a printer driver to determine whether a specific escape function is supported on the output device it drives. |
| Setabortproc | `9` | Sets the application-defined function that allows a print job to be canceled during printing. |
| Startdoc | `10` | Notifies the printer driver that a new print job is starting. |
| Enddoc | `11` | Notifies the printer driver that the current print job is ending. |
| Getphyspagesize | `12` | Retrieves the physical page size currently selected on an output device. |
| Getprintingoffset | `13` | Retrieves the offset from the upper-left corner of the physical page where the actual printing or drawing begins. |
| Getscalingfactor | `14` | Retrieves the scaling factors for the x-axis and the y-axis of a printer. |
| MetaEscapeEnhancedMetafile | `15` | Used to embed an enhanced metafile format (EMF) metafile within a WMF metafile. |
| Setpenwidth | `16` | Sets the width of a pen in pixels. |
| Setcopycount | `17` | Sets the number of copies. |
| Setpapersource | `18` | Sets the source, such as a particular paper tray or bin on a printer, for output forms. |
| Passthrough | `19` | This record passes through arbitrary data. |
| Gettechnology | `20` | Gets information concerning graphics technology that is supported on a device. |
| Setlinecap | `21` | Specifies the line-drawing mode to use in output to a device. |
| Setlinejoin | `22` | Specifies the line-joining mode to use in output to a device. |
| Setmiterlimit | `23` | Sets the limit for the length of miter joins to use in output to a device. |
| Bandinfo | `24` | Retrieves or specifies settings concerning banding on a device, such as the number of bands. |
| Drawpatternrect | `25` | Draws a rectangle with a defined pattern. |
| Getvectorpensize | `26` | Retrieves the physical pen size currently defined on a device. |
| Getvectorbrushsize | `27` | Retrieves the physical brush size currently defined on a device. |
| Enableduplex | `28` | Enables or disables double-sided (duplex) printing on a device. |
| Getsetpaperbins | `29` | Retrieves or specifies the source of output forms on a device. |
| Getsetprintorient | `30` | Retrieves or specifies the paper orientation on a device. |
| Enumpaperbins | `31` | Retrieves information concerning the sources of different forms on an output device. |
| Setdibscaling | `32` | Specifies the scaling of device-independent bitmaps (DIBs). |
| Epsprinting | `33` | Indicates the start and end of an encapsulated PostScript (EPS) section. |
| Enumpapermetrics | `34` | Queries a printer driver for paper dimensions and other forms data. |
| Getsetpapermetrics | `35` | Retrieves or specifies paper dimensions and other forms data on an output device. |
| PostscriptData | `37` | Sends arbitrary PostScript data to an output device. |
| PostscriptIgnore | `38` | Notifies an output device to ignore PostScript data. |
| Getdeviceunits | `42` | Gets the device units currently configured on an output device. |
| Getextendedtextmetrics | `256` | Gets extended text metrics currently configured on an output device. |
| Getpairkerntable | `258` | Gets the font kern table currently defined on an output device. |
| Exttextout | `512` | Draws text using the currently selected font, background color, and text color. |
| Getfacename | `513` | Gets the font face name currently configured on a device. |
| Downloadface | `514` | Sets the font face name on a device. |
| MetafileDriver | `2049` | Queries a printer driver about the support for metafiles on an output device. |
| Querydibsupport | `3073` | Queries the printer driver about its support for DIBs on an output device. |
| BeginPath | `4096` | Opens a path. |
| ClipToPath | `4097` | Defines a clip region that is bounded by a path. The input MUST be a 16-bit quantity that defines the action to take. |
| EndPath | `4098` | Ends a path. |
| OpenChannel | `4110` | The same as STARTDOC specified with a NULL document and output filename, data in raw mode, and a type of zero. |
| Downloadheader | `4111` | Instructs the printer driver to download sets of PostScript procedures. |
| CloseChannel | `4112` | The same as ENDDOC. See OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Sends arbitrary data directly to a printer driver, which is expected to process this data only when in PostScript mode. PostscriptIdentify. |
| EncapsulatedPostscript | `4116` | Sends arbitrary data directly to the printer driver. |
| PostscriptIdentify | `4117` | Sets the printer driver to either PostScript or GDI mode. |
| PostscriptInjection | `4118` | Inserts a block of raw data into a PostScript stream. The input MUST be a 32-bit quantity specifying the number of bytes to inject, a 16-bit quantity specifying the injection point, and a 16-bit quantity specifying the page number, followed by the bytes to inject. |
| Checkjpegformat | `4119` | Checks whether the printer supports a JPEG image. |
| Checkpngformat | `4120` | Checks whether the printer supports a PNG image. |
| GetPsFeaturesetting | `4121` | Gets information on a specified feature setting for a PostScript printer driver. |
| MxdcEscape | `4122` | Enables applications to write documents to a file or to a printer in XML Paper Specification (XPS) format. |
| Spclpassthrough2 | `4568` | Enables applications to include private procedures and other arbitrary data in documents. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


