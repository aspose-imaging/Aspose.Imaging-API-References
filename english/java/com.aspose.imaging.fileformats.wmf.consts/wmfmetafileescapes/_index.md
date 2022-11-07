---
title: WmfMetafileEscapes
second_title: Aspose.Imaging for Java API Reference
description: The MetafileEscapes Enumeration specifies printer driver functionality that might not be directly accessible through WMF records defined in the RecordType Enumeration section 2.1.1.1.
type: docs
weight: 24
url: /java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

The MetafileEscapes Enumeration specifies printer driver functionality that might not be directly accessible through WMF records defined in the RecordType Enumeration (section 2.1.1.1).
## Fields

| Field | Description |
| --- | --- |
| [Newframe](#Newframe) | Notifies the printer driver that the application has finished writing to a page. |
| [Abortdoc](#Abortdoc) | Stops processing the current document. |
| [Nextband](#Nextband) | Notifies the printer driver that the application has finished writing to a band. |
| [Setcolortable](#Setcolortable) | Sets color table values. |
| [Getcolortable](#Getcolortable) | Gets color table values. |
| [Flushout](#Flushout) | Causes all pending output to be flushed to the output device. |
| [Draftmode](#Draftmode) | Indicates that the printer driver SHOULD print text only, and no graphics. |
| [Queryescsupport](#Queryescsupport) | Queries a printer driver to determine whether a specific escape function is supported on the output device it drives. |
| [Setabortproc](#Setabortproc) | Sets the application-defined function that allows a print job to be canceled during printing. |
| [Startdoc](#Startdoc) | Notifies the printer driver that a new print job is starting. |
| [Enddoc](#Enddoc) | Notifies the printer driver that the current print job is ending. |
| [Getphyspagesize](#Getphyspagesize) | Retrieves the physical page size currently selected on an output device. |
| [Getprintingoffset](#Getprintingoffset) | Retrieves the offset from the upper-left corner of the physical page where the actual printing or drawing begins. |
| [Getscalingfactor](#Getscalingfactor) | Retrieves the scaling factors for the x-axis and the y-axis of a printer. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Used to embed an enhanced metafile format (EMF) metafile within a WMF metafile. |
| [Setpenwidth](#Setpenwidth) | Sets the width of a pen in pixels. |
| [Setcopycount](#Setcopycount) | Sets the number of copies. |
| [Setpapersource](#Setpapersource) | Sets the source, such as a particular paper tray or bin on a printer, for output forms. |
| [Passthrough](#Passthrough) | This record passes through arbitrary data. |
| [Gettechnology](#Gettechnology) | Gets information concerning graphics technology that is supported on a device. |
| [Setlinecap](#Setlinecap) | Specifies the line-drawing mode to use in output to a device. |
| [Setlinejoin](#Setlinejoin) | Specifies the line-joining mode to use in output to a device. |
| [Setmiterlimit](#Setmiterlimit) | Sets the limit for the length of miter joins to use in output to a device. |
| [Bandinfo](#Bandinfo) | Retrieves or specifies settings concerning banding on a device, such as the number of bands. |
| [Drawpatternrect](#Drawpatternrect) | Draws a rectangle with a defined pattern. |
| [Getvectorpensize](#Getvectorpensize) | Retrieves the physical pen size currently defined on a device. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Retrieves the physical brush size currently defined on a device. |
| [Enableduplex](#Enableduplex) | Enables or disables double-sided (duplex) printing on a device. |
| [Getsetpaperbins](#Getsetpaperbins) | Retrieves or specifies the source of output forms on a device. |
| [Getsetprintorient](#Getsetprintorient) | Retrieves or specifies the paper orientation on a device. |
| [Enumpaperbins](#Enumpaperbins) | Retrieves information concerning the sources of different forms on an output device. |
| [Setdibscaling](#Setdibscaling) | Specifies the scaling of device-independent bitmaps (DIBs). |
| [Epsprinting](#Epsprinting) | Indicates the start and end of an encapsulated PostScript (EPS) section. |
| [Enumpapermetrics](#Enumpapermetrics) | Queries a printer driver for paper dimensions and other forms data. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Retrieves or specifies paper dimensions and other forms data on an output device. |
| [PostscriptData](#PostscriptData) | Sends arbitrary PostScript data to an output device. |
| [PostscriptIgnore](#PostscriptIgnore) | Notifies an output device to ignore PostScript data. |
| [Getdeviceunits](#Getdeviceunits) | Gets the device units currently configured on an output device. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Gets extended text metrics currently configured on an output device. |
| [Getpairkerntable](#Getpairkerntable) | Gets the font kern table currently defined on an output device. |
| [Exttextout](#Exttextout) | Draws text using the currently selected font, background color, and text color. |
| [Getfacename](#Getfacename) | Gets the font face name currently configured on a device. |
| [Downloadface](#Downloadface) | Sets the font face name on a device. |
| [MetafileDriver](#MetafileDriver) | Queries a printer driver about the support for metafiles on an output device. |
| [Querydibsupport](#Querydibsupport) | Queries the printer driver about its support for DIBs on an output device. |
| [BeginPath](#BeginPath) | Opens a path. |
| [ClipToPath](#ClipToPath) | Defines a clip region that is bounded by a path. |
| [EndPath](#EndPath) | Ends a path. |
| [OpenChannel](#OpenChannel) | The same as STARTDOC specified with a NULL document and output filename, data in raw mode, and a type of zero. |
| [Downloadheader](#Downloadheader) | Instructs the printer driver to download sets of PostScript procedures. |
| [CloseChannel](#CloseChannel) | The same as ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Sends arbitrary data directly to a printer driver, which is expected to process this data only when in PostScript mode. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Sends arbitrary data directly to the printer driver. |
| [PostscriptIdentify](#PostscriptIdentify) | Sets the printer driver to either PostScript or GDI mode. |
| [PostscriptInjection](#PostscriptInjection) | Inserts a block of raw data into a PostScript stream. |
| [Checkjpegformat](#Checkjpegformat) | Checks whether the printer supports a JPEG image. |
| [Checkpngformat](#Checkpngformat) | Checks whether the printer supports a PNG image. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Gets information on a specified feature setting for a PostScript printer driver. |
| [MxdcEscape](#MxdcEscape) | Enables applications to write documents to a file or to a printer in XML Paper Specification (XPS) format. |
| [Spclpassthrough2](#Spclpassthrough2) | Enables applications to include private procedures and other arbitrary data in documents. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Notifies the printer driver that the application has finished writing to a page.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Stops processing the current document.

### Nextband {#Nextband}
```
public static final int Nextband
```


Notifies the printer driver that the application has finished writing to a band.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Sets color table values.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Gets color table values.

### Flushout {#Flushout}
```
public static final int Flushout
```


Causes all pending output to be flushed to the output device.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Indicates that the printer driver SHOULD print text only, and no graphics.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Queries a printer driver to determine whether a specific escape function is supported on the output device it drives.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Sets the application-defined function that allows a print job to be canceled during printing.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Notifies the printer driver that a new print job is starting.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Notifies the printer driver that the current print job is ending.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Retrieves the physical page size currently selected on an output device.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Retrieves the offset from the upper-left corner of the physical page where the actual printing or drawing begins.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Retrieves the scaling factors for the x-axis and the y-axis of a printer.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Used to embed an enhanced metafile format (EMF) metafile within a WMF metafile.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Sets the width of a pen in pixels.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Sets the number of copies.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Sets the source, such as a particular paper tray or bin on a printer, for output forms.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


This record passes through arbitrary data.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Gets information concerning graphics technology that is supported on a device.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Specifies the line-drawing mode to use in output to a device.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Specifies the line-joining mode to use in output to a device.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Sets the limit for the length of miter joins to use in output to a device.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Retrieves or specifies settings concerning banding on a device, such as the number of bands.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Draws a rectangle with a defined pattern.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Retrieves the physical pen size currently defined on a device.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Retrieves the physical brush size currently defined on a device.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Enables or disables double-sided (duplex) printing on a device.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Retrieves or specifies the source of output forms on a device.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Retrieves or specifies the paper orientation on a device.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Retrieves information concerning the sources of different forms on an output device.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Specifies the scaling of device-independent bitmaps (DIBs).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Indicates the start and end of an encapsulated PostScript (EPS) section.

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Queries a printer driver for paper dimensions and other forms data.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Retrieves or specifies paper dimensions and other forms data on an output device.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Sends arbitrary PostScript data to an output device.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Notifies an output device to ignore PostScript data.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Gets the device units currently configured on an output device.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Gets extended text metrics currently configured on an output device.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Gets the font kern table currently defined on an output device.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Draws text using the currently selected font, background color, and text color.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Gets the font face name currently configured on a device.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Sets the font face name on a device.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Queries a printer driver about the support for metafiles on an output device.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Queries the printer driver about its support for DIBs on an output device.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Opens a path.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Defines a clip region that is bounded by a path. The input MUST be a 16-bit quantity that defines the action to take.

### EndPath {#EndPath}
```
public static final int EndPath
```


Ends a path.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


The same as STARTDOC specified with a NULL document and output filename, data in raw mode, and a type of zero.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Instructs the printer driver to download sets of PostScript procedures.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


The same as ENDDOC. See OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Sends arbitrary data directly to a printer driver, which is expected to process this data only when in PostScript mode. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Sends arbitrary data directly to the printer driver.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Sets the printer driver to either PostScript or GDI mode.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Inserts a block of raw data into a PostScript stream. The input MUST be a 32-bit quantity specifying the number of bytes to inject, a 16-bit quantity specifying the injection point, and a 16-bit quantity specifying the page number, followed by the bytes to inject.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Checks whether the printer supports a JPEG image.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Checks whether the printer supports a PNG image.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Gets information on a specified feature setting for a PostScript printer driver.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Enables applications to write documents to a file or to a printer in XML Paper Specification (XPS) format.

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Enables applications to include private procedures and other arbitrary data in documents.

