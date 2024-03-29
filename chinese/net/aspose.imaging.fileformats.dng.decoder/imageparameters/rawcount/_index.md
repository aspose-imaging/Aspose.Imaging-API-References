---
title: RawCount
second_title: Aspose.Imaging for .NET API 参考
description: 获取文件中RAW图像的数量0表示文件未被识别
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.dng.decoder/imageparameters/rawcount/
---
## ImageParameters.RawCount property

获取文件中RAW图像的数量（0表示文件未被识别）。

```csharp
public uint RawCount { get; }
```

### 适当的价值

原始计数。

### 例子

此示例说明如何从文件加载 DNG 图像、打印其属性并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "test.dng"))
{
    Aspose.Imaging.FileFormats.Dng.DngImage dngImage = (Aspose.Imaging.FileFormats.Dng.DngImage) image;
    Aspose.Imaging.FileFormats.Dng.Decoder.RawData rawData = dngImage.ImgData;
    Aspose.Imaging.FileFormats.Dng.Decoder.ImageParameters parameters = rawData.ImageDataParameters;
    if (parameters != null)
    {
        System.Console.WriteLine("The camera manufacturer:              {0}", parameters.CameraManufacturer);
        System.Console.WriteLine("The camera model:                     {0}", parameters.Model);
        System.Console.WriteLine("The colors count:                     {0}", parameters.ColorsCount);
        System.Console.WriteLine("The colors description:               {0}", parameters.Description);
        System.Console.WriteLine("The DNG version:                      {0}", parameters.DngVersion);
        System.Console.WriteLine("The number of RAW images in the file: {0}", parameters.RawCount);
        System.Console.WriteLine("The software:                         {0}", parameters.Software);
        System.Console.WriteLine("The order of the color pixels:        {0}", System.Convert.ToString(parameters.Filters, 2));

        string[] translationCfaDng = parameters.TranslationCfaDng;
        if (translationCfaDng != null)
        {
            System.Console.WriteLine("The translation array for CFA mosaic {0}:", translationCfaDng.Length);
            foreach (string s in translationCfaDng)
            {
                System.Console.WriteLine("- {0}", s);
            }
        }
    }

    Aspose.Imaging.FileFormats.Dng.Decoder.ImageOtherParameters otherParameters = rawData.ImageOtherParameters;
    if (otherParameters != null)
    {
        System.Console.WriteLine("The aperture:                         {0}", otherParameters.Aperture);
        //System.Console.WriteLine("作者：{0}", otherParameters.Artist);
        System.Console.WriteLine("The description:                      {0}", otherParameters.Description);
        System.Console.WriteLine("The focal length:                     {0}", otherParameters.FocalLength);
        System.Console.WriteLine("The ISO sensitivity:                  {0}", otherParameters.IsoSpeed);
        System.Console.WriteLine("The serial number of the image:       {0}", otherParameters.ShotOrder);
        System.Console.WriteLine("The shutter speed:                    {0}", otherParameters.ShutterSpeed);
        System.Console.WriteLine("The date of shooting:                 {0}", System.DateTime.FromFileTime(otherParameters.Timestamp));
    }

    // 使用默认选项导出为 PNG。
    dngImage.Save(dir + "test.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

// 相机制造商：徕卡
// 相机型号：M8 数码相机
// 颜色计数：3
// 颜色描述：RGBG
// DNG 版本：16777216
// 文件中 RAW 图像的数量：1
// 软件：1.107
// 颜色像素的顺序：10110100101101001011010010110100
// 光圈：0
// 说明：                      
// 焦距：50
// ISO感光度：160
// 图片的序列号：0
// 快门速度：12
// 拍摄日期：8/3/2007 3:13:49 AM
```

### 也可以看看

* class [ImageParameters](../../imageparameters)
* 命名空间 [Aspose.Imaging.FileFormats.Dng.Decoder](../../imageparameters)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
