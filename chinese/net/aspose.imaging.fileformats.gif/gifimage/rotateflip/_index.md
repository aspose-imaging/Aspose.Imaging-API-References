---
title: "GifImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。仅在活动帧上执行旋转、翻转或两者同时操作。此操作仅对图像当前活动帧进行转换，保持序列中其他帧的完整性。"
type: docs
weight: 400
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/rotateflip/
---
## GifImage.RotateFlip method

仅对活动帧执行旋转、翻转或两者。此操作仅对图像当前活动的帧应用变换，保持序列中其他帧的完整性。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

## 示例

此示例加载一个 GIF 图像，将其顺时针旋转 90 度，并可选地水平和（或）垂直翻转图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // 旋转、翻转并保存到输出文件。
    using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


