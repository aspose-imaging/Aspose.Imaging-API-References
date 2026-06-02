---
title: "JpegImage.ExifData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 属性。使用此属性管理 EXIF 数据，允许您添加或检索与图像关联的元数据。无论是提取相机设置信息还是修改现有元数据，此属性都提供了管理 EXIF 数据容器的灵活性。"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/exifdata/
---
## JpegImage.ExifData property

使用此属性管理 EXIF 数据，允许您添加或检索与图像关联的元数据。无论是提取相机设置信息还是修改现有元数据，此属性都提供了管理 EXIF 数据容器的灵活性。

```csharp
public JpegExifData ExifData { get; set; }
```

## 示例

以下示例展示了如何从 JPEG 图像中提取 EXIF 标签。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.Exif.ExifData exifData = image.ExifData;

    System.Console.WriteLine("The general EXIF data");
    System.Console.WriteLine("------------------------------------------");
    if (exifData != null)
    {
        System.Console.WriteLine("The EXIF version: {0}", exifData.ExifVersion);
        System.Console.WriteLine("The camera serial number: {0}", exifData.BodySerialNumber);
        System.Console.WriteLine("The color space: {0}", exifData.ColorSpace);
        System.Console.WriteLine("The brightness: {0}", exifData.BrightnessValue);
        System.Console.WriteLine("The contrast: {0}", exifData.Contrast);
        System.Console.WriteLine("The gamma: {0}", exifData.Gamma);
        System.Console.WriteLine("The sharpness: {0}", exifData.Sharpness);
        System.Console.WriteLine("The aperture: {0}", exifData.ApertureValue);
        System.Console.WriteLine("The exposure mode: {0}", exifData.ExposureMode);
        System.Console.WriteLine("The exposure bias: {0}", exifData.ExposureBiasValue);
        System.Console.WriteLine("The exposure time: {0}", exifData.ExposureTime);
        System.Console.WriteLine("The focal length: {0}", exifData.FocalLength);
        System.Console.WriteLine("The focal plane resolution unit: {0}", exifData.FocalPlaneResolutionUnit);
        System.Console.WriteLine("The lens model: {0}", exifData.LensModel);
        System.Console.WriteLine("The shutter speed: {0}", exifData.ShutterSpeedValue);
    }

    System.Console.WriteLine("The JPEG EXIF data");
    System.Console.WriteLine("------------------------------------------");
    Aspose.Imaging.Exif.JpegExifData jpegExifData = image.ExifData as Aspose.Imaging.Exif.JpegExifData;
    if (jpegExifData != null)
    {
        System.Console.WriteLine("The camera manufacturer: {0}", jpegExifData.Make);
        System.Console.WriteLine("The camera model: {0}", jpegExifData.Model);
        System.Console.WriteLine("The photometric interpretation: {0}", jpegExifData.PhotometricInterpretation);
        System.Console.WriteLine("The artist: {0}", jpegExifData.Artist);
        System.Console.WriteLine("The copyright: {0}", jpegExifData.Copyright);
        System.Console.WriteLine("The image description: {0}", jpegExifData.ImageDescription);
        System.Console.WriteLine("The orientation: {0}", jpegExifData.Orientation);
        System.Console.WriteLine("The software: {0}", jpegExifData.Software);
    }
}

//输出如下：
//通用 EXIF 数据
//------------------------------------------
//EXIF 版本: System.Byte[]
//相机序列号: 7100536
//色彩空间: SRgb
//亮度:
//对比度: Normal
//伽马:
//锐度: 0
//光圈: 4.64(4643856 / 1000000)
//曝光模式: Manual
//曝光补偿: 0.67(4 / 6)
//曝光时间: 0.01(1 / 160)
//焦距: 145.00(1450 / 10)
//焦平面分辨率单位: Cm
//镜头型号: 70.0 - 200.0 mm f/ 4.0
//快门速度: 7.32(7321928 / 1000000)
//JPEG EXIF 数据
//------------------------------------------
//相机制造商: NIKON CORPORATION
//相机型号: NIKON D5
//光度解释: 0
//艺术家: 
//版权: 
//图像描述:
//方向: TopLeft
//软件：Adobe Photoshop Camera Raw 9.9（Macintosh）
```

### 另请参见

* class [JpegExifData](../../../aspose.imaging.exif/jpegexifdata/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


