---
title: "FileFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'un des formats de fichiers d'imagerie pris en charge."
type: docs
weight: 45
url: /fr/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

L'un des formats de fichiers d'imagerie pris en charge.
## Champs

| Champ | Description |
| --- | --- |
| [Unknown](#Unknown) | Format de fichier inconnu. |
| [Custom](#Custom) | Format de fichier personnalisé. |
| [Bmp](#Bmp) | Format de fichier Bmp (Dib). |
| [Gif](#Gif) | Format de fichier Gif. |
| [Jpeg](#Jpeg) | Format de fichier Jpeg. |
| [Png](#Png) | Format de fichier Png. |
| [Tiff](#Tiff) | Format de fichier Tiff. |
| [Psd](#Psd) | Format de fichier Psd. |
| [Pdf](#Pdf) | Format de fichier Pdf |
| [Ico](#Ico) | Le format ico |
| [Jpeg2000](#Jpeg2000) | Format de fichier Jpeg2000 |
| [Djvu](#Djvu) | Format de fichier Djvu |
| [Webp](#Webp) | Le format de fichier webp |
| [Emf](#Emf) | Le format de fichier Emf/Emf+ |
| [Dicom](#Dicom) | Le format dicom |
| [Svg](#Svg) | Format de fichier SVG |
| [Wmf](#Wmf) | Le format de fichier Wmf |
| [Dng](#Dng) | Le format de fichier DNG |
| [Odg](#Odg) | Le format graphique Open document |
| [Eps](#Eps) | Le format Encapsulated PostScript |
| [Cdr](#Cdr) | Le format de fichier CDR |
| [Cmx](#Cmx) | Le format de fichier CMX |
| [Otg](#Otg) | Le format de fichier otg |
| [Html5Canvas](#Html5Canvas) | Le format Html5 Canvas |
| [Apng](#Apng) | Le format de fichier PNG animé. |
| [Tga](#Tga) | Le format de fichier Truevision TGA. |
| [Dxf](#Dxf) | Le format AutoCAD Drawing Exchange. |
| [Emz](#Emz) | Le emz, emf compressé |
| [Wmz](#Wmz) | Le WMZ, wmf compressé |
| [Svgz](#Svgz) | Le SVGZ, svg compressé |
| [FOdg](#FOdg) | Le format fodg, odg plat |
| [Avif](#Avif) | Le format de fichier AVIF. |
| [BigTiff](#BigTiff) | Le format Big Tiff. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Utilisez un chemin absolu vers le fichier
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Une représentation sous forme de chaîne du format de fichier.
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


Format de fichier inconnu.

### Custom {#Custom}
```
public static final long Custom
```


Format de fichier personnalisé.

### Bmp {#Bmp}
```
public static final long Bmp
```


Format de fichier Bmp (Dib).

### Gif {#Gif}
```
public static final long Gif
```


Format de fichier Gif.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Format de fichier Jpeg.

### Png {#Png}
```
public static final long Png
```


Format de fichier Png.

### Tiff {#Tiff}
```
public static final long Tiff
```


Format de fichier Tiff.

### Psd {#Psd}
```
public static final long Psd
```


Format de fichier Psd.

### Pdf {#Pdf}
```
public static final long Pdf
```


Format de fichier Pdf

### Ico {#Ico}
```
public static final long Ico
```


Le format ico

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Format de fichier Jpeg2000

### Djvu {#Djvu}
```
public static final long Djvu
```


Format de fichier Djvu

### Webp {#Webp}
```
public static final long Webp
```


Le format de fichier webp

### Emf {#Emf}
```
public static final long Emf
```


Le format de fichier Emf/Emf+

### Dicom {#Dicom}
```
public static final long Dicom
```


Le format dicom

### Svg {#Svg}
```
public static final long Svg
```


Format de fichier SVG

### Wmf {#Wmf}
```
public static final long Wmf
```


Le format de fichier Wmf

### Dng {#Dng}
```
public static final long Dng
```


Le format de fichier DNG

### Odg {#Odg}
```
public static final long Odg
```


Le format graphique Open document

### Eps {#Eps}
```
public static final long Eps
```


Le format Encapsulated PostScript

### Cdr {#Cdr}
```
public static final long Cdr
```


Le format de fichier CDR

### Cmx {#Cmx}
```
public static final long Cmx
```


Le format de fichier CMX

### Otg {#Otg}
```
public static final long Otg
```


Le format de fichier otg

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Le format Html5 Canvas

### Apng {#Apng}
```
public static final long Apng
```


Le format de fichier PNG animé.

### Tga {#Tga}
```
public static final long Tga
```


Le format de fichier Truevision TGA.

### Dxf {#Dxf}
```
public static final long Dxf
```


Le format AutoCAD Drawing Exchange.

### Emz {#Emz}
```
public static final long Emz
```


Le emz, emf compressé

### Wmz {#Wmz}
```
public static final long Wmz
```


Le WMZ, wmf compressé

### Svgz {#Svgz}
```
public static final long Svgz
```


Le SVGZ, svg compressé

### FOdg {#FOdg}
```
public static final long FOdg
```


Le format fodg, odg plat

### Avif {#Avif}
```
public static final long Avif
```


Le format de fichier AVIF.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Le format Big Tiff.

