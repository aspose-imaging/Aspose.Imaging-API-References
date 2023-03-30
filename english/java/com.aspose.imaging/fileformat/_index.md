---
title: FileFormat
second_title: Aspose.Imaging for Java API Reference
description: One of supported imaging file formats.
type: docs
weight: 45
url: /java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

One of supported imaging file formats.
## Fields

| Field | Description |
| --- | --- |
| [Undefined](#Undefined) | Undefined file format. |
| [Custom](#Custom) | Custom file format. |
| [Bmp](#Bmp) | Bmp (Dib) file format. |
| [Gif](#Gif) | Gif file format. |
| [Jpeg](#Jpeg) | Jpeg file format. |
| [Png](#Png) | Png file format. |
| [Tiff](#Tiff) | Tiff file format. |
| [Psd](#Psd) | Psd file format. |
| [Pdf](#Pdf) | Pdf file format |
| [Ico](#Ico) | The ico format |
| [Jpeg2000](#Jpeg2000) | Jpeg2000 file format |
| [Djvu](#Djvu) | Djvu file format |
| [Webp](#Webp) | The webp file format |
| [Emf](#Emf) | The Emf/Emf+ file format |
| [Dicom](#Dicom) | The dicom format |
| [Svg](#Svg) | SVG file format |
| [Wmf](#Wmf) | The Wmf file format |
| [Dng](#Dng) | The DNG file format |
| [Odg](#Odg) | The Open document graphic format |
| [Eps](#Eps) | The Encapsulated PostScript format |
| [Cdr](#Cdr) | The CDR file format |
| [Cmx](#Cmx) | The CMX file format |
| [Otg](#Otg) | The otg file format |
| [Html5Canvas](#Html5Canvas) | The Html5 Canvas format |
| [Apng](#Apng) | The animated Png file format. |
| [Tga](#Tga) | The Truevision TGA file format. |
| [Dxf](#Dxf) | The AutoCAD Drawing Exchange Format. |
| [Emz](#Emz) | The emz, compressed emf |
| [Wmz](#Wmz) | The WMZ, compressed wmf |
| [Svgz](#Svgz) | The SVGZ, compressed svg |
| [FOdg](#FOdg) | The fodg, flat odg format |
| [BigTiff](#BigTiff) | The Big Tiff format. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Use an absolute path to the file
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// A string represenation of the file format.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### Undefined {#Undefined}
```
public static final long Undefined
```


Undefined file format.

### Custom {#Custom}
```
public static final long Custom
```


Custom file format.

### Bmp {#Bmp}
```
public static final long Bmp
```


Bmp (Dib) file format.

### Gif {#Gif}
```
public static final long Gif
```


Gif file format.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Jpeg file format.

### Png {#Png}
```
public static final long Png
```


Png file format.

### Tiff {#Tiff}
```
public static final long Tiff
```


Tiff file format.

### Psd {#Psd}
```
public static final long Psd
```


Psd file format.

### Pdf {#Pdf}
```
public static final long Pdf
```


Pdf file format

### Ico {#Ico}
```
public static final long Ico
```


The ico format

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Jpeg2000 file format

### Djvu {#Djvu}
```
public static final long Djvu
```


Djvu file format

### Webp {#Webp}
```
public static final long Webp
```


The webp file format

### Emf {#Emf}
```
public static final long Emf
```


The Emf/Emf+ file format

### Dicom {#Dicom}
```
public static final long Dicom
```


The dicom format

### Svg {#Svg}
```
public static final long Svg
```


SVG file format

### Wmf {#Wmf}
```
public static final long Wmf
```


The Wmf file format

### Dng {#Dng}
```
public static final long Dng
```


The DNG file format

### Odg {#Odg}
```
public static final long Odg
```


The Open document graphic format

### Eps {#Eps}
```
public static final long Eps
```


The Encapsulated PostScript format

### Cdr {#Cdr}
```
public static final long Cdr
```


The CDR file format

### Cmx {#Cmx}
```
public static final long Cmx
```


The CMX file format

### Otg {#Otg}
```
public static final long Otg
```


The otg file format

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


The Html5 Canvas format

### Apng {#Apng}
```
public static final long Apng
```


The animated Png file format.

### Tga {#Tga}
```
public static final long Tga
```


The Truevision TGA file format.

### Dxf {#Dxf}
```
public static final long Dxf
```


The AutoCAD Drawing Exchange Format.

### Emz {#Emz}
```
public static final long Emz
```


The emz, compressed emf

### Wmz {#Wmz}
```
public static final long Wmz
```


The WMZ, compressed wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


The SVGZ, compressed svg

### FOdg {#FOdg}
```
public static final long FOdg
```


The fodg, flat odg format

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


The Big Tiff format.

