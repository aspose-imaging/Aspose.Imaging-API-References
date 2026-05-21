---
title: "FormatoFile"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Uno dei formati di file di imaging supportati."
type: docs
weight: 45
url: /it/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Uno dei formati di file di imaging supportati.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Unknown](#Unknown) | Formato file sconosciuto. |
| [Custom](#Custom) | Formato file personalizzato. |
| [Bmp](#Bmp) | Formato file Bmp (Dib). |
| [Gif](#Gif) | Formato file Gif. |
| [Jpeg](#Jpeg) | Formato file Jpeg. |
| [Png](#Png) | Formato file Png. |
| [Tiff](#Tiff) | Formato file Tiff. |
| [Psd](#Psd) | Formato file Psd. |
| [Pdf](#Pdf) | Formato file Pdf |
| [Ico](#Ico) | Il formato ico |
| [Jpeg2000](#Jpeg2000) | Formato file Jpeg2000 |
| [Djvu](#Djvu) | Formato file Djvu |
| [Webp](#Webp) | Il formato file webp |
| [Emf](#Emf) | Il formato file Emf/Emf+ |
| [Dicom](#Dicom) | Il formato dicom |
| [Svg](#Svg) | Formato file SVG |
| [Wmf](#Wmf) | Il formato file Wmf |
| [Dng](#Dng) | Il formato file DNG |
| [Odg](#Odg) | Il formato grafico Open document |
| [Eps](#Eps) | Il formato Encapsulated PostScript |
| [Cdr](#Cdr) | Il formato file CDR |
| [Cmx](#Cmx) | Il formato file CMX |
| [Otg](#Otg) | Il formato file otg |
| [Html5Canvas](#Html5Canvas) | Il formato Html5 Canvas |
| [Apng](#Apng) | Il formato file Png animato. |
| [Tga](#Tga) | Il formato file Truevision TGA. |
| [Dxf](#Dxf) | Il formato AutoCAD Drawing Exchange. |
| [Emz](#Emz) | L'emz, emf compresso |
| [Wmz](#Wmz) | Il WMZ, wmf compresso |
| [Svgz](#Svgz) | Il SVGZ, svg compresso |
| [FOdg](#FOdg) | Il fodg, formato odg piatto |
| [Avif](#Avif) | Il formato file AVIF. |
| [BigTiff](#BigTiff) | Il formato Big Tiff. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Usa un percorso assoluto al file
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Una rappresentazione stringa del formato file.
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


Formato file sconosciuto.

### Custom {#Custom}
```
public static final long Custom
```


Formato file personalizzato.

### Bmp {#Bmp}
```
public static final long Bmp
```


Formato file Bmp (Dib).

### Gif {#Gif}
```
public static final long Gif
```


Formato file Gif.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Formato file Jpeg.

### Png {#Png}
```
public static final long Png
```


Formato file Png.

### Tiff {#Tiff}
```
public static final long Tiff
```


Formato file Tiff.

### Psd {#Psd}
```
public static final long Psd
```


Formato file Psd.

### Pdf {#Pdf}
```
public static final long Pdf
```


Formato file Pdf

### Ico {#Ico}
```
public static final long Ico
```


Il formato ico

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Formato file Jpeg2000

### Djvu {#Djvu}
```
public static final long Djvu
```


Formato file Djvu

### Webp {#Webp}
```
public static final long Webp
```


Il formato file webp

### Emf {#Emf}
```
public static final long Emf
```


Il formato file Emf/Emf+

### Dicom {#Dicom}
```
public static final long Dicom
```


Il formato dicom

### Svg {#Svg}
```
public static final long Svg
```


Formato file SVG

### Wmf {#Wmf}
```
public static final long Wmf
```


Il formato file Wmf

### Dng {#Dng}
```
public static final long Dng
```


Il formato file DNG

### Odg {#Odg}
```
public static final long Odg
```


Il formato grafico Open document

### Eps {#Eps}
```
public static final long Eps
```


Il formato Encapsulated PostScript

### Cdr {#Cdr}
```
public static final long Cdr
```


Il formato file CDR

### Cmx {#Cmx}
```
public static final long Cmx
```


Il formato file CMX

### Otg {#Otg}
```
public static final long Otg
```


Il formato file otg

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Il formato Html5 Canvas

### Apng {#Apng}
```
public static final long Apng
```


Il formato file Png animato.

### Tga {#Tga}
```
public static final long Tga
```


Il formato file Truevision TGA.

### Dxf {#Dxf}
```
public static final long Dxf
```


Il formato AutoCAD Drawing Exchange.

### Emz {#Emz}
```
public static final long Emz
```


L'emz, emf compresso

### Wmz {#Wmz}
```
public static final long Wmz
```


Il WMZ, wmf compresso

### Svgz {#Svgz}
```
public static final long Svgz
```


Il SVGZ, svg compresso

### FOdg {#FOdg}
```
public static final long FOdg
```


Il fodg, formato odg piatto

### Avif {#Avif}
```
public static final long Avif
```


Il formato file AVIF.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Il formato Big Tiff.

