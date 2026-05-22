---
title: "Image.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。裁剪指定的矩形"
type: docs
weight: 210
url: /zh/net/aspose.imaging/image/crop/
---
## Crop(Rectangle) {#crop}

裁剪指定的矩形。

```csharp
public virtual void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

## 示例

以下示例裁剪光栅图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    image.Crop(area);

    // 将裁剪后的图像保存为 PNG
    image.Save(dir + "sample.Crop.png");
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

使用位移裁剪图像。

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 右移。 |
| topShift | Int32 | 上移。 |
| bottomShift | Int32 | 下移。 |

## 示例

以下示例裁剪光栅图像。裁剪区域通过左、上、右、下边距指定。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // 再次裁剪。设置图像尺寸 10% 的边距。
    int horizontalMargin = rasterImage.Width / 10;
    int verticalMargin = rasterImage.Height / 10;
    image.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // 将裁剪后的图像保存为 PNG。
    image.Save(dir + "sample.Crop.png");
}
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


