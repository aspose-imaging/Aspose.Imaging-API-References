---
title: "StreamSource.StreamSource"
second_title: "Aspose.Imaging for .NET API 参考"
description: "StreamSource 构造函数。初始化 StreamSource 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource() {#constructor}

初始化 [`StreamSource`](../) 类的新实例。

```csharp
public StreamSource()
```

### 另请参见

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)

---

## StreamSource(Stream) {#constructor_1}

初始化 [`StreamSource`](../) 类的新实例。

```csharp
public StreamSource(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |

## 示例

本示例展示了如何将像素信息加载到 Color 类型的数组中，操作该数组并将其设置回图像。为执行这些操作，示例使用 MemoryStream 对象创建一个新的（GIF 格式）图像文件。

```csharp
[C#]

//创建 MemoryStream 的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //通过将区域指定为图像边界来获取图像像素
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置交替索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //将索引像素颜色设置为黄色
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //将索引像素颜色设置为蓝色
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //将像素更改应用到图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    // 将 MemoryStream 写入文件
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### 另请参见

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_2}

初始化 [`StreamSource`](../) 类的新实例。

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |
| disposeStream | Boolean | 如果设置为 `true`，流将被释放。 |

## 示例

此示例演示了使用 System.IO.Stream 创建新图像文件（JPEG 类型）。

```csharp
[C#]

//创建 JpegOptions 的实例并设置其各种属性。
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//创建 System.IO.Stream 的实例。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//为 JpegOptions 实例定义 source 属性。
//第二个布尔参数决定在超出作用域后是否释放 Stream。
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//创建 Image 的实例，并使用 JpegOptions 作为参数调用 Create 方法来初始化 Image 对象。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //进行一些图像处理
}
```

### 另请参见

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)


