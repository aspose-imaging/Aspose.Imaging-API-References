---
title: StreamSource
second_title: Aspose.Imaging for .NET API 参考
description: 初始化StreamSourceaspose.imaging.sources/streamsource类的新实例
type: docs
weight: 10
url: /zh/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

初始化[`StreamSource`](../../streamsource)类的新实例。

```csharp
public StreamSource(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |

### 例子

这个例子展示了如何在颜色类型的数组中加载像素信息，操作数组并将其设置回图像。为了执行这些操作，这个例子创建了一个新的 Image 文件（GIF 格式）uisng MemoryStream 对象。

```csharp
[C#]

    //创建一个MemoryStream
的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 GifOptions 实例并设置其各种属性，包括 Source 属性
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

        //创建Image
的实例
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //通过指定区域为图像边界
获取图像的像素
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置alrenative索引pixel
的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //设置索引像素颜色为yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //设置索引像素颜色为blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

            //将像素变化应用到image
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

        // 将 MemoryStream 写入 File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### 也可以看看

* class [StreamSource](../../streamsource)
* 命名空间 [Aspose.Imaging.Sources](../../streamsource)
* 部件 [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

初始化[`StreamSource`](../../streamsource)类的新实例。

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |
| disposeStream | Boolean | 如果设置为` true` 流将被处理。 |

### 例子

这个例子演示了使用 System.IO.Stream 创建一个新的图像文件（JPEG 类型）

```csharp
[C#]

//创建一个JpegOptions实例并设置它的各种属性
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    //创建System.IO.Stream
的实例
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//定义JpegOptions
实例的源属性
//第二个布尔参数确定Stream一旦超出范围就被释放
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

    //创建一个Image实例，调用Create方法以JpegOptions为参数初始化Image对象
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
        //做一些图像处理
}
```

### 也可以看看

* class [StreamSource](../../streamsource)
* 命名空间 [Aspose.Imaging.Sources](../../streamsource)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
