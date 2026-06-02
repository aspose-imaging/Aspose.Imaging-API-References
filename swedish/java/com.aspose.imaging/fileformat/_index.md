---
title: "FileFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "Ett av de stödjade bildfilformaten."
type: docs
weight: 45
url: /sv/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Ett av de stödjade bildfilformaten.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Unknown](#Unknown) | Okänt filformat. |
| [Custom](#Custom) | Anpassat filformat. |
| [Bmp](#Bmp) | Bmp (Dib) filformat. |
| [Gif](#Gif) | Gif filformat. |
| [Jpeg](#Jpeg) | Jpeg filformat. |
| [Png](#Png) | Png filformat. |
| [Tiff](#Tiff) | Tiff filformat. |
| [Psd](#Psd) | Psd filformat. |
| [Pdf](#Pdf) | Pdf filformat |
| [Ico](#Ico) | Ico-formatet |
| [Jpeg2000](#Jpeg2000) | Jpeg2000 filformat |
| [Djvu](#Djvu) | Djvu filformat |
| [Webp](#Webp) | Webp-filformatet |
| [Emf](#Emf) | Emf/Emf+ filformatet |
| [Dicom](#Dicom) | dicom-formatet |
| [Svg](#Svg) | SVG filformat |
| [Wmf](#Wmf) | Wmf-filformatet |
| [Dng](#Dng) | DNG-filformatet |
| [Odg](#Odg) | Open document graphic-formatet |
| [Eps](#Eps) | Det Encapsulated PostScript-formatet |
| [Cdr](#Cdr) | Det CDR-filformatet |
| [Cmx](#Cmx) | Det CMX-filformatet |
| [Otg](#Otg) | Det otg-filformatet |
| [Html5Canvas](#Html5Canvas) | Det Html5 Canvas-formatet |
| [Apng](#Apng) | Det animerade PNG-filformatet. |
| [Tga](#Tga) | Det Truevision TGA-filformatet. |
| [Dxf](#Dxf) | Det AutoCAD Drawing Exchange Format. |
| [Emz](#Emz) | emz, komprimerad emf |
| [Wmz](#Wmz) | WMZ, komprimerad wmf |
| [Svgz](#Svgz) | SVGZ, komprimerad svg |
| [FOdg](#FOdg) | fodg, platt odg-format |
| [Avif](#Avif) | Det AVIF-filformatet. |
| [BigTiff](#BigTiff) | Det Big Tiff-formatet. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Använd en absolut sökväg till filen
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// En strängrepresentation av filformatet.
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


Okänt filformat.

### Custom {#Custom}
```
public static final long Custom
```


Anpassat filformat.

### Bmp {#Bmp}
```
public static final long Bmp
```


Bmp (Dib) filformat.

### Gif {#Gif}
```
public static final long Gif
```


Gif filformat.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Jpeg filformat.

### Png {#Png}
```
public static final long Png
```


Png filformat.

### Tiff {#Tiff}
```
public static final long Tiff
```


Tiff filformat.

### Psd {#Psd}
```
public static final long Psd
```


Psd filformat.

### Pdf {#Pdf}
```
public static final long Pdf
```


Pdf filformat

### Ico {#Ico}
```
public static final long Ico
```


Ico-formatet

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Jpeg2000 filformat

### Djvu {#Djvu}
```
public static final long Djvu
```


Djvu filformat

### Webp {#Webp}
```
public static final long Webp
```


Webp-filformatet

### Emf {#Emf}
```
public static final long Emf
```


Emf/Emf+ filformatet

### Dicom {#Dicom}
```
public static final long Dicom
```


dicom-formatet

### Svg {#Svg}
```
public static final long Svg
```


SVG filformat

### Wmf {#Wmf}
```
public static final long Wmf
```


Wmf-filformatet

### Dng {#Dng}
```
public static final long Dng
```


DNG-filformatet

### Odg {#Odg}
```
public static final long Odg
```


Open document graphic-formatet

### Eps {#Eps}
```
public static final long Eps
```


Det Encapsulated PostScript-formatet

### Cdr {#Cdr}
```
public static final long Cdr
```


Det CDR-filformatet

### Cmx {#Cmx}
```
public static final long Cmx
```


Det CMX-filformatet

### Otg {#Otg}
```
public static final long Otg
```


Det otg-filformatet

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Det Html5 Canvas-formatet

### Apng {#Apng}
```
public static final long Apng
```


Det animerade PNG-filformatet.

### Tga {#Tga}
```
public static final long Tga
```


Det Truevision TGA-filformatet.

### Dxf {#Dxf}
```
public static final long Dxf
```


Det AutoCAD Drawing Exchange Format.

### Emz {#Emz}
```
public static final long Emz
```


emz, komprimerad emf

### Wmz {#Wmz}
```
public static final long Wmz
```


WMZ, komprimerad wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


SVGZ, komprimerad svg

### FOdg {#FOdg}
```
public static final long FOdg
```


fodg, platt odg-format

### Avif {#Avif}
```
public static final long Avif
```


Det AVIF-filformatet.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Det Big Tiff-formatet.

