---
title: "图像其他参数"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "其他图像参数"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

其他图像参数
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDescription()](#getDescription--) | 获取图像描述。 |
| [getArtist()](#getArtist--) | 获取图像的作者。 |
| [getTimestamp()](#getTimestamp--) | 获取拍摄日期。 |
| [getShotOrder()](#getShotOrder--) | 获取图像的序列号。 |
| [getAperture()](#getAperture--) | 获取光圈。 |
| [getShutterSpeed()](#getShutterSpeed--) | 获取快门速度。 |
| [getGpsData()](#getGpsData--) | 获取 GPS 数据。 |
| [getFocalLength()](#getFocalLength--) | 获取焦距长度。 |
| [getIsoSpeed()](#getIsoSpeed--) | 获取 ISO 灵敏度。 |

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
// 相机型号:                     M8 Digital Camera
// 颜色计数:                     3
// 颜色描述:               RGBG
// DNG 版本:                      16777216
// 文件中 RAW 图像的数量: 1
// 软件:                         1.107
// 颜色像素的顺序:        10110100101101001011010010110100
// 光圈:                         0
// 描述:
// 焦距:                     50
// ISO 感光度:                  160
// 图像序列号:       0
// 快门速度:                    12
// 拍摄日期:                 8/3/2007 3:13:49 AM
```

### getDescription() {#getDescription--}
```
public String getDescription()
```


获取图像描述。

值: 描述。

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


获取图像的作者。

值：艺术家。

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


获取拍摄日期。

值: 时间戳。

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


获取图像的序列号。

值: 拍摄顺序。

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


获取光圈。

值: 光圈。

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


获取快门速度。

值: 快门。

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


获取 GPS 数据。

值: GPS 数据。

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


获取焦距长度。

值：焦距长度。

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


获取 ISO 灵敏度。

值：ISO 速度。

**Returns:**
float
