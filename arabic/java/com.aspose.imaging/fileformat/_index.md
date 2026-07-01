---
title: "تنسيق الملف"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أحد صيغ ملفات التصوير المدعومة."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

أحد صيغ ملفات التصوير المدعومة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Unknown](#Unknown) | تنسيق ملف غير معروف. |
| [Custom](#Custom) | تنسيق ملف مخصص. |
| [Bmp](#Bmp) | تنسيق ملف Bmp (Dib). |
| [Gif](#Gif) | تنسيق ملف Gif. |
| [Jpeg](#Jpeg) | تنسيق ملف Jpeg. |
| [Png](#Png) | تنسيق ملف Png. |
| [Tiff](#Tiff) | تنسيق ملف Tiff. |
| [Psd](#Psd) | تنسيق ملف Psd. |
| [Pdf](#Pdf) | تنسيق ملف Pdf |
| [Ico](#Ico) | تنسيق ico |
| [Jpeg2000](#Jpeg2000) | تنسيق ملف Jpeg2000 |
| [Djvu](#Djvu) | تنسيق ملف Djvu |
| [Webp](#Webp) | تنسيق ملف webp |
| [Emf](#Emf) | تنسيق ملف Emf/Emf+ |
| [Dicom](#Dicom) | تنسيق dicom |
| [Svg](#Svg) | تنسيق ملف SVG |
| [Wmf](#Wmf) | تنسيق ملف Wmf |
| [Dng](#Dng) | تنسيق ملف DNG |
| [Odg](#Odg) | تنسيق المستند المفتوح الرسومي |
| [Eps](#Eps) | تنسيق PostScript المغلف |
| [Cdr](#Cdr) | تنسيق ملف CDR |
| [Cmx](#Cmx) | تنسيق ملف CMX |
| [Otg](#Otg) | تنسيق ملف otg |
| [Html5Canvas](#Html5Canvas) | تنسيق Html5 Canvas |
| [Apng](#Apng) | تنسيق ملف PNG المتحرك. |
| [Tga](#Tga) | تنسيق ملف TGA من Truevision. |
| [Dxf](#Dxf) | تنسيق AutoCAD Drawing Exchange. |
| [Emz](#Emz) | ملف emz، مضغوط emf |
| [Wmz](#Wmz) | ملف WMZ، مضغوط wmf |
| [Svgz](#Svgz) | ملف SVGZ، مضغوط svg |
| [FOdg](#FOdg) | تنسيق fodg، تنسيق odg مسطح |
| [Avif](#Avif) | تنسيق ملف AVIF. |
| [BigTiff](#BigTiff) | تنسيق Big Tiff. |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// استخدم مسارًا مطلقًا للملف
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// تمثيل نصي لتنسيق الملف.
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


تنسيق ملف غير معروف.

### Custom {#Custom}
```
public static final long Custom
```


تنسيق ملف مخصص.

### Bmp {#Bmp}
```
public static final long Bmp
```


تنسيق ملف Bmp (Dib).

### Gif {#Gif}
```
public static final long Gif
```


تنسيق ملف Gif.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


تنسيق ملف Jpeg.

### Png {#Png}
```
public static final long Png
```


تنسيق ملف Png.

### Tiff {#Tiff}
```
public static final long Tiff
```


تنسيق ملف Tiff.

### Psd {#Psd}
```
public static final long Psd
```


تنسيق ملف Psd.

### Pdf {#Pdf}
```
public static final long Pdf
```


تنسيق ملف Pdf

### Ico {#Ico}
```
public static final long Ico
```


تنسيق ico

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


تنسيق ملف Jpeg2000

### Djvu {#Djvu}
```
public static final long Djvu
```


تنسيق ملف Djvu

### Webp {#Webp}
```
public static final long Webp
```


تنسيق ملف webp

### Emf {#Emf}
```
public static final long Emf
```


تنسيق ملف Emf/Emf+

### Dicom {#Dicom}
```
public static final long Dicom
```


تنسيق dicom

### Svg {#Svg}
```
public static final long Svg
```


تنسيق ملف SVG

### Wmf {#Wmf}
```
public static final long Wmf
```


تنسيق ملف Wmf

### Dng {#Dng}
```
public static final long Dng
```


تنسيق ملف DNG

### Odg {#Odg}
```
public static final long Odg
```


تنسيق المستند المفتوح الرسومي

### Eps {#Eps}
```
public static final long Eps
```


تنسيق PostScript المغلف

### Cdr {#Cdr}
```
public static final long Cdr
```


تنسيق ملف CDR

### Cmx {#Cmx}
```
public static final long Cmx
```


تنسيق ملف CMX

### Otg {#Otg}
```
public static final long Otg
```


تنسيق ملف otg

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


تنسيق Html5 Canvas

### Apng {#Apng}
```
public static final long Apng
```


تنسيق ملف PNG المتحرك.

### Tga {#Tga}
```
public static final long Tga
```


تنسيق ملف TGA من Truevision.

### Dxf {#Dxf}
```
public static final long Dxf
```


تنسيق AutoCAD Drawing Exchange.

### Emz {#Emz}
```
public static final long Emz
```


ملف emz، مضغوط emf

### Wmz {#Wmz}
```
public static final long Wmz
```


ملف WMZ، مضغوط wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


ملف SVGZ، مضغوط svg

### FOdg {#FOdg}
```
public static final long FOdg
```


تنسيق fodg، تنسيق odg مسطح

### Avif {#Avif}
```
public static final long Avif
```


تنسيق ملف AVIF.

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


تنسيق Big Tiff.

