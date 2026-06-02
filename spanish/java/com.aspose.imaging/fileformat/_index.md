---
title: "FileFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Uno de los formatos de archivo de imagen compatibles."
type: docs
weight: 45
url: /es/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Uno de los formatos de archivo de imagen compatibles.
## Campos

| Campo | Descripción |
| --- | --- |
| [Unknown](#Unknown) | Formato de archivo desconocido. |
| [Custom](#Custom) | Formato de archivo personalizado. |
| [Bmp](#Bmp) | Formato de archivo Bmp (Dib). |
| [Gif](#Gif) | Formato de archivo Gif. |
| [Jpeg](#Jpeg) | Formato de archivo Jpeg. |
| [Png](#Png) | Formato de archivo Png. |
| [Tiff](#Tiff) | Formato de archivo Tiff. |
| [Psd](#Psd) | Formato de archivo Psd. |
| [Pdf](#Pdf) | Formato de archivo Pdf |
| [Ico](#Ico) | El formato ico |
| [Jpeg2000](#Jpeg2000) | Formato de archivo Jpeg2000 |
| [Djvu](#Djvu) | Formato de archivo Djvu |
| [Webp](#Webp) | El formato webp |
| [Emf](#Emf) | El formato Emf/Emf+ |
| [Dicom](#Dicom) | El formato dicom |
| [Svg](#Svg) | Formato de archivo SVG |
| [Wmf](#Wmf) | El formato Wmf |
| [Dng](#Dng) | El formato DNG |
| [Odg](#Odg) | El formato gráfico Open document |
| [Eps](#Eps) | El formato Encapsulated PostScript |
| [Cdr](#Cdr) | El formato de archivo CDR |
| [Cmx](#Cmx) | El formato de archivo CMX |
| [Otg](#Otg) | El formato de archivo otg |
| [Html5Canvas](#Html5Canvas) | El formato Html5 Canvas |
| [Apng](#Apng) | El formato de archivo Png animado. |
| [Tga](#Tga) | El formato de archivo TGA de Truevision. |
| [Dxf](#Dxf) | El formato AutoCAD Drawing Exchange. |
| [Emz](#Emz) | El emz, emf comprimido |
| [Wmz](#Wmz) | El WMZ, wmf comprimido |
| [Svgz](#Svgz) | El SVGZ, svg comprimido |
| [FOdg](#FOdg) | El fodg, formato odg plano |
| [Avif](#Avif) | El formato de archivo AVIF. |
| [BigTiff](#BigTiff) | El formato Big Tiff. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Utilice una ruta absoluta al archivo
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Una representación de cadena del formato de archivo.
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


Formato de archivo desconocido.

### Custom {#Custom}
```
public static final long Custom
```


Formato de archivo personalizado.

### Bmp {#Bmp}
```
public static final long Bmp
```


Formato de archivo Bmp (Dib).

### Gif {#Gif}
```
public static final long Gif
```


Formato de archivo Gif.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Formato de archivo Jpeg.

### Png {#Png}
```
public static final long Png
```


Formato de archivo Png.

### Tiff {#Tiff}
```
public static final long Tiff
```


Formato de archivo Tiff.

### Psd {#Psd}
```
public static final long Psd
```


Formato de archivo Psd.

### Pdf {#Pdf}
```
public static final long Pdf
```


Formato de archivo Pdf

### Ico {#Ico}
```
public static final long Ico
```


El formato ico

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Formato de archivo Jpeg2000

### Djvu {#Djvu}
```
public static final long Djvu
```


Formato de archivo Djvu

### Webp {#Webp}
```
public static final long Webp
```


El formato webp

### Emf {#Emf}
```
public static final long Emf
```


El formato Emf/Emf+

### Dicom {#Dicom}
```
public static final long Dicom
```


El formato dicom

### Svg {#Svg}
```
public static final long Svg
```


Formato de archivo SVG

### Wmf {#Wmf}
```
public static final long Wmf
```


El formato Wmf

### Dng {#Dng}
```
public static final long Dng
```


El formato DNG

### Odg {#Odg}
```
public static final long Odg
```


El formato gráfico Open document

### Eps {#Eps}
```
public static final long Eps
```


El formato Encapsulated PostScript

### Cdr {#Cdr}
```
public static final long Cdr
```


El formato de archivo CDR

### Cmx {#Cmx}
```
public static final long Cmx
```


El formato de archivo CMX

### Otg {#Otg}
```
public static final long Otg
```


El formato de archivo otg

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


El formato Html5 Canvas

### Apng {#Apng}
```
public static final long Apng
```


El formato de archivo Png animado.

### Tga {#Tga}
```
public static final long Tga
```


El formato de archivo TGA de Truevision.

### Dxf {#Dxf}
```
public static final long Dxf
```


El formato AutoCAD Drawing Exchange.

### Emz {#Emz}
```
public static final long Emz
```


El emz, emf comprimido

### Wmz {#Wmz}
```
public static final long Wmz
```


El WMZ, wmf comprimido

### Svgz {#Svgz}
```
public static final long Svgz
```


El SVGZ, svg comprimido

### FOdg {#FOdg}
```
public static final long FOdg
```


El fodg, formato odg plano

### Avif {#Avif}
```
public static final long Avif
```


El formato de archivo AVIF.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


El formato Big Tiff.

