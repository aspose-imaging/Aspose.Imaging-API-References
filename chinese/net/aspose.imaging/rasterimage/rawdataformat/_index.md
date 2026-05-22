---
title: "RasterImage.RawDataFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 属性。获取原始数据格式"
type: docs
weight: 80
url: /zh/net/aspose.imaging/rasterimage/rawdataformat/
---
## RasterImage.RawDataFormat property

获取原始数据格式。

```csharp
public virtual PixelDataFormat RawDataFormat { get; }
```

### Property Value

原始数据格式。

## 示例

以下示例加载光栅图像并打印原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

// 要加载的图像文件。
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// 输出可能如下所示：
// ImageFile=c:\\temp\\sample.bmp, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\\temp\\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

此示例展示了如何从文件流加载 DJVU 图像并打印页面信息。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### 另请参见

* class [PixelDataFormat](../../pixeldataformat/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


