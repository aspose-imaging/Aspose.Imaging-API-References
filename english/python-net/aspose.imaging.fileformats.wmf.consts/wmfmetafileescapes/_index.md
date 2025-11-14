---
title: WmfMetafileEscapes Enumeration
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

The MetafileEscapes Enumeration specifies printer driver functionality that might not be<br/>                directly accessible through WMF records defined in the RecordType Enumeration (section 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ABORTDOC | Stops processing the current document. |
| BANDINFO | Retrieves or specifies settings concerning banding on a device, such as the<br/>                number of bands. |
| BEGIN_PATH | Opens a path. |
| CHECKJPEGFORMAT | Checks whether the printer supports a JPEG image. |
| CHECKPNGFORMAT | Checks whether the printer supports a PNG image. |
| CLIP_TO_PATH | Defines a clip region that is bounded by a path. The input MUST be a 16-bit<br/>                quantity that defines the action to take. |
| CLOSE_CHANNEL | The same as ENDDOC. See OPEN_CHANNEL. |
| DOWNLOADFACE | Sets the font face name on a device. |
| DOWNLOADHEADER | Instructs the printer driver to download sets of PostScript procedures. |
| DRAFTMODE | Indicates that the printer driver SHOULD print text only, and no graphics. |
| DRAWPATTERNRECT | Draws a rectangle with a defined pattern. |
| ENABLEDUPLEX | Enables or disables double-sided (duplex) printing on a device. |
| ENCAPSULATED_POSTSCRIPT | Sends arbitrary data directly to the printer driver. |
| ENDDOC | Notifies the printer driver that the current print job is ending. |
| END_PATH | Ends a path. |
| ENUMPAPERBINS | Retrieves information concerning the sources of different forms on an<br/>                output device. |
| ENUMPAPERMETRICS | Queries a printer driver for paper dimensions and other forms data. |
| EPSPRINTING | Indicates the start and end of an encapsulated PostScript (EPS) section. |
| EXTTEXTOUT | Draws text using the currently selected font, background color, and text color. |
| FLUSHOUT | Causes all pending output to be flushed to the output device. |
| GETCOLORTABLE | Gets color table values. |
| GETDEVICEUNITS | Gets the device units currently configured on an output device. |
| GETEXTENDEDTEXTMETRICS | Gets extended text metrics currently configured on an output<br/>                device. |
| GETFACENAME | Gets the font face name currently configured on a device. |
| GETPAIRKERNTABLE | Gets the font kern table currently defined on an output device. |
| GETPHYSPAGESIZE | Retrieves the physical page size currently selected on an output device. |
| GETPRINTINGOFFSET | Retrieves the offset from the upper-left corner of the physical page<br/>                where the actual printing or drawing begins. |
| GETSCALINGFACTOR | Retrieves the scaling factors for the x-axis and the y-axis of a printer. |
| GETSETPAPERBINS | Retrieves or specifies the source of output forms on a device. |
| GETSETPAPERMETRICS | Retrieves or specifies paper dimensions and other forms data on an<br/>                output device. |
| GETSETPRINTORIENT | Retrieves or specifies the paper orientation on a device. |
| GETTECHNOLOGY | Gets information concerning graphics technology that is supported on a<br/>                device. |
| GETVECTORBRUSHSIZE | Retrieves the physical brush size currently defined on a device. |
| GETVECTORPENSIZE | Retrieves the physical pen size currently defined on a device. |
| GET_PS_FEATURESETTING | Gets information on a specified feature setting for a PostScript<br/>                printer driver. |
| METAFILE_DRIVER | Queries a printer driver about the support for metafiles on an output<br/>                device. |
| META_ESCAPE_ENHANCED_METAFILE | Used to embed an enhanced metafile format (EMF)<br/>                metafile within a WMF metafile. |
| MXDC_ESCAPE | Enables applications to write documents to a file or to a printer in XML Paper<br/>                Specification (XPS) format. |
| NEWFRAME | Notifies the printer driver that the application has finished writing to a page. |
| NEXTBAND | Notifies the printer driver that the application has finished writing to a band. |
| OPEN_CHANNEL | The same as STARTDOC specified with a NULL document and output<br/>                filename, data in raw mode, and a type of zero. |
| PASSTHROUGH | This record passes through arbitrary data. |
| POSTSCRIPT_DATA | Sends arbitrary PostScript data to an output device. |
| POSTSCRIPT_IDENTIFY | Sets the printer driver to either PostScript or GDI mode. |
| POSTSCRIPT_IGNORE | Notifies an output device to ignore PostScript data. |
| POSTSCRIPT_INJECTION | Inserts a block of raw data into a PostScript stream. The input<br/>                MUST be a 32-bit quantity specifying the number of bytes to inject, a 16-bit quantity<br/>                specifying the injection point, and a 16-bit quantity specifying the page number, followed by<br/>                the bytes to inject. |
| POSTSCRIPT_PASSTHROUGH | Sends arbitrary data directly to a printer driver, which is<br/>                expected to process this data only when in PostScript mode. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Queries the printer driver about its support for DIBs on an output device. |
| QUERYESCSUPPORT | Queries a printer driver to determine whether a specific escape function<br/>                is supported on the output device it drives. |
| SETABORTPROC | Sets the application-defined function that allows a print job to be canceled<br/>                during printing. |
| SETCOLORTABLE | Sets color table values. |
| SETCOPYCOUNT | Sets the number of copies. |
| SETDIBSCALING | Specifies the scaling of device-independent bitmaps (DIBs). |
| SETLINECAP | Specifies the line-drawing mode to use in output to a device. |
| SETLINEJOIN | Specifies the line-joining mode to use in output to a device. |
| SETMITERLIMIT | Sets the limit for the length of miter joins to use in output to a device. |
| SETPAPERSOURCE | Sets the source, such as a particular paper tray or bin on a printer, for<br/>                output forms. |
| SETPENWIDTH | Sets the width of a pen in pixels. |
| SPCLPASSTHROUGH2 | Enables applications to include private procedures and other arbitrary<br/>                data in documents. |
| STARTDOC | Notifies the printer driver that a new print job is starting. |
