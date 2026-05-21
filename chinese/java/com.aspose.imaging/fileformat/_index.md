---
title: "文件格式"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "受支持的图像文件格式之一。"
type: docs
weight: 45
url: /zh/java/com.aspose.imaging/fileformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileFormat extends System.Enum
```

受支持的图像文件格式之一。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Unknown](#Unknown) | 未知文件格式。 |
| [Custom](#Custom) | 自定义文件格式。 |
| [Bmp](#Bmp) | Bmp (Dib) 文件格式。 |
| [Gif](#Gif) | Gif 文件格式。 |
| [Jpeg](#Jpeg) | Jpeg 文件格式。 |
| [Png](#Png) | Png 文件格式。 |
| [Tiff](#Tiff) | Tiff 文件格式。 |
| [Psd](#Psd) | Psd 文件格式。 |
| [Pdf](#Pdf) | Pdf 文件格式 |
| [Ico](#Ico) | ico 格式 |
| [Jpeg2000](#Jpeg2000) | Jpeg2000 文件格式 |
| [Djvu](#Djvu) | Djvu 文件格式 |
| [Webp](#Webp) | webp 文件格式 |
| [Emf](#Emf) | Emf/Emf+ 文件格式 |
| [Dicom](#Dicom) | dicom 格式 |
| [Svg](#Svg) | SVG 文件格式 |
| [Wmf](#Wmf) | Wmf 文件格式 |
| [Dng](#Dng) | DNG 文件格式 |
| [Odg](#Odg) | Open 文档图形格式 |
| [Eps](#Eps) | 封装的 PostScript 格式 |
| [Cdr](#Cdr) | 该 CDR 文件格式 |
| [Cmx](#Cmx) | 该 CMX 文件格式 |
| [Otg](#Otg) | 该 otg 文件格式 |
| [Html5Canvas](#Html5Canvas) | 该 Html5 Canvas 格式 |
| [Apng](#Apng) | 该动画 Png 文件格式。 |
| [Tga](#Tga) | 该 Truevision TGA 文件格式。 |
| [Dxf](#Dxf) | 该 AutoCAD Drawing Exchange Format。 |
| [Emz](#Emz) | 该 emz，压缩的 emf |
| [Wmz](#Wmz) | 该 WMZ，压缩的 wmf |
| [Svgz](#Svgz) | 该 SVGZ，压缩的 svg |
| [FOdg](#FOdg) | 该 fodg，平面 odg 格式 |
| [Avif](#Avif) | 该 AVIF 文件格式。 |
| [BigTiff](#BigTiff) | 该 Big Tiff 格式。 |

## Example: This example shows how to determine the image format without loading the entire image from a file.

``` java
String dir = "c:\\temp\\";

// 使用文件的绝对路径
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// 一个文件格式的字符串表示。
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


未知文件格式。

### Custom {#Custom}
```
public static final long Custom
```


自定义文件格式。

### Bmp {#Bmp}
```
public static final long Bmp
```


Bmp (Dib) 文件格式。

### Gif {#Gif}
```
public static final long Gif
```


Gif 文件格式。

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Jpeg 文件格式。

### Png {#Png}
```
public static final long Png
```


Png 文件格式。

### Tiff {#Tiff}
```
public static final long Tiff
```


Tiff 文件格式。

### Psd {#Psd}
```
public static final long Psd
```


Psd 文件格式。

### Pdf {#Pdf}
```
public static final long Pdf
```


Pdf 文件格式

### Ico {#Ico}
```
public static final long Ico
```


ico 格式

### Jpeg2000 {#Jpeg2000}
```
public static final long Jpeg2000
```


Jpeg2000 文件格式

### Djvu {#Djvu}
```
public static final long Djvu
```


Djvu 文件格式

### Webp {#Webp}
```
public static final long Webp
```


webp 文件格式

### Emf {#Emf}
```
public static final long Emf
```


Emf/Emf+ 文件格式

### Dicom {#Dicom}
```
public static final long Dicom
```


dicom 格式

### Svg {#Svg}
```
public static final long Svg
```


SVG 文件格式

### Wmf {#Wmf}
```
public static final long Wmf
```


Wmf 文件格式

### Dng {#Dng}
```
public static final long Dng
```


DNG 文件格式

### Odg {#Odg}
```
public static final long Odg
```


Open 文档图形格式

### Eps {#Eps}
```
public static final long Eps
```


封装的 PostScript 格式

### Cdr {#Cdr}
```
public static final long Cdr
```


该 CDR 文件格式

### Cmx {#Cmx}
```
public static final long Cmx
```


该 CMX 文件格式

### Otg {#Otg}
```
public static final long Otg
```


该 otg 文件格式

### Html5Canvas {#Html5Canvas}
```
public static final long Html5Canvas
```


该 Html5 Canvas 格式

### Apng {#Apng}
```
public static final long Apng
```


该动画 Png 文件格式。

### Tga {#Tga}
```
public static final long Tga
```


该 Truevision TGA 文件格式。

### Dxf {#Dxf}
```
public static final long Dxf
```


该 AutoCAD Drawing Exchange Format。

### Emz {#Emz}
```
public static final long Emz
```


该 emz，压缩的 emf

### Wmz {#Wmz}
```
public static final long Wmz
```


该 WMZ，压缩的 wmf

### Svgz {#Svgz}
```
public static final long Svgz
```


该 SVGZ，压缩的 svg

### FOdg {#FOdg}
```
public static final long FOdg
```


该 fodg，平面 odg 格式

### Avif {#Avif}
```
public static final long Avif
```


该 AVIF 文件格式。

### BigTiff {#BigTiff}
```
public static final long BigTiff
```


该 Big Tiff 格式。

