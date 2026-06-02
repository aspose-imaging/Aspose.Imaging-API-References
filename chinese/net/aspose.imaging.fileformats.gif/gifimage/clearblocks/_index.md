---
title: "GifImage.ClearBlocks"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。清除所有 GIF 块会移除图像中存储的任何现有数据。此操作有效地将图像重置为空状态，删除所有先前添加的块。当您需要从空白状态开始创建或修改 GIF 图像时，请使用此方法。"
type: docs
weight: 270
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/clearblocks/
---
## GifImage.ClearBlocks method

清除所有 GIF 块会移除图像中存储的任何现有数据。此操作有效地将图像重置为空状态，删除之前添加的所有块。当您需要以全新状态创建或修改 GIF 图像时，请使用此方法。

```csharp
public void ClearBlocks()
```

## 示例

以下示例展示了如何从 GIF 图像中移除所有块。

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }

    System.Console.WriteLine("Clear all the blocks");
    gifImage.ClearBlocks();

    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }
}

// 输出如下：
// 活动帧尺寸：{ Width = 100, Height = 100 }
// 清除所有块
// 未设置活动帧
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


