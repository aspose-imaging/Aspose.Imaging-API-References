---
title: "FileFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Один из поддерживаемых форматов файлов изображений."
type: docs
weight: 45
url: /ru/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

Один из поддерживаемых форматов файлов изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [Unknown](#Unknown) | Неизвестный формат файла. |
| [Custom](#Custom) | Пользовательский формат файла. |
| [Bmp](#Bmp) | Формат файла Bmp (Dib). |
| [Gif](#Gif) | Формат файла Gif. |
| [Jpeg](#Jpeg) | Формат файла Jpeg. |
| [Png](#Png) | Формат файла Png. |
| [Tiff](#Tiff) | Формат файла Tiff. |
| [Psd](#Psd) | Формат файла Psd. |
| [Pdf](#Pdf) | Формат файла Pdf |
| [Ico](#Ico) | Формат ico |
| [Jpeg2000](#Jpeg2000) | Формат файла Jpeg2000 |
| [Djvu](#Djvu) | Формат файла Djvu |
| [Webp](#Webp) | Формат файла webp |
| [Emf](#Emf) | Формат файлов Emf/Emf+ |
| [Dicom](#Dicom) | Формат dicom |
| [Svg](#Svg) | Формат файла SVG |
| [Wmf](#Wmf) | Формат файла Wmf |
| [Dng](#Dng) | Формат файла DNG |
| [Odg](#Odg) | Формат графики Open document |
| [Eps](#Eps) | Формат Encapsulated PostScript |
| [Cdr](#Cdr) | Формат файла CDR |
| [Cmx](#Cmx) | Формат файла CMX |
| [Otg](#Otg) | Формат файла otg |
| [Html5Canvas](#Html5Canvas) | Формат Html5 Canvas |
| [Apng](#Apng) | Формат анимированного Png файла. |
| [Tga](#Tga) | Формат файла Truevision TGA. |
| [Dxf](#Dxf) | Формат AutoCAD Drawing Exchange. |
| [Emz](#Emz) | Формат emz, сжатый emf |
| [Wmz](#Wmz) | Формат WMZ, сжатый wmf |
| [Svgz](#Svgz) | Формат SVGZ, сжатый svg |
| [FOdg](#FOdg) | Формат fodg, плоский odg |
| [Avif](#Avif) | Формат файла AVIF. |
| [BigTiff](#BigTiff) | Формат Big Tiff. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// Используйте абсолютный путь к файлу
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Строковое представление формата файла.
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


Неизвестный формат файла.

### Custom {#Custom}
```
public static final long Custom
```


Пользовательский формат файла.

### Bmp {#Bmp}
```
public static final long Bmp
```


Формат файла Bmp (Dib).

### Gif {#Gif}
```
public static final long Gif
```


Формат файла Gif.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Формат файла Jpeg.

### Png {#Png}
```
public static final long Png
```


Формат файла Png.

### Tiff {#Tiff}
```
public static final long Tiff
```


Формат файла Tiff.

### Psd {#Psd}
```
public static final long Psd
```


Формат файла Psd.

### Pdf {#Pdf}
```
public static final long Pdf
```


Формат файла Pdf

### Ico {#Ico}
```
public static final long Ico
```


Формат ico

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Формат файла Jpeg2000

### Djvu {#Djvu}
```
public static final long Djvu
```


Формат файла Djvu

### Webp {#Webp}
```
public static final long Webp
```


Формат файла webp

### Emf {#Emf}
```
public static final long Emf
```


Формат файлов Emf/Emf+

### Dicom {#Dicom}
```
public static final long Dicom
```


Формат dicom

### Svg {#Svg}
```
public static final long Svg
```


Формат файла SVG

### Wmf {#Wmf}
```
public static final long Wmf
```


Формат файла Wmf

### Dng {#Dng}
```
public static final long Dng
```


Формат файла DNG

### Odg {#Odg}
```
public static final long Odg
```


Формат графики Open document

### Eps {#Eps}
```
public static final long Eps
```


Формат Encapsulated PostScript

### Cdr {#Cdr}
```
public static final long Cdr
```


Формат файла CDR

### Cmx {#Cmx}
```
public static final long Cmx
```


Формат файла CMX

### Otg {#Otg}
```
public static final long Otg
```


Формат файла otg

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


Формат Html5 Canvas

### Apng {#Apng}
```
public static final long Apng
```


Формат анимированного Png файла.

### Tga {#Tga}
```
public static final long Tga
```


Формат файла Truevision TGA.

### Dxf {#Dxf}
```
public static final long Dxf
```


Формат AutoCAD Drawing Exchange.

### Emz {#Emz}
```
public static final long Emz
```


Формат emz, сжатый emf

### Wmz {#Wmz}
```
public static final long Wmz
```


Формат WMZ, сжатый wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


Формат SVGZ, сжатый svg

### FOdg {#FOdg}
```
public static final long FOdg
```


Формат fodg, плоский odg

### Avif {#Avif}
```
public static final long Avif
```


Формат файла AVIF.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


Формат Big Tiff.

