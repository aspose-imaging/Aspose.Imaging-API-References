---
title: "Image.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。旋转、翻转或同时旋转并翻转图像"
type: docs
weight: 300
url: /zh/net/aspose.imaging/image/rotateflip/
---
## Image.RotateFlip method

旋转、翻转或同时旋转和翻转图像。

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转的类型。 |

## 示例

此示例演示在图像上使用 Rotate 操作。示例从某个磁盘位置加载现有图像文件，并根据枚举 Aspose.Imaging.RotateFlipType 的值对图像执行旋转操作。

```csharp
[C#]

//创建 image 类的实例，并通过文件路径使用现有图像文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //将图像绕 X 轴旋转 180 度
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // 保存所有更改。
    image.Save();
}
```

此示例加载图像，将其顺时针旋转90度，并可选地水平和（或）垂直翻转图像。

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
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

此示例加载 ODG 图像，将其顺时针旋转 90 度，并可选择水平和（或）垂直翻转图像。

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

foreach (Aspose.Imaging.Image rotateFlipType in rotateFlipTypes)
{
    // 旋转、翻转并保存到输出文件。
    using (Aspose.Imaging.Image image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


