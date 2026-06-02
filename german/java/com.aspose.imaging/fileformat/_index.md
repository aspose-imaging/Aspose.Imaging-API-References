---
title: "Dateiformat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eines der unterstützten Bilddateiformate."
type: docs
weight: 45
url: /de/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Eines der unterstützten Bilddateiformate.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Unknown](#Unknown) | Unbekanntes Dateiformat. |
| [Custom](#Custom) | Benutzerdefiniertes Dateiformat. |
| [Bmp](#Bmp) | Bmp (Dib) Dateiformat. |
| [Gif](#Gif) | Gif Dateiformat. |
| [Jpeg](#Jpeg) | Jpeg Dateiformat. |
| [Png](#Png) | Png Dateiformat. |
| [Tiff](#Tiff) | Tiff Dateiformat. |
| [Psd](#Psd) | Psd Dateiformat. |
| [Pdf](#Pdf) | Pdf Dateiformat |
| [Ico](#Ico) | Das ico-Format |
| [Jpeg2000](#Jpeg2000) | Jpeg2000 Dateiformat |
| [Djvu](#Djvu) | Djvu Dateiformat |
| [Webp](#Webp) | Das webp-Dateiformat |
| [Emf](#Emf) | Das Emf/Emf+ Dateiformat |
| [Dicom](#Dicom) | Das dicom-Format |
| [Svg](#Svg) | SVG Dateiformat |
| [Wmf](#Wmf) | Das Wmf-Dateiformat |
| [Dng](#Dng) | Das DNG-Dateiformat |
| [Odg](#Odg) | Das Open Document Graphic-Format |
| [Eps](#Eps) | Das Encapsulated PostScript-Format |
| [Cdr](#Cdr) | Das CDR-Dateiformat |
| [Cmx](#Cmx) | Das CMX-Dateiformat |
| [Otg](#Otg) | Das otg-Dateiformat |
| [Html5Canvas](#Html5Canvas) | Das Html5 Canvas-Format |
| [Apng](#Apng) | Das animierte Png-Dateiformat. |
| [Tga](#Tga) | Das Truevision TGA-Dateiformat. |
| [Dxf](#Dxf) | Das AutoCAD Drawing Exchange-Format. |
| [Emz](#Emz) | Das emz, komprimiertes emf |
| [Wmz](#Wmz) | Das WMZ, komprimiertes wmf |
| [Svgz](#Svgz) | Das SVGZ, komprimiertes svg |
| [FOdg](#FOdg) | Das fodg, flaches odg-Format |
| [Avif](#Avif) | Das AVIF-Dateiformat. |
| [BigTiff](#BigTiff) | Das Big Tiff-Format. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Verwenden Sie einen absoluten Pfad zur Datei
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Eine Zeichenkettenrepräsentation des Dateiformats.
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

### Unknown {#Unknown}
```
public static final long Unknown
```


Unbekanntes Dateiformat.

### Custom {#Custom}
```
public static final long Custom
```


Benutzerdefiniertes Dateiformat.

### Bmp {#Bmp}
```
public static final long Bmp
```


Bmp (Dib) Dateiformat.

### Gif {#Gif}
```
public static final long Gif
```


Gif Dateiformat.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Jpeg Dateiformat.

### Png {#Png}
```
public static final long Png
```


Png Dateiformat.

### Tiff {#Tiff}
```
public static final long Tiff
```


Tiff Dateiformat.

### Psd {#Psd}
```
public static final long Psd
```


Psd Dateiformat.

### Pdf {#Pdf}
```
public static final long Pdf
```


Pdf Dateiformat

### Ico {#Ico}
```
public static final long Ico
```


Das ico-Format

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Jpeg2000 Dateiformat

### Djvu {#Djvu}
```
public static final long Djvu
```


Djvu Dateiformat

### Webp {#Webp}
```
public static final long Webp
```


Das webp-Dateiformat

### Emf {#Emf}
```
public static final long Emf
```


Das Emf/Emf+ Dateiformat

### Dicom {#Dicom}
```
public static final long Dicom
```


Das dicom-Format

### Svg {#Svg}
```
public static final long Svg
```


SVG Dateiformat

### Wmf {#Wmf}
```
public static final long Wmf
```


Das Wmf-Dateiformat

### Dng {#Dng}
```
public static final long Dng
```


Das DNG-Dateiformat

### Odg {#Odg}
```
public static final long Odg
```


Das Open Document Graphic-Format

### Eps {#Eps}
```
public static final long Eps
```


Das Encapsulated PostScript-Format

### Cdr {#Cdr}
```
public static final long Cdr
```


Das CDR-Dateiformat

### Cmx {#Cmx}
```
public static final long Cmx
```


Das CMX-Dateiformat

### Otg {#Otg}
```
public static final long Otg
```


Das otg-Dateiformat

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Das Html5 Canvas-Format

### Apng {#Apng}
```
public static final long Apng
```


Das animierte Png-Dateiformat.

### Tga {#Tga}
```
public static final long Tga
```


Das Truevision TGA-Dateiformat.

### Dxf {#Dxf}
```
public static final long Dxf
```


Das AutoCAD Drawing Exchange-Format.

### Emz {#Emz}
```
public static final long Emz
```


Das emz, komprimiertes emf

### Wmz {#Wmz}
```
public static final long Wmz
```


Das WMZ, komprimiertes wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


Das SVGZ, komprimiertes svg

### FOdg {#FOdg}
```
public static final long FOdg
```


Das fodg, flaches odg-Format

### Avif {#Avif}
```
public static final long Avif
```


Das AVIF-Dateiformat.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Das Big Tiff-Format.

