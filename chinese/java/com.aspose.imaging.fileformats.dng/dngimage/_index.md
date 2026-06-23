---
title: "DngImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 API 用于处理用于数字摄影需求的 DNG Digital Negative 图像文件格式，提供对原始文件和元数据的全面支持。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

该 API 用于处理用于数字摄影需求的 DNG (Digital Negative) 图像文件格式，提供对原始文件和元数据的全面支持。它面向各种制造商的数码相机设计，使开发者能够高效地操作诸如每像素位数、提取内部数据以及调整图像平衡等方面。凭借无缝更新和保存图像数据的能力，此 API 让开发者能够轻松处理 DNG 文件，确保高质量的结果和多样化的处理选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DngImage()](#DngImage--) | 轻松初始化 [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此属性，轻松获取图像的每像素位数。 |
| [getHeight()](#getHeight--) | 使用此属性获取图像的高度。 |
| [getWidth()](#getWidth--) | 使用此属性访问图像的宽度。 |
| [getFileFormat()](#getFileFormat--) | 使用此属性识别图像的文件格式。 |
| [getImgData()](#getImgData--) | 使用此属性管理图像数据。 |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | 使用此属性管理图像数据。 |

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

### DngImage() {#DngImage--}
```
public DngImage()
```


轻松初始化 [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) 类的新实例。非常适合希望在项目中快速高效使用 DngImage 对象的开发者。

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此属性，轻松获取图像的每像素位数。非常适合快速、准确地了解图像的像素深度。

值：图像每像素位数。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


使用此属性获取图像的高度。非常适合轻松确定图像的垂直尺寸。

值：图像高度。

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


使用此属性访问图像的宽度。非常适合快速高效地获取图像的水平尺寸。

值：图像宽度。

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此属性识别图像的文件格式。非常适合了解格式——简明直观的细节。

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


使用此属性管理图像数据。无论是读取还是更新，此属性都提供对图像数据的无缝访问，以实现高效的操作。

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


使用此属性管理图像数据。无论是读取还是更新，此属性都提供对图像数据的无缝访问，以实现高效的操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | 图像数据。 |

