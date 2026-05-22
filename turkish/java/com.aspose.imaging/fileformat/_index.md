---
title: "FileFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Desteklenen görüntü dosyası formatlarından biri."
type: docs
weight: 45
url: /tr/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Desteklenen görüntü dosyası formatlarından biri.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Unknown](#Unknown) | Bilinmeyen dosya formatı. |
| [Custom](#Custom) | Özel dosya formatı. |
| [Bmp](#Bmp) | Bmp (Dib) dosya formatı. |
| [Gif](#Gif) | Gif dosya formatı. |
| [Jpeg](#Jpeg) | Jpeg dosya formatı. |
| [Png](#Png) | Png dosya formatı. |
| [Tiff](#Tiff) | Tiff dosya formatı. |
| [Psd](#Psd) | Psd dosya formatı. |
| [Pdf](#Pdf) | Pdf dosya formatı |
| [Ico](#Ico) | ico formatı |
| [Jpeg2000](#Jpeg2000) | Jpeg2000 dosya formatı |
| [Djvu](#Djvu) | Djvu dosya formatı |
| [Webp](#Webp) | webp dosya formatı |
| [Emf](#Emf) | Emf/Emf+ dosya formatı |
| [Dicom](#Dicom) | dicom formatı |
| [Svg](#Svg) | SVG dosya formatı |
| [Wmf](#Wmf) | Wmf dosya formatı |
| [Dng](#Dng) | DNG dosya formatı |
| [Odg](#Odg) | Open document grafik formatı |
| [Eps](#Eps) | Encapsulated PostScript formatı |
| [Cdr](#Cdr) | CDR dosya formatı |
| [Cmx](#Cmx) | CMX dosya formatı |
| [Otg](#Otg) | otg dosya formatı |
| [Html5Canvas](#Html5Canvas) | Html5 Canvas formatı |
| [Apng](#Apng) | Animasyonlu Png dosya formatı. |
| [Tga](#Tga) | Truevision TGA dosya formatı. |
| [Dxf](#Dxf) | AutoCAD Drawing Exchange Formatı. |
| [Emz](#Emz) | emz, sıkıştırılmış emf |
| [Wmz](#Wmz) | WMZ, sıkıştırılmış wmf |
| [Svgz](#Svgz) | SVGZ, sıkıştırılmış svg |
| [FOdg](#FOdg) | fodg, düz odg formatı |
| [Avif](#Avif) | AVIF dosya formatı. |
| [BigTiff](#BigTiff) | Büyük Tiff formatı. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Dosyaya mutlak bir yol kullanın
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Dosya formatının bir dize temsili.
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


Bilinmeyen dosya formatı.

### Custom {#Custom}
```
public static final long Custom
```


Özel dosya formatı.

### Bmp {#Bmp}
```
public static final long Bmp
```


Bmp (Dib) dosya formatı.

### Gif {#Gif}
```
public static final long Gif
```


Gif dosya formatı.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Jpeg dosya formatı.

### Png {#Png}
```
public static final long Png
```


Png dosya formatı.

### Tiff {#Tiff}
```
public static final long Tiff
```


Tiff dosya formatı.

### Psd {#Psd}
```
public static final long Psd
```


Psd dosya formatı.

### Pdf {#Pdf}
```
public static final long Pdf
```


Pdf dosya formatı

### Ico {#Ico}
```
public static final long Ico
```


ico formatı

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Jpeg2000 dosya formatı

### Djvu {#Djvu}
```
public static final long Djvu
```


Djvu dosya formatı

### Webp {#Webp}
```
public static final long Webp
```


webp dosya formatı

### Emf {#Emf}
```
public static final long Emf
```


Emf/Emf+ dosya formatı

### Dicom {#Dicom}
```
public static final long Dicom
```


dicom formatı

### Svg {#Svg}
```
public static final long Svg
```


SVG dosya formatı

### Wmf {#Wmf}
```
public static final long Wmf
```


Wmf dosya formatı

### Dng {#Dng}
```
public static final long Dng
```


DNG dosya formatı

### Odg {#Odg}
```
public static final long Odg
```


Open document grafik formatı

### Eps {#Eps}
```
public static final long Eps
```


Encapsulated PostScript formatı

### Cdr {#Cdr}
```
public static final long Cdr
```


CDR dosya formatı

### Cmx {#Cmx}
```
public static final long Cmx
```


CMX dosya formatı

### Otg {#Otg}
```
public static final long Otg
```


otg dosya formatı

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Html5 Canvas formatı

### Apng {#Apng}
```
public static final long Apng
```


Animasyonlu Png dosya formatı.

### Tga {#Tga}
```
public static final long Tga
```


Truevision TGA dosya formatı.

### Dxf {#Dxf}
```
public static final long Dxf
```


AutoCAD Drawing Exchange Formatı.

### Emz {#Emz}
```
public static final long Emz
```


emz, sıkıştırılmış emf

### Wmz {#Wmz}
```
public static final long Wmz
```


WMZ, sıkıştırılmış wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


SVGZ, sıkıştırılmış svg

### FOdg {#FOdg}
```
public static final long FOdg
```


fodg, düz odg formatı

### Avif {#Avif}
```
public static final long Avif
```


AVIF dosya formatı.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Büyük Tiff formatı.

