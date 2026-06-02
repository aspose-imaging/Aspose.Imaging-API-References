---
title: "Image.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。按比例调整宽度。使用默认的 NearestNeighbourResample。"
type: docs
weight: 280
url: /zh/net/aspose.imaging/image/resizewidthproportionally/
---
## ResizeWidthProportionally(int) {#resizewidthproportionally}

按比例调整宽度。使用默认的 NearestNeighbourResample。

```csharp
public void ResizeWidthProportionally(int newWidth)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeWidthProportionally(int, ResizeType) {#resizewidthproportionally_2}

按比例调整宽度。

```csharp
public virtual void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载图像并使用各种缩放方法按比例调整大小。仅指定宽度，高度会自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### 另请参见

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeWidthProportionally(int, ImageResizeSettings) {#resizewidthproportionally_1}

按比例调整宽度。

```csharp
public virtual void ResizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| 设置 | ImageResizeSettings | 图像缩放设置。 |

### 另请参见

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


