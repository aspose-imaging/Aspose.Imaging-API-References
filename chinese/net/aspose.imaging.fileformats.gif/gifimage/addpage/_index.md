---
title: "GifImage.AddPage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。将新页面无缝合并到现有图像中，提升内容并扩展范围。此方法通过添加额外内容来增强图像集合，促进图像管理和组合的创造力与灵活性。"
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

将新页面无缝合并到现有图像中，增强其内容并扩展其范围。此方法为图像集合添加额外内容，促进图像管理和构图的创造性与灵活性。

```csharp
public void AddPage(RasterImage page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | RasterImage | 要添加的页面。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *page* 为 null。 |

## 示例

使用单页光栅图像创建多页 GIF 图像。

```csharp
[C#]

static void Main(string[] args)
{
    // 加载帧
    var frames = LoadFrames("Animation frames").ToArray();

    // 使用第一帧创建 GIF 图像
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // 使用 AddPage 方法向 GIF 图像添加帧
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // 保存 GIF 图像
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


