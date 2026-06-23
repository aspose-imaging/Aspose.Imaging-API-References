---
title: "ImageParameters"
second_title: "Aspose.Imaging for Java API 参考"
description: "Dng 图像参数"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Dng 图像参数
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | 获取 DNG 版本。 |
| [getDescription()](#getDescription--) | 获取颜色描述 (RGBG、RGBE、GMCY 或 GBTG)。 |
| [getModel()](#getModel--) | 获取相机型号。 |
| [getCameraManufacturer()](#getCameraManufacturer--) | 获取相机制造商。 |
| [isFoveon()](#isFoveon--) | 获取是否为 foveon 矩阵。 |
| [getSoftware()](#getSoftware--) | 获取软件。 |
| [getRawCount()](#getRawCount--) | 获取文件中 RAW 图像的数量 (0 表示文件未被识别)。 |
| [getFilters()](#getFilters--) | 获取描述矩阵中色像素顺序的位掩码。 |
| [getColorsCount()](#getColorsCount--) | 获取颜色。 |
| [getXmpData()](#getXmpData--) | 获取 XMP 数据。 |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | 获取 CFA 马赛克 DNG 格式的转换数组。 |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // 将时间戳转换为人类可读的字符串。
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // 使用默认选项导出为 PNG。
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// 相机制造商：              Leica
// 相机型号：                     M8 Digital Camera
// 颜色数量：                     3
// 颜色描述：               RGBG
// DNG 版本：                      16777216
// 文件中 RAW 图像的数量： 1
// 软件版本：                         1.107
// 颜色像素顺序：        10110100101101001011010010110100
// 光圈：                         0
// 描述：
// 焦距：                     50
// ISO 灵敏度：                  160
// 图像序列号：       0
// 快门速度：                    12
// 拍摄日期：                 8/3/2007 3:13:49 AM
```

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


获取 DNG 版本。

值： DNG 版本。

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取颜色描述 (RGBG、RGBE、GMCY 或 GBTG)。

值： cdesc。

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


获取相机型号。

值：型号。

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


获取相机制造商。

值： 制造商。

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


获取是否为 foveon 矩阵。

值：该 是 foveon。

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


获取软件。

值：软件。

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


获取文件中 RAW 图像的数量 (0 表示文件未被识别)。

值：该 原始计数。

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


获取描述矩阵中色像素顺序的位掩码。

值：该 过滤器。

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


获取颜色。

值：该 颜色。

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


获取 XMP 数据。

值：该 XMP 数据。

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


获取 CFA 马赛克 DNG 格式的转换数组。

值：该 xtrans。

**Returns:**
java.lang.String[]
